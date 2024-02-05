<template>
  <div class="element-choice-panel">
    <div class="data-block-grabber">
      <div class="overlap-6">
        <div class="datablock"></div>
        <div class="text-wrapper-8">Splunk DataBlock</div>
        <div class="cloud-rect">
          <div class="overlap-group-3">
            <div class="text-wrapper-9">Cloud</div>
          </div>
        </div>
        <div class="cloud-check">
          <img
            class="icon-check"
            alt="Icon check"
            src="https://c.animaapp.com/UdvrWtN1/img/---icon--check--5@2x.png"
          />
        </div>
        <div class="platform-rect">
          <div class="overlap-group-3">
            <div class="text-wrapper-9">Platform</div>
          </div>
        </div>
        <div class="platform-check">
          <img
            class="icon-check"
            alt="Icon check"
            src="https://c.animaapp.com/UdvrWtN1/img/---icon--check--5@2x.png"
          />
        </div>
        <div class="datasection">
          <div class="overlap-group-3">
            <div class="datasection-drop">
              <img
                class="icon-nav-arrow-down"
                alt="Icon nav arrow down"
                src="https://c.animaapp.com/UdvrWtN1/img/---icon--nav-arrow-down--1@2x.png"
              />
            </div>
            <p class="p">Please select a data section...</p>
          </div>
        </div>
      </div>
    </div>
    <div class="screenshot-upload">
      <div class="overlap-7">
        <div class="text-wrapper-10">Custom Screenshots</div>
        <div class="overlap-wrapper">
          <div class="overlap-8">
            <div class="screenshot-element-2"></div>
            <img
              class="img"
              alt="Screenshot img"
              src="https://c.animaapp.com/UdvrWtN1/img/screenshotimg@2x.png"
            />
            <div class="overlap-group-wrapper">
              <div class="overlap-group-4">
                <div class="name-and-settings-3"></div>
                <div class="text-wrapper-11">...</div>
                <div class="text-wrapper-12">screenshot_4</div>
              </div>
            </div>
          </div>
        </div>
        <div class="overlap-9">
          <div class="text-wrapper-13">Drop files to upload</div>
          <img
            class="icon-drag-hand"
            alt="Icon drag hand"
            src="https://c.animaapp.com/UdvrWtN1/img/---icon--drag-hand-gesture-@2x.png"
          />
        </div>
        <img
          class="icon-cloud-upload"
          alt="Icon cloud upload"
          src="https://c.animaapp.com/UdvrWtN1/img/---icon--cloud-upload-@2x.png"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ElementChoicePanel",
};
</script>

<style>
.element-choice-panel {
  background-color: #4e4e4e;
  height: 476px;
  left: 768px;
  position: absolute;
  top: 4px;
  width: 270px;
}

.element-choice-panel .data-block-grabber {
  height: 91px;
  left: 21px;
  position: absolute;
  top: 26px;
  width: 229px;
}

.element-choice-panel .overlap-6 {
  height: 91px;
  position: relative;
  width: 227px;
}

.element-choice-panel .datablock {
  background: linear-gradient(180deg, rgb(11.41, 50.73, 1.58) 0%, rgba(60.68, 182.71, 160.74, 0) 100%);
  border-radius: 5px;
  height: 90px;
  left: 0;
  position: absolute;
  top: 1px;
  width: 227px;
}

.element-choice-panel .text-wrapper-8 {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 15px;
  font-weight: 700;
  height: 31px;
  left: 37px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 5px;
  width: 154px;
}

.element-choice-panel .cloud-rect {
  height: 17px;
  left: 34px;
  position: absolute;
  top: 32px;
  width: 79px;
}

.element-choice-panel .overlap-group-3 {
  background-color: #2c2c2c;
  border-radius: 5px;
  height: 19px;
  left: -1px;
  position: relative;
  top: -1px;
}

.element-choice-panel .text-wrapper-9 {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 13px;
  font-weight: 700;
  height: 15px;
  left: 4px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 2px;
  white-space: nowrap;
  width: 70px;
}

.element-choice-panel .cloud-check {
  background-color: #3a3939;
  border-radius: 5px;
  height: 15px;
  left: 13px;
  position: absolute;
  top: 33px;
  width: 15px;
}

.element-choice-panel .icon-check {
  height: 9px;
  left: 3px;
  position: absolute;
  top: 3px;
  width: 10px;
}

.element-choice-panel .platform-rect {
  height: 17px;
  left: 140px;
  position: absolute;
  top: 32px;
  width: 79px;
}

.element-choice-panel .platform-check {
  background-color: #3a3939;
  border-radius: 5px;
  height: 15px;
  left: 119px;
  position: absolute;
  top: 33px;
  width: 15px;
}

.element-choice-panel .datasection {
  height: 17px;
  left: 11px;
  position: absolute;
  top: 61px;
  width: 209px;
}

.element-choice-panel .datasection-drop {
  background-color: #3a3939;
  border-radius: 5px;
  height: 13px;
  left: 190px;
  position: absolute;
  top: 3px;
  width: 16px;
}

.element-choice-panel .icon-nav-arrow-down {
  height: 5px;
  left: 3px;
  position: absolute;
  top: 4px;
  width: 10px;
}

.element-choice-panel .p {
  color: #9c9c9c;
  font-family: "Inter", Helvetica;
  font-size: 10px;
  font-weight: 400;
  height: 13px;
  left: 7px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 3px;
  width: 174px;
}

.element-choice-panel .screenshot-upload {
  height: 304px;
  left: 21px;
  position: absolute;
  top: 146px;
  width: 231px;
}

.element-choice-panel .overlap-7 {
  background: linear-gradient(180deg, rgb(119.99, 71.98, 136.85) 0%, rgba(39.68, 57.32, 149.88, 0) 100%);
  border-radius: 5px;
  height: 304px;
  position: relative;
  width: 227px;
}

.element-choice-panel .text-wrapper-10 {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 15px;
  font-weight: 700;
  height: 31px;
  left: 35px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 8px;
  width: 154px;
}

.element-choice-panel .overlap-wrapper {
  height: 53px;
  left: 18px;
  position: absolute;
  top: 51px;
  width: 77px;
}

.element-choice-panel .overlap-8 {
  height: 55px;
  left: -1px;
  position: relative;
  top: -1px;
  width: 82px;
}

.element-choice-panel .screenshot-element-2 {
  background-color: #2c2c2c;
  border: 1px solid;
  border-color: transparent;
  border-image: linear-gradient(to bottom, rgb(70.36, 166.37, 255), rgba(0, 79.8, 153.46, 0.96)) 1;
  border-radius: 5px;
  height: 55px;
  left: 0;
  position: absolute;
  top: 0;
  width: 79px;
}

.element-choice-panel .img {
  height: 36px;
  left: 1px;
  object-fit: cover;
  position: absolute;
  top: 1px;
  width: 77px;
}

.element-choice-panel .overlap-group-wrapper {
  height: 25px;
  left: 1px;
  position: absolute;
  top: 29px;
  width: 81px;
}

.element-choice-panel .overlap-group-4 {
  height: 26px;
  position: relative;
  width: 78px;
}

.element-choice-panel .name-and-settings-3 {
  background-color: #2c2c2c;
  border: 0.5px solid;
  border-color: transparent;
  border-image: linear-gradient(to bottom, rgb(70.36, 166.37, 255), rgba(0, 79.8, 153.46, 0.96)) 1;
  border-radius: 5px;
  height: 18px;
  left: 0;
  position: absolute;
  top: 8px;
  width: 78px;
}

.element-choice-panel .text-wrapper-11 {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 15px;
  font-weight: 700;
  height: 25px;
  left: 56px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 0;
  width: 19px;
}

.element-choice-panel .text-wrapper-12 {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 6px;
  font-weight: 400;
  height: 13px;
  left: 4px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 10px;
  width: 53px;
}

.element-choice-panel .overlap-9 {
  height: 62px;
  left: 37px;
  position: absolute;
  top: 214px;
  width: 154px;
}

.element-choice-panel .text-wrapper-13 {
  color: #d1d1d1;
  font-family: "Inter", Helvetica;
  font-size: 15px;
  font-weight: 700;
  height: 31px;
  left: 0;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 32px;
  width: 154px;
}

.element-choice-panel .icon-drag-hand {
  height: 33px;
  left: 57px;
  position: absolute;
  top: 0;
  width: 34px;
}

.element-choice-panel .icon-cloud-upload {
  height: 28px;
  left: 99px;
  position: absolute;
  top: 181px;
  width: 30px;
}
</style>
