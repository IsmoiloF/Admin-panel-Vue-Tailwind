<template>
  <button :type="btnType" class="py-2 px-3 border bg-green-500 rounded-md focus:ring-sky-400 text-white">{{ textContent }}</button>
</template>

<script>
export default {
  name:"Button",
  props:{
    btnType:String,
    textContent:String
  }
};
</script>

<stylem lang="scss"></stylem>
