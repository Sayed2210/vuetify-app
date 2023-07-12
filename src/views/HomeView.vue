<template>
  <div class="home">
    <!-- navigation-drawer -->
    <!-- <v-layout>
      

      <v-navigation-drawer location="left" permanent expand-on-hover rail>
        <v-list :items="items"></v-list>
      </v-navigation-drawer>
      <v-app-bar color="primary" prominent>
        <v-app-bar-nav-icon variant="text"></v-app-bar-nav-icon>

        <v-toolbar-title>My files</v-toolbar-title>

        <v-spacer></v-spacer>

        <v-btn variant="text" icon="mdi-magnify"></v-btn>

        <v-btn variant="text" icon="mdi-filter"></v-btn>

        <v-btn variant="text" icon="mdi-dots-vertical"></v-btn>
      </v-app-bar>

      <v-main style="height: 500px">
        <v-card-text>
          The navigation drawer will appear from the bottom on smaller size
          screens.
        </v-card-text>
      </v-main>
    </v-layout> -->
    <!-- <v-container>
      <v-row>
        <v-col cols="4" v-for="num in 3" :key="num">Elsayed</v-col>
      </v-row>
    </v-container>
    <v-card>
      <v-tabs v-model="tab" bg-color="primary">
        <v-tab :value="num" v-for="num in 4" :key="num">Item {{ num }}</v-tab>
      </v-tabs>

      <v-card-text>
        <v-window v-model="tab">
          <v-window-item :value="num" v-for="num in 4" :key="num">
            Content {{ num }}
          </v-window-item>
        </v-window>
      </v-card-text>
    </v-card>
    <v-card class="w-100">
      <v-progress-linear
        indeterminate
        :height="5"
        v-if="loading"
      ></v-progress-linear>
      <v-progress-circular
        indeterminate
        v-if="loading"
        class="d-block"
      ></v-progress-circular>
      <v-btn @click="startLoading">Loding</v-btn>
    </v-card> -->

    <!-- api call for pagination -->
    <!-- <v-container>
      <v-row>
        <v-col cols="12">
          <v-card :loading="loading">
            <v-row v-if="!loading">
              <v-col cols="3" v-for="item in passengers.data" :key="item._id"
                ><v-card
                  ><v-card-title> {{ item.name }}</v-card-title>
                  <v-card-subtitle> {{ item.trips }}</v-card-subtitle>
                </v-card></v-col
              >
            </v-row>
          </v-card>
        </v-col>
        <v-col cols="12"
          ><v-pagination
            v-model="page"
            :length="passengers.totalPages"
            rounded="0"
            @update:model-value="getData"
          ></v-pagination
        ></v-col>
      </v-row>
    </v-container> -->
    <!-- <v-container>
      <v-row>
        <v-col cols="12" md="4" lg="4" sm="6"
          ><v-row>
            <v-col cols="4">Elsayed</v-col>
            <v-col cols="4">HAssan</v-col>
            <v-col cols="4">Elsayed</v-col>
          </v-row></v-col
        >
        <v-col cols="12" md="4" lg="4" sm="6">Elsayed</v-col>
        <v-col cols="12" md="4" lg="4" sm="6">Elsayed</v-col>
      </v-row>
    </v-container>
    <v-btn color="blue" @click="clickme" :loading="loading"
      >Hey! <v-icon color="white" icon="mdi-arrow-left"></v-icon
    ></v-btn>
      -->
    <!-- cards -->
    <!-- <v-container>
      <v-row>
        <v-col v-for="num in numbers" :key="num">
          <v-card class="mx-auto" max-width="344">
            <v-img
              src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
              height="200px"
              cover
            ></v-img>

            <v-card-title> Top western road trips </v-card-title>

            <v-card-subtitle> 1,000 miles of wonder </v-card-subtitle>

            <v-card-actions>
              <v-btn color="orange-lighten-2" variant="text"> Explore </v-btn>

              <v-spacer></v-spacer>

              <v-btn
                :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'"
                @click="show = !show"
              ></v-btn>
            </v-card-actions>

            <v-expand-transition>
              <div v-show="show">
                <v-divider></v-divider>

                <v-card-text>
                  I'm a thing. But, like most politicians, he promised more than
                  he could deliver. You won't have time for sleeping, soldier,
                  not with all the bed making you'll be doing. Then we'll go
                  with that data file! Hey, you add a one and two zeros to that
                  or we walk! You're going to do his laundry? I've got to find a
                  way to escape.
                </v-card-text>
              </div>
            </v-expand-transition>
          </v-card>
        </v-col>
      </v-row>
    </v-container> -->
    <!-- <v-divider></v-divider> -->
    <!-- <v-expansion-panels>
      <v-expansion-panel
        title="Title"
        text="Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, ratione debitis quis est labore voluptatibus! Eaque cupiditate minima"
      >
      </v-expansion-panel>
    </v-expansion-panels> -->

    <!-- menu -->
    <!-- <v-btn color="primary" id="my_menu"> Dropdown </v-btn>
    <v-menu activator="#my_menu" location="bottom">
      <v-list :items="items"></v-list>
    </v-menu>
    <v-layout>
      <v-navigation-drawer permanent absolute>
        <v-list>
          <v-list-item
            prepend-avatar="https://cdn.vuetifyjs.com/images/john.png"
            title="John Leider"
            subtitle="john@google.com"
          >
            <template v-slot:append>
              <v-btn size="small" variant="text" icon="mdi-menu-down"></v-btn>
            </template>
          </v-list-item>
        </v-list>

        <v-divider></v-divider> -->
    <!-- lists -->
    <!-- <v-list :lines="false" density="compact" nav>
          <v-list-item
            v-for="(item, i) in items"
            :key="i"
            :value="item"
            color="primary"
          >
            <template v-slot:prepend>
              <v-icon :icon="item.icon"></v-icon>
            </template>

            <v-list-item-title v-text="item.text"></v-list-item-title>
          </v-list-item>
        </v-list> 
      </v-navigation-drawer>

      <v-main style="height: 354px"></v-main>
    </v-layout>
    <v-toolbar
      dark
      prominent
      image="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Vuetify</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-export</v-icon>
      </v-btn>
    </v-toolbar>
    <v-toolbar extended extension-height="100" class="ma-10">
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Title</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-heart</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-dots-vertical</v-icon>
      </v-btn>
    </v-toolbar>
    <v-divider></v-divider>
    <v-btn>
      Start
      <v-tooltip class="ma-10" activator="parent" location="right"
        >Tooltip</v-tooltip
      >
    </v-btn>
    <v-layout>
      <v-app-bar color="red" density="compact">
        <template v-slot:prepend>
          <v-app-bar-nav-icon></v-app-bar-nav-icon>
        </template>

        <v-app-bar-title>Photos</v-app-bar-title>

        <template v-slot:append>
          <v-btn icon="mdi-dots-vertical"></v-btn>
        </template>
      </v-app-bar>

      <v-main>
        <v-container fluid>
          <v-row dense>
            <v-col v-for="n in 8" :key="n" cols="3">
              <v-sheet color="grey-lighten-2" height="96"></v-sheet>
            </v-col>
          </v-row>
        </v-container>
      </v-main>
      <v-bottom-navigation>
        <v-btn value="recent">
          <v-icon>mdi-history</v-icon>

          Recent
        </v-btn>

        <v-btn value="favorites">
          <v-icon>mdi-heart</v-icon>

          Favorites
        </v-btn>

        <v-btn value="nearby">
          <v-icon>mdi-map-marker</v-icon>

          Nearby
        </v-btn>
      </v-bottom-navigation>
      <v-breadcrumbs :items="links">
        <template v-slot:prepend>
          <v-icon size="small" icon="$vuetify"></v-icon>
        </template>
      </v-breadcrumbs>
    </v-layout>
    -->
    <!-- <v-card>
      <v-container fluid>
        <v-row>
          <v-col cols="12">
            <h2>{{ selected }}</h2>
            <v-autocomplete
              v-model="values"
              :items="items"
              label="Default"
              v-model:search="search"
              :error-messages="errMsg"
              class="text-start"
            ></v-autocomplete>
            <v-select
              :items="items"
              density="comfortable"
              label="Comfortable"
              v-model="search"
              :error-messages="errMsg"
              class="text-start"
              multiple
              return-object
              item-title="state"
              item-value="abbr"
            ></v-select>
            <v-btn @click="validate">Submit</v-btn>
            <v-row>
              <v-col cols="3" v-for="item in items" :key="item.state">
                <v-card
                  ><v-card-title>{{ item.state }}</v-card-title>
                  <v-card-actions>
                    <v-checkbox
                      label="Chosen One"
                      :value="item.state"
                      v-model="selected"
                    ></v-checkbox> </v-card-actions></v-card
              ></v-col>
            </v-row>
            <v-row
              ><v-col cols="12">{{ selected }}</v-col></v-row
            >
            <v-radio-group v-model="selected">
              <v-radio label="Ahmed" value="Ahmed"></v-radio>
              <v-radio label="Elsayed" value="Elsayed"></v-radio>
              <v-radio label="Hassan" value="Hassan"></v-radio>
              <v-radio label="Mohamed" value="Mohamed"></v-radio>
            </v-radio-group>
            <v-file-input
              v-model:model-value="img"
              show-size
              counter
              multiple
              label="File input"
              @update:model-value="renderImg()"
            ></v-file-input>
            <v-card><img :src="imgUrl" alt="" /></v-card>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="12">
            <v-slider
              append-icon="mdi-plus"
              prepend-icon="mdi-minus"
              @click:append="inc"
              @click:prepend="dec"
              thumb-label="always"
              v-model="range"
              min="0"
              max="100"
            ></v-slider>
          </v-col>
        </v-row>
      </v-container>
    </v-card> -->
    <!-- <v-layout>
      <v-app-bar :theme="switchTheme"> </v-app-bar>
      <v-container>
        <v-row>
          <v-col cols="12">
            <v-card>
              <v-switch
                label="Theme"
                v-model="switchTheme"
                false-value="light"
                true-value="dark"
              ></v-switch>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
      <v-footer :theme="switchTheme">
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Velit
        doloribus rerum sed vero, vitae nihil quibusdam aperiam hic, illum eos
        facere aspernatur eligendi perspiciatis ipsa similique, illo ipsum atque
        veritatis.
      </v-footer>
    </v-layout> -->
    <v-container>
      <v-row>
        <v-col cols="3">
          <v-btn-toggle v-model="toggle" background-color="primary" dark>
            <v-btn value="start">
              <v-icon>mdi-format-align-left</v-icon>
            </v-btn>
            <v-btn value="center">
              <v-icon>mdi-format-align-center</v-icon>
            </v-btn>
            <v-btn value="end">
              <v-icon>mdi-format-align-right</v-icon>
            </v-btn>
          </v-btn-toggle>
        </v-col>
        <v-col cols="3">
          <v-btn-toggle
            v-model="fontStyle"
            background-color="primary"
            dark
            multiple
          >
            <v-btn value="bold">
              <v-icon>mdi-format-bold</v-icon>
            </v-btn>
            <v-btn value="italic">
              <v-icon>mdi-format-italic</v-icon>
            </v-btn>
            <v-btn value="underline">
              <v-icon>mdi-format-underline</v-icon>
            </v-btn>
          </v-btn-toggle>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12">
          <v-card>
            <textarea
              :class="`text-${toggle} w-100 font-weight-${fbold}`"
              rows="10"
              :style="`font-style: ${fitalic}; text-decoration: ${funderline}`"
            ></textarea>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script setup>
