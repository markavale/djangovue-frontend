<template>
  <div>
      <Navbar />
      <Sidebar />
  </div>
</template>

<script>
import Sidebar from '@/components/layout/Sidebar'
import Navbar from '@/components/Navbar'
export default {
    name: 'Header',
    components:{
        Sidebar,
        Navbar,

    }
}
</script>

<style>

</style>