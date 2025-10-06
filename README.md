<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ManoKing - Lechon Manok & Liempo House Franchise</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <style>
        body {
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        
        .animate-fadeIn {
            animation: fadeIn 0.3s ease-in-out;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        html {
            scroll-behavior: smooth;
        }
        
        .hover-scale:hover {
            transform: scale(1.05);
        }

        .bg-gradient-hero {
            background: linear-gradient(135deg, #FFD500 0%, #FFA500 100%);
        }

        .text-shadow {
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
        }

        .pulse-animation {
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }
    </style>
</head>
<body class="text-white bg-gray-900">
    <!-- Navbar -->
    <nav class="fixed top-0 left-0 w-full bg-red-600 text-white flex justify-between items-center px-6 py-4 z-50 shadow-2xl backdrop-blur-sm">
        <div class="flex items-center space-x-2">
            <div class="text-3xl">🍗</div>
            <h1 class="font-extrabold text-2xl tracking-wide text-shadow">ManoKing</h1>
        </div>

        <!-- Desktop Menu -->
        <div class="hidden md:flex gap-8 font-semibold">
            <a href="#home" class="hover:text-yellow-400 transition-all duration-300 hover:scale-110">Home</a>
            <a href="#whymanoking" class="hover:text-yellow-400 transition-all duration-300 hover:scale-110">Why ManoKing</a>
            <a href="#menu" class="hover:text-yellow-400 transition-all duration-300 hover:scale-110">Menu</a>
            <a href="#gallery" class="hover:text-yellow-400 transition-all duration-300 hover:scale-110">Gallery</a>
            <a href="#videos" class="hover:text-yellow-400 transition-all duration-300 hover:scale-110">Videos</a>
            <a href="#franchise" class="hover:text-yellow-400 transition-all duration-300 hover:scale-110">Franchise</a>
            <a href="#contact" class="hover:text-yellow-400 transition-all duration-300 hover:scale-110">Contact</a>
        </div>

        <!-- Mobile Menu Button -->
        <button class="md:hidden p-2 rounded-lg hover:bg-red-700 transition-colors" id="menuToggle">
            <svg id="menuIcon" class="w-7 h-7" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
            </svg>
            <svg id="closeIcon" class="w-7 h-7 hidden" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
            </svg>
        </button>

        <!-- Mobile Dropdown -->
        <div id="mobileMenu" class="absolute top-full left-0 w-full bg-red-600 flex-col text-center font-semibold md:hidden hidden animate-fadeIn shadow-2xl">
            <a href="#home" class="block py-4 border-b border-white/20 hover:bg-yellow-400 hover:text-red-600 transition-all duration-300 mobile-link">🏠 Home</a>
            <a href="#whymanoking" class="block py-4 border-b border-white/20 hover:bg-yellow-400 hover:text-red-600 transition-all duration-300 mobile-link">⭐ Why ManoKing</a>
            <a href="#menu" class="block py-4 border-b border-white/20 hover:bg-yellow-400 hover:text-red-600 transition-all duration-300 mobile-link">🍽️ Menu</a>
            <a href="#gallery" class="block py-4 border-b border-white/20 hover:bg-yellow-400 hover:text-red-600 transition-all duration-300 mobile-link">📸 Gallery</a>
            <a href="#videos" class="block py-4 border-b border-white/20 hover:bg-yellow-400 hover:text-red-600 transition-all duration-300 mobile-link">🎥 Videos</a>
            <a href="#franchise" class="block py-4 border-b border-white/20 hover:bg-yellow-400 hover:text-red-600 transition-all duration-300 mobile-link">🤝 Franchise</a>
            <a href="#contact" class="block py-4 hover:bg-yellow-400 hover:text-red-600 transition-all duration-300 mobile-link">📞 Contact</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="bg-gradient-hero text-red-600 py-32 text-center relative overflow-hidden mt-20" data-aos="fade-up">
        <div class="absolute inset-0 bg-black/10"></div>
        <div class="relative z-10 max-w-6xl mx-auto px-4">
            <div class="text-8xl mb-6 pulse-animation">🍗</div>
            <h1 class="text-6xl md:text-7xl font-extrabold mb-6 text-shadow">"TILAWI LANG! NAMIT GID KAEEYO!"</h1>
            <p class="text-2xl mb-8 text-black font-bold max-w-4xl mx-auto">
                Start your own <span class="text-red-600 bg-white px-2 py-1 rounded">ManoKing Lechon Manok & Liempo House</span> Franchise today!
            </p>
            <p class="text-black mb-12 text-lg font-medium">Proven & Tested Business Model • 5+ Years in Western Visayas • Now Expanding Nationwide!</p>
            <div class="flex flex-wrap justify-center gap-6">
                <a href="#franchise" class="bg-red-600 text-white px-8 py-4 rounded-2xl font-bold text-lg hover-scale transition-all duration-300 shadow-2xl hover:shadow-red-600/50">🔥 Apply for Franchise</a>
                <a href="#videos" class="bg-black text-yellow-400 px-8 py-4 rounded-2xl font-bold text-lg hover-scale transition-all duration-300 shadow-2xl">🍗 Watch Food Review</a>
                <a href="#videos" class="bg-red-700 text-white px-8 py-4 rounded-2xl font-bold text-lg hover-scale transition-all duration-300 shadow-2xl">🎥 Franchise Video</a>
            </div>
        </div>
    </section>

    <!-- Why ManoKing -->
    <section id="whymanoking" class="bg-red-600 py-20 px-8 text-center relative" data-aos="fade-up">
        <div class="absolute inset-0 bg-black/10"></div>
        <div class="relative z-10">
            <h2 class="text-5xl font-extrabold mb-4 text-shadow">Why Choose ManoKing Franchise?</h2>
            <p class="text-xl mb-12 max-w-3xl mx-auto">Join the most successful lechon manok franchise in Western Visayas!</p>
            <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
                <div class="bg-white text-red-600 p-8 rounded-2xl card-hover transition-all duration-300" data-aos="zoom-in" data-aos-delay="100">
                    <div class="text-6xl mb-6">🏆</div>
                    <h3 class="text-2xl font-bold mb-4">Proven Success</h3>
                    <p class="text-gray-700 text-lg">5+ years of successful operations in Western Visayas with consistent growth and customer satisfaction.</p>
                </div>
                <div class="bg-white text-red-600 p-8 rounded-2xl card-hover transition-all duration-300" data-aos="zoom-in" data-aos-delay="200">
                    <div class="text-6xl mb-6">💰</div>
                    <h3 class="text-2xl font-bold mb-4">Low Investment</h3>
                    <p class="text-gray-700 text-lg">Affordable franchise package with flexible payment terms and high return on investment potential.</p>
                </div>
                <div class="bg-white text-red-600 p-8 rounded-2xl card-hover transition-all duration-300" data-aos="zoom-in" data-aos-delay="300">
                    <div class="text-6xl mb-6">🤝</div>
                    <h3 class="text-2xl font-bold mb-4">Full Support</h3>
                    <p class="text-gray-700 text-lg">Complete training, marketing support, and ongoing assistance to ensure your franchise success.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="bg-gray-900 py-20 px-8" data-aos="fade-up">
        <h2 class="text-5xl font-extrabold text-center mb-6 text-yellow-400 text-shadow">Our Signature Menu</h2>
        <p class="text-center text-xl mb-16 text-gray-300 max-w-3xl mx-auto">Taste the authentic flavors that made us famous across Western Visayas!</p>
        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8 max-w-7xl mx-auto">
            <div class="bg-gradient-to-br from-red-600 to-red-700 p-8 rounded-2xl text-center card-hover transition-all duration-300 shadow-2xl" data-aos="flip-left" data-aos-delay="100">
                <div class="text-7xl mb-6">🍗</div>
                <h3 class="text-2xl font-bold mb-4">Lechon Manok</h3>
                <p class="text-lg">Perfectly roasted chicken with our secret blend of spices that keeps customers coming back!</p>
            </div>
            <div class="bg-gradient-to-br from-red-600 to-red-700 p-8 rounded-2xl text-center card-hover transition-all duration-300 shadow-2xl" data-aos="flip-left" data-aos-delay="200">
                <div class="text-7xl mb-6">🥩</div>
                <h3 class="text-2xl font-bold mb-4">Liempo</h3>
                <p class="text-lg">Juicy grilled pork belly marinated to perfection with our signature sauce</p>
            </div>
            <div class="bg-gradient-to-br from-red-600 to-red-700 p-8 rounded-2xl text-center card-hover transition-all duration-300 shadow-2xl" data-aos="flip-left" data-aos-delay="300">
                <div class="text-7xl mb-6">🍚</div>
                <h3 class="text-2xl font-bold mb-4">Rice Meals</h3>
                <p class="text-lg">Complete meals with rice and our signature dishes - perfect for any time of day</p>
            </div>
            <div class="bg-gradient-to-br from-red-600 to-red-700 p-8 rounded-2xl text-center card-hover transition-all duration-300 shadow-2xl" data-aos="flip-left" data-aos-delay="400">
                <div class="text-7xl mb-6">🥤</div>
                <h3 class="text-2xl font-bold mb-4">Beverages</h3>
                <p class="text-lg">Refreshing drinks to complement your meal and beat the tropical heat</p>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="bg-gradient-to-br from-yellow-400 to-yellow-500 py-20 px-8" data-aos="fade-up">
        <h2 class="text-5xl font-extrabold text-center mb-6 text-red-600 text-shadow">Gallery</h2>
        <p class="text-center text-xl mb-16 text-black font-medium max-w-3xl mx-auto">See our delicious food, happy customers, and successful franchise locations!</p>
        <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
            <div class="bg-gradient-to-br from-red-600 to-red-700 h-80 rounded-2xl flex flex-col items-center justify-center text-white shadow-2xl card-hover transition-all duration-300" data-aos="zoom-in" data-aos-delay="100">
                <div class="text-8xl mb-4">🍗</div>
                <p class="text-xl font-bold">Fresh Lechon Manok</p>
            </div>
            <div class="bg-gradient-to-br from-red-600 to-red-700 h-80 rounded-2xl flex flex-col items-center justify-center text-white shadow-2xl card-hover transition-all duration-300" data-aos="zoom-in" data-aos-delay="200">
                <div class="text-8xl mb-4">🥩</div>
                <p class="text-xl font-bold">Grilled Liempo</p>
            </div>
            <div class="bg-gradient-to-br from-red-600 to-red-700 h-80 rounded-2xl flex flex-col items-center justify-center text-white shadow-2xl card-hover transition-all duration-300" data-aos="zoom-in" data-aos-delay="300">
                <div class="text-8xl mb-4">🏪</div>
                <p class="text-xl font-bold">Our Stores</p>
            </div>
            <div class="bg-gradient-to-br from-red-600 to-red-700 h-80 rounded-2xl flex flex-col items-center justify-center text-white shadow-2xl card-hover transition-all duration-300" data-aos="zoom-in" data-aos-delay="400">
                <div class="text-8xl mb-4">👨‍🍳</div>
                <p class="text-xl font-bold">Expert Chefs</p>
            </div>
            <div class="bg-gradient-to-br from-red-600 to-red-700 h-80 rounded-2xl flex flex-col items-center justify-center text-white shadow-2xl card-hover transition-all duration-300" data-aos="zoom-in" data-aos-delay="500">
                <div class="text-8xl mb-4">🍽️</div>
                <p class="text-xl font-bold">Dining Experience</p>
            </div>
            <div class="bg-gradient-to-br from-red-600 to-red-700 h-80 rounded-2xl flex flex-col items-center justify-center text-white shadow-2xl card-hover transition-all duration-300" data-aos="zoom-in" data-aos-delay="600">
                <div class="text-8xl mb-4">😋</div>
                <p class="text-xl font-bold">Happy Customers</p>
            </div>
        </div>
    </section>

    <!-- Videos Section -->
    <section id="videos" class="bg-gray-900 py-20 px-8" data-aos="fade-up">
        <h2 class="text-5xl font-extrabold text-center mb-6 text-yellow-400 text-shadow">Watch Our Videos</h2>
        <p class="text-center text-xl mb-16 text-gray-300 max-w-3xl mx-auto">See what food bloggers and customers are saying about ManoKing!</p>
        <div class="grid md:grid-cols-2 gap-12 max-w-5xl mx-auto">
            <div class="bg-gradient-to-br from-red-600 to-red-700 h-80 rounded-2xl flex flex-col items-center justify-center text-white shadow-2xl card-hover transition-all duration-300 cursor-pointer" data-aos="fade-right">
                <div class="text-8xl mb-6">🎥</div>
                <h3 class="text-2xl font-bold mb-4">Food Review Videos</h3>
                <p class="text-center px-6 text-lg">Watch food bloggers review our delicious lechon manok and liempo. See why we're the talk of the town!</p>
                <div class="mt-4 bg-yellow-400 text-red-600 px-6 py-2 rounded-full font-bold">▶ Watch Now</div>
            </div>
            <div class="bg-gradient-to-br from-red-600 to-red-700 h-80 rounded-2xl flex flex-col items-center justify-center text-white shadow-2xl card-hover transition-all duration-300 cursor-pointer" data-aos="fade-left">
                <div class="text-8xl mb-6">📹</div>
                <h3 class="text-2xl font-bold mb-4">Franchise Success Stories</h3>
                <p class="text-center px-6 text-lg">Learn about our franchise opportunity and hear from successful franchise owners across the Philippines</p>
                <div class="mt-4 bg-yellow-400 text-red-600 px-6 py-2 rounded-full font-bold">▶ Watch Now</div>
            </div>
        </div>
    </section>

    <!-- Franchise Application -->
    <section id="franchise" class="bg-red-600 py-20 px-8 relative" data-aos="fade-up">
        <div class="absolute inset-0 bg-black/10"></div>
        <div class="relative z-10">
            <h2 class="text-5xl font-extrabold text-center mb-6 text-shadow">Apply for ManoKing Franchise</h2>
            <p class="text-center text-xl mb-12 max-w-3xl mx-auto">Ready to start your own successful business? Fill out the form below and our team will contact you within 24 hours!</p>
            <div class="max-w-3xl mx-auto bg-white rounded-2xl p-10 shadow-2xl">
                <form id="franchiseForm" class="space-y-8">
                    <div class="grid md:grid-cols-2 gap-6">
                        <div>
                            <label class="block text-gray-700 font-bold mb-3 text-lg">Full Name *</label>
                            <input type="text" name="name" required class="w-full p-4 border-2 border-gray-300 rounded-xl text-gray-900 text-lg focus:ring-4 focus:ring-red-600/20 focus:border-red-600 transition-all duration-300">
                        </div>
                        <div>
                            <label class="block text-gray-700 font-bold mb-3 text-lg">Contact Number *</label>
                            <input type="tel" name="contact" required class="w-full p-4 border-2 border-gray-300 rounded-xl text-gray-900 text-lg focus:ring-4 focus:ring-red-600/20 focus:border-red-600 transition-all duration-300">
                        </div>
                    </div>
                    <div class="grid md:grid-cols-2 gap-6">
                        <div>
                            <label class="block text-gray-700 font-bold mb-3 text-lg">Email Address *</label>
                            <input type="email" name="email" required class="w-full p-4 border-2 border-gray-300 rounded-xl text-gray-900 text-lg focus:ring-4 focus:ring-red-600/20 focus:border-red-600 transition-all duration-300">
                        </div>
                        <div>
                            <label class="block text-gray-700 font-bold mb-3 text-lg">Preferred Location *</label>
                            <input type="text" name="location" required class="w-full p-4 border-2 border-gray-300 rounded-xl text-gray-900 text-lg focus:ring-4 focus:ring-red-600/20 focus:border-red-600 transition-all duration-300">
                        </div>
                    </div>
                    <div>
                        <label class="block text-gray-700 font-bold mb-3 text-lg">Outlet Type</label>
                        <select name="outlet" class="w-full p-4 border-2 border-gray-300 rounded-xl text-gray-900 text-lg focus:ring-4 focus:ring-red-600/20 focus:border-red-600 transition-all duration-300">
                            <option value="">Select outlet type</option>
                            <option value="kiosk">Kiosk (₱300,000 - ₱500,000)</option>
                            <option value="small-store">Small Store (₱500,000 - ₱800,000)</option>
                            <option value="full-restaurant">Full Restaurant (₱800,000 - ₱1,200,000)</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-gray-700 font-bold mb-3 text-lg">Message</label>
                        <textarea name="message" rows="5" class="w-full p-4 border-2 border-gray-300 rounded-xl text-gray-900 text-lg focus:ring-4 focus:ring-red-600/20 focus:border-red-600 transition-all duration-300" placeholder="Tell us about your business experience and why you want to join ManoKing..."></textarea>
                    </div>
                    <button type="submit" class="w-full bg-red-600 text-white py-4 rounded-xl font-bold text-xl hover:bg-red-700 transition-all duration-300 shadow-2xl hover:shadow-red-600/50 hover-scale">
                        🔥 Submit Franchise Application
                    </button>
                </form>
                <div id="formStatus" class="mt-6 text-center font-bold text-lg"></div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-gray-900 py-20 px-8" data-aos="fade-up">
        <h2 class="text-5xl font-extrabold text-center mb-6 text-yellow-400 text-shadow">Contact Us</h2>
        <p class="text-center text-xl mb-16 text-gray-300 max-w-3xl mx-auto">Get in touch with our franchise team. We're here to help you start your ManoKing journey!</p>
        <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto text-center">
            <div class="bg-gradient-to-br from-red-600 to-red-700 p-8 rounded-2xl card-hover transition-all duration-300 shadow-2xl" data-aos="zoom-in" data-aos-delay="100">
                <div class="text-6xl mb-6">📞</div>
                <h3 class="text-2xl font-bold mb-4">Phone</h3>
                <p class="text-lg">+63 XXX XXX XXXX</p>
                <p class="text-sm mt-2 opacity-80">Available 9AM - 6PM</p>
            </div>
            <div class="bg-gradient-to-br from-red-600 to-red-700 p-8 rounded-2xl card-hover transition-all duration-300 shadow-2xl" data-aos="zoom-in" data-aos-delay="200">
                <div class="text-6xl mb-6">📧</div>
                <h3 class="text-2xl font-bold mb-4">Email</h3>
                <p class="text-lg">franchise@manoking.com</p>
                <p class="text-sm mt-2 opacity-80">We reply within 24 hours</p>
            </div>
            <div class="bg-gradient-to-br from-red-600 to-red-700 p-8 rounded-2xl card-hover transition-all duration-300 shadow-2xl" data-aos="zoom-in" data-aos-delay="300">
                <div class="text-6xl mb-6">📍</div>
                <h3 class="text-2xl font-bold mb-4">Location</h3>
                <p class="text-lg">Western Visayas, Philippines</p>
                <p class="text-sm mt-2 opacity-80">Expanding Nationwide</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-black py-12 px-8 text-center">
        <div class="max-w-6xl mx-auto">
            <div class="flex items-center justify-center space-x-3 mb-6">
                <div class="text-4xl">🍗</div>
                <h3 class="text-3xl font-bold text-yellow-400">ManoKing</h3>
            </div>
            <p class="text-gray-400 mb-6 text-lg">Lechon Manok & Liempo House - "TILAWI LANG! NAMIT GID KAEEYO!"</p>
            <div class="flex flex-wrap justify-center gap-6 mb-8">
                <a href="#home" class="text-gray-400 hover:text-yellow-400 transition-colors">Home</a>
                <a href="#whymanoking" class="text-gray-400 hover:text-yellow-400 transition-colors">Why ManoKing</a>
                <a href="#menu" class="text-gray-400 hover:text-yellow-400 transition-colors">Menu</a>
                <a href="#franchise" class="text-gray-400 hover:text-yellow-400 transition-colors">Franchise</a>
                <a href="#contact" class="text-gray-400 hover:text-yellow-400 transition-colors">Contact</a>
            </div>
            <div class="border-t border-gray-800 pt-6">
                <p class="text-gray-500">© 2024 ManoKing. All rights reserved. | Franchise opportunities available nationwide.</p>
            </div>
        </div>
    </footer>

    <script>
        // Initialize AOS
        AOS.init({
            duration: 800,
            once: true,
            offset: 100
        });

        // Mobile menu toggle
        const menuToggle = document.getElementById('menuToggle');
        const mobileMenu = document.getElementById('mobileMenu');
        const menuIcon = document.getElementById('menuIcon');
        const closeIcon = document.getElementById('closeIcon');
        let menuOpen = false;

        menuToggle.addEventListener('click', function() {
            menuOpen = !menuOpen;
            
            if (menuOpen) {
                mobileMenu.classList.remove('hidden');
                mobileMenu.classList.add('flex');
                menuIcon.classList.add('hidden');
                closeIcon.classList.remove('hidden');
            } else {
                mobileMenu.classList.add('hidden');
                mobileMenu.classList.remove('flex');
                menuIcon.classList.remove('hidden');
                closeIcon.classList.add('hidden');
            }
        });

        // Close mobile menu when clicking on links
        const mobileLinks = document.querySelectorAll('.mobile-link');
        mobileLinks.forEach(link => {
            link.addEventListener('click', function() {
                mobileMenu.classList.add('hidden');
                mobileMenu.classList.remove('flex');
                menuIcon.classList.remove('hidden');
                closeIcon.classList.add('hidden');
                menuOpen = false;
            });
        });

        // Form handling
        const franchiseForm = document.getElementById('franchiseForm');
        const formStatus = document.getElementById('formStatus');

        franchiseForm.addEventListener('submit', async function(e) {
            e.preventDefault();
            
            const formData = new FormData(franchiseForm);
            const data = Object.fromEntries(formData);
            
            formStatus.textContent = '⏳ Sending your application...';
            formStatus.className = 'mt-6 text-center font-bold text-lg text-blue-600';
            
            try {
                // Simulate form submission with more realistic delay
                await new Promise(resolve => setTimeout(resolve, 2000));
                
                formStatus.textContent = '✅ Application Sent Successfully! Our franchise team will contact you within 24 hours.';
                formStatus.className = 'mt-6 text-center font-bold text-lg text-green-600';
                
                // Reset form
                franchiseForm.reset();
                
                // Auto-hide success message after 10 seconds
                setTimeout(() => {
                    formStatus.textContent = '';
                }, 10000);
                
            } catch (error) {
                formStatus.textContent = '❌ Failed to send application. Please try again or contact us directly.';
                formStatus.className = 'mt-6 text-center font-bold text-lg text-red-600';
            }
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    const offsetTop = target.offsetTop - 80; // Account for fixed navbar
                    window.scrollTo({
                        top: offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });

        // Add scroll effect to navbar
        window.addEventListener('scroll', function() {
            const navbar = document.querySelector('nav');
            if (window.scrollY > 100) {
                navbar.classList.add('bg-red-700');
                navbar.classList.remove('bg-red-600');
            } else {
                navbar.classList.add('bg-red-600');
                navbar.classList.remove('bg-red-700');
            }
        });

        // Add click effects to video sections
        const videoCards = document.querySelectorAll('#videos .cursor-pointer');
        videoCards.forEach(card => {
            card.addEventListener('click', function() {
                const title = this.querySelector('h3').textContent;
                alert(`🎥 ${title}\n\nThis would normally open the video player. In a real implementation, you would integrate with YouTube, Vimeo, or your own video hosting solution.`);
            });
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'98a40643a0c7fee5',t:'MTc1OTc0MTgxNC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
