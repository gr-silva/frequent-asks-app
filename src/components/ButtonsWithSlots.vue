<template>
  <button class="button-with-slots">
    <!--FIXME: CORRIGIR BUG TAMANHO SLOT  -->
    <slot class="slot-icon" />
    <p class="text-of-buttons-with-slots">{{ text }}</p>
  </button>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({ props: { text: String } })
</script>

<style scoped>
.button-with-slots {
  margin-left: 5px;
  margin-right: 6px;
  margin-top: 32px;
  top: 541px;
  left: 701px;
  width: 293px;
  height: 53px;

  background: #3f4452b3 0% 0% no-repeat padding-box;
  opacity: 1;
}

.slot-icon {
  margin-left: 32.35px;
  margin-right: 239.73px;
  margin-top: 17px;
  margin-bottom: 15.29px;

  top: 609px;
  left: 732px;
  width: 18px;
  height: 22px;

  border: 1px solid var(--unnamed-color-22e0db);
  border: 1px solid #22e0db;
  opacity: 1;
}

.text-of-buttons-with-slots {
  top: 611px;
  left: 786px;
  width: 72px;
  height: 19px;

  margin-top: 17px;
  margin-bottom: 17px;
  margin-left: 85px;
  margin-right: 137;

  color: var(--unnamed-color-f5f6f8);
  text-align: left;
  font: normal normal normal 16px/19px Lato;
  letter-spacing: 0px;
  color: #f5f6f8;
  opacity: 1;
}
</style>
