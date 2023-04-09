<template>
    <div class="2xl:container 2xl:mx-auto">
      <div class="lg:px-20 md:px-6 px-4 md:py-12 py-8">
  <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 justify-center items-center mx-10">
      <div class="grid grid-rows-2 justify-center items-center">
        <div class="number" id="counter1">0</div>
        <div class="title">Learning Materials Donated</div>
      </div>
      <div class="grid grid-rows-2 justify-center items-center">
        <div class="number" id="counter3">0</div>
        <div class="title">LMS Users</div>
      </div>
      <div class="grid grid-rows-2 justify-center items-center">
        <div class="number" id="counter2">0</div>
        <div class="title">Trained Professional</div>
      </div>
      <div class="grid grid-rows-2 justify-center items-center">
        <div class="number" id="0104">000</div>
        <div class="title">Lorem Ipsum</div>
      </div>
      </div>
      </div>
  </div>

</template>
<script>
      function countUp(target, duration, elementId) {
        let start = 0;
        let end = target;
        let range = end - start;
        let current = start;
        let increment = end > start ? 1 : -1;
        let stepTime = Math.abs(Math.floor(duration / range));
        let timer = setInterval(function() {
          current += increment;
          document.getElementById(elementId).innerText = current.toLocaleString();
          if (current == end) {
            clearInterval(timer);
          }
        }, stepTime);
      }
      countUp(1200, 5000, 'counter1'); 
      countUp(5500, 5000, 'counter2'); 
      countUp(3000, 5000, 'counter3'); 
    </script>
<style scoped>
.number{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 700;
  font-size: 48px;
  line-height: 64px;
  text-align: center;
  font-feature-settings: 'liga' off;
  color: #7BC144;
}

.title{
  font-family: 'Manrope';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 32px;
  text-align: center;
  font-feature-settings: 'liga' off;
  color: #18191F;
}

</style>

