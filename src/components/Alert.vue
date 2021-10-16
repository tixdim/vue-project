<template>
  <div>
    <!-- <div if {{ message }} = "Note added" > <b-alert variant="success" show>{{ message }}</b-alert> </div> -->
    <b-alert variant="success" show>{{ message }}</b-alert>
    <br>
  </div>
</template>

<script>
export default {
  props: ['message'],
};
</script>