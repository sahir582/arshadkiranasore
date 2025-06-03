
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arshad Kirana Store - Business Landing Page</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Canva-inspired styles */
        html {
            scroll-behavior: smooth;
        }
        .hero-bg {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://images.unsplash.com/photo-1516321310764-0f0f9b3c5b1f?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80') no-repeat center center/cover;
        }
        .font-heading {
            font-family: 'Poppins', sans-serif;
        }
        .font-body {
            font-family: 'Roboto', sans-serif;
        }
        /* Ensure images are responsive and fit properly */
        .service-img {
            object-fit: contain;
            max-width: 100%;
        }
        /* Contact button styles */
        .contact-button {
            position: fixed;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            z-index: 20;
        }
        /* Custom styles for the image box */
        .image-box {
            background-color: #f8e8d9; /* Cream background */
            border-bottom: 4px solid #8b5e3c; /* Brown border to match image theme */
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&family=Roboto:wght@400&display=swap" rel="stylesheet">
</head>
<body class="font-body text-gray-800 bg-white">
    <!-- Image Box Section -->
    <section class="image-box pt-16 pb-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-center">
                <img src="https://export-download.canva.com/SMZJE/DAGpF7SMZJE/2/0/0001-1816543943321826787.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAQYCGKMUH5AO7UJ26%2F20250531%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250531T110253Z&X-Amz-Expires=79967&X-Amz-Signature=e51f22246911d09eb04165b481c5cd3dd83f99c8b8cad98da41f398b9a37db2b&X-Amz-SignedHeaders=host&response-content-disposition=attachment%3B%20filename%2A%3DUTF-8%27%27Cream%2520and%2520Brown%2520Photographic%2520Beauty%2520Site%2520Launch%2520Website.png&response-expires=Sun%2C%2001%20Jun%202025%2009%3A15%3A40%20GMT" 
                     alt="Arshad Kirana Store Promo" 
                     class="w-full max-w-4xl rounded-lg shadow-lg border-4 border-red-500" 
                     onerror="this.src='https://via.placeholder.com/800x400?text=Promotional+Banner'">
            </div>
        </div>
    </section>

    <!-- Navbar -->
    <nav class="bg-white shadow-lg fixed w-full z-10 top-0">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <span class="text-2xl font-heading font-bold text-red-500">Arshad Kirana Store</span>
                </div>
                <div class="flex items-center space-x-4">
                    <a href="#home" class="text-gray-600 hover:text-red-500 px-3 py-2 rounded-md text-sm font-medium">Home</a>
                    <a href="#services" class="text-gray-600 hover:text-red-500 px-3 py-2 rounded-md text-sm font-medium">Services</a>
                    <a href="#testimonials" class="text-gray-600 hover:text-red-500 px-3 py-2 rounded-md text-sm font-medium">Testimonials</a>
                    <a href="#contact" class="text-gray-600 hover:text-red-500 px-3 py-2 rounded-md text-sm font-medium">Contact</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-bg text-white pt-24 pb-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h1 class="text-4xl md:text-5xl font-heading font-extrabold mb-4">Welcome to Arshad Kirana Store</h1>
            <p class="text-lg md:text-xl mb-8 max-w-2xl mx-auto">Your one-stop shop for quality groceries and essentials. Start shopping today!</p>
            <a href="#contact" class="inline-block bg-white text-red-500 font-semibold py-3 px-6 rounded-full hover:bg-gray-100 transition">Get Started</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-heading font-bold text-center mb-12">Our Services</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-lg shadow-lg text-center">
                    <img src="https://template.canva.com/EAFbCS-9WbQ/2/0/1600w-5HPNn8Zx6oU.jpg" alt="Quality Products" class="w-16 h-16 mx-auto mb-4 service-img" onerror="this.src='https://via.placeholder.com/64?text=Quality'">
                    <h3 class="text-xl font-heading font-semibold mb-4 text-red-500">Quality Products</h3>
                    <p class="text-gray-600">Fresh groceries and essentials for your daily needs.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg text-center">
                    <img src="https://i.imgur.com/WMW8Bts.png" alt="Fast Delivery" class="w-16 h-16 mx-auto mb-4 service-img" onerror="this.src='https://via.placeholder.com/64?text=Delivery'">
                    <h3 class="text-xl font-heading font-semibold mb-4 text-red-500">Fast Delivery</h3>
                    <p class="text-gray-600">Get your orders delivered to your doorstep quickly.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg text-center">
                    <img src="https://i.imgur.com/J8efyOS.jpeg" alt="Customer Support" class="w-16 h-16 mx-auto mb-4 service-img" onerror="this.src='https://via.placeholder.com/64?text=Support'">
                    <h3 class="text-xl font-heading font-semibold mb-4 text-red-500">Customer Support</h3>
                    <p class="text-gray-600">Friendly team to assist you with your shopping needs.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-heading font-bold text-center mb-12">Trusted by Customers</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg flex items-start">
                    <img src="https://images.unsplash.com/photo-1607349913338-fca6f7fc42d0?ixlib=rb-4.0.3&auto=format&fit=crop&w=100&q=80" alt="Ravi" class="w-12 h-12 rounded-full mr-4" onerror="this.src='https://via.placeholder.com/100?text=Ravi'">
                    <div>
                        <p class="text-gray-600 mb-4">"I’ve been shopping here for months, and the quality is always top-notch. The delivery is super quick, and the team is so helpful when I need to make changes to my order!"</p>
                        <p class="font-heading font-semibold text-red-500">Ravi, Customer</p>
                    </div>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg flex items-start">
                    <img src="https://images.unsplash.com/photo-1599834562135-b6fc90e642ca?ixlib=rb-4.0.3&auto=format&fit=crop&w=100&q=80" alt="Md Sarik" class="w-12 h-12 rounded-full mr-4" onerror="this.src='https://via.placeholder.com/100?text=Sarik'">
                    <div>
                        <p class="text-gray-600 mb-4">"The best kirana store in town!"</p>
                        <p class="font-heading font-semibold text-red-500">Md Sarik, Customer</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-heading font-bold text-center mb-12">Let’s Connect</h2>
            <div class="max-w-lg mx-auto">
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <div class="space-y-4">
                        <div>
                            <label for="name" class="block text-sm font-heading font-medium text-gray-700">Name</label>
                            <input type="text" id="name" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:ring-red-500 focus:border-red-500" placeholder="Your Name">
                        </div>
                        <div>
                            <label for="email" class="block text-sm font-heading font-medium text-gray-700">Email</label>
                            <input type="email" id="email" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:ring-red-500 focus:border-red-500" placeholder="Your Email">
                        </div>
                        <div>
                            <label for="message" class="block text-sm font-heading font-medium text-gray-700">Message</label>
                            <textarea id="message" rows="4" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:ring-red-500 focus:border-red-500" placeholder="Your Message"></textarea>
                        </div>
                        <button onclick="submitForm()" class="w-full bg-red-500 text-white font-heading font-semibold py-2 px-4 rounded-full hover:bg-red-600 transition">Send Message</button>
                    </div>
                    <div class="mt-6 text-center">
                        <p class="text-gray-600"><strong>Contact Number:</strong> <a href="tel:+917479961459" class="text-red-500 hover:underline">+91 7479961459</a></p>
                        <p class="text-gray-600"><strong>Email:</strong> <a href="mailto:mdsahir255@gmail.com" class="text-red-500 hover:underline">mdsahir255@gmail.com</a></p>
                        <p class="text-gray-600"><strong>Address:</strong> Khiriband, Bhagalpur 812005, India</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Button -->
    <a href="tel:+917479961459" class="contact-button inline-block bg-red-500 text-white font-heading font-semibold py-3 px-6 rounded-full hover:bg-red-600 transition">Call Us</a>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p>© 2025 Arshad Kirana Store. All rights reserved.</p>
        </div>
    </footer>

    <script>
        function submitForm() {
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const message = document.getElementById('message').value;
            if (name && email && message) {
                alert('Message sent successfully!');
                document.getElementById('name').value = '';
                document.getElementById('email').value = '';
                document.getElementById('message').value = '';
            } else {
                alert('Please fill in all fields.');
            }
        }
    </script>
</body>
</html>
