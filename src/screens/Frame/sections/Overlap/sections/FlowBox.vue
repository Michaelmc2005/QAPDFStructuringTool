<template>
  <div class="flow-box">
    <div class="flowbox-outer">
      <div class="flowbox-inner">
        <div class="flow-data-block">
          <div class="overlap-group">
            <div class="text-wrapper">Splunk DataBlock</div>
            <div class="flow-data-section">
              <div class="div">
                <div class="flow-datasection">
                  <img
                    class="icon-edit-pencil"
                    alt="Icon edit pencil"
                    src="https://c.animaapp.com/UdvrWtN1/img/---icon--edit-pencil-@2x.png"
                  />
                </div>
                <div class="text-wrapper-2">Data Section: Users</div>
              </div>
            </div>
            <div class="preview-manage">
              <div class="div-wrapper">
                <div class="text-wrapper-3">Preview/Manage Fields</div>
              </div>
            </div>
          </div>
        </div>
        <div class="flow-custom">
          <div class="overlap-2">
            <div class="text-wrapper">Custom Screenshot</div>
            <div class="screenshot-group">
              <div class="overlap-3">
                <div class="screenshot-element" />
                <img
                  class="screenshot-img"
                  alt="Screenshot img"
                  src="https://c.animaapp.com/UdvrWtN1/img/screenshotimg-1@2x.png"
                />
                <div class="name-and-settings">
                  <div class="overlap-group-2">
                    <div class="name-and-settings-2" />
                    <div class="text-wrapper-4">...</div>
                    <div class="text-wrapper-5">screenshot_4</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="flow-line" />
        <div class="flow-line-2" />
        <div class="add-flow">
          <div class="overlap-4">
            <div class="add-flow-circle" />
            <div class="text-wrapper-6">+</div>
          </div>
        </div>
        <div class="flow-box-scroller-wrapper">
          <div class="flow-box-scroller" />
        </div>
      </div>
      <div class="end-pdfbutton">
        <div class="overlap-5">
          <div class="text-wrapper-7">End PDF</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FlowBox",
};
</script>

<style>
.flow-box {
  height: 476px;
  left: 0;
  position: absolute;
  top: 4px;
  width: 755px;
}

.flow-box .flowbox-outer {
  background-color: #4e4e4e;
  border-radius: 4px;
  height: 476px;
  position: relative;
}

.flow-box .flowbox-inner {
  background-color: #414141;
  border-radius: 5px;
  height: 390px;
  left: 18px;
  position: absolute;
  top: 37px;
  width: 719px;
}

.flow-box .flow-data-block {
  height: 55px;
  left: 34px;
  position: absolute;
  top: 16px;
  width: 653px;
}

.flow-box .overlap-group {
  background: linear-gradient(180deg, rgb(18.37, 33.35, 14.62) 0%, rgba(19.74, 93.48, 1.31, 0.3) 100%);
  border-radius: 5px;
  height: 59px;
  left: -2px;
  position: relative;
  top: -2px;
  width: 655px;
}

.flow-box .text-wrapper {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 15px;
  font-weight: 700;
  height: 31px;
  left: 9px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 14px;
  width: 154px;
}

.flow-box .flow-data-section {
  height: 31px;
  left: 238px;
  position: absolute;
  top: 14px;
  width: 182px;
}

.flow-box .div {
  background-color: #2c2c2c;
  border-radius: 10px;
  height: 31px;
  position: relative;
  width: 180px;
}

.flow-box .flow-datasection {
  background-color: #3a3939;
  border-radius: 5px;
  height: 25px;
  left: 153px;
  position: absolute;
  top: 3px;
  width: 23px;
}

.flow-box .icon-edit-pencil {
  height: 16px;
  left: 4px;
  position: absolute;
  top: 3px;
  width: 16px;
}

.flow-box .text-wrapper-2 {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 13px;
  font-weight: 600;
  height: 31px;
  left: 0;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 0;
  width: 154px;
}

.flow-box .preview-manage {
  height: 37px;
  left: 531px;
  position: absolute;
  top: 12px;
  width: 116px;
}

.flow-box .div-wrapper {
  background-color: #2c2c2c;
  border-radius: 10px;
  height: 37px;
  position: relative;
  width: 114px;
}

