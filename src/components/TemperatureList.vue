<template>
    <div class="card rounded-4 border-0 card-margin px-4 mb-4" style="background-color: #efefef">
    <div class="card-body"> 
     <h3 class="mb-3 text-3">Temperature</h3>
      <div class="d-flex">
        <div class="me-3">
          <div class="rounded-circle  d-flex justify-content-center bg-color-1 p-3 pt-4"><h1 class="text-white">21<span>&#176;</span>c</h1></div>
        </div>
        <div>
          <div class="d-flex align-items-center"><span class="me-2"> <img src="../assets/fire.svg"/></span><span class="fs-2 text-4">26<span>&#176;</span>c</span></div>
          <div class="border-bottom"></div>
          <div class="d-flex align-items-center"><span class="me-2"> <img src="../assets/snowflake.svg"/></span><span class="fs-2 text-4">18<span>&#176;</span>c</span></div>
        </div>
      </div>
    </div>
    
  </div>
  </template>
  
  <script>
  export default {
    name: 'TemperatureList',
    
  }
  </script>