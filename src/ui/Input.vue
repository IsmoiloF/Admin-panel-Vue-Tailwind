<template>
  <label :for="labelId" class="w-[300px] block my-3">
    <p class="text-indigo-500 my-2">{{ placeholder }}</p>
    <input
    :id="labelId"
      :type="inputType"
      id="form"
      class="p-3 w-full ring-2 focus:ring-cyan-700 focus:outlin placeholder:text-slayd-700"
      :placeholder="placeholder"
    />
  </label>
</template>

<script>
export default {
  name: "Input",
  props: {
    labelId: String,
    placeholder:String,
    inputType:String,
  },
};
</script>

<style lang="scss"></style>
