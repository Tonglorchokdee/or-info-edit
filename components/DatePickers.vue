<template>
    <v-menu ref="menu1" v-model="menu1" :close-on-content-click="false" transition="scale-transition" offset-y
        max-width="290px" min-width="auto">
        <template v-slot:activator="{ on, attrs }">
            <v-text-field v-model="dateFormatted" locale="th-th" label="เลือกวัน/เดือน/ปี" outlined prepend-inner-icon="mdi-calendar"  persistent-hint
                 v-bind="attrs" @blur="date = parseDate(dateFormatted)" v-on="on">
            </v-text-field>
        </template>
        <v-date-picker v-model="date" locale="th-th" scrollable>
            <v-spacer></v-spacer>
            <v-btn text color="primary" @click="menu1 = false">
                ยกเลิก
            </v-btn>
            <v-btn text color="primary" @click="$refs.menu1.save(date)">
                ยืนยัน
            </v-btn>
        </v-date-picker>
    </v-menu>
</template>
<script>
export default {
    name: "Date Pickers",
    data: vm => ({
        date: (new Date(Date.now() - (new Date()).getTimezoneOffset() * 60000)).toISOString().substr(0, 10),
        dateFormatted: vm.formatDate((new Date(Date.now() - (new Date()).getTimezoneOffset() * 60000)).toISOString().substr(0, 10)),
        menu1: false,
    }),

    computed: {
        computedDateFormatted() {
            return this.formatDate(this.date)
        },
    },

    watch: {
        date(val) {
            this.dateFormatted = this.formatDate(this.date)
        },
    },

    methods: {
        formatDate(date) {
            if (!date) return null

            const [year, month, day] = date.split('-')
            return `${day}/${month}/${year}`
        },
        parseDate(date) {
            if (!date) return null

            const [day, month, year] = date.split('/')
            return `${year}-${month.padStart(2, '0')}-${day.padStart(2, '0')}`
        },
    },
}
</script>