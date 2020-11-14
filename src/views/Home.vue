<template>
  <div class="home">
    <Navbar />
    <h1>Home</h1>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar";
// import { mapGetters, mapActions } from "vuex";
export default {
  name: "Home",
  data() {
    return {
      users: [],
    };
  },
  components: {
    Navbar,
  },
  mounted() {
    console.log("Mounted");
  },
  computed: {
   
  },
  methods: {
    
  },
  created() {
  },
};
</script>
