<template>
  <div class="box h-fit flex justify-center items-center">
    <div class="2xl:container flex justify-center items-center 2xl:mx-auto xl:px-20 md:px-6 px-4">
        <div class=" flex flex-col md:flex-row justify-center items-center space-y-6 md:space-y-0 md:space-x-16 xl:space-x-48">
            <div class="md:flex-shrink-0 flex md:justify-start justify-center items-center md:items-start flex-col space-y-4 lg:space-y-6 ">
                <div class="flex flex-col md:justify-start items-center md:items-start space-y-3 lg:space-y-4">
                    <p class="title my-9">They Said It First</p>
                    <p class="subtitle mb-9">Scuola Maria is fortunate to work with PCI early on when the pandemic <br>hit the country. My ideas and my curriculum design all came to life in <br>the NEST — our exclusive LMS for our students. If not for PCI, we wouldn't <br>be able to continue education at this very difficult time.</p>
                    
                </div>
                <div class="subtitle1 mt-10">
                  Ina Gonda-Ramos, MAE-CDE, LPT 
                </div>
                <div class="designation">
                  Program Director of Scuola Maria
                </div>
                <div class="orange"><div class="black mx-6"></div></div>
            </div>
            <div class="w-full">
                <img class="w-full" src="../assets/testimonial.png">
            </div>
        </div>
    </div>
  </div>

</template>

<style scoped>
.box{
  background: rgba(253, 192, 15, 0.31);

}

.title{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 700;
  font-size: 30px;
  line-height: 32px;
  font-feature-settings: 'liga' off;
  color: #18191F;
}

.subtitle{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 32px;
  font-feature-settings: 'liga' off;
  color: #18191F;
}

.subtitle1{
  font-family: 'Manrope';
  font-style: normal;
  font-weight: 700;
  font-size: 18px;
  line-height: 28px;
  font-feature-settings: 'liga' off;
  color: #222222;
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