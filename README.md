# shah

<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Cybersecurity Analyst Portfolio and physicist</title>

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet" />

  <style>
    body { font-family: 'Inter', sans-serif; }
    .link-underline { position: relative; }
    .link-underline:after {
      content: "";
      position: absolute;
      left: 0; bottom: -2px;
      width: 100%; height: 2px;
      background: currentColor;
      transform: scaleX(0);
      transform-origin: left;
      transition: transform .25s ease;
      opacity: 0.6;
    }
    .link-underline:hover:after { transform: scaleX(1); }
  </style>
</head>
<body class="bg-white text-slate-900 dark:bg-slate-950 dark:text-slate-100 transition-colors">

  <!-- Navbar -->
  <header class="sticky top-0 bg-white/80 dark:bg-slate-950/80 backdrop-blur z-40 border-b border-slate-200 dark:border-slate-800">
    <nav class="container mx-auto flex justify-between items-center py-4 px-4">
      <h1 class="text-lg font-bold">Cyber Analyst and physicist and phys</h1>
      <div class="flex gap-6 text-sm">
        <a href="#about" class="hover:opacity-80">About</a>
        <a href="#skills" class="hover:opacity-80">Skills</a>
        <a href="#experience" class="hover:opacity-80">Experience</a>
        <a href="#projects" class="hover:opacity-80">Projects</a>
        <a href="#certs" class="hover:opacity-80">Certifications</a>
        <a href="#contact" class="hover:opacity-80">Contact</a>
      </div>
      <div class="flex gap-2">
        <button id="themeToggle" class="px-3 py-2 border rounded-lg">🌙</button>
        <a id="downloadCV" href="#" class="px-3 py-2 bg-indigo-600 text-white rounded-lg">Download CV</a>
      </div>
    </nav>
  </header>

  
  </section>
<!-- Hero Section -->
<section id="home" class="container mx-auto py-16 px-4 text-center">
  <div class="flex flex-col items-center">
    <!-- Profile Photo -->
    <img src="folder/MYPROFILR/profile.jpg.jpg" alt="Profile Photo"
         class="w-40 h-40 rounded-full border-4 border-indigo-600 shadow-lg mb-6 object-cover" />

    <h2 class="text-4xl md:text-6xl font-extrabold">Cybersecurity Analyst and physician</h2>
    <p class="mt-4 text-lg text-gray-600 dark:text-gray-300 max-w-2xl mx-auto">
      Certified cybersecurity analyst with a <b>BSc in Physics (Hazara University, 2023)</b>.
      1 year teaching experience in Physics and 6 months in Cybersecurity (physics teaching).
    </p>
    <div class="mt-6 flex justify-center gap-4">
      <a href="#projects" class="px-5 py-3 bg-indigo-600 text-white rounded-lg">View Projects</a>
      <a href="#contact" class="px-5 py-3 border rounded-lg">Hire Me</a>
    </div>
  </div>
</section>

    <!-- Name Section -->
    <section id="name" class="container mx-auto py-8 px-4 text-center">
    <h2 class="text-2xl font-bold mb-2">My Name</h2>
    <p class="text-2xl font-extrabold text-red-600" style="font-family: 'Inter', sans-serif;">Shah Rukh Khan</p>
    </section>
  <!-- About -->
  <section id="about" class="container mx-auto py-16 px-4">
    <h2 class="text-2xl font-bold mb-4">About Me</h2>
    <p>
      I combine a strong scientific background with hands-on cybersecurity skills. 
      I enjoy secure coding in linux sql, vulnerability assessment, and helping teams adopt best practices and siem tool . physics related 
      as we creat river water measure project in qsac
    </p>
  </section>

  <!-- Skills -->
  <section id="skills" class="bg-slate-50 dark:bg-slate-900/40 py-16 px-4">
    <div class="container mx-auto">
      <h2 class="text-2xl font-bold mb-6">Skills</h2>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="p-4 border rounded-xl">Security Fundamentals<br><span class="text-sm">Vulnerability assessment, SOC basics</span></div>
        <div class="p-4 border rounded-xl">Secure Development<br><span class="text-sm">Java, OWASP Top 10, Git</span></div>
        <div class="p-4 border rounded-xl">Tools<br><span class="text-sm">linux and sql, Nmap, seim tool  bugbunty</span></div>
      </div>
    </div>
  </section>

  <!-- Experience -->
  <section id="experience" class="container mx-auto py-16 px-4">
    <h2 class="text-2xl font-bold mb-6">Experience</h2>
    <div class="space-y-6">
      <div class="p-4 border rounded-xl">
        <h3 class="font-semibold">Cybersecurity Trainee </h3>
        <p class="text-sm">6 months · 2024—2025</p>
      </div>
      <div class="p-4 border rounded-xl">
        <h3 class="font-semibold">Physics Teacher</h3>
        <p class="text-sm">1 year · 2023—2024</p>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="bg-slate-50 dark:bg-slate-900/40 py-16 px-4">
    <div class="container mx-auto">
      <div class="flex justify-between items-center mb-6">
        <h2 class="text-2xl font-bold">Projects</h2>
        <select id="filter" class="border rounded-lg px-3 py-2 text-sm">
          <option value="all">All</option>
          <option value="security">Security</option>
          <option value="java">Java</option>
        </select>
      </div>
      <div id="projectGrid" class="grid md:grid-cols-3 gap-6">
        <div data-tags="java security" class="p-4 border rounded-xl">Secure system</div>
        <div data-tags="security" class="p-4 border rounded-xl">vollenerabilty assessment seim toool</div>
        <div data-tags="java" class="p-4 border rounded-xl">Log Hardening Config</div>
      </div>
    </div>
  </section>

    <!-- Certificates Gallery -->
    <section id="certificates-gallery" class="container mx-auto py-16 px-4">
      <h2 class="text-2xl font-bold mb-6">My Certificates</h2>
      <div class="grid md:grid-cols-3 gap-6">
        <!-- Example certificate images, update src for your actual files -->
        <div class="p-4 border rounded-xl flex flex-col items-center">
          <img src="folder/MYPROFILR/my asset/certificat/cyber1.jpg.jpeg" class="w-64 h-auto rounded-lg shadow mb-4" />
          <span class="text-sm">Cybersecurity Certificate</span>
        </div>
        <div class="p-4 border rounded-xl flex flex-col items-center">
          <img src="folder/MYPROFILR/my asset/certificat/mlsa.jpg.jpeg" alt="Microsoft Learn Student Ambassadors" class="w-64 h-auto rounded-lg shadow mb-4" />
          <span class="text-sm">Microsoft Learn Student Ambassadors</span>
        </div>
        <!-- Add more certificate images as needed -->
      </div>
    </section>
    <!-- Assets -->
    
        <!-- Add more certificate images as needed -->
      </div><section id="certs" class="container mx-auto py-16 px-4">
  <h2 class="text-2xl font-bold mb-6">Certifications</h2>
  <div class="p-4 border rounded-xl">
    Coursera — Cybersecurity Certificate,
  microsoft learn student ambassadors