.flow-box .text-wrapper-3 {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 11px;
  font-weight: 700;
  height: 37px;
  left: 0;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 0;
  width: 114px;
}

.flow-box .flow-custom {
  height: 55px;
  left: 34px;
  position: absolute;
  top: 156px;
  width: 653px;
}

.flow-box .overlap-2 {
  background-color: #2c2c2c;
  border-radius: 5px;
  height: 59px;
  left: -2px;
  position: relative;
  top: -2px;
  width: 655px;
}

.flow-box .screenshot-group {
  height: 44px;
  left: 568px;
  position: absolute;
  top: 8px;
  width: 77px;
}

.flow-box .overlap-3 {
  height: 46px;
  left: -1px;
  position: relative;
  top: -1px;
  width: 82px;
}

.flow-box .screenshot-element {
  background-color: #2c2c2c;
  border: 1px solid;
  border-color: transparent;
  border-image: linear-gradient(to bottom, rgb(70.36, 166.37, 255), rgba(0, 79.8, 153.46, 0.96)) 1;
  border-radius: 5px;
  height: 46px;
  left: 0;
  position: absolute;
  top: 0;
  width: 79px;
}

.flow-box .screenshot-img {
  height: 30px;
  left: 1px;
  object-fit: cover;
  position: absolute;
  top: 1px;
  width: 77px;
}

.flow-box .name-and-settings {
  height: 21px;
  left: 1px;
  position: absolute;
  top: 24px;
  width: 81px;
}

.flow-box .overlap-group-2 {
  height: 21px;
  position: relative;
  width: 78px;
}

.flow-box .name-and-settings-2 {
  background-color: #2c2c2c;
  border: 0.5px solid;
  border-color: transparent;
  border-image: linear-gradient(to bottom, rgb(70.36, 166.37, 255), rgba(0, 79.8, 153.46, 0.96)) 1;
  border-radius: 5px;
  height: 15px;
  left: 0;
  position: absolute;
  top: 6px;
  width: 78px;
}

.flow-box .text-wrapper-4 {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 15px;
  font-weight: 700;
  height: 21px;
  left: 56px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 0;
  width: 19px;
}

.flow-box .text-wrapper-5 {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 6px;
  font-weight: 400;
  height: 11px;
  left: 4px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 8px;
  width: 53px;
}

.flow-box .flow-line {
  background-color: #d9d9d9;
  height: 55px;
  left: 356px;
  position: absolute;
  top: 86px;
  width: 6px;
}

.flow-box .flow-line-2 {
  background-color: #d9d9d9;
  height: 55px;
  left: 356px;
  position: absolute;
  top: 227px;
  width: 6px;
}

.flow-box .add-flow {
  height: 27px;
  left: 347px;
  position: absolute;
  top: 297px;
  width: 27px;
}

.flow-box .overlap-4 {
  height: 27px;
  position: relative;
  width: 25px;
}

.flow-box .add-flow-circle {
  background-color: #d9d9d9;
  border-radius: 12.5px;
  height: 25px;
  left: 0;
  position: absolute;
  top: 2px;
  width: 25px;
}

.flow-box .text-wrapper-6 {
  color: #545454;
  font-family: "Inter", Helvetica;
  font-size: 15px;
  font-weight: 700;
  height: 27px;
  left: 3px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 0;
  width: 19px;
}

.flow-box .flow-box-scroller-wrapper {
  background-color: #8b8b8b;
  border-radius: 10px;
  height: 340px;
  left: 698px;
  position: absolute;
  top: 14px;
  width: 6px;
}

.flow-box .flow-box-scroller {
  background-color: #2c2c2c;
  border-radius: 10px;
  height: 51px;
}

.flow-box .end-pdfbutton {
  height: 28px;
  left: 298px;
  position: absolute;
  top: 440px;
  width: 160px;
}

.flow-box .overlap-5 {
  background: linear-gradient(180deg, rgb(140.25, 172.38, 255) 0%, rgba(33.6, 0, 167.98, 0.79) 100%);
  border-radius: 20px;
  height: 28px;
  position: relative;
  width: 158px;
}

.flow-box .text-wrapper-7 {
  color: #ffffff;
  font-family: "Inter", Helvetica;
  font-size: 15px;
  font-weight: 700;
  height: 16px;
  left: 43px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 6px;
  white-space: nowrap;
  width: 73px;
}
</style>
