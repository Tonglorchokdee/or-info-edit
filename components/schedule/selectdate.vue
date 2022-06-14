<template>

    <div>
        <div class="search-layout">
          <v-list-item-title class="text-h5 mb-1 ml-16 mt-5">
            ตารางผ่าตัด
          </v-list-item-title>
          <input  class="search mt-12" type="text" placeholder="ค้นหา" />
          <v-col class='mt-10' cols="12" sm="6" md="4">
            <v-menu
              v-model="menu2"
              :close-on-content-click="false"
              :nudge-right="40"
              transition="scale-transition"
              offset-y
              min-width="auto"
            >
              <template v-slot:activator="{ on, attrs }">
                <v-text-field
                  v-model="date"
                  prepend-icon="mdi-calendar"
                  readonly
                  v-bind="attrs"
                  v-on="on"
                ></v-text-field>
              </template>
              <v-date-picker
                v-model="date"
                @input="menu2 = false"
              ></v-date-picker>
            </v-menu>
          </v-col>
          <v-spacer></v-spacer>
        </div>
        <a class="alert mt-10">*จะแสดงตารางของวันถัดไปในทุกๆ 4 โมงเย็น</a>
    </div>

</template>
<script>
export default {
  auth: true,
  name: "schedule",
  layout: "main",
  methods: {},
  data: () => ({
    page: 1,
    date: new Date(Date.now() - new Date().getTimezoneOffset() * 60000)
      .toISOString()
      .substr(0, 10),
    menu: false,
    modal: false,
    menu2: false,
  }),
};
</script>

<style lang="scss" scoped>
.search-layout {
  display: flex;
  margin-bottom: 20px;
}

.search {
  border: 2px solid rgb(72, 154, 225);
  border-radius: 10px;
  margin-right: 45px;
  width: 80%;
  height: 55px;
  padding: 12px 0px 12px 10px;
}

.alert {
  color: red;
  margin-left: 80%;

}

</style>
