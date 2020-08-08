<template>
  <v-app>
    <HeaderItem></HeaderItem>
    <router-view/>
    <FooterItem></FooterItem>
  </v-app>
</template>

<script>
import HeaderItem from '../src/components/header-item'
import FooterItem from '../src/components/footer-item'

export default {
  name: 'Main',
  components: {
    HeaderItem, FooterItem
  }
}
</script>
