<template>
  <div class="overlap">
    <FlowBox />
    <ElementChoicePanel />
    <ClientCodeSelector />
    <ManageFieldBox />
  </div>
</template>

<script>
import FlowBox from "./Overlap/sections/FlowBox.vue";
import ElementChoicePanel from "./Overlap/sections/ElementChoicePanel.vue";
import ClientCodeSelector from "./Overlap/sections/ClientCodeSelector.vue";
import ManageFieldBox from "./Overlap/sections/ManageFieldBox.vue";

export default {
  name: "Overlap",
  components: {
    FlowBox,
    ElementChoicePanel,
    ClientCodeSelector,
    ManageFieldBox,
  },
};
</script>

<style>
.overlap {
  height: 480px;
  left: 38px;
  position: absolute;
  top: 65px;
  width: 1038px;
}
</style>