import { ref, computed } from "vue";
const toggle = ref([]);
const fontStyle = ref([]);
const fbold = computed(() => {
  return fontStyle.value.filter((el) => el === "bold").join();
});
const fitalic = computed(() => {
  return fontStyle.value.filter((el) => el === "italic").join();
});
const funderline = computed(() => {
  return fontStyle.value.filter((el) => el === "underline").join();
});
// const switchTheme = ref("light");
// const range = ref(0);
// const inc = () => {
//   range.value += 10;
// };
// const dec = () => {
//   range.value -= 10;
// };
// const search = ref("");
// const errMsg = ref("");
// const validate = () => {
//   errMsg.value = "";
//   if (!errMsg.value) {
//     errMsg.value = "Please Enter A Value";
//   }
// };
// const img = ref([]);
// const imgUrl = ref("");
// const renderImg = () => {
//   console.log(img.value);
//   if (!img.value[0]) {
//     imgUrl.value = "";
//     return;
//   }
//   const file = img.value[0];
//   const reader = new FileReader();
//   reader.readAsDataURL(file);
//   reader.addEventListener("load", () => {
//     imgUrl.value = reader.result;
//   });
// };
// const items = ref([
//   { state: "Florida" },
//   { state: "Georgia" },
//   { state: "Nebraska" },
//   { state: "California" },
// ]);
// const drawer = ref(false);
// const page = ref(1);
// const passengers = ref([]);
// const loading = ref(true);
// const getData = async () => {
//   loading.value = true;
//   await fetch(
//     `https://api.instantwebtools.net/v1/passenger?page=${
//       page.value - 1
//     }&size=12`
//   )
//     .then((res) => res.json())
//     .then((data) => {
//       passengers.value = data;
//       loading.value = false;
//       console.log(passengers.value);
//     });
// };
// onMounted(async () => {
//   loading.value = true;
//   await fetch(
//     `https://api.instantwebtools.net/v1/passenger?page=${
//       page.value - 1
//     }&size=12`
//   )
//     .then((res) => res.json())
//     .then((data) => {
//       passengers.value = data;
//       loading.value = false;
//       console.log(passengers.value);
//     });
// });
// const numbers = ref([1, 2, 3]);
// const items = ref([
//   { text: "My Files", icon: "mdi-folder" },
//   { text: "Shared with me", icon: "mdi-account-multiple" },
//   { text: "Starred", icon: "mdi-star" },
//   { text: "Recent", icon: "mdi-history" },
//   { text: "Offline", icon: "mdi-check-circle" },
//   { text: "Uploads", icon: "mdi-upload" },
//   { text: "Backups", icon: "mdi-cloud-upload" },
// ]);
// const links = ref([
//   {
//     title: "Dashboard",
//     disabled: false,
//     href: "breadcrumbs_dashboard",
//   },
//   {
//     title: "Link 1",
//     disabled: false,
//     href: "breadcrumbs_link_1",
//   },
//   {
//     title: "Link 2",
//     disabled: true,
//     href: "breadcrumbs_link_2",
//   },
// ]);
// const loading = ref(false);
// const startLoading = () => {
//   loading.value = true;
//   setTimeout(() => {
//     loading.value = false;
//   }, 2000);
// };
</script>
