<template>
  <div class="card rounded-4 border-0 card-margin px-4 mb-4" style="background-color: #efefef">
    <div class="card-body"> 
     <h3 class="mb-3 text-3">Air Quality</h3>
      <div class="d-flex">
        <div class="me-3">
          <div class="rounded-circle  d-flex justify-content-center bg-color-2 py-3 px-4"><h1 class="text-white">72</h1></div>
        </div>
        <div>
          <div><i class="bi bi-arrow-up-short fs-3 text-2"></i><span class="fs-2 text-4">93</span></div>
          <div class="border-bottom"></div>
          <div><i class="bi bi-arrow-down-short fs-3 text-warning"></i><span class="fs-2 text-4">61</span></div>
        </div>
      </div>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'AirQuality',
  
}
</script>

