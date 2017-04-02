<template lang="html">
  <div class="col-sm6 col-md4 col-lg-3">
    <div class=".panel.panel-default">
      <div class="panel-body quote">
        <slot></slot>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ['quotes']
}
</script>

<style lang="css">
panel-body{
  font-family: 'Arizonia',
  font-size: 24px;
  color: #6e6e6e;
}
.quote{
  cursor: pointer;
}
.quote:hover{
  background-color: #ffe2e2;
}
</style>
