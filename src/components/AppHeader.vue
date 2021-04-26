<template>
  <div>
    <button v-show="loggedIn" type="button">Logout</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      loggedIn: false,
    };
  },
};
</script>
