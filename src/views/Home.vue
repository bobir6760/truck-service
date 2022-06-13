
<template>
  <div class="home">
    <Navbar />
    <Service />
    <Mann />
    <Location />
    <Base />
    <Volvo />
    <Work />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import Service from "@/components/Service.vue";
import Mann from "@/components/Mann.vue";
import Location from "@/components/Location.vue";
import Base from "@/components/Base.vue";
import Volvo from "@/components/Volvo.vue";
import Work from "@/components/Work.vue";
export default {
  name: "Home",
  components: {
    Navbar,
    Service,
    Mann,
    Location,
    Base,
    Volvo,
    Work,
  },
};
</script>
<style lang="scss" scoped>
.home {
  position: relative;
}
</style>