</section>
    </section>

  </section>

  <!-- Contact -->
  <section id="contact" class="bg-slate-50 dark:bg-slate-900/40 py-16 px-4">
    <div class="container mx-auto">
      <h2 class="text-2xl font-bold mb-6">Contact</h2>
      <form id="contactForm" class="space-y-4 max-w-lg">
  <input type="text" name="name" placeholder="Shah Rukh Khan" class="w-full border rounded-lg px-3 py-2" required />
  <input type="email" name="email" placeholder="shahrukhkhann138@gmail.com" class="w-full border rounded-lg px-3 py-2" required />
  <input type="email" name="email" placeholder="shahrukhkhann138@gmail.com" class="w-full border rounded-lg px-3 py-2" required />
  <textarea name="message" rows="4" placeholder="Your message" class="w-full border rounded-lg px-3 py-2" required></textarea>
  <button class="px-5 py-3 bg-indigo-600 text-white rounded-lg">Send Message</button>
  <p id="formStatus" class="text-sm mt-2"></p>
      </form>
    </div>
  </section>

<!-- Contact Me -->
<section id="contact" class="bg-gray-100 dark:bg-gray-800 py-16 px-4">
  <div class="container mx-auto">
    <h2 class="text-3xl font-bold mb-6 text-center">Contact Me</h2>
    <p class="text-center text-gray-600 dark:text-gray-300 mb-8">
      Interested in working together or have a question? Feel free to reach out!
    </p>
    <form id="contactForm" class="space-y-4 max-w-lg mx-auto">
      <input type="text" name="name" placeholder="Your Name"
             class="w-full border rounded-lg px-3 py-2" required />
      <input type="email" name="email" placeholder="Your Email"
             class="w-full border rounded-lg px-3 py-2" required />
      <textarea name="message" rows="4" placeholder="Message"
                class="w-full border rounded-lg px-3 py-2" required></textarea>
      <button class="px-5 py-3 bg-indigo-600 text-white rounded-lg w-full">
        Send Message
      </button>
      <p id="formStatus" class="text-sm mt-2 text-center"></p>
    </form>
  </div>
</section>
<!-- Footer -->
<footer class="bg-gray-900 text-gray-300 py-6 mt-12">
  <div class="container mx-auto px-4 flex flex-col md:flex-row items-center justify-between">
    <p class="text-sm">
      © <span id="year"></span> Cybersecurity Analyst Portfolio. All rights reserved.
    </p>
    <div class="flex gap-4 mt-4 md:mt-0">
      <a href="mailto:yourname@email.com" class="hover:text-white">shahrukhkhann138@gmail.com</a>
      <a href="https://www.linkedin.com/in/yourprofile" target="_blank" class="hover:text-white">LinkedIn</a>
      <a href="https://github.com/yourgithub" target="_blank" class="hover:text-white">GitHub</a>
    </div>
  </div>
</footer>


  <!-- Footer -->
  <footer class="container mx-auto py-6 text-center text-sm text-slate-500">
    © <span id="year"></span> Cybersecurity Analyst Portfolio
  </footer>

  <!-- Script -->
  <script src="script.js"></script>
</body>
</html>
