<template>
  <button class="styled-button">
    <!--FIXME: CORRIGIR BUG TAMANHO SLOT  -->
    <div class="w-full">
      <slot v-if="hasSlot" class="slot-icon" />
      <span class="text-of-styled-button">{{ text }}</span>
    </div>
  </button>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({ props: { text: String, hasSlot: Boolean } })
</script>

<style scoped>
.styled-button {
  margin-left: 5px;
  margin-right: 6px;
  margin-top: 32px;

  top: 541px;
  left: 701px;
  width: 293px;
  height: 53px;

  border: none;
  background: none;
}
.styled-button:hover {
  background: #3f4452b3 0% 0% no-repeat padding-box;
  opacity: 1;
}
.slot-icon {
  top: 609px;
  left: 732px;
  width: 18px;
  height: 22px;

  border: 1px solid var(--unnamed-color-22e0db);
  border: 1px solid #22e0db;
  opacity: 1;
}

.text-of-styled-button {
  top: 611px;
  left: 786px;
  width: 72px;
  height: 19px;

  padding-top: 17px;
  padding-bottom: 17px;
  padding-left: 85px;
  padding-right: 137px;

  text-align: left;
  font: normal normal normal 16px/19px Lato;
  letter-spacing: 0px;
  color: #f5f6f8;
  opacity: 1;
}
</style>
