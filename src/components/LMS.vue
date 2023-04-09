<template>
  
  <div class="2xl:container flex justify-center items-center 2xl:mx-auto xl:px-20 md:px-6 px-4 py-12 container reveal fade-right">
        <div class=" flex flex-col md:flex-row justify-center items-center space-y-6 md:space-y-0 md:space-x-16 xl:space-x-48">
            <div class="md:flex-shrink-0 flex md:justify-start justify-center items-center md:items-start flex-col space-y-4 lg:space-y-6 ">
              <div class="w-full">
                <img class="w-full" src="../assets/lms1.png">
              </div>

            </div>
            <div class="flex flex-col md:justify-start items-center md:items-start space-y-3 lg:space-y-4">
                    <p class="bold mb-9">General Education</p>
                    <p class="notbold">Transform your learning digitally. <br>Streamline all your school processes in <br>one platform made especially for <br>students, for teachers, and for parents.</p>
                    <button class=" bold2">
                    Learn More
                </button>
            </div>
        </div>
    </div>



    <div class="2xl:container flex justify-center items-center 2xl:mx-auto xl:px-20 md:px-6 px-4 py-12 container reveal fade-left">
        <div class=" flex flex-col md:flex-row justify-center items-center space-y-6 md:space-y-0 md:space-x-16 xl:space-x-48">
            <div class="md:flex-shrink-0 flex md:justify-start justify-center items-center md:items-start flex-col space-y-4 lg:space-y-6 ">
                <div class="flex flex-col md:justify-start items-center md:items-start space-y-3 lg:space-y-4">
                    <p class="bold mb-9">Professional Training</p>
                    <p class="notbold">Bringing you a platform that provides end to <br>end solution in the training process for your <br>employees, customers, or partners that allows. </p>
                    
                </div>
                <button class=" bold2">
                    Learn More
                </button>
            </div>
            <div class="w-full">
                <img class="w-full" src="../assets/lms2.png">
            </div>
        </div>
    </div>

</template>

<script>
function reveal() {
  var reveals = document.querySelectorAll(".reveal");

  for (var i = 0; i < reveals.length; i++) {
    var windowHeight = window.innerHeight;
    var elementTop = reveals[i].getBoundingClientRect().top;
    var elementVisible = 150;

    if (elementTop < windowHeight - elementVisible) {
      reveals[i].classList.add("active");
    } else {
      reveals[i].classList.remove("active");
    }
  }
}

window.addEventListener("scroll", reveal);
</script>

<style scoped>

.reveal {
  position: relative;
  opacity: 0;
}

.reveal.active {
  opacity: 1;
}
.active.fade-bottom {
  animation: fade-bottom 1s ease-in;
}
.active.fade-left {
  animation: fade-left 1s ease-in;
}
.active.fade-right {
  animation: fade-right 1s ease-in;
}
@keyframes fade-bottom {
  0% {
    transform: translateY(50px);
    opacity: 0;
  }
  100% {
    transform: translateY(0);
    opacity: 1;
  }
}
@keyframes fade-left {
  0% {
    transform: translateX(-100px);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}

@keyframes fade-right {
  0% {
    transform: translateX(100px);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}


.bold{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 700;
  font-size: 35px;
  line-height: 140%;
  text-align: center;
  letter-spacing: 0.02em;
  color: #000000;
}

.bold2{
  font-family: 'Poppins';
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 186.5%;
  letter-spacing: 0.02em;
  color: #3966D8;
}


.notbold{
  font-family: 'Noto Serif';
  font-style: normal;
  font-weight: 400;
  font-size: 20px;
  line-height: 186.5%;
  letter-spacing: 0.02em;
  color: #545454;
}

</style>