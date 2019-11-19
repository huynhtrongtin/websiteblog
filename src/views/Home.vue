<template>
  <div class="home-page">
    <div class="ms-nav-wrapper">
      <ms-header/>
    </div>       
    <ms-redefine-education></ms-redefine-education>
    <ms-registration></ms-registration>
    <ms-why-study></ms-why-study>
    <ms-study></ms-study>
  </div>
</template>

<script>
// @ is an alias to /src
import msHeader from '@/components/header/ms-header.vue'
import msRedefineEducation from '@/components/home/ms-redefine-education.vue'
import msRegistration from '@/components/home/ms-registration.vue'
import msWhyStudy from '@/components/home/ms-why-study.vue'
import msStudy from '@/components/home/ms-study.vue'
export default {
  name: 'home',
  components: {
    msHeader,
    msRedefineEducation,
    msRegistration,
    msWhyStudy,
    msStudy
  }
};
</script>
