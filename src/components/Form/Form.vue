<template>
  <div>
    <h1 class="text-center text-indigo-700">Form elements</h1>

    <Input inputType="text" placeholder="Enter user name" labelId="username" />

    <Input
      inputType="password"
      placeholder="`Enter password`"
      labelId="password"
    />

    <Button btnType="button" textContent="SIGN UP" class="hover:bg-green-700" />

    <Card >
      <img src="https://picsum.photos/id/356/320/210" alt="" />

      <div class="card-body p-3">
        <h1 class="text-3xl">Card titile</h1>

        <p class="text-xl my-2">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Error,
          excepturi!
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Et, dolores.
        </p>
        <div>
          
          <Button btnType="button" textContent="DIS LIKE" class="bg-red-500 my-3 h-[50px]" />
          <Button btnType="button" textContent="LIKE" class="bg-green-500 my-3 mx-2 h-[50px]" />

        </div>
      </div>
    </Card>
  </div>
</template>
<script>
import Card from "../../ui/Card.vue";
import Button from "../../ui/Button.vue";
import Input from "../../ui/Input.vue";

export default {
  name: "Form",
  components: {
    Input,
    Button,
    Card,
  },
};
</script>
<style lang="scss"></style>
