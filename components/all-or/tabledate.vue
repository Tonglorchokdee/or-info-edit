<template>
  <v-simple-table class="table-date">
    <template v-slot:default>
      <thead>
        <tr>
          <th class="first-th" width="120"></th>
          <th class="text-center th-w"><span>08.00-09.00</span></th>
          <th class="text-center th-w"><span>09.00-10.00</span></th>
          <th class="text-center th-w"><span>11.00-12.00</span></th>
          <th class="text-center th-w"><span>12.00-13.00</span></th>
          <th class="text-center th-w"><span>13.00-14.00</span></th>
          <th class="text-center th-w"><span>14.00-15.00</span></th>
          <th class="text-center th-w"><span>15.00-16.00</span></th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="text-center first-td">ห้องผ่าตัด 1</td>
          <td class="pa-0 ma-0">
            <div class="success-item">
              <v-list-item class="pa-0 ma-0">
                <v-list-item-content>
                  <div class="text-overline">
                    08.00-09.00
                  </div>
                  <v-list-item-title class="mb-1 d-flex">
                    <v-tooltip top>
                      <template v-slot:activator="{ on, attrs }">
                        <span class="mr-3 d-flex align-center" v-bind="attrs" v-on="on">
                          <v-img class="mr-1" contain src="/user.svg"></v-img>
                          สุรพล
                        </span>
                      </template>
                      <span>สุรพล (ชื่อเต็ม)</span>
                    </v-tooltip>
                    <v-tooltip top>
                      <template v-slot:activator="{ on, attrs }">
                        <span class="mr-3 d-flex align-center" v-bind="attrs" v-on="on">
                          <v-img class="mr-1" contain src="/doctor.svg"></v-img>
                          ปิติชัย
                        </span>
                      </template>
                      <span>ปิติชัย (ชื่อเต็ม)</span>
                    </v-tooltip>
                  </v-list-item-title>
                  <v-list-item-subtitle>
                    <span>N185 : Chronic Kidney Disease, stage 5</span>
                  </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </div>
          </td>
          <td class="pa-0 ma-0" colspan="3">
            <div class="waiting-item">
              <v-list-item class="pa-0 ma-0">
                <v-list-item-content>
                  <div class="text-overline">
                    10.00
                  </div>
                  <v-list-item-title class="mb-1 d-flex">
                    <v-tooltip top>
                      <template v-slot:activator="{ on, attrs }">
                        <span class="mr-3 d-flex align-center" v-bind="attrs" v-on="on">
                          <v-img class="mr-1" contain src="/user.svg"></v-img>
                          สุรพล
                        </span>
                      </template>
                      <span>สุรพล (ชื่อเต็ม)</span>
                    </v-tooltip>
                    <v-tooltip top>
                      <template v-slot:activator="{ on, attrs }">
                        <span class="mr-3 d-flex align-center" v-bind="attrs" v-on="on">
                          <v-img class="mr-1" contain src="/doctor.svg"></v-img>
                          ปิติชัย
                        </span>
                      </template>
                      <span>ปิติชัย (ชื่อเต็ม)</span>
                    </v-tooltip>
                  </v-list-item-title>
                  <v-list-item-subtitle>N185 : Chronic Kidney Disease,
                    stage 5</v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </div>
          </td>
          <td class="pa-0 ma-0" colspan="3">
            <div class="waiting-item">
              <v-list-item class="pa-0 ma-0">
                <v-list-item-content>
                  <div class="text-overline">
                    12.00
                  </div>
                  <v-list-item-title class="mb-1 d-flex">
                    <v-tooltip top>
                      <template v-slot:activator="{ on, attrs }">
                        <span class="mr-3 d-flex align-center" v-bind="attrs" v-on="on">
                          <v-img class="mr-1" contain src="/user.svg"></v-img>
                          สุรพล
                        </span>
                      </template>
                      <span>สุรพล (ชื่อเต็ม)</span>
                    </v-tooltip>
                    <v-tooltip top>
                      <template v-slot:activator="{ on, attrs }">
                        <span class="mr-3 d-flex align-center" v-bind="attrs" v-on="on">
                          <v-img class="mr-1" contain src="/doctor.svg"></v-img>
                          ปิติชัย
                        </span>
                      </template>
                      <span>ปิติชัย (ชื่อเต็ม)</span>
                    </v-tooltip>
                  </v-list-item-title>
                  <v-list-item-subtitle>N185 : Chronic Kidney Disease,
                    stage 5</v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </div>
          </td>
        </tr>
        <tr>
          <td class="text-center first-td">ห้องผ่าตัด 2</td>
          <td class="pa-0 ma-0" colspan="2">
          </td>
          <td class="pa-0 ma-0">
            <div class="success-item">
              <v-list-item class="pa-0 ma-0">
                <v-list-item-content>
                  <div class="text-overline">
                    11.00-12.00
                  </div>
                  <v-list-item-title class="mb-1 d-flex">
                    <v-tooltip top>
                      <template v-slot:activator="{ on, attrs }">
                        <span class="mr-3 d-flex align-center" v-bind="attrs" v-on="on">
                          <v-img class="mr-1" contain src="/user.svg"></v-img>
                          สุรพล
                        </span>
                      </template>
                      <span>สุรพล (ชื่อเต็ม)</span>
                    </v-tooltip>
                    <v-tooltip top>
                      <template v-slot:activator="{ on, attrs }">
                        <span class="mr-3 d-flex align-center" v-bind="attrs" v-on="on">
                          <v-img class="mr-1" contain src="/doctor.svg"></v-img>
                          ปิติชัย
                        </span>
                      </template>
                      <span>ปิติชัย (ชื่อเต็ม)</span>
                    </v-tooltip>
                  </v-list-item-title>
                  <v-list-item-subtitle>
                    <span>N185 : Chronic Kidney Disease, stage 5</span>
                  </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </div>
          </td>
          <td class="pa-0 ma-0">
            <div class="success-item">
              <v-list-item class="pa-0 ma-0">
                <v-list-item-content>
                  <div class="text-overline">
                    12.00-13.00
                  </div>
                  <v-list-item-title class="mb-1 d-flex">
                    <v-tooltip top>
                      <template v-slot:activator="{ on, attrs }">
                        <span class="mr-3 d-flex align-center" v-bind="attrs" v-on="on">
                          <v-img class="mr-1" contain src="/user.svg"></v-img>
                          สุรพล
                        </span>
                      </template>
                      <span>สุรพล (ชื่อเต็ม)</span>
                    </v-tooltip>
                    <v-tooltip top>
                      <template v-slot:activator="{ on, attrs }">
                        <span class="mr-3 d-flex align-center" v-bind="attrs" v-on="on">
                          <v-img  class="mr-1" contain src="/doctor.svg"></v-img>
                          ปิติชัย
                        </span>
                      </template>
                      <span>ปิติชัย (ชื่อเต็ม)</span>
                    </v-tooltip>
                  </v-list-item-title>
                  <v-list-item-subtitle>
                    <span>N185 : Chronic Kidney Disease, stage 5</span>
                  </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
            </div>
          </td>
        </tr>
        <!-- <tr v-for="item in desserts" :key="item.name">
          <td class="text-center first-td">{{ item.room }}</td>
          <td>{{ item.name }}</td>
          <td>{{ item.calories }}</td>
        </tr> -->
      </tbody>
    </template>
  </v-simple-table>
</template>

<script>
export default {
  name: "Table Date",
  // data() {
  //   return {
  //     desserts: [
  //       {
  //         room: 'ห้องผ่าตัด 1',
  //         name: 'Frozen Yogurt',
  //         calories: 159,
  //       },

  //     ],
  //   }
  // },
};
</script>

