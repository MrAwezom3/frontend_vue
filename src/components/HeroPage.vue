<template>
  
  <div class="2xl:container flex justify-center items-center 2xl:mx-auto xl:px-20 md:px-6 px-4 py-12">
        <div class=" flex flex-col md:flex-row justify-center items-center space-y-6 md:space-y-0 md:space-x-16 xl:space-x-48">
            <div class="md:flex-shrink-0 flex md:justify-start justify-center items-center md:items-start flex-col space-y-4 lg:space-y-6 ">
                <div class="flex flex-col md:justify-start items-center md:items-start space-y-3 lg:space-y-4">
                    <p class="bold">The LMS that's <br>built for your <br>needs</p>
                    <p class="notbold">Experience seamless communication, easy data <br>migration, and secured user management in one <br>awesome platform.</p>
                </div>
                <button class="h-[50px] w-[262px] hidden  md:block bold2">
                    GO TO LMS PORTAL
                </button>
            </div>
            <div class="w-full image-container">
                <img class="w-full" src="../assets/hero-banner.png">
            </div>
            <button class="h-[50px] w-[262px] md:hidden bold2">
              GO TO LMS PORTAL
            </button>
        </div>
    </div>

</template>

<style scoped>

.bold{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 800;
  font-size: 55px;
  line-height: 118.92%;
  color: #000000;
}

.bold2{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 24px;
  color: #FFFFFF;
  background: #3966D8;
  border-radius: 5px;
}


.image-container {
  position: relative;
}

.image-container::before {
  content: "";
  display: block;
  position: absolute;
  top: 47%;
  left: 56%;
  transform: translate(-50%, -50%);
  border-radius: 50%;
  width: 500px;
  height: 500px;
  border: 3px solid #eed64b;
  opacity: 0.7;
  animation: pulse 2s infinite;
  z-index: -1;
}

@keyframes pulse {
  0% {
    transform: translate(-50%, -50%) scale(1);
    opacity: 0.7;
  }
  50% {
    transform: translate(-50%, -50%) scale(1.2);
    opacity: 0.4;
  }
  100% {
    transform: translate(-50%, -50%) scale(1);
    opacity: 0.7;
  }
}
.notbold{
  font-family: 'Noto Serif';
  font-style: normal;
  font-weight: 400;
  font-size: 20px;
  line-height: 118.92%;
  color: #545454;
}

</style>