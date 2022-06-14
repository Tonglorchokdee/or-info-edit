<template>
    <v-row justify="center">
        <v-col cols="12" sm="12" md="12">
            <TabMenu></TabMenu>
            <v-card outlined class="card-main">
                <div class="or-topic">
                    <v-row>
                        <v-col sm="8">
                            <v-list-item three-line>
                                <v-list-item-content>
                                    <v-list-item-title class="text-h5 mb-1 font-weight-bold">
                                        รายชื่อแพทย์
                                    </v-list-item-title>
                                    <v-list-item-subtitle class="status-room mt-5">
                                        <v-badge color="success" left inline bordered><span
                                                class="font-weight-medium">ผ่าตัดเสร็จแล้ว</span></v-badge>
                                        <v-badge color="warning" left inline bordered><span
                                                class="font-weight-medium">กำลังผ่าตัด</span></v-badge>
                                    </v-list-item-subtitle>
                                </v-list-item-content>
                            </v-list-item>
                        </v-col>
                        <v-col sm="4">
                            <DatePickers></DatePickers>
                            <v-alert border="left" dense outlined type="error">
                                * จะแสดงตารางของวันถัดไปในทุกๆ <strong>4 โมงเย็น</strong>
                            </v-alert>
                        </v-col>
                    </v-row>
                </div>

                <div class="list-or">
                    <Tabledate></Tabledate>
                </div>
            </v-card>
        </v-col>
    </v-row>
</template>
<script>
import Tabledate from "@/components/list-doctor/tabledate.vue";
export default {
    auth: true,
    name: "list doctor",
    layout: "main",
    methods: {},
    components: { Tabledate }
};
</script>

<style lang="scss" scoped>
</style>
