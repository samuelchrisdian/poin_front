<template>
  <!-- <footer
    class="footer"
    :data-background-color="backgroundColor"
  >
    <div class="container">
      <div class="copyright" align="center">
        &copy; {{ year }}, Designed by
        SMK Telkom Malang
      </div>
    </div>
  </footer>-->

  <footer class="footer">
    <div class="w-100 clearfix" align="center">
      <span class="text-muted d-block text-center text-sm-left d-sm-inline-block">
        Copyright &copy; {{ year }}
        <a href="http://www.urbanui.com/" target="_blank">Moklet</a>. All rights reserved.
      </span>
    </div>
  </footer>
</template>
<script>
export default {
  props: {
    backgroundColor: String,
    type: String
  },
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
