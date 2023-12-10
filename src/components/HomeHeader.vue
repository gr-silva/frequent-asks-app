<template>
  <div class="container">
    <img src="@/assets/images/astronaut.svg" alt="Astronaut" />
    <h1>Perguntas Frequentes</h1>
    <p>Escolha a categoria desejada</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({})
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

h1 {
  margin-left: 36px;
  margin-bottom: 7px;
  top: 462px;
  left: 731px;
  width: 100%;
  height: 24px;
  color: var(--unnamed-color-f5f6f8);
  text-align: left;
  font: normal normal bold 20px/24px Lato;
  letter-spacing: 0px;
  color: #f5f6f8;
  opacity: 1;
}

p {
  top: 493px;
  left: 731px;
  width: 162px;
  height: 16px;
  margin-left: 36px;
  margin-right: 107px;
  margin-top: 0px;
  color: var(--unnamed-color-f5f6f8);
  text-align: left;
  font: normal normal normal 13px/16px Lato;
  letter-spacing: 0px;
  color: #f5f6f8;
  opacity: 1;
}
</style>
