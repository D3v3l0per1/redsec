<template>
  <v-app dark>

    <v-navigation-drawer temporary v-model="sideNav" fixed>
      <v-list>
        <v-list-tile v-for="item in menuItems" :key="item.title" router :to="item.link">
          <v-list-tile-content>{{ item.title }}</v-list-tile-content>
        </v-list-tile>
      </v-list>
    </v-navigation-drawer>

    <v-toolbar dense class="primary">
      <v-toolbar-side-icon @click.native="sideNav = !sideNav" class="hidden-md-and-up"></v-toolbar-side-icon>
      <v-toolbar-title>Red Security</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat v-for="item in menuItems" :key="item.title" router :to="item.link">{{ item.title }}</v-btn>
      </v-toolbar-items>
    </v-toolbar>

    <main>
      <router-view></router-view>
    </main>

    <v-footer class="pa-3">
      <div><small>This website is owned and operated by Red Security™</small></div>
      <v-spacer></v-spacer>
      <div>&copy; {{ new Date().getFullYear() }}</div>
    </v-footer>

  </v-app>
</template>

<script>
export default {
  data () {
    return {
      sideNav: false,
      menuItems: [
        { icon: '', title: 'Home', link: '/' },
        { icon: '', title: 'About us', link: '/about' },
        { icon: '', title: 'Groups', link: '/groups' },
        { icon: '', title: 'News', link: '/news' },
        { icon: '', title: 'Donate', link: '/donate' },
        { icon: '', title: 'Shop', link: '/shop' },
        { icon: '', title: 'Contact', link: '/contact' }
      ]
    }
  },
  name: 'App'
}
</script>
