<template>
  <div>
    <Sidebar />
    <cHeader />
    <nuxt keep-alive />
    <cFooter />
  </div>
</template>

<script>
import Footer from '@/components/layout/footer.vue'
import Header from '@/components/layout/header.vue'
import Sidebar from '@/components/layout/sidebar.vue'
export default {
  components: {
    cFooter: Footer,
    cHeader: Header,
    Sidebar
  }
}
</script>

<style>
</style>
