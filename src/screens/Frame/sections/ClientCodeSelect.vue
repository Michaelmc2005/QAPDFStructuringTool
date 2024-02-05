<template>
  <div class="client-code-select">
    <div class="overlap-10">
      <div class="div-3"></div>
      <div class="text-wrapper-15">Select a client</div>
      <div class="icon-nav-arrow-down-wrapper">
        <img
          class="icon-nav-arrow-down-2"
          alt="Icon nav arrow down"
          src="https://c.animaapp.com/UdvrWtN1/img/---icon--nav-arrow-down-@2x.png"
        />
      </div>
      <div class="text-wrapper-16">Client Code:</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ClientCodeSelect",
};
</script>

<style>
.client-code-select {
  height: 39px;
  left: 38px;
  position: absolute;
  top: 22px;
  width: 245px;
}

.client-code-select .overlap-10 {
  height: 41px;
  position: relative;
  top: -1px;
  width: 242px;
}

.client-code-select .div-3 {
  background-color: #2c2c2c;
  border: 1px solid;
  border-color: transparent;
  border-image: linear-gradient(to bottom, rgb(70.36, 166.37, 255), rgba(0, 79.8, 153.46, 0.96)) 1;
  border-radius: 5px;
  height: 41px;
  left: 119px;
  position: absolute;
  top: 0;
  width: 123px;
}

.client-code-select .text-wrapper-15 {
  color: #9c9c9c;
  font-family: "Inter", Helvetica;
  font-size: 10px;
  font-weight: 400;
  height: 18px;
  left: 130px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 11px;
  width: 77px;
}

.client-code-select .icon-nav-arrow-down-wrapper {
  background-color: #3a3939;
  border-radius: 5px;
  height: 35px;
  left: 217px;
  position: absolute;
  top: 3px;
  width: 22px;
}

.client-code-select .icon-nav-arrow-down-2 {
  height: 10px;
  left: 2px;
  position: absolute;
  top: 14px;
  width: 18px;
}

.client-code-select .text-wrapper-16 {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 16px;
  font-weight: 700;
  height: 34px;
  left: 0;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 3px;
  width: 120px;
}
</style>
