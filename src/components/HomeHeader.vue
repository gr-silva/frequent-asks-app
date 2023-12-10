<template>
  <img src="@/assets/images/astronaut.svg" alt="Astronaut" />
  <h1 class="header-title">Perguntas Frequentes</h1>
  <h5 class="header-subtitle">Escolha a categoria desejada</h5>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({})
</script>

<style>
.header-title {
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

.header-subtitle {
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
