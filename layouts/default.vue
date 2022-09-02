<template>
  <v-app dark class="application">
    <v-container pt-0 style="position: relative;  ">
      <v-navigation-drawer
        v-model="drawer"
        
        fixed
        
      >
        <v-list>
          <v-list-item
            v-for="(item, i) in items"
            :key="i"
            :to="item.to"
            router
            exact
          >
            <v-list-item-action>
              <v-icon>{{ item.icon }}</v-icon>
            </v-list-item-action>
            <v-list-item-content>
              <v-list-item-title v-text="item.title" />
            </v-list-item-content>
          </v-list-item>
        </v-list>
      </v-navigation-drawer>
      <v-app-bar color="#E0F2FF" style="position: sticky; top: 0; z-index: 2;" flat>
        <img src="~/static/assets/logo.svg" alt="" />
        <v-spacer />
        <nuxt-link
          style="font-size: 12px; font-weight: 700; color: #3e3c3c; text-decoration: none;"
          to="#"
        >
          Sign in
        </nuxt-link>
        <v-btn icon @click.stop="drawer = !drawer" class="hidden-md-and-up">
          <v-icon>mdi-menu</v-icon>
        </v-btn>
      </v-app-bar>
      <v-main class="pt- white">
        <Nuxt />
      </v-main>
    </v-container>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data() {
    return {
      drawer: false,

      items: [
        {
          icon: 'mdi-home',
          title: 'Home',
          to: '/',
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'About us',
          to: '#',
        },
      ],
    }
  },
}
</script>
<style lang="scss" scoped>
.application {
  background-color: #eef2f4;
}
</style>