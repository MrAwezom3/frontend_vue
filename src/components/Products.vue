<template>
      <div class="2xl:container 2xl:mx-auto">
          <div class="lg:px-20 md:px-6 px-4 md:py-12 py-8">
              <div class="products justify-center flex">
                OUR PRODUCTS
              </div>
              <div class="learn justify-center flex">
                Learn without Limits
              </div>
              <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 lg:gap-8 mt-8 md:mt-10">
                  <div class="p-8">
                      <div class="flex justify-center items-center mb-8 md:mt-24">
                          <img class="" src="../assets/product1.svg"/>
                      </div>
                      <div class="flex justify-center items-center bold">
                            Educat LMS
                      </div>
                      <div class="flex justify-center items-center notbold">
                        A Learning Management System and content library that offers a variety of ways on how to learn through blended learning.
                      </div>
                  </div>
                  <div class="p-8">
                      <div class="flex justify-center items-center mb-8 md:mt-24">
                          <img class="" src="../assets/product2.svg" />
                      </div>
                      <div class="flex justify-center items-center bold">
                            Educat Library
                      </div>
                      <div class="flex justify-center items-center notbold">
                        An online library that contains Digital Modules, Worksheets and Assessments aligned with DepEd’s K to 12 Curriculum
                      </div>
                  </div>
                  <div class="p-8">
                      <div class="flex justify-center items-center mb-8 md:mt-24">
                          <img class="" src="../assets/product3.svg"/>
                      </div>
                      <div class="flex justify-center items-center bold">
                            Educat Rover
                      </div>
                      <div class="flex justify-center items-center notbold">
                        An offline solution run by mini-computers that are equipped with wireless local area network for contactless file transfers.
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