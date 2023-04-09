<template>
  <div class="box h-fit lg:mx-60 mx-30 flex justify-center items-center">
    <div class="2xl:container flex justify-center items-center 2xl:mx-auto xl:px-20 md:px-6 px-4">
        <div class=" flex flex-col md:flex-row justify-center items-center space-y-6 md:space-y-0 md:space-x-16 xl:space-x-48 my-10">
            <div class="w-full lg:block hidden">
                <img class="w-full" src="../assets/cat.svg">
            </div>
            <div class="md:flex-shrink-0  md:justify-start justify-center items-center md:items-start flex-col space-y-4 lg:space-y-6 grid place-items-center ">
                <div class="flex flex-col md:justify-start items-center md:items-start space-y-3 lg:space-y-4">
                    <p class="title mt-1 items-center justify-center flex">Want to see what Educat can do for you?</p>
                    <p class="subtitle mb-9 flex">Learn more by booking a demo today and discover why Educat is the only <br>platform you'll ever need for your learning and training needs.</p>
                </div>
                <button class="subtitle1 h-[61px] w-[279px] ">
                  TAKE A LOOK
                </button>
            </div>
            <div class="w-full flex">
              <img class="w-full block lg:hidden" src="../assets/cat.svg">
              <img class="w-full" src="../assets/paws.svg">
            </div>
        </div>
    </div>
  </div>

</template>

<style scoped>
.box{
  background: #3966D8;
  border-radius: 15px;

}

.title{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 700;
  font-size: 30px;
  line-height: 163.42%;
  text-align: center;
  color: #FFFFFF;
}

.subtitle{
  font-family: 'Noto Serif';
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 183.85%;
  text-align: center;
  color: #FFFFFF;
}

.subtitle1{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 30px;
  color: #4474FF;
  background-color: #FFFFFF;
}

.designation{
  font-family: 'Manrope';
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 26px;
  font-feature-settings: 'liga' off;
  color: #18191F;
}

.orange{
  height: 10px;
  width: 10px;
  border-radius: 50%;
  background: #FDC00F;
}

  .black{
  height: 10px;
  width: 10px;
  border-radius: 50%;
  background: #222222;
}

</style>