<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laravel Developer Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        html { scroll-behavior: smooth; }
    </style>
</head>
<body class="bg-gray-900 text-white">

    <!-- Navbar -->
    <nav class="bg-gray-800 fixed w-full z-10 shadow-lg">
        <div class="container mx-auto flex justify-between items-center py-4 px-6">
            <a href="#" class="text-2xl font-bold text-blue-400">My Portfolio</a>
            <div class="space-x-6">
                <a href="#about" class="hover:text-blue-400">About</a>
                <a href="#skills" class="hover:text-blue-400">Skills</a>
                <a href="#projects" class="hover:text-blue-400">Projects</a>
                <a href="#contact" class="hover:text-blue-400">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="h-screen flex flex-col justify-center items-center text-center px-4">
        <img src="https://via.placeholder.com/150" alt="Profile Image" class="w-40 h-40 rounded-full border-4 border-blue-400">
        <h1 class="text-5xl font-bold text-blue-400 mt-4">Hello, I'm a Laravel Developer</h1>
        <p class="text-lg mt-4 text-gray-300">Building robust web applications with Laravel & Vue.js</p>
        <a href="#projects" class="mt-6 bg-blue-500 px-6 py-3 rounded-lg text-lg hover:bg-blue-600 transition">View My Work</a>
    </section>

    <!-- About Me -->
    <section id="about" class="py-20 bg-gray-800 text-center">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-blue-400">About Me</h2>
            <p class="mt-4 text-gray-300">I am a Laravel developer with 2.5 years of experience, specializing in backend development, APIs, and modern web applications.</p>
        </div>
    </section>

    <!-- Skills with Progress Bar -->
    <section id="skills" class="py-20 text-center">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-blue-400">My Skills</h2>
            <div class="mt-6 space-y-6 max-w-lg mx-auto">
                <div class="text-left">
                    <p class="font-semibold"><i class="fab fa-laravel text-red-500"></i> Laravel (90%)</p>
                    <div class="w-full bg-gray-700 h-2 rounded-full">
                        <div class="bg-blue-500 h-2 rounded-full" style="width: 90%;"></div>
                    </div>
                </div>
                <div class="text-left">
                    <p class="font-semibold"><i class="fab fa-vuejs text-green-500"></i> Vue.js (80%)</p>
                    <div class="w-full bg-gray-700 h-2 rounded-full">
                        <div class="bg-blue-500 h-2 rounded-full" style="width: 80%;"></div>
                    </div>
                </div>
                <div class="text-left">
                    <p class="font-semibold"><i class="fas fa-database text-yellow-500"></i> MySQL (85%)</p>
                    <div class="w-full bg-gray-700 h-2 rounded-full">
                        <div class="bg-blue-500 h-2 rounded-full" style="width: 85%;"></div>
                    </div>
                </div>
                <div class="text-left">
                    <p class="font-semibold"><i class="fas fa-code text-blue-300"></i> Tailwind CSS (75%)</p>
                    <div class="w-full bg-gray-700 h-2 rounded-full">
                        <div class="bg-blue-500 h-2 rounded-full" style="width: 75%;"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="py-20 bg-gray-800 text-center">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-blue-400">My Projects</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6 mt-6">
                <div class="p-6 bg-gray-900 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold text-blue-400">E-Commerce Website</h3>
                    <p class="text-gray-300 mt-2">Built with Laravel, Vue.js, and Stripe Payment Gateway.</p>
                </div>
                <div class="p-6 bg-gray-900 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold text-blue-400">Blog CMS</h3>
                    <p class="text-gray-300 mt-2">A dynamic content management system for blogs.</p>
                </div>
                <div class="p-6 bg-gray-900 rounded-lg shadow-lg">
                    <h3 class="text-xl font-semibold text-blue-400">Real-Time Chat App</h3>
                    <p class="text-gray-300 mt-2">Built with Laravel WebSockets and Vue.js.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="py-20 text-center">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-blue-400">Contact Me</h2>
            <p class="text-gray-300 mt-4">Let's work together! Feel free to reach out.</p>
            <a href="mailto:your.email@example.com" class="mt-6 inline-block bg-blue-500 px-6 py-3 rounded-lg text-lg hover:bg-blue-600 transition">Email Me</a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-6 bg-gray-800 text-center text-gray-400">
        &copy; 2025 Laravel Developer Portfolio | Built with Tailwind CSS
    </footer>

</body>
</html>
