<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RealHomes and Property | Commercial Real Estate</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
        .gold-accent { color: #D4AF37; }
        .bg-gold { background-color: #D4AF37; }
        .bg-navy { background-color: #0A192F; }
        .hero-gradient { background: linear-gradient(rgba(10, 25, 47, 0.8), rgba(10, 25, 47, 0.6)); }
        .card-hover:hover { transform: translateY(-10px); transition: all 0.3s ease; }
    </style>
</head>
<body class="bg-white text-gray-800">

    <nav class="fixed w-full z-50 bg-white/90 backdrop-blur-md shadow-sm">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold text-navy">REAL<span class="gold-accent">HOMES</span></div>
            <div class="hidden md:flex space-x-8 font-medium">
                <a href="#home" class="hover:text-yellow-600 transition">Home</a>
                <a href="#about" class="hover:text-yellow-600 transition">About</a>
                <a href="#properties" class="hover:text-yellow-600 transition">Properties</a>
                <a href="#services" class="hover:text-yellow-600 transition">Services</a>
                <a href="#contact" class="px-5 py-2 bg-navy text-white rounded-md hover:bg-gray-800 transition">Contact Us</a>
            </div>
        </div>
    </nav>

    <section id="home" class="relative h-screen flex items-center justify-center text-white">
        <div class="absolute inset-0 z-0">
            <img src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?auto=format&fit=crop&q=80&w=2070" alt="Abuja Skyline" class="w-full h-full object-cover">
            <div class="absolute inset-0 hero-gradient"></div>
        </div>
        <div class="relative z-10 text-center px-6 max-w-4xl">
            <h1 class="text-5xl md:text-7xl font-bold mb-6">Your Trusted Partner in <span class="gold-accent">Commercial Real Estate</span></h1>
            <p class="text-xl mb-10 text-gray-200">Helping you find the perfect property for your business and investment needs.</p>
            <div class="flex flex-col md:flex-row justify-center gap-4">
                <a href="#properties" class="bg-gold hover:bg-yellow-600 text-white px-8 py-4 rounded-lg font-bold transition">Explore Properties</a>
                <a href="#contact" class="bg-white/10 backdrop-blur-md border border-white/30 hover:bg-white hover:text-navy px-8 py-4 rounded-lg font-bold transition">Contact Us</a>
            </div>
        </div>
    </section>

    <section id="about" class="py-24 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-16 items-center">
            <div>
                <span class="text-sm font-bold uppercase tracking-widest gold-accent">Since Inception</span>
                <h2 class="text-4xl font-bold mt-4 mb-6 text-navy">Reliability You Can Build On</h2>
                <p class="text-gray-600 leading-relaxed mb-6">
                    RealHomes and Property is a reliable commercial real estate agency based in Lugbe, Federal Capital Territory. We specialize in navigating the complex commercial landscape of Abuja and beyond.
                </p>
                <p class="text-gray-600 leading-relaxed">
                    Our focus remains steadfast: professionalism, trusted service, and delivering the best property solutions to our local and international clients.
                </p>
            </div>
            <div class="grid grid-cols-2 gap-4">
                <div class="p-8 bg-white shadow-lg rounded-xl text-center">
                    <i data-lucide="shield-check" class="mx-auto mb-4 gold-accent w-10 h-10"></i>
                    <h4 class="font-bold">Trusted</h4>
                </div>
                <div class="p-8 bg-navy text-white shadow-lg rounded-xl text-center">
                    <i data-lucide="award" class="mx-auto mb-4 gold-accent w-10 h-10"></i>
                    <h4 class="font-bold">Professional</h4>
                </div>
                <div class="p-8 bg-navy text-white shadow-lg rounded-xl text-center">
                    <i data-lucide="trending-up" class="mx-auto mb-4 gold-accent w-10 h-10"></i>
                    <h4 class="font-bold">Expertise</h4>
                </div>
                <div class="p-8 bg-white shadow-lg rounded-xl text-center">
                    <i data-lucide="users" class="mx-auto mb-4 gold-accent w-10 h-10"></i>
                    <h4 class="font-bold">Client-First</h4>
                </div>
            </div>
        </div>
    </section>

    <section id="properties" class="py-24">
        <div class="max-w-7xl mx-auto px-6">
            <div class="flex justify-between items-end mb-12">
                <h2 class="text-4xl font-bold text-navy">Featured Properties</h2>
                <a href="#" class="gold-accent font-semibold border-b-2 border-gold pb-1">View All Listings</a>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white rounded-xl overflow-hidden shadow-md card-hover">
                    <img src="https://images.unsplash.com/photo-1497366216548-37526070297c?auto=format&fit=crop&q=80&w=600" class="w-full h-64 object-cover" alt="Office Space">
                    <div class="p-6">
                        <span class="text-sm bg-blue-100 text-blue-800 px-3 py-1 rounded-full font-medium">For Lease</span>
                        <h3 class="text-xl font-bold mt-4">Modern Corporate Plaza</h3>
                        <p class="text-gray-500 mb-4 flex items-center"><i data-lucide="map-pin" class="w-4 h-4 mr-1"></i> Central Business District, Abuja</p>
                        <div class="flex justify-between items-center mt-6">
                            <span class="text-2xl font-bold text-navy">₦15,000,000/yr</span>
                            <button class="bg-navy text-white px-4 py-2 rounded text-sm">View Details</button>
                        </div>
                    </div>
                </div>
                <div class="bg-white rounded-xl overflow-hidden shadow-md card-hover">
                    <img src="https://images.unsplash.com/photo-1541888946425-d81bb19480c5?auto=format&fit=crop&q=80&w=600" class="w-full h-64 object-cover" alt="Warehouse">
                    <div class="p-6">
                        <span class="text-sm bg-green-100 text-green-800 px-3 py-1 rounded-full font-medium">For Sale</span>
                        <h3 class="text-xl font-bold mt-4">Industrial Logistics Hub</h3>
                        <p class="text-gray-500 mb-4 flex items-center"><i data-lucide="map-pin" class="w-4 h-4 mr-1"></i> Idu Industrial Area</p>
                        <div class="flex justify-between items-center mt-6">
                            <span class="text-2xl font-bold text-navy">₦250,000,000</span>
                            <button class="bg-navy text-white px-4 py-2 rounded text-sm">View Details</button>
                        </div>
                    </div>
                </div>
                <div class="bg-white rounded-xl overflow-hidden shadow-md card-hover">
                    <img src="https://images.unsplash.com/photo-1556761175-b413da4baf72?auto=format&fit=crop&q=80&w=600" class="w-full h-64 object-cover" alt="Retail Store">
                    <div class="p-6">
                        <span class="text-sm bg-blue-100 text-blue-800 px-3 py-1 rounded-full font-medium">For Lease</span>
                        <h3 class="text-xl font-bold mt-4">Premium Retail Space</h3>
                        <p class="text-gray-500 mb-4 flex items-center"><i data-lucide="map-pin" class="w-4 h-4 mr-1"></i> Lugbe, Abuja</p>
                        <div class="flex justify-between items-center mt-6">
                            <span class="text-2xl font-bold text-navy">₦5,500,000/yr</span>
                            <button class="bg-navy text-white px-4 py-2 rounded text-sm">View Details</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="py-24 bg-navy text-white">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <h2 class="text-4xl font-bold mb-16">Our Specialized Services</h2>
            <div class="grid md:grid-cols-4 gap-8">
                <div class="p-8 border border-white/10 rounded-xl hover:bg-white/5 transition">
                    <i data-lucide="key" class="mx-auto mb-6 gold-accent w-12 h-12"></i>
                    <h3 class="text-xl font-bold mb-4">Property Sales</h3>
                    <p class="text-gray-400">Seamless acquisition of prime commercial land and buildings.</p>
                </div>
                <div class="p-8 border border-white/10 rounded-xl hover:bg-white/5 transition">
                    <i data-lucide="building-2" class="mx-auto mb-6 gold-accent w-12 h-12"></i>
                    <h3 class="text-xl font-bold mb-4">Property Leasing</h3>
                    <p class="text-gray-400">Connecting businesses with flexible and modern workspaces.</p>
                </div>
                <div class="p-8 border border-white/10 rounded-xl hover:bg-white/5 transition">
                    <i data-lucide="file-text" class="mx-auto mb-6 gold-accent w-12 h-12"></i>
                    <h3 class="text-xl font-bold mb-4">RE Consultation</h3>
                    <p class="text-gray-400">Expert market analysis and strategic portfolio planning.</p>
                </div>
                <div class="p-8 border border-white/10 rounded-xl hover:bg-white/5 transition">
                    <i data-lucide="pie-chart" class="mx-auto mb-6 gold-accent w-12 h-12"></i>
                    <h3 class="text-xl font-bold mb-4">Investment Advisory</h3>
                    <p class="text-gray-400">Maximized ROI through data-driven investment strategies.</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="py-24 bg-white border-t">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-20">
            <div>
                <h2 class="text-4xl font-bold text-navy mb-8">Get In Touch Today</h2>
                <div class="space-y-6">
                    <div class="flex items-start">
                        <i data-lucide="map-pin" class="gold-accent mr-4 mt-1"></i>
                        <p class="text-gray-600">Federal Housing, Total Road, Lugbe 980001,<br>Federal Capital Territory</p>
                    </div>
                    <div class="flex items-center">
                        <i data-lucide="phone" class="gold-accent mr-4"></i>
                        <p class="text-gray-600">09136177347</p>
                    </div>
                    <div class="flex items-center">
                        <i data-lucide="mail" class="gold-accent mr-4"></i>
                        <p class="text-gray-600">info@realhomesproperty.com</p>
                    </div>
                </div>
                <div class="mt-12 p-8 bg-gray-50 rounded-2xl">
                    <h4 class="font-bold mb-2">Schedule a Consultation</h4>
                    <p class="text-sm text-gray-500 mb-4">Let our experts guide your next big investment.</p>
                    <button class="w-full bg-navy text-white py-3 rounded-lg font-bold">Book an Appointment</button>
                </div>
            </div>

            <form class="space-y-6 bg-white p-8 shadow-2xl rounded-2xl border border-gray-100">
                <div class="grid md:grid-cols-2 gap-6">
                    <div>
                        <label class="block text-sm font-semibold mb-2">Name</label>
                        <input type="text" class="w-full px-4 py-3 bg-gray-50 border border-gray-200 rounded-lg focus:outline-none focus:ring-2 focus:ring-yellow-500">
                    </div>
                    <div>
                        <label class="block text-sm font-semibold mb-2">Email</label>
                        <input type="email" class="w-full px-4 py-3 bg-gray-50 border border-gray-200 rounded-lg focus:outline-none focus:ring-2 focus:ring-yellow-500">
                    </div>
                </div>
                <div>
                    <label class="block text-sm font-semibold mb-2">Message</label>
                    <textarea rows="4" class="w-full px-4 py-3 bg-gray-50 border border-gray-200 rounded-lg focus:outline-none focus:ring-2 focus:ring-yellow-500"></textarea>
                </div>
                <button type="submit" class="w-full bg-gold hover:bg-yellow-600 text-white py-4 rounded-lg font-bold transition">Send Message</button>
            </form>
        </div>
        <div class="mt-20 text-center text-gray-400 text-sm">
            &copy; 2026 RealHomes and Property. All rights reserved.
        </div>
    </footer>

    <script>
        lucide.createIcons();
    </script>
</body>
</html>
