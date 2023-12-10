<template>
  <div class="container">
    <HomeHeader />
    <ButtonsWithSlots text="Basecamp"> </ButtonsWithSlots>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HomeHeader from '@/components/HomeHeader.vue'
import ButtonsWithSlots from '@/components/ButtonsWithSlots.vue'

export default defineComponent({
  components: { HomeHeader, ButtonsWithSlots }
})
</script>
<style scoped>
.container {
  top: 312px;
  left: 695px;
  width: 305px;
  height: 457px;
  background: transparent
    linear-gradient(180deg, #404451 0%, var(--unnamed-color-26282c) 100%) 0% 0%
    no-repeat padding-box;
  background: transparent linear-gradient(180deg, #404451 0%, #26282c 100%) 0%
    0% no-repeat padding-box;
  box-shadow: 0px 10px 30px #3f445266;
  border-radius: 15px;
  opacity: 1;
}
</style>
