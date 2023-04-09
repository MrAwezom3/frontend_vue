<template>
  <div class="2xl:container 2xl:mx-auto">
      <div class="lg:px-20 md:px-6 px-4 md:py-12 py-8">
          <div class="products justify-center flex">
            OUR HAPPY CLIENTS
          </div>
          <div class="learn justify-center flex">
            Our Partners
          </div>
          <div class="grid grid-cols-6 gap-6 lg:gap-8">
              <div class="p-4">
                  <div class="flex justify-center items-center mb-8 md:mt-12 grayscale hover:grayscale-0 transition">
                      <img class="" src="../assets/Partners/partner1.png"/>
                  </div>
              </div>
              <div class="p-4">
                <div class="flex justify-center items-center mb-8 md:mt-12 grayscale hover:grayscale-0 transition">
                      <img class="" src="../assets/Partners/partner2.png" />
                  </div>
              </div>
              <div class="p-4">
                <div class="flex justify-center items-center mb-8 md:mt-12 grayscale hover:grayscale-0 transition">
                      <img class="" src="../assets/Partners/partner3.png" />
                  </div>
              </div>
              <div class="p-4">
                <div class="flex justify-center items-center mb-8 md:mt-12 grayscale hover:grayscale-0 transition">
                      <img class="" src="../assets/Partners/partner4.png" />
                  </div>
              </div>
              <div class="p-4">
                <div class="flex justify-center items-center mb-8 md:mt-12 grayscale hover:grayscale-0 transition">
                      <img class="" src="../assets/Partners/partner5.png" />
                  </div>
              </div>
              <div class="p-4">
                <div class="flex justify-center items-center mb-8 md:mt-12 grayscale hover:grayscale-0 transition">
                      <img class="" src="../assets/Partners/partner6.png" />
                  </div>
              </div>

          </div>
      </div>
  </div>
</template>

<script>
export default {
name: "component",
data() {
  return {};
},
};
</script>



<style scoped>
.products{
font-family: 'Noto Serif';
font-style: normal;
font-weight: 700;
font-size: 20px;
line-height: 140%;
letter-spacing: 0.165em;
color: #CBCBCB;

}

.learn{
font-family: 'Poppins';
font-style: normal;
font-weight: 700;
font-size: 35px;
line-height: 140%;
text-align: center;
letter-spacing: 0.02em;
color: #222222;
}

.bold{
font-family: 'Poppins';
font-style: normal;
font-weight: 600;
font-size: 18px;
line-height: 163.42%;
text-align: center;
color: #121212;
}

.notbold{
font-family: 'Noto Serif';
font-style: normal;
font-weight: 400;
font-size: 14px;
line-height: 170.23%;
text-align: center;
color: #545454;
}

</style>