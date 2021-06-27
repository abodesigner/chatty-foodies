<template>
  <div class="home">
    <Navbar />
    <HeroSection />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/includes/navigation";
import HeroSection from "@/components/HeroSection";
export default {
  name: "Home",
  components: {
    Navbar,
    HeroSection,
  },
};
</script>
