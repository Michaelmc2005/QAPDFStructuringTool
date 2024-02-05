<template>
  <div class="client-code-selector">
    <div class="client-code">
      <div class="client-code-wrapper">
        <div class="client-code-2">
          {{ "{client code}" }}
        </div>
      </div>
    </div>
    <div class="client-code-3">
      <div class="client-code-wrapper">
        <div class="client-code-2">
          {{ "{client code}" }}
        </div>
      </div>
    </div>
    <div class="client-code-4">
      <div class="client-code-wrapper">
        <div class="client-code-2">
          {{ "{client code}" }}
        </div>
      </div>
    </div>
    <div class="client-code-selector-wrapper">
      <div class="div-2" />
    </div>
  </div>
</template>

<script>
export default {
  name: "ClientCodeSelector",
};
</script>

<style>
.client-code-selector {
  background-color: #414141;
  border-radius: 5px;
  height: 95px;
  left: 120px;
  position: absolute;
  top: 0;
  width: 121px;
}

.client-code-selector .client-code {
  height: 24px;
  left: 5px;
  position: absolute;
  top: 6px;
  width: 108px;
}

.client-code-selector .client-code-wrapper {
  background-color: #7b7b7b;
  border-radius: 3px;
  height: 24px;
  position: relative;
  width: 106px;
}

.client-code-selector .client-code-2 {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 12px;
  font-weight: 700;
  height: 24px;
  left: 0;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 4px;
  width: 106px;
}

.client-code-selector .client-code-3 {
  height: 24px;
  left: 5px;
  position: absolute;
  top: 34px;
  width: 108px;
}

.client-code-selector .client-code-4 {
  height: 24px;
  left: 5px;
  position: absolute;
  top: 62px;
  width: 108px;
}

.client-code-selector .client-code-selector-wrapper {
  background-color: #8b8b8b;
  border-radius: 10px;
  height: 80px;
  left: 113px;
  position: absolute;
  top: 6px;
  width: 6px;
}

.client-code-selector .div-2 {
  background-color: #2c2c2c;
  border-radius: 10px;
  height: 12px;
}
</style>
