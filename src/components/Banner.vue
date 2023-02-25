<template>
   <div id="main-banner">
      <h1>Arte&Burger</h1>
   </div> 
</template>

<script>
export default {
   name: "Banner"
}
</script>

<style scoped>
#main-banner {
      background-image: url('~@/assets/burger.jpg') !important;
      background-position: 0;
      background-size: cover;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: flex-start;
   }

   #main-banner h1 {
      color: #FFF;
      text-align: center;
      font-size: 35px;
      background-color: #222;
   }

</style>