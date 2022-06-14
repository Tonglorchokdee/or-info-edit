<template>
    <v-row justify="center">
        <v-col cols="12" sm="12" md="12">
            <TabMenu></TabMenu>
            <v-card outlined class="card-main">
                <div class="or-topic">
                    <v-row>
                        <v-col sm="4" cols="12">
                            <v-list-item three-line>
                                <v-list-item-content>
                                    <v-list-item-title class="text-h5 mb-1 font-weight-bold">
                                        ตารางผ่าตัด
                                    </v-list-item-title>
                                </v-list-item-content>
                            </v-list-item>
                        </v-col>
                        <v-col sm="4" cols="12">
                            <v-text-field outlined label="ค้นหา" prepend-inner-icon="mdi-magnify"></v-text-field>
                        </v-col>
                        <v-col sm="4" cols="12">
                            <DatePickers></DatePickers>
                            <v-alert border="left" dense outlined type="error">
                                * จะแสดงตารางของวันถัดไปในทุกๆ <strong>4 โมงเย็น</strong>
                            </v-alert>
                        </v-col>
                    </v-row>
                </div>

                <div class="list-or">
                    <tableor></tableor>
                    <waitor></waitor>
                </div>
                <div class="text-center mb-4">
                    <v-pagination color="info" light  v-model="page" :length="2" ></v-pagination>
                </div>
            </v-card>
        </v-col>
    </v-row>
</template>
<script>
import Tableor from "~/components/schedule/tableor.vue";
import Waitor from '~/components/schedule/waitor.vue';
export default {
    auth: true,
    name: "schedule",
    layout: "main",
    methods: {},
    components: { Tableor, Waitor },
     data () {
      return {
        page: 1,
      }
    },
};
</script>
