<template>
  <div>
    <NavBar />
    <ContentCard />
    <AboutMeCard />
    <Footer />
  </div>
</template>

<script>
import NavBar from "./NavBar";
import ContentCard from "@/components/ContentCard.vue";
import Footer from "@/components/Footer.vue";
export default {
  components: {
    NavBar,
    ContentCard,
    Footer,
  },
};
</script>

<style lang="scss" scoped></style>
