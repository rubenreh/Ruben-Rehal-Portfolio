<script>
export default {
  data() {
    return {
      activeTab: 1,
      tech: [
        {
          id: 1,
          name: 'C++',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/c++icon.png?raw=true',
          status: 'Advanced'
        },
        {
          id: 2,
          name: 'Java',
          imageUrl: 'https://raw.githubusercontent.com/rubenreh/Ruben-Rehal-Portfolio/main/public/img/javaicon.webp',
          status: 'Advanced'
        },
        {
          id: 3,
          name: 'VHDL',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/vhdlicon.png?raw=true',
          status: 'Advanced'
        },
        {
          id: 4,
          name: 'Microcontrollers',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/microicon.png?raw=true',
          status: 'Advanced'
        },
        {
          id: 5,
          name: 'C',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/Cicon.png?raw=true',
          status: 'Intermediate'
        },
        {
          id: 6,
          name: 'PCB Design',
          imageUrl: 'https://raw.githubusercontent.com/rubenreh/Ruben-Rehal-Portfolio/main/public/img/pcbicon.webp',
          status: 'Advanced'
        },
        {
          id: 7,
          name: 'Python',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/pythonicon.png?raw=true',
          status: 'Intermediate'
        },
        {
          id: 8,
          name: 'UI Design',
          imageUrl: 'https://raw.githubusercontent.com/rubenreh/Ruben-Rehal-Portfolio/main/public/img/uiicon.webp',
          status: 'Intermediate'
        },
        {
          id: 9,
          name: 'HTML',
          imageUrl: 'https://raw.githubusercontent.com/rubenreh/Ruben-Rehal-Portfolio/main/public/img/htmlicon.webp',
          status: 'Intermediate'
        },
        {
          id: 10,
          name: 'Circuit Design',
          imageUrl: 'https://raw.githubusercontent.com/rubenreh/Ruben-Rehal-Portfolio/main/public/img/circuitnewicon.webp',
          status: 'Intermediate'
        },
        {
          id: 11,
          name: 'Racket',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/racketicon.png?raw=true',
          status: 'Beginner'
        },
        {
          id: 12,
          name: 'RISC-V ISA',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/riscV.png?raw=true',
          status: 'Intermediate'
        }
      ],
      tools: [
        {
          id: 1,
          name: 'Solidworks',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/solidworksicon.jpg?raw=true',
          status: 'Advanced'
        },
        {
          id: 2,
          name: 'GitHub',
          imageUrl: 'https://cdn-icons-png.flaticon.com/512/25/25231.png',
          status: 'Intermediate'
        },
        {
          id: 3,
          name: 'Inventor',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/inventoricon.png?raw=true',
          status: 'Advanced'
        },
        {
          id: 4,
          name: 'KiCad',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/kicadicon.png?raw=true',
          status: 'Advanced'
        },
        {
          id: 5,
          name: 'AutoCAD',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/autocadicon.png?raw=true',
          status: 'Advanced'
        },
        {
          id: 6,
          name: 'XCode',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/xcodeicon.png?raw=true',
          status: 'Intermediate'
        },
        {
          id: 7,
          name: 'MATLAB',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/matlabicon.png?raw=true',
          status: 'Intermediate'
        },
        {
          id: 8,
          name: 'Arduino IDE',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/arduinoicon.png?raw=true',
          status: 'Advanced'
        },
        {
          id: 9,
          name: 'mockAPI',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/mockapiicon.png?raw=true',
          status: 'Intermediate'
        },
        {
          id: 10,
          name: 'Altium Designer',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/altiumicon.png?raw=true',
          status: 'Intermediate'
        },
        {
          id: 11,
          name: 'Assembly',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/Assembly.png?raw=true',
          status: 'Intermediate'
        },
        {
          id: 12,
          name: 'Linux',
          imageUrl: 'https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/linuxicon.png?raw=true',
          status: 'Intermediate'
        }
      ]
    };
  }
}
</script>
<template>
  <div
    class="bg-[#1e1e1f] px-5 py-5 md:px-12 md:py-10 text-left border border-[#383838] rounded-3xl text-amber-50 mx-3 mb-5">
    <article data-page="about">

      <header>
        <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
          About Me &nbsp;
          <div class="h-[1px] w-32 bg-amber-200 md:w-96 aos-init aos-animate" data-aos="zoom-in-left"
            data-aos-duration="600"></div>
        </div>
      </header>

      <section
        class="text-sm md:text-lg text-justify flex flex-col gap-4 md:flex-row md:gap-8 md:justify-left md:items-center">
        <div class="flex justify-center">
          <img class="w-9/12 rounded-full mb-3 fadein-up"
            src="https://github.com/rubenreh/Ruben-Rehal-Portfolio/blob/main/public/img/HatsThrowing.PNG?raw=true" alt="Foto">
        </div>
        <div class="md:w-7/12">
          <p class="mb-3 md:mb-7 fadein-left fadeins-1">
            &nbsp; &nbsp; &nbsp; Hey there! My name is Ruben Rehal and I am currently a Computer Engineering Student at the
            University of Waterloo. Where I recieved the Presidents and Mary and Jack Burnett Scholarship. I am on track to
            graduate in 2028 with a Bachelor of Applied Science degree.
          </p>
          <p class="mb-3 fadein-left fadeins-2">
            &nbsp; &nbsp; &nbsp; My passion for sports, technology, and athletics drives me to balance
            my education with various extracurriculars. As a Hardware Engineer with the Midnight Sun Solar
            Rayce Car Team, I help design, manufacture, and race solar-powered vehicles, fueling my enthusiasm
            for sustainable technology and innovation. Feel free to reach out with any questions! 
          </p>
          Contact me : r2rehal@uwaterloo.ca
        </div>

      </section>

    </article>
  </div>

  <div class="px-5 py-5 md:px-12 md:py-10 text-left text-amber-50 mx-3">
    <article data-page="about">
      <header>
        <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
          <div class="h-[1px] w-10 bg-amber-200 md:w-20 aos-init aos-animate" data-aos="zoom-in-left"
            data-aos-duration="600"></div>
          &nbsp; Skills
        </div>
      </header>
      <section>
        <div>
          <ul class="flex flex-wrap text-sm font-medium text-center text-gray-500 dark:text-gray-400 mb-5">
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-orange-200 bg-orange-200 bg-opacity-10': activeTab === 1 }" @click="activeTab = 1">Technical</button>
            </li>
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-orange-200 bg-orange-200 bg-opacity-10': activeTab === 2 }" @click="activeTab = 2">Tools</button>
            </li>
          </ul>
        </div>
        <div v-show="activeTab === 1">
          <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
            <div v-for="item in tech" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-orange-200 px-2 py-2 hover:bg-orange-200 hover:bg-opacity-10 md:gap-3 lg:px-3">
                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                  <img alt="HTML" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]  "
                    :src="item.imageUrl" style="color: transparent;">
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">{{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                    {{ item.status }}</div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div v-show="activeTab === 2">
          <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
            <div v-for="item in tools" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-orange-200 px-2 py-2 hover:bg-orange-200 hover:bg-opacity-10 md:gap-3 lg:px-3">
                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                  <img alt="HTML" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]  "
                    :src="item.imageUrl" style="color: transparent;">
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">{{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                    {{ item.status }}</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </article>
  </div>
</template>

<style>
.fadein-left {
  opacity: 0;
  animation: fadeInLeft 0.5s ease-out forwards;
}

@keyframes fadeInLeft {
  0% {
    opacity: 0;
    transform: translateX(100%);
  }

  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

.fadeins-1 {
  animation-delay: 500ms;
}

.fadeins-2 {
  animation-delay: 800ms;
}

.img-tech,
.tech {
  transition: transform 0.3s ease;
}

.item-tech:hover .img-tech {
  transform: scale(1.3);
}

.item-tech:hover .tech {
  transform: translateY(-12px);
}

.item-tech:hover .status-tech {
  opacity: 1;
}
</style>
