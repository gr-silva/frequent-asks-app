<template>
  <div class="container">
    <HomeHeader />
    <div class="styled-buttons">
      <StyledButton
        v-for="{ title, icon } in $data"
        :key="title"
        :text="title"
        :hasSlot="true"
        :imagePath="icon"
      />
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HomeHeader from '@/components/HomeHeader.vue'
import StyledButton from '@/components/StyledButton.vue'
import { IHomeButtons } from '@/types/HomeInterfaces'

export default defineComponent({
  components: { HomeHeader, StyledButton },
  data() {
    return [
      {
        title: 'Basecamp',
        icon: 'rocket.svg'
      },
      {
        title: 'Bootcamp',
        icon: 'astronaut-helmet.svg'
      },
      {
        title: 'Cataline',
        icon: 'student-hat.svg'
      },
      {
        title: 'Parcerias',
        icon: 'partnership.svg'
      }
    ] as IHomeButtons[]
  }
})
</script>
<style scoped>
.container {
  top: 312px;
  left: 695px;
  width: 305px;
  height: 457px;
  background: transparent linear-gradient(180deg, #404451 0%, #26282c 100%) 0%
    0% no-repeat padding-box;
  box-shadow: 0px 10px 30px #3f445266;
  border-radius: 15px;
  opacity: 1;
}
</style>
