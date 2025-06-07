<template>
  <div class="min-h-screen bg-gray-900 text-white">
    <!-- Header -->
    <header class="py-5 bg-gray-800">
      <div class="container mx-auto px-6 flex justify-between items-center">
        <h1 class="text-2xl font-bold text-red-500">Beryl</h1>
        <nav>
          <ul class="flex space-x-6">
            <li><a href="#" class="hover:text-red-500">Home</a></li>
            <li><a href="#services" class="hover:text-red-500">Services</a></li>
            <li><a href="#portfolio" class="hover:text-red-500">Portfolio</a></li>
            <li><a href="#contact" class="hover:text-red-500">Contact</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <!-- Hero Section -->
    <section
      class="bg-cover bg-center h-96"
      style="background-image: url('https://i.pinimg.com/564x/7c/66/33/7c663303bc939d2eb6d5af9197241ef4.jpg');"
    >
      <div class="flex items-center justify-center h-full bg-black bg-opacity-50">
        <div class="text-center">
          <img
            class="rounded-full mx-auto mb-4 w-20"
            src="./assets/css/gambar/Omganteng.png"
            alt="Profile Picture"
          />
          <h2 class="text-4xl font-bold">Azzam Beryl Nemesio Wijoyo</h2>
          <p class="text-red-500">UI Designer & Frontend Engineer</p>
        </div>
      </div>
    </section>

    <!-- About Me -->
    <section class="py-16">
      <div class="container mx-auto px-6 md:flex justify-between">
        <div class="md:w-1/2">
          <h3 class="text-red-500 text-xl font-bold mb-4">Discover</h3>
          <h2 class="text-3xl font-bold mb-6">About Me</h2>
          <p class="text-gray-400 leading-loose mb-6">
            Halo! Saya Azzam Beryl Nemesio Wijoyo, seorang individu yang antusias di bidang Teknologi Informasi dengan 
            pengalaman lebih dari 3 tahun dalam pengembangan perangkat lunak dan desain antarmuka. 
            Saya memiliki semangat tinggi dalam menciptakan solusi digital yang inovatif dan efisien. 
            Ketertarikan saya terhadap proses kreatif dan detail dalam merancang serta membangun produk digital mendorong saya untuk terus belajar dan berkembang.
          </p>
          <div class="bg-gray-800 p-6 rounded-md mb-6">
            <ul class="space-y-2">
              <li><strong>Name:</strong> Azzam Beryl</li>
              <li><strong>Phone:</strong> +6282332762344</li>
              <li><strong>Age:</strong> 19</li>
              <li><strong>Address:</strong> Situbondo, Jatim</li>
              <li><strong>Job:</strong> Nothing</li>
              <li><strong>Hobby:</strong> Singing, Sketching</li>
            </ul>
          </div>
          <a
            href="/cv-azzam-beryl.pdf"
            download
            class="bg-red-500 text-white py-2 px-4 rounded hover:bg-red-600"
          >
            Download CV
          </a>
        </div>
        <div class="md:w-1/2 mt-10 md:mt-0 mx-20 flex justify-center items-center">
          <img
            src="./assets/css/gambar/Beril_1.jpg"
            alt="Beryl"
            class="rounded-md shadow-md w-80"
          />
        </div>
      </div>
    </section>

    <!-- Services -->
    <section class="py-16 bg-gray-800" id="services">
      <div class="container mx-auto px-6">
        <h3 class="text-red-500 text-xl font-bold mb-4 text-center">What I Do</h3>
        <h2 class="text-3xl font-bold mb-10 text-center">My Services</h2>
        <div class="md:flex md:space-x-6">
          <div class="flex-1 mb-10 md:mb-0 bg-gray-900 p-6 rounded-lg text-center hover:scale-105 transition-transform hover:bg-gray-700">
            <img src="assets/css/gambar/flask.png" class="rounded-md shadow-md w-80 mx-auto mb-4" />
            <h4 class="text-2xl font-bold mb-4">Backend Developer</h4>
            <p class="text-gray-400">Flask.</p>
          </div>
          <div class="flex-1 mb-10 md:mb-0 bg-gray-900 p-6 rounded-lg text-center hover:scale-105 transition-transform hover:bg-gray-700">
            <img src="assets/css/gambar/vue_js.png" class="rounded-md shadow-md w-80 mx-auto mb-4" />
            <h4 class="text-2xl font-bold mb-4">Frontend Web Development</h4>
            <p class="text-gray-400">Vue.js.</p>
          </div>
          <div class="flex-1 bg-gray-900 p-6 rounded-lg text-center hover:scale-105 transition-transform hover:bg-gray-700">
            <img src="./assets/css/gambar/pngwing.com.png" class="rounded-md shadow-md w-80 mx-auto mb-4" />
            <h4 class="text-2xl font-bold mb-4">User Interface</h4>
            <p class="text-gray-400">Figma.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Portfolio -->
