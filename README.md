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
    </style>
</head>
<body class="text-white bg-gray-900">
    <!-- Navbar -->
    <nav class="fixed top-0 left-0 w-full bg-red-600 text-white flex justify-between items-center px-6 py-3 z-50 shadow-lg">
        <h1 class="font-extrabold text-2xl tracking-wide">ManoKing</h1>

        <!-- Desktop Menu -->
        <div class="hidden md:flex gap-6 font-semibold">
            <a href="#home" class="hover:text-yellow-400 transition-colors">Home</a>
            <a href="#whymanoking" class="hover:text-yellow-400 transition-colors">Why ManoKing</a>
            <a href="#menu" class="hover:text-yellow-400 transition-colors">Menu</a>
            <a href="#gallery" class="hover:text-yellow-400 transition-colors">Gallery</a>
            <a href="#videos" class="hover:text-yellow-400 transition-colors">Videos</a>
            <a href="#franchise" class="hover:text-yellow-400 transition-colors">Franchise</a>
            <a href="#contact" class="hover:text-yellow-400 transition-colors">Contact</a>
        </div>

        <!-- Mobile Menu Button -->
        <button class="md:hidden" id="menuToggle">
            <svg id="menuIcon" class="w-7 h-7" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
            </svg>
            <svg id="closeIcon" class="w-7 h-7 hidden" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
            </svg>
        </button>

        <!-- Mobile Dropdown -->
        <div id="mobileMenu" class="absolute top-full left-0 w-full bg-red-600 flex-col text-center font-semibold md:hidden hidden animate-fadeIn">
            <a href="#home" class="block py-3 border-b border-white/20 hover:bg-yellow-400 hover:text-red-600 transition-colors mobile-link">Home</a>
            <a href="#whymanoking" class="block py-3 border-b border-white/20 hover:bg-yellow-400 hover:text-red-600 transition-colors mobile-link">Why ManoKing</a>
            <a href="#menu" class="block py-3 border-b border-white/20 hover:bg-yellow-400 hover:text-red-600 transition-colors mobile-link">Menu</a>
            <a href="#gallery" class="block py-3 border-b border-white/20 hover:bg-yellow-400 hover:text-red-600 transition-colors mobile-link">Gallery</a>
            <a href="#videos" class="block py-3 border-b border-white/20 hover:bg-yellow-400 hover:text-red-600 transition-colors mobile-link">Videos</a>
            <a href="#franchise" class="block py-3 border-b border-white/20 hover:bg-yellow-400 hover:text-red-600 transition-colors mobile-link">Franchise</a>
            <a href="#contact" class="block py-3 border-b border-white/20 hover:bg-yellow-400 hover:text-red-600 transition-colors mobile-link">Contact</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="bg-yellow-400 text-red-600 py-32 text-center relative overflow-hidden mt-16" data-aos="fade-up">
        <h1 class="text-5xl font-extrabold mb-4">"TILAWI LANG! NAMIT GID KAEEYO!"</h1>
        <p class="text-xl mb-6 text-black font-medium">
            Start your own <span class="text-red-600 font-bold">ManoKing Lechon Manok & Liempo House</span> Franchise today!
        </p>
        <p class="text-black mb-8">Proven & Tested Business Model • 5+ Years in Western Visayas • Now Expanding Nationwide!</p>
        <div class="flex flex-wrap justify-center gap-4">
            <a href="#franchise" class="bg-red-600 text-white px-6 py-3 rounded-xl font-bold hover-scale transition-transform">🔥 Apply for Franchise</a>
            <a href="#videos" class="bg-black text-yellow-400 px-6 py-3 rounded-xl font-bold hover-scale transition-transform">🍗 Watch Food Review</a>
            <a href="#videos" class="bg-red-700 text-white px-6 py-3 rounded-xl font-bold hover-scale transition-transform">🎥 Franchise Video</a>
        </div>
    </section>

    <!-- Why ManoKing -->
    <section id="whymanoking" class="bg-red-600 py-16 px-8 text-center" data-aos="fade-up">
        <h2 class="text-4xl font-extrabold mb-8">Why Choose ManoKing Franchise?</h2>
        <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
            <div class="bg-white text-red-600 p-6 rounded-xl" data-aos="zoom-in" data-aos-delay="100">
                <div class="text-4xl mb-4">🏆</div>
                <h3 class="text-xl font-bold mb-2">Proven Success</h3>
                <p class="text-gray-700">5+ years of successful operations in Western Visayas with consistent growth and customer satisfaction.</p>
            </div>
            <div class="bg-white text-red-600 p-6 rounded-xl" data-aos="zoom-in" data-aos-delay="200">
                <div class="text-4xl mb-4">💰</div>
                <h3 class="text-xl font-bold mb-2">Low Investment</h3>
                <p class="text-gray-700">Affordable franchise package with flexible payment terms and high return on investment potential.</p>
            </div>
            <div class="bg-white text-red-600 p-6 rounded-xl" data-aos="zoom-in" data-aos-delay="300">
                <div class="text-4xl mb-4">🤝</div>
                <h3 class="text-xl font-bold mb-2">Full Support</h3>
                <p class="text-gray-700">Complete training, marketing support, and ongoing assistance to ensure your franchise success.</p>
            </div>
        </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="bg-gray-900 py-16 px-8" data-aos="fade-up">
        <h2 class="text-4xl font-extrabold text-center mb-12 text-yellow-400">Our Signature Menu</h2>
        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8 max-w-6xl mx-auto">
            <div class="bg-red-600 p-6 rounded-xl text-center" data-aos="flip-left" data-aos-delay="100">
                <div class="text-5xl mb-4">🍗</div>
                <h3 class="text-xl font-bold mb-2">Lechon Manok</h3>
                <p class="text-sm">Perfectly roasted chicken with our secret blend of spices</p>
            </div>
            <div class="bg-red-600 p-6 rounded-xl text-center" data-aos="flip-left" data-aos-delay="200">
                <div class="text-5xl mb-4">🥩</div>
                <h3 class="text-xl font-bold mb-2">Liempo</h3>
                <p class="text-sm">Juicy grilled pork belly marinated to perfection</p>
            </div>
            <div class="bg-red-600 p-6 rounded-xl text-center" data-aos="flip-left" data-aos-delay="300">
                <div class="text-5xl mb-4">🍚</div>
                <h3 class="text-xl font-bold mb-2">Rice Meals</h3>
                <p class="text-sm">Complete meals with rice and our signature dishes</p>
            </div>
            <div class="bg-red-600 p-6 rounded-xl text-center" data-aos="flip-left" data-aos-delay="400">
                <div class="text-5xl mb-4">🥤</div>
                <h3 class="text-xl font-bold mb-2">Beverages</h3>
                <p class="text-sm">Refreshing drinks to complement your meal</p>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="bg-yellow-400 py-16 px-8" data-aos="fade-up">
        <h2 class="text-4xl font-extrabold text-center mb-12 text-red-600">Gallery</h2>
        <div class="grid md:grid-cols-3 gap-6 max-w-6xl mx-auto">
            <div class="bg-red-600 h-64 rounded-xl flex items-center justify-center text-white text-6xl" data-aos="zoom-in" data-aos-delay="100">🍗</div>
            <div class="bg-red-600 h-64 rounded-xl flex items-center justify-center text-white text-6xl" data-aos="zoom-in" data-aos-delay="200">🥩</div>
            <div class="bg-red-600 h-64 rounded-xl flex items-center justify-center text-white text-6xl" data-aos="zoom-in" data-aos-delay="300">🏪</div>
            <div class="bg-red-600 h-64 rounded-xl flex items-center justify-center text-white text-6xl" data-aos="zoom-in" data-aos-delay="400">👨‍🍳</div>
            <div class="bg-red-600 h-64 rounded-xl flex items-center justify-center text-white text-6xl" data-aos="zoom-in" data-aos-delay="500">🍽️</div>
            <div class="bg-red-600 h-64 rounded-xl flex items-center justify-center text-white text-6xl" data-aos="zoom-in" data-aos-delay="600">😋</div>
        </div>
    </section>

    <!-- Videos Section -->
    <section id="videos" class="bg-gray-900 py-16 px-8" data-aos="fade-up">
        <h2 class="text-4xl font-extrabold text-center mb-12 text-yellow-400">Watch Our Videos</h2>
        <div class="grid md:grid-cols-2 gap-8 max-w-4xl mx-auto">
            <div class="bg-red-600 h-64 rounded-xl flex flex-col items-center justify-center text-white" data-aos="fade-right">
                <div class="text-6xl mb-4">🎥</div>
                <h3 class="text-xl font-bold mb-2">Food Review</h3>
                <p class="text-center px-4">Watch food bloggers review our delicious lechon manok and liempo</p>
            </div>
            <div class="bg-red-600 h-64 rounded-xl flex flex-col items-center justify-center text-white" data-aos="fade-left">
                <div class="text-6xl mb-4">📹</div>
                <h3 class="text-xl font-bold mb-2">Franchise Video</h3>
                <p class="text-center px-4">Learn about our franchise opportunity and success stories</p>
            </div>
        </div>
    </section>

    <!-- Franchise Application -->
    <section id="franchise" class="bg-red-600 py-16 px-8" data-aos="fade-up">
        <h2 class="text-4xl font-extrabold text-center mb-8">Apply for ManoKing Franchise</h2>
        <div class="max-w-2xl mx-auto bg-white rounded-xl p-8">
            <form id="franchiseForm" class="space-y-6">
                <div class="grid md:grid-cols-2 gap-4">
                    <div>
                        <label class="block text-gray-700 font-semibold mb-2">Full Name *</label>
                        <input type="text" name="name" required class="w-full p-3 border border-gray-300 rounded-lg text-gray-900 focus:ring-2 focus:ring-red-600 focus:border-transparent">
                    </div>
                    <div>
                        <label class="block text-gray-700 font-semibold mb-2">Contact Number *</label>
                        <input type="tel" name="contact" required class="w-full p-3 border border-gray-300 rounded-lg text-gray-900 focus:ring-2 focus:ring-red-600 focus:border-transparent">
                    </div>
                </div>
                <div class="grid md:grid-cols-2 gap-4">
                    <div>
                        <label class="block text-gray-700 font-semibold mb-2">Email Address *</label>
                        <input type="email" name="email" required class="w-full p-3 border border-gray-300 rounded-lg text-gray-900 focus:ring-2 focus:ring-red-600 focus:border-transparent">
                    </div>
                    <div>
                        <label class="block text-gray-700 font-semibold mb-2">Preferred Location *</label>
                        <input type="text" name="location" required class="w-full p-3 border border-gray-300 rounded-lg text-gray-900 focus:ring-2 focus:ring-red-600 focus:border-transparent">
                    </div>
                </div>
                <div>
                    <label class="block text-gray-700 font-semibold mb-2">Outlet Type</label>
                    <select name="outlet" class="w-full p-3 border border-gray-300 rounded-lg text-gray-900 focus:ring-2 focus:ring-red-600 focus:border-transparent">
                        <option value="">Select outlet type</option>
                        <option value="kiosk">Kiosk</option>
                        <option value="small-store">Small Store</option>
                        <option value="full-restaurant">Full Restaurant</option>
                    </select>
                </div>
                <div>
                    <label class="block text-gray-700 font-semibold mb-2">Message</label>
                    <textarea name="message" rows="4" class="w-full p-3 border border-gray-300 rounded-lg text-gray-900 focus:ring-2 focus:ring-red-600 focus:border-transparent" placeholder="Tell us about your business experience and why you want to join ManoKing..."></textarea>
                </div>
                <button type="submit" class="w-full bg-red-600 text-white py-3 rounded-lg font-bold text-lg hover:bg-red-700 transition-colors">
                    🔥 Submit Franchise Application
                </button>
            </form>
            <div id="formStatus" class="mt-4 text-center font-semibold"></div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-gray-900 py-16 px-8" data-aos="fade-up">
        <h2 class="text-4xl font-extrabold text-center mb-12 text-yellow-400">Contact Us</h2>
        <div class="grid md:grid-cols-3 gap-8 max-w-4xl mx-auto text-center">
            <div class="bg-red-600 p-6 rounded-xl" data-aos="zoom-in" data-aos-delay="100">
                <div class="text-4xl mb-4">📞</div>
                <h3 class="text-xl font-bold mb-2">Phone</h3>
                <p>+63 XXX XXX XXXX</p>
            </div>
            <div class="bg-red-600 p-6 rounded-xl" data-aos="zoom-in" data-aos-delay="200">
                <div class="text-4xl mb-4">📧</div>
                <h3 class="text-xl font-bold mb-2">Email</h3>
                <p>franchise@manoking.com</p>
            </div>
            <div class="bg-red-600 p-6 rounded-xl" data-aos="zoom-in" data-aos-delay="300">
                <div class="text-4xl mb-4">📍</div>
                <h3 class="text-xl font-bold mb-2">Location</h3>
                <p>Western Visayas, Philippines</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-black py-8 px-8 text-center">
        <div class="max-w-4xl mx-auto">
            <h3 class="text-2xl font-bold text-yellow-400 mb-4">ManoKing</h3>
            <p class="text-gray-400 mb-4">Lechon Manok & Liempo House - "TILAWI LANG! NAMIT GID KAEEYO!"</p>
            <p class="text-gray-500 text-sm">© 2024 ManoKing. All rights reserved. | Franchise opportunities available nationwide.</p>
        </div>
    </footer>

    <script>
        // Initialize AOS
        AOS.init({
            duration: 800,
            once: true
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
            
            formStatus.textContent = 'Sending...';
            formStatus.className = 'mt-4 text-center font-semibold text-blue-600';
            
            try {
                // Simulate form submission
                await new Promise(resolve => setTimeout(resolve, 1500));
                
                formStatus.textContent = '✅ Application Sent! Our team will contact you soon.';
                formStatus.className = 'mt-4 text-center font-semibold text-green-600';
                
                // Reset form
                franchiseForm.reset();
                
            } catch (error) {
                formStatus.textContent = '❌ Failed to send. Please try again later.';
                formStatus.className = 'mt-4 text-center font-semibold text-red-600';
            }
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'98a42dd793650452',t:'MTc1OTc0MzQzNS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
