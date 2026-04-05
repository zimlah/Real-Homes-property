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
        .hero-gradient { background: linear-gradient(rgba(10, 25, 47, 0.85), rgba(10, 25, 47, 0.65)); }
        .card-hover { transition: all 0.3s ease; }
        .card-hover:hover { transform: translateY(-10px); }
    </style>
</head>
<body class="bg-white text-gray-800">

    <nav class="fixed w-full z-50 bg-white/95 backdrop-blur-md shadow-sm">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold text-navy uppercase tracking-tighter">
                REAL<span class="gold-accent">HOMES</span>
            </div>
            <div class="hidden md:flex space-x-8 font-medium">
                <a href="#home" class="hover:text-yellow-600 transition">Home</a>
                <a href="#about" class="hover:text-yellow-600 transition">About</a>
                <a href="#properties" class="hover:text-yellow-600 transition">Properties</a>
                <a href="#services" class="hover:text-yellow-600 transition">Services</a>
                <a href="#contact" class="bg-navy text-white px-5 py-2 rounded shadow-lg hover:bg-gray-800 transition">Contact Us</a>
            </div>
        </div>
    </nav>

    <section id="home" class="relative h-screen flex items-center justify-center text-white">
        <div class="absolute inset-0 z-0">
            <img src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070" 
                 alt="Commercial Building" 
                 class="w-full h-full object-cover">
            <div class="absolute inset-0 hero-gradient"></div>
        </div>
        <div class="relative z-10 text-center px-6 max-w-4xl">
            <h1 class="text-5xl md:text-7xl font-bold mb-6">Your Trusted Partner in <span class="gold-accent">Commercial Real Estate</span></h1>
            <div class="w-24 h-1 bg-gold mx-auto mb-8"></div>
            <p class="text-xl mb-10 text-gray-200">Helping you find the perfect property for your business and investment needs.</p>
            <div class="flex flex-col md:flex-row justify-center gap-4">
                <a href="#properties" class="bg-gold hover:bg-yellow-600 text-white px-10 py-4 rounded-lg font-bold shadow-xl transition">Explore Properties</a>
                <a href="#contact" class="bg-white/10 backdrop-blur-md border border-white/30 hover:bg-white hover:text-navy px-10 py-4 rounded-lg font-bold transition">Contact Us</a>
            </div>
        </div>
    </section>

    <section id="properties" class="py-24 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-3xl font-bold text-navy mb-12 border-l-4 border-gold pl-4">Featured Listings</h2>
            <div class="grid md:grid-cols-3 gap-8">
                
                <div class="bg-white rounded-xl overflow-hidden shadow-lg card-hover">
                    <img src="https://images.unsplash.com/photo-1497366216548-37526070297c?q=80&w=600" alt="Listing 1" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold">Premium Office Plaza</h3>
                        <p class="text-gray-500 text-sm mb-4">Central Area, Abuja</p>
                        <div class="flex justify-between items-center pt-4 border-t">
                            <span class="text-xl font-bold text-navy">₦12.5M/yr</span>
                            <button class="text-gold font-semibold hover:underline">View Details</button>
                        </div>
                    </div>
                </div>

                <div class="bg-white rounded-xl overflow-hidden shadow-lg card-hover">
                    <img src="https://images.unsplash.com/photo-1582441801535-916b1f385ecd?q=80&w=600" alt="Listing 2" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold">Luxury Retail Space</h3>
                        <p class="text-gray-500 text-sm mb-4">Wuse II, Abuja</p>
                        <div class="flex justify-between items-center pt-4 border-t">
                            <span class="text-xl font-bold text-navy">₦8.0M/yr</span>
                            <button class="text-gold font-semibold hover:underline">View Details</button>
                        </div>
                    </div>
                </div>

                <div class="bg-white rounded-xl overflow-hidden shadow-lg card-hover">
                    <img src="https://images.unsplash.com/photo-1541888946425-d81bb19480c5?q=80&w=600" alt="Listing 3" class="w-full h-56 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold">Warehouse Complex</h3>
                        <p class="text-gray-500 text-sm mb-4">Idu Industrial Area</p>
                        <div class="flex justify-between items-center pt-4 border-t">
                            <span class="text-xl font-bold text-navy">₦25.0M/yr</span>
                            <button class="text-gold font-semibold hover:underline">View Details</button>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <footer id="contact" class="bg-navy text-white py-16">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold mb-4">Ready to find your next space?</h2>
            <p class="text-gray-400 mb-8">Visit us at Federal Housing, Total Road, Lugbe, Abuja</p>
            <a href="tel:09136177347" class="text-2xl font-bold gold-accent hover:text-white transition">09136177347</a>
            <div class="mt-12 text-sm text-gray-500">
                &copy; 2026 RealHomes and Property. Professional Commercial Agency.
            </div>
        </div>
    </footer>

    <script>
        lucide.createIcons();
    </script>
</body>
</html>
