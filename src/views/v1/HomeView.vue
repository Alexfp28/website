<script>

import ToolBarComponent from "@/components/v1/ToolBarComponent.vue";
import HomeComponent from "@/components/v1/HomeComponent.vue";
import LearnComponent from '@/components/v1/LearnComponent.vue'
import LaboralComponent from '@/components/v1/LaboralComponent.vue'
import ExperienceComponent from '@/components/v1/ExperienceComponent.vue'
import FooterComponent from '@/components/v1/FooterComponent.vue'
import PersonalComponent from '@/components/v1/PersonalComponent.vue'

export default {
  components: { FooterComponent, ExperienceComponent, LaboralComponent, PersonalComponent, LearnComponent, HomeComponent, ToolBarComponent},
  data() {
    return {
      "ToolBarComponent": ToolBarComponent,
      "HomeComponent": HomeComponent,
      "LearnComponent": LearnComponent,
      "PersonalComponent": PersonalComponent,
      "LaboralComponent": LaboralComponent,
      "ExperienceComponent": ExperienceComponent,
      "FooterComponent": FooterComponent
    };
  }
};


</script>

<template>
  <main>
    <ToolBarComponent/>
    <HomeComponent/>

    <div class="h-5rem"/>

   <LearnComponent/>

    <div class="h-5rem"/>

    <PersonalComponent/>

    <div class="h-5rem"/>

    <LaboralComponent/>

    <div class="h-5rem"/>

    <ExperienceComponent/>

    <FooterComponent/>

  </main>
</template>
