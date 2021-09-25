<template>
  <div class="row justify-content-center">
    <div class="col-4 g-0 bg-white border border-primary rounded list-height">
      <div class="border border-primary border-top-0 border-start-0 border-end-0 ">
         <a href="#" class="tab fs-4 text-decoration-none
      d-inline-block p-1 border border-primary border-top-0 border-start-0 border-bottom-0  px-3">
        待辦事項
      </a>
      <a href="#" class="tab fs-4 text-decoration-none
      d-inline-block p-1 border border-primary border-top-0 border-start-0 border-bottom-0 px-3">
        未完成事項
      </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TodoList',
};
</script>

<style>
.list-height{
min-height: 200px;
}
.tab:focus{
background: #fcd5ce;
color: white;
}
</style>
