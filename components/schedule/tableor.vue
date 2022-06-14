<template>
  <div class="pa-3">
    <div class="or-room">
      <h3> ห้องผ่าตัด 1</h3>
    </div>
    <v-simple-table class="table-or" width="1200">
      <template v-slot:default>
        <thead>
          <tr>
            <th>
              <v-icon color="darken-2">
                mdi-cursor-move
              </v-icon>
            </th>
            <th class="text-center th-w"><span>สถานะ การผ่าตัด</span></th>
            <th class="text-center th-w"><span>ลำดับ</span></th>
            <th class="text-center th-w"><span>เวลานัด</span></th>
            <th class="text-center th-w"><span>เวลาที่เริ่ม</span></th>
            <th class="text-center th-w"><span>ผ่าตัดเสร็จ</span></th>
            <th class="text-center th-w"><span>HN</span></th>
            <th class="text-center th-w"><span>ชื่อ-นามสกุล</span></th>
            <th class="text-center th-w"><span>อายุ</span></th>
            <th class="text-center th-w"><span>Ward</span></th>
            <th class="text-center th-w"><span>Diagnosis</span></th>
            <th class="text-center th-w"><span>ข้าง</span></th>
            <th class="text-center th-w"><span>Operation</span></th>
            <th class="text-center th-w"><span>Surgeon</span></th>
            <th class="text-center th-w"><span>ANES Type</span></th>
            <th class="text-center th-w"><span>จอง ICU</span></th>
            <th class="text-center th-w"><span>สถานะ ICU</span></th>
            <th class="text-center th-w"><span>ผล DTX</span></th>
            <th class="text-center th-w"><span>Premed</span></th>
            <th class="text-center th-w"><span>ผู้ดูแลเคส</span></th>
            <th class="text-center th-w"><span>หมายเหตุ</span></th>
            <th class="text-center th-w"><span>ดูข้อมูล</span></th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>
              <v-icon color="blue darken-2">
                mdi-cursor-move
              </v-icon>
            </td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
          </tr>
           <tr>
            <td>
              <v-icon color="blue darken-2">
                mdi-cursor-move
              </v-icon>
            </td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
          </tr>

        </tbody>
      </template>
    </v-simple-table>
  </div>
</template>

<script>
export default {
  name: "Table OR",
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

