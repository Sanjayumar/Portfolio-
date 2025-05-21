<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sanjay Kumar – Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: { inter: ['Inter', 'sans-serif'] }
        }
      }
    }
  </script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
    body {
      font-family: 'Inter', sans-serif;
    }
  </style>
</head>
<body class="bg-gray-50 dark:bg-gray-900 text-gray-800 dark:text-gray-200 transition-colors duration-300">

  <!-- Header -->
  <header class="bg-white dark:bg-gray-800 shadow-md sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <div>
        <h1 class="text-2xl font-bold text-gray-900 dark:text-white">Sanjay Kumar</h1>
        <p class="text-sm text-gray-500 dark:text-gray-400">Math teacher Specilist </p>
      </div>
      <div class="flex gap-6 items-center">
        <nav class="hidden md:flex gap-6 text-sm font-medium">
          <a href="#about" class="hover:text-blue-500 transition">About</a>
          <a href="#projects" class="hover:text-blue-500 transition">Projects</a>
          <a href="#skills" class="hover:text-blue-500 transition">Skills</a>
          <a href="#contact" class="hover:text-blue-500 transition">Contact</a>
        </nav>
        <!-- Dark mode toggle -->
        <button onclick="document.documentElement.classList.toggle('dark')" class="text-xl">
          <i class="fas fa-moon dark:hidden"></i>
          <i class="fas fa-sun hidden dark:inline"></i>
        </button>
      </div>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="py-16 px-6 text-center bg-blue-50 dark:bg-blue-900 transition">
    <img src="2.png" alt="Profile Picture" class="w-32 h-32 rounded-full mx-auto mb-4 shadow-md border-4 border-white dark:border-gray-800 object-cover" />
    <h2 class="text-4xl font-bold mb-2 text-blue-900 dark:text-white">Hi, I am sanjay kumar</h2>
    <p class="text-lg text-blue-700 dark:text-blue-200 max-w-xl mx-auto">
      I create clean, modern websites with a focus on user experience and responsive design.
    </p>
  </section>

  <!-- About -->
  <section id="about" class="py-16 px-6 max-w-5xl mx-auto">
    <h3 class="text-3xl font-semibold mb-4">About Me</h3>
    <p class="text-gray-600 dark:text-gray-300 text-lg leading-relaxed">
      I'm a frontend developer who loves crafting beautiful UIs. I work with HTML, CSS, Tailwind, JavaScript, and React. I also enjoy UI/UX design and collaborating with creative teams.
    </p>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-16 px-6 bg-white dark:bg-gray-800">
    <div class="max-w-6xl mx-auto">
      <h3 class="text-3xl font-semibold mb-10">Projects</h3>
      <div class="grid md:grid-cols-2 gap-8">
        <div class="bg-gray-50 dark:bg-gray-700 p-6 rounded-lg shadow hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-2">Personal Portfolio</h4>
          <p class="text-gray-600 dark:text-gray-300">Responsive portfolio with Tailwind CSS and dark mode toggle.</p>
        </div>
        <div class="bg-gray-50 dark:bg-gray-700 p-6 rounded-lg shadow hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-2">Task Manager App</h4>
          <p class="text-gray-600 dark:text-gray-300">Productivity app with authentication and task features.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="py-16 px-6 max-w-5xl mx-auto">
    <h3 class="text-3xl font-semibold mb-6">Skills</h3>
    <div class="flex flex-wrap gap-4">
      <span class="px-4 py-2 bg-blue-100 text-blue-800 rounded-full dark:bg-blue-800 dark:text-white font-medium">HTML</span>
      <span class="px-4 py-2 bg-blue-100 text-blue-800 rounded-full dark:bg-blue-800 dark:text-white font-medium">Tailwind CSS</span>
      <span class="px-4 py-2 bg-blue-100 text-blue-800 rounded-full dark:bg-blue-800 dark:text-white font-medium">JavaScript</span>
      <span class="px-4 py-2 bg-blue-100 text-blue-800 rounded-full dark:bg-blue-800 dark:text-white font-medium">React</span>
      <span class="px-4 py-2 bg-blue-100 text-blue-800 rounded-full dark:bg-blue-800 dark:text-white font-medium">Figma</span>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-16 px-6 bg-gray-100 dark:bg-gray-900 text-center">
    <h3 class="text-3xl font-semibold mb-6">Contact Me</h3>
    <p class="text-lg text-gray-600 dark:text-gray-300 mb-4">Feel free to reach out through any of the following methods:</p>
    <div class="space-y-3">
      <p><i class="fas fa-envelope text-blue-600"></i> john.doe@example.com</p>
      <p><i class="fas fa-phone text-green-600"></i> +123-456-7890</p>
      <p><i class="fab fa-whatsapp text-green-500"></i> WhatsApp: +123-456-7890</p>
    </div>
    <div class="mt-6 flex justify-center gap-6 text-2xl text-blue-600 dark:text-blue-400">
      <a href="https://github.com/yourprofile" target="_blank"><i class="fab fa-github"></i></a>
      <a href="https://linkedin.com/in/yourprofile" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="https://twitter.com/yourprofile" target="_blank"><i class="fab fa-twitter"></i></a>
      <a href="https://facebook.com/yourprofile" target="_blank"><i class="fab fa-facebook"></i></a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center py-6 text-sm text-gray-500 dark:text-gray-400">
    &copy; 2025 John Doe. Built with Tailwind CSS.
  </footer>

</body>
</html>
