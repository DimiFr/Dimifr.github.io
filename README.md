<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Landing Page</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-800">
  <!-- Hero Section -->
  <section class="min-h-screen flex flex-col justify-center items-center text-center px-6">
    <h1 class="text-5xl font-bold mb-4">Welcome to My Landing Page 🚀</h1>
    <p class="text-lg mb-6 max-w-xl">A simple and beautiful GitHub Pages landing page to showcase who I am and what I do.</p>
    <a href="#contact" class="bg-blue-600 text-white px-6 py-3 rounded-full shadow-md hover:bg-blue-700 transition">Get in Touch</a>
  </section>

  <!-- About Section -->
  <section id="about" class="py-20 bg-white text-center">
    <h2 class="text-3xl font-semibold mb-4">About Me</h2>
    <p class="max-w-2xl mx-auto">I’m a developer passionate about building clean, fast, and accessible web experiences. This landing page is my little corner on the internet.</p>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="py-20 bg-gray-100">
    <div class="max-w-5xl mx-auto px-6">
      <h2 class="text-3xl font-semibold text-center mb-10">Projects</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded-xl shadow hover:shadow-lg transition">
          <h3 class="font-bold text-xl mb-2">Project One</h3>
          <p>A short description of the project. <a href="#" class="text-blue-600">View More →</a></p>
        </div>
        <div class="bg-white p-6 rounded-xl shadow hover:shadow-lg transition">
          <h3 class="font-bold text-xl mb-2">Project Two</h3>
          <p>Another project showcase. <a href="#" class="text-blue-600">View More →</a></p>
        </div>
        <div class="bg-white p-6 rounded-xl shadow hover:shadow-lg transition">
          <h3 class="font-bold text-xl mb-2">Project Three</h3>
          <p>One more example project. <a href="#" class="text-blue-600">View More →</a></p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-20 bg-white text-center">
    <h2 class="text-3xl font-semibold mb-4">Contact Me</h2>
    <p class="mb-6">Let’s connect! Find me on:</p>
    <div class="flex justify-center gap-6">
      <a href="https://github.com/yourusername" class="text-gray-700 hover:text-blue-600">GitHub</a>
      <a href="https://linkedin.com/in/yourusername" class="text-gray-700 hover:text-blue-600">LinkedIn</a>
      <a href="mailto:youremail@example.com" class="text-gray-700 hover:text-blue-600">Email</a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-6 bg-gray-800 text-white text-center">
    <p>&copy; 2025 Your Name. Built with ❤️ and GitHub Pages.</p>
  </footer>
</body>
</html>
