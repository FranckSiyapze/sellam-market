<template>
  <div >
    <div class="row mx-0 c">
      <div class="col-4 pos">
        column
      </div>
      <div class="col-8">
        <BlocProduct/>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.pos{
  position: sticky;
  width: 260px;
  min-width: 260px;
}
.c{
  position: static;
}
</style>
