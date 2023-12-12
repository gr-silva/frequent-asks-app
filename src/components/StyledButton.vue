<template>
  <button class="styled-button">
    <div class="slot">
      <img v-if="hasSlot" :src="imagePath" class="slot-icon" />
      <span class="text-of-styled-button">{{ text }}</span>
    </div>
  </button>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  props: {
    text: String,
    hasSlot: Boolean,
    imagePath: String
  }
})
</script>

<style scoped>
.slot {
  display: flex;
}
.styled-button {
  margin-left: 6px;
  margin-right: 6px;

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

  margin-top: 17px;
  margin-bottom: 15.29px;
  margin-left: 32.25px;

  opacity: 1;
}

.text-of-styled-button {
  top: 611px;
  left: 786px;
  width: 21px;
  height: 21px;

  margin-top: 17px;
  margin-bottom: 17px;
  margin-left: 31.73px;
  margin-right: 137px;

  text-align: left;
  font: normal normal normal 16px/19px Lato;
  letter-spacing: 0px;
  color: #f5f6f8;
  opacity: 1;
}
</style>
