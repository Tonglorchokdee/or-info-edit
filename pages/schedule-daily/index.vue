<template>
    <div>
        <v-breadcrumbs :items="bcitems" divider="/"></v-breadcrumbs>
        <v-row justify="center">
            <v-col cols="12" sm="12" md="12">
                <v-card outlined class="">

                </v-card>
            </v-col>
        </v-row>
    </div>
</template>
<script>
export default {
    auth: true,
    name: "or-schedule",
    layout: "main",
    data: () => ({
        bcitems: [
            {
                text: 'ตารางเคส OR',
                disabled: false,
                href: 'schedule-calendar',
            },
            {
                text: 'เคส OR รายวัน',
                disabled: true,
                href: 'schedule-daily',
            },

        ],
    }),
    methods: {
    },
};
</script>

<style lang="scss" scoped>
</style>
