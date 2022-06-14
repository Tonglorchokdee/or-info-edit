<template>
            <v-dialog
                v-model="dialog"
                persistent
                width="800px"
                >
                <template v-slot:activator="{ on, attrs }">
                <v-col
                    cols="12"
                    sm="6"
                >
                    <v-btn
                    color="primary"
                    outlined
                    v-bind="attrs"
                    v-on="on"
                    >
                        เลือกห้องผ่าตัด 
                    <v-icon
                        color="blue-grey darken-2"
                    >
                        mdi-chevron-down
                    </v-icon>
                    </v-btn>
                </v-col>  

                <v-col
                cols="12"
                sm="6"
                >
                    <v-btn
                    color="primary"
                    >
                        ยืนยัน
                    </v-btn>
                </v-col>
                
                </template>
                <v-card outlined class="">
                    <v-card-title>
                    <span class="text-h5">เลือกห้องผ่าตัด</span>
                    </v-card-title>
                    <v-card-text>
                    <v-container>
                        <v-row>
                        <v-col
                            cols="12"
                            sm="6"
                            md="4"
                        >
                            <v-btn
                            color="blue lighten-2"
                            x-large
                            >
                            <v-icon
                                color="blue darken-3"
                            >
                                mdi-hospital-building
                            </v-icon>
                                ห้องผ่าตัด 1
                            </v-btn>
                        </v-col>
                        <v-col
                            cols="12"
                            sm="6"
                            md="4"
                        >
                            <v-btn
                            color="blue lighten-2"
                            x-large
                            >
                            <v-icon
                                color="blue darken-3"
                            >
                                mdi-hospital-building
                            </v-icon>
                                ห้องผ่าตัด 2
                            </v-btn>
                        </v-col>
                        <v-col
                            cols="12"
                            sm="6"
                            md="4"
                        >
                            <v-btn
                            color="blue lighten-2"
                            x-large
                            >
                            <v-icon
                                color="blue darken-3"
                            >
                                mdi-hospital-building
                            </v-icon>
                                ห้องผ่าตัด 3
                            </v-btn>
                        </v-col>
                        <v-col 
                            cols="12"
                            sm="6"
                            md="4"
                        >
                            <v-btn
                            color="blue lighten-2"
                            x-large
                            >
                            <v-icon
                                color="blue darken-3"
                            >
                                mdi-hospital-building
                            </v-icon>
                                ห้องผ่าตัด 4
                            </v-btn>
                        </v-col>
                        <v-col 
                            cols="12"
                            sm="6"
                            md="4"
                        >
                            <v-btn
                            color="blue lighten-2"
                            x-large
                            >
                            <v-icon
                                color="blue darken-3"
                            >
                                mdi-hospital-building
                            </v-icon>
                                ห้องผ่าตัด 5
                            </v-btn>
                        </v-col>
                        <v-col 
                            cols="12"
                            sm="6"
                            md="4"
                        >
                            <v-btn
                            color="blue lighten-2"
                            x-large
                            >
                            <v-icon
                                color="blue darken-3"
                            >
                                mdi-hospital-building
                            </v-icon>
                                ห้องผ่าตัด 6
                            </v-btn>
                        </v-col>
                        <v-col  
                            cols="12"
                            sm="6"
                            md="4"
                        >
                            <v-btn
                            color="blue lighten-2"
                            x-large
                            >
                            <v-icon
                                color="blue darken-3"
                            >
                                mdi-hospital-building
                            </v-icon>
                                ห้องผ่าตัด 7
                            </v-btn>
                        </v-col>
                        <v-col  
                            cols="12"
                            sm="6"
                            md="4"
                        >
                            <v-btn
                            color="blue lighten-2"
                            x-large
                            >
                            <v-icon
                                color="blue darken-3"
                            >
                                mdi-hospital-building
                            </v-icon>
                                ห้องผ่าตัด 8
                            </v-btn>
                        </v-col>
                        <v-col  
                            cols="12"
                            sm="6"
                            md="4"
                        >
                            <v-btn
                            color="blue lighten-2"
                            x-large
                            >
                            <v-icon
                                color="blue darken-3"
                            >
                                mdi-hospital-building
                            </v-icon>
                                ห้องผ่าตัด 9
                            </v-btn>
                        </v-col>
                        <v-col  
                            cols="12"
                            sm="6"
                            md="4"
                        >
                            <v-btn
                            color="blue lighten-2"
                            x-large
                            >
                            <v-icon
                                color="blue darken-3"
                            >
                                mdi-hospital-building
                            </v-icon>
                                ห้องผ่าตัด 10
                            </v-btn>
                        </v-col>
                        </v-row>
                    </v-container>
                    </v-card-text>
                    <v-card-actions>
                    <v-spacer></v-spacer>

                    <v-row>
                        
                    <v-btn
                        color="primary"
                        @click="dialog = false"
                    >
                        เลือก
                    </v-btn>

                    </v-row>

                    </v-card-actions>
                    
                </v-card>
            </v-dialog>
</template>

<script>
export default {
    name: "select",
    data: () => ({
      dialog: false,
      absolute: true,
      opacity: 1,
      overlay: false,
    }),

};
</script>