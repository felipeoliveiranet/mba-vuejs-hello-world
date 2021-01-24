<template>
  <div id="footer">
    <p class="icons" aria-hidden="true">
      <img src="../assets/fiap-icon.png">
    </p>
    <p>RM {{studentID}}<br/>{{studentName}}</p>
  </div>
</template>

<script>
export default {
  name: 'FooterDefault',
  props: ['studentID', 'studentName']
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#footer {
  background-color: #35495e;
  color: #fff;
  font-size: 14px;
  padding: 5px;
}
</style>
