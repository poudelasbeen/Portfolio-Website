<script>
  import Step from "./Step.svelte";
  


  let steps = [
      {
          name: "Internal Marks Management System",
          icon: "",
          description:
              "A basic marks management system is a web application built with React, Postgresql, HTML, CSS and JS.",
      },
      {
          name: "Student Study System",
          icon: "",
          description:
          "Student Study System is a web application built using Python with Django, SQLite, HTML, CSS and JS",
      },
      {
          name: "Weather App",
          icon: "",
          description:
              "A Weather App is a Java mobile application that pulls weather API to display the weather details of the location which you want to search .",
      },
  ];

  let benefits = [
      {
          metric: "10x",
          name: "Passionate Learner:",
          description:
              "I am a passionate learner who thrives on acquiring new knowledge and skills. I believe that learning is a lifelong journey, and I am constantly seeking opportunities to expand my horizons and stay at the forefront of my field.",
      },
      {
          name: "Research Enthusiast:",
          description:
              "I am deeply enthusiastic about cutting-edge research and innovation. I enjoy staying up-to-date with the latest developments in my industry and actively engage in research projects that contribute to the advancement of knowledge and technology.",
      },
      {
          name: "Self-Taught Trailblazer: ",
          description:
              "As a self-taught individual, I take pride in my ability to independently acquire new skills and overcome challenges. I believe in the power of determination and resourcefulness to achieve personal and professional goals.",
      },
      {
          name: "Effective Communicator: ",
          description:
              " I possess strong communication skills, both written and verbal, which enable me to convey complex ideas and information in a clear and engaging manner. Effective communication is crucial in building connections and fostering collaboration.",
      },
      {
          name: "Problem Solver: ",
          description:
              "I thrive in solving complex problems by approaching them with creativity and a systematic mindset. I enjoy tackling challenges head-on and finding innovative solutions that lead to meaningful outcomes.",
      },
  ];
</script>

<main class="flex flex-col flex-1 p-4">
  <section
      id="introPage"
      class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14"
  >
      <div
          class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
      >
          <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
              Hi! I'm <span class="poppins text-violet-400">Asbin</span> Poudel
              <br />
              <span class="poppins text-violet-400">Computer Engineer</span>
          </h2>
          <p class="text-base sm:text-lg md:text-xl">
            I am a Computer Engineering graduate from Pokhara University with a solid foundation in programming and a strong
            passion for technology and data science, I bring hands-on experience as an IT Assistant. I am eager to apply my skills in
            data analysis, database management, network infrastructure, and IT support to drive data-driven solutions and contribute
            to innovative, technology-focused projects in dynamic environments.

            
          </p>
          
          <button class="blueShadow mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950">
            <div class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200" />
            <a href="#connect_with_me"> <!-- Add the ID of the "Get in touch" section as the href value -->
                <h4 class="relative z-9">Get in touch &rarr;</h4>
            </a>
        </button>
        
        
      </div>
      <div class="relative shadow-2xl grid place-items-center">
          <img
              src={"images/profile.png"}
              alt="profile images"
              class="object-cover z-[2] max-h-[70vh]"
          />
      </div>
      <!-- <div  class="flex p-0.5 relative max-w-[700px] w-full mx-auto">
          <div
              class="absolute inset-0 overflow-hidden rounded-md flex items-center justify-center"
          >
              <div
                  class="bg-gradient-to-r absolute inset-[-20px]  from-violet-800 to-indigo-800 specialSpin"
              />
          </div>

          <img
              src={"images/zetane-engine.jpeg"}
              alt="Zetane Engine"
              class="w-full h-full object-cover z-[2]"
          />
      </div> -->
  </section>

  <!-- Work Experience Section -->
<section class="py-20 lg:py-32 flex flex-col gap-16" id="experience">
  <div class="flex flex-col gap-2 text-center">
      <h6 class="text-large sm:text-xl md:text-2xl">
          My Professional Journey
      </h6>
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
          Work <span class="poppins text-violet-400">Experience</span>
      </h3>
  </div>

  <!-- Timeline Container -->
  <div class="relative border-l-4 border-violet-400 pl-6 space-y-12 max-w-4xl mx-auto">
      
      <!-- NMB -->
      <div class="relative">
          <div class="absolute -left-8 top-1 w-6 h-6 rounded-full bg-violet-400 border-4 border-white shadow"></div>
          <h4 class="font-semibold text-xl">Sr. Assistant - IT Department</h4>
          <p class="text-white-500">NMB Laghubitta Bittiya Sanstha Ltd. | June 2025 – Present</p>
          <ul class="list-disc list-inside text-white-600 mt-2 space-y-1">
              <li>System Administrator & Windows Server Management</li>
              <li>Database management, optimization, and reporting</li>
              <li>Network engineering & infrastructure support</li>
              <li>Managed and updated organizational website</li>
              <li>Provided IT support and resolved user issues</li>
          </ul>
      </div>

      <!-- Global IME -->
      <div class="relative">
          <div class="absolute -left-8 top-1 w-6 h-6 rounded-full bg-violet-400 border-4 border-white shadow"></div>
          <h4 class="font-semibold text-xl">Assistant - IT Department</h4>
          <p class="text-white-500">Global IME Laghubitta Bittiya Sanstha Ltd. | Apr 2024 – Jun 2025</p>
          <ul class="list-disc list-inside text-white-600 mt-2 space-y-1">
              <li>Database management, performance optimization, and reporting</li>
              <li>System monitoring & troubleshooting hardware/software issues</li>
              <li>Website updates and content management</li>
              <li>Network support and hardware/software installation</li>
              <li>Ensured hardware performance & system security</li>
          </ul>
      </div>

      <!-- NIC Asia -->
      <div class="relative">
          <div class="absolute -left-8 top-1 w-6 h-6 rounded-full bg-violet-400 border-4 border-white shadow"></div>
          <h4 class="font-semibold text-xl">Assistant - IT Department</h4>
          <p class="text-white-500">NIC Asia Laghubitta Bittiya Sanstha Ltd. | Jan 2024 – Apr 2024</p>
          <ul class="list-disc list-inside text-white-600 mt-2 space-y-1">
              <li>Supported IT operations across branches</li>
              <li>Installed hardware and software applications</li>
              <li>Troubleshot issues and escalated when required</li>
              <li>Monitored hardware operation & security</li>
              <li>Coordinated with vendors regarding software applications</li>
          </ul>
      </div>
  </div>
</section>



  <section class="py-20 lg:py-32 flex flex-col gap-24" id="projects">
      <class class="flex flex-col gap-2 text-center">
          <h6 class="text-large sm:text-xl md:text-2xl">
              A few of my creative endeavors.
          </h6>
      </class>
          <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
              Curious to <span class="poppins text-violet-400">see</span> my projects?
          </h3>

      <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
          <Step step={steps[0]}>
              <p>
                  IMMS is a basic internal marks management system built with  <strong
                      class="text-violet-400"
                      >React, Postgresql, HTML, CSS and JS
                      </strong
                      >
              </p>
          </Step>
          <Step step={steps[1]}>
              <p>
                  Student Study System is a web application built using  <strong
                      class="text-violet-400">Python with Django</strong
                  >,
                  <strong class="text-violet-400"> SQLite, HTML, CSS and JS.</strong
                  >
              </p>
          </Step>
          <Step step={steps[2]}>
              <p>
                  A Weather App is a <strong class="text-violet-400"
                      >Java</strong
                  >
                  mobile application
                  <strong class="text-violet-400"> that
                  pulls weather API 
                  <strong class="text-violet-400">
                  to display the weather details of the location which you want to search .
              </p>
          </Step>
      </div>
  </section>
  <section
      id="about"
      class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
  >
      <!-- <div class="z-[-1] bg-violet-950 w-screen left-1/2 -translate-x-1/2 top-0 h-full absolute"> </div> -->
      <div
          class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-violet-700 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-violet-700 py-4"
      >
          <h6 class="text-large sm:text-xl md:text-2xl">
              Want to know more?
          </h6>
          <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
              A bit <span class="poppins text-violet-400">about</span> me.
          </h3>
      </div>
      <p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
          I am . . .
      </p>
      <div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
          {#each benefits as benefit, index}
              <!-- <div class="flex flex-col gap-2 mx-auto">
                  <div class="flex items-end gap-4">
                      <p
                          class="poppins text-6xl sm:text-7xl md:text-8xl text-slate-500 font-medium"
                      >
                          {benefit.metric}
                      </p>
                      <p
                          class="text-xl sm:text-2xl md:text-3xl capitalize pb-2"
                      >
                          {benefit.name}
                      </p>
                  </div>
                  <p class="text-center italic">- {benefit.description}</p>
              </div> -->
              <div class="flex gap-6 sm:gap-8">
                  <p
                      class="poppins text-4xl sm:text-5xl md:text-6xl text-slate-500 font-semibold"
                  >
                      0{index + 1}
                  </p>
                  <div class="flex flex-col gap-6 sm:gap-8">
                      <h3 class="text-2xl sm:text-3xl md:text-5xl">
                          {benefit.name}
                      </h3>
                      <p>{benefit.description}</p>
                  </div>
              </div>
          {/each}
      </div>
      
<section class="py-20 lg:py-32 flex flex-col gap-24" id="education">
  <div class="flex flex-col gap-2 text-center">
      <h6 class="text-large sm:text-xl md:text-2xl">
          My Educational Achievements
      </h6>
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
          Education <span class="poppins text-violet-400">History</span>
      </h3>
  </div>

  <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 lg:gap-10">
      <!-- First Educational Achievement -->
      <div class="bg-blue shadow-lg rounded-lg p-4">
          <h4 class="font-semibold text-xl">Bachelor's in Computer Engineering</h4>
          <p class="text-gray-500">Pokhara University</p>
          <p class="text-gray-500">Graduated: Oct 2023</p>
      </div>

      <!-- Second Educational Achievement -->
      <div class="bg-blue shadow-lg rounded-lg p-4">
          <h4 class="font-semibold text-xl">High School </h4>
          <p class="text-gray-500">Amarsingh Secondary School</p>
          <p class="text-gray-500">Graduated: 2018</p>
      </div>
      <div class="bg-blue shadow-lg rounded-lg p-4">
        <h4 class="font-semibold text-xl"> School Leaving Certificate </h4>
        <p class="text-gray-500">L.Angel Secondary School</p>
        <p class="text-gray-500">Graduated: 2016</p>
    </div>
  </div>
</section>
<!-- Add this code below your existing sections -->
<section class="py-20 lg:py-32 flex flex-col gap-24" id="skills">
  <div class="flex flex-col gap-2 text-center">
      <h6 class="text-large sm:text-xl md:text-2xl">
          My Skills
      </h6>
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
          What I <span class="poppins text-violet-400">Can Do</span>
      </h3>
  </div>

  <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 lg:gap-10">
      <!-- Skill #1 -->
      <div class="bg-blue shadow-lg rounded-lg p-4">
          <h4 class="font-semibold text-xl">Web Development</h4>
          <p class="text-gray-500">HTML, CSS, JavaScript, React, Node.js</p>
      </div>

      <!-- Skill #2 -->
      <div class="bg-blue shadow-lg rounded-lg p-4">
          <h4 class="font-semibold text-xl">Python Programming</h4>
          <p class="text-gray-500">Django,  Data Analysis, Artificial Intelligence</p>
      </div>
      <div class="bg-blue shadow-lg rounded-lg p-4">
        <h4 class="font-semibold text-xl">Mobile App Development</h4>
        <p class="text-gray-500">Java, Android Studio</p>
    </div>
    <div class="bg-blue shadow-lg rounded-lg p-4">
      <h4 class="font-semibold text-xl">Others</h4>
      <p class="text-gray-500">C++, SQL, Git, PostgreSQL, LATEX, Cloud Computing</p>
  </div>
  </div>
</section>




      <!-- <h5 class={" text-2xl sm:text-3xl font-semibold text-center poppins "}>
          The <span class="text-violet-400">Complete</span> Package
      </h5>
      <div
          class="flex flex-col overflow-x-scroll gap-10 max-w-[800px] mx-auto w-full"
      >
          <table class="bg-white text-slate-700 rounded text-center">
              <thead class={"border-b border-solid border-slate-200  "}>
                  <tr class="">
                      <th />
                      <th class="whitespace-nowrap p-2 px-4">Candidate #1</th>
                      <th class="whitespace-nowrap p-2 px-4">Candidate #2</th>
                      <th class="whitespace-nowrap p-2 px-4">Candidate #3</th>
                      <th
                          class="bg-violet-700 text-white whitespace-nowrap p-4 px-8"
                          >Me</th
                      >
                  </tr>
              </thead>
              <tbody>
                  <tr class="border-b border-solid border-slate-200">
                      <td
                          class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                          >Dedication</td
                      >
                      <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                      <td><i class="fa-solid fa-check text-slate-500" /></td>
                      <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                      <td><i class="fa-solid fa-check text-green-500" /></td>
                  </tr>
                  <tr class="border-b border-solid border-slate-200">
                      <td
                          class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                          >Critical Thought</td
                      >
                      <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                      <td><i class="fa-solid fa-check text-slate-500" /></td>
                      <td><i class="fa-solid fa-check text-slate-500" /></td>
                      <td><i class="fa-solid fa-check text-green-500" /></td>
                  </tr>
                  <tr>
                      <td
                          class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                          >Interpersonal Skills</td
                      >
                      <td><i class="fa-solid fa-check text-slate-500" /></td>
                      <td><i class="fa-solid fa-check text-slate-500" /></td>
                      <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                      <td><i class="fa-solid fa-check text-green-500" /></td>
                  </tr>
                  <tr class="border-t border-solid border-slate-200">
                      <td
                          class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                          >Progamming Ability</td
                      >
                      <td><i class="fa-solid fa-check text-slate-500" /></td>
                      <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                      <td><i class="fa-solid fa-check text-slate-500" /></td>
                      <td><i class="fa-solid fa-check text-green-500" /></td>
                  </tr>
              </tbody>
          </table>
      </div> -->
      <div class="mx-auto -mt-12 italic flex-color sm:hidden opacity-50">
          <p>Scroll to see more &rarr;</p>
      </div>
      <p class="mx-auto">So why not invest?</p>
  </section>
</main>