<section class="py-16 bg-gray-900" id="portfolio">
  <div class="container mx-auto px-6">
    <h3 class="text-red-500 text-xl font-bold mb-4 text-center">My Work</h3>
    <h2 class="text-3xl font-bold mb-10 text-center">Project Portfolio</h2>
    <div class="grid md:grid-cols-2 gap-8">
      <!-- Project 1 - Web Project -->
      <a
        href="https://website-bimbel.vercel.app/"
        target="_blank"
        rel="noopener noreferrer"
        class="bg-gray-800 p-6 rounded-lg hover:scale-105 transition-transform hover:shadow-xl block"
      >
        <img
          src="assets/css/gambar/project-web.jpg/projek_1.png"
          alt="Web Project"
          class="rounded mb-4 w-full h-48 object-cover"
        />
        <h4 class="text-2xl font-bold mb-2 text-center">Web Project</h4>
        <p class="text-gray-400 text-center">A responsive web-based application.</p>
      </a>

      <!-- Project 2 - Figma -->
      <a
        href="https://www.figma.com/design/MBTi2RQ6AMEQg4liQEx7QB/Ecommerce--Community-?node-id=0-1&p=f&t=HKRZtjhbJEOGf1Wk-0"
        target="_blank"
        rel="noopener noreferrer"
        class="bg-gray-800 p-6 rounded-lg hover:scale-105 transition-transform hover:shadow-xl block"
      >
        <img
          src="assets/css/gambar/project-figma.jpg/figma_2.png"
          alt="UI/UX Figma"
          class="rounded mb-4 w-full h-48 object-cover"
        />
        <h4 class="text-2xl font-bold mb-2 text-center">UI/UX Design</h4>
        <p class="text-gray-400 text-center">Figma interface and user flow design.</p>
      </a>
    </div>
  </div>
</section>


    <!-- Contact -->
    <section class="py-16" id="contact">
      <div class="container mx-auto px-6">
        <h3 class="text-red-500 text-xl font-bold mb-4 text-center">Get In Touch</h3>
        <h2 class="text-3xl font-bold mb-10 text-center">Contact Me</h2>
        <form class="bg-gray-800 p-8 rounded-lg shadow-md">
          <div class="mb-4">
            <label for="name" class="block text-gray-400 mb-2">Name</label>
            <input
              type="text"
              id="name"
              required
              class="w-full p-3 rounded bg-gray-900 text-white focus:outline-none focus:ring focus:ring-red-500"
              placeholder="Your Name"
            />
          </div>
          <div class="mb-4">
            <label for="email" class="block text-gray-400 mb-2">Email</label>
            <input
              type="email"
              id="email"
              required
              class="w-full p-3 rounded bg-gray-900 text-white focus:outline-none focus:ring focus:ring-red-500"
              placeholder="Your Email"
            />
          </div>
          <div class="mb-4">
            <label for="message" class="block text-gray-400 mb-2">Message</label>
            <textarea
              id="message"
              rows="4"
              required
              class="w-full p-3 rounded bg-gray-900 text-white focus:outline-none focus:ring focus:ring-red-500"
              placeholder="Your Message"
            ></textarea>
          </div>
          <button
            type="submit"
            class="w-full bg-red-500 text-white py-2 rounded hover:bg-red-600"
          >
            Send Message
          </button>
        </form>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
};
</script>

<style scoped>
</style>
