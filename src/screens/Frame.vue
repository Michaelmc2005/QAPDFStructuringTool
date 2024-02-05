<template>
  <div class="frame">
    <div class="div-4">
      <Overlap class="overlap"></Overlap>
      <div class="text-wrapper-17">QA PDF STRUCTURE TOOL</div>
      <ClientCodeSelect />
    </div>
  </div>
</template>

<script>
import Overlap from "./Frame/sections/Overlap.vue";
import ClientCodeSelect from "./Frame/sections/ClientCodeSelect.vue";

export default {
  name: "Frame",
  components: {
    Overlap,
    ClientCodeSelect,
  },
};
</script>

<style>
.html, body {
  overflow: hidden;
}
.frame {
  background-color: #303030;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100vw;
  height: 75%;
  transform: scale(1.60);
  margin-top: 22vh;
  padding-top: 17px;
}

.frame .div-4 {
  background-color: #303030;
  height: 582px;
  position: relative;
  width: 1103px;
}

.frame .text-wrapper-17 {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 32px;
  font-weight: 700;
  height: 34px;
  left: 348px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 23px;
  white-space: nowrap;
  width: 437px;
}

</style>