# wt_project

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Joshya Beauty Parlor</title>

  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />

  <!-- Tailwind -->
  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    body {
      scroll-behavior: smooth;
    }
  </style>
</head>

<body class="bg-gray-100">

  <!-- Header -->
  <nav class="bg-gradient-to-r from-pink-500 via-purple-500 to-pink-600 text-white shadow-lg p-4 sticky top-0 z-50">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold">Joshya Beauty Parlor</h1>
      <ul class="flex gap-6 text-lg">
        <li><a href="#home" class="hover:underline">Home</a></li>
        <li><a href="#services" class="hover:underline">Services</a></li>
        <li><a href="#handfeet" class="hover:underline">Hand & Feet</a></li>
        <li><a href="#pricing" class="hover:underline">Pricing</a></li>
        <li><a href="#schedule" class="hover:underline">Schedule</a></li>
        <li><a href="#contact" class="hover:underline">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero -->
  <section id="home" class="text-center py-20 bg-cover bg-center"
    style="background-image: url('https://images.pexels.com/photos/415829/pexels-photo-415829.jpeg');">
    <div class="bg-black bg-opacity-50 text-white p-10 inline-block rounded-xl">
      <h2 class="text-4xl font-bold mb-4">Welcome to Joshya Beauty Parlor</h2>
      <p class="text-lg max-w-xl mx-auto">
        Enhance your beauty with our professional salon services. Experience premium care and stunning transformations.
      </p>
      <a href="#services"
        class="mt-5 inline-block bg-pink-500 px-6 py-3 rounded-lg text-white font-semibold hover:bg-pink-600">Explore
        Services</a>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="py-16 container mx-auto">
    <h2 class="text-3xl font-bold text-center mb-10">Our Services</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">

      <div class="bg-white shadow-lg p-6 rounded-xl">
        <img src="facill.jpg" class="rounded mb-3 w-full h-48 object-cover" />
        <h3 class="font-bold text-xl mb-2">Facials</h3>
        <p>Glow, clean-up, fruit facial, gold facial & more.</p>
      </div>

      <div class="bg-white shadow-lg p-6 rounded-xl">
        <img src="Personal-Grooming-Hair.jpg" class="rounded mb-3 w-full h-48 object-cover" />
        <h3 class="font-bold text-xl mb-2">Hair Styling</h3>
        <p>Cutting, smoothing, keratin, hair spa & bridal hair.</p>
      </div>

      <div class="bg-white shadow-lg p-6 rounded-xl">
        <img src="https://images.pexels.com/photos/3762662/pexels-photo-3762662.jpeg"
          class="rounded mb-3 w-full h-48 object-cover" />
        <h3 class="font-bold text-xl mb-2">Makeup</h3>
        <p>Bridal makeup, party makeup, HD makeup.</p>
      </div>

      <div class="bg-white shadow-lg p-6 rounded-xl">
        <img src="nails.jpg" class="rounded mb-3 w-full h-48 object-cover" />
        <h3 class="font-bold text-xl mb-2">Nail Art</h3>
        <p>Gel nails, acrylic nails, French tips.</p>
      </div>

      <div class="bg-white shadow-lg p-6 rounded-xl">
        <img src="wax.jpg" class="rounded mb-3 w-full h-48 object-cover" />
        <h3 class="font-bold text-xl mb-2">Waxing</h3>
        <p>Full body waxing, arms, legs, eyebrow threading.</p>
      </div>

      <div class="bg-white shadow-lg p-6 rounded-xl">
        <img src="https://images.pexels.com/photos/3865792/pexels-photo-3865792.jpeg"
          class="rounded mb-3 w-full h-48 object-cover" />
        <h3 class="font-bold text-xl mb-2">Spa</h3>
        <p>Relaxing head massage, body spa, skin therapy.</p>
      </div>

    </div>
  </section>

  <!-- Pricing -->
  <section id="pricing" class="py-16 bg-gradient-to-r from-pink-200 via-purple-200 to-pink-200">
    <h2 class="text-3xl font-bold text-center mb-10">Service Pricing</h2>

    <div class="container mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 px-6">

      <div class="bg-white rounded-2xl shadow-xl p-6 border-2 border-pink-400 hover:shadow-2xl hover:border-purple-500 transition">
        <h3 class="text-xl font-bold mb-4 text-pink-600">Facial Treatments</h3>
        <ul class="space-y-2">
          <li class="flex justify-between"><span>Basic Facial</span><span class="font-semibold">₹499</span></li>
          <li class="flex justify-between"><span>Gold Facial</span><span class="font-semibold">₹999</span></li>
          <li class="flex justify-between"><span>Diamond Facial</span><span class="font-semibold">₹1499</span></li>
        </ul>
      </div>

      <div class="bg-white rounded-2xl shadow-xl p-6 border-2 border-purple-400 hover:shadow-2xl hover:border-pink-500 transition">
        <h3 class="text-xl font-bold mb-4 text-purple-600">Hair Styling</h3>
        <ul class="space-y-2">
          <li class="flex justify-between"><span>Hair Cut</span><span class="font-semibold">₹199</span></li>
          <li class="flex justify-between"><span>Straightening</span><span class="font-semibold">₹999</span></li>
          <li class="flex justify-between"><span>Keratin</span><span class="font-semibold">₹1999</span></li>
        </ul>
      </div>

      <div class="bg-white rounded-2xl shadow-xl p-6 border-2 border-pink-400 hover:shadow-2xl hover:border-purple-500 transition">
        <h3 class="text-xl font-bold mb-4 text-pink-600">Nail & Waxing</h3>
        <ul class="space-y-2">
          <li class="flex justify-between"><span>Nail Polish</span><span class="font-semibold">₹149</span></li>
          <li class="flex justify-between"><span>Nail Art</span><span class="font-semibold">₹399</span></li>
          <li class="flex justify-between"><span>Waxing</span><span class="font-semibold">₹299</span></li>
        </ul>
      </div>

    </div>
  </section>


   <section id="handfeet" class="py-16 bg-gradient-to-r from-purple-100 via-pink-100 to-purple-100">
   
    <h2 class="text-3xl font-bold text-center mb-10">Our Premium Services </h2>

    <div class="container mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 px-6">

      <div
        class="bg-white p-6 rounded-2xl shadow-lg border border-pink-300 hover:shadow-2xl transform hover:scale-105 transition duration-300">
        <h3 class="text-xl font-bold mb-2 text-pink-600">Classic Manicure</h3>
        <p class="text-gray-700">Gentle shaping, buffing & natural shine.</p>
      </div>

      <div
        class="bg-white p-6 rounded-2xl shadow-lg border border-purple-300 hover:shadow-2xl transform hover:scale-105 transition duration-300">
        <h3 class="text-xl font-bold mb-2 text-purple-600">Classic Pedicure</h3>
        <p class="text-gray-700">Deep cleaning, scrubbing & softening treatment.</p>
      </div>

      <div
        class="bg-white p-6 rounded-2xl shadow-lg border border-pink-300 hover:shadow-2xl transform hover:scale-105 transition duration-300">
        <h3 class="text-xl font-bold mb-2 text-pink-600">Spa Manicure</h3>
        <p class="text-gray-700">Luxurious hand spa with hydrating mask.</p>
      </div>

      <div
        class="bg-white p-6 rounded-2xl shadow-lg border border-purple-300 hover:shadow-2xl transform hover:scale-105 transition duration-300">
        <h3 class="text-xl font-bold mb-2 text-purple-600">Spa Pedicure</h3>
        <p class="text-gray-700">Exfoliation, massage & foot relaxation.</p>
      </div>

      <div
        class="bg-white p-6 rounded-2xl shadow-lg border border-pink-300 hover:shadow-2xl transform hover:scale-105 transition duration-300">
        <h3 class="text-xl font-bold mb-2 text-pink-600">Gel Polish</h3>
        <p class="text-gray-700">Long-lasting glossy gel finish.</p>
      </div>

      <div
        class="bg-white p-6 rounded-2xl shadow-lg border border-purple-300 hover:shadow-2xl transform hover:scale-105 transition duration-300">
        <h3 class="text-xl font-bold mb-2 text-purple-600">Foot Scrub Therapy</h3>
        <p class="text-gray-700">Smoothens cracked heels & rough skin.</p>
      </div>

      <div
        class="bg-white p-6 rounded-2xl shadow-lg border border-pink-300 hover:shadow-2xl transform hover:scale-105 transition duration-300">
        <h3 class="text-xl font-bold mb-2 text-pink-600">Nail Strengthening Treatment</h3>
        <p class="text-gray-700">Repairs brittle & weak nails.</p>
      </div>

      <div
        class="bg-white p-6 rounded-2xl shadow-lg border border-purple-300 hover:shadow-2xl transform hover:scale-105 transition duration-300">
        <h3 class="text-xl font-bold mb-2 text-purple-600">Paraffin Manicure</h3>
        <p class="text-gray-700">Warm wax treatment for soft glowing hands.</p>
      </div>

      <div
        class="bg-white p-6 rounded-2xl shadow-lg border border-pink-300 hover:shadow-2xl transform hover:scale-105 transition duration-300">
        <h3 class="text-xl font-bold mb-2 text-pink-600">Paraffin Pedicure</h3>
        <p class="text-gray-700">Deep hydration for cracked heels.</p>
      </div>

    </div>
  </section>


  <!-- Schedule Maker -->
  <section id="schedule" class="py-16 container mx-auto">
    <h2 class="text-3xl font-bold text-center mb-6">Schedule Maker</h2>
    <div class="bg-white p-6 shadow-lg rounded-xl max-w-xl mx-auto">
      <label class="block font-semibold mb-1">Your Name:</label>
      <input id="name" class="w-full border p-2 rounded mb-3" placeholder="Enter your name">

      <label class="block font-semibold mb-1">Select Service:</label>
      <select id="service" class="w-full border p-2 rounded mb-3">
        <option>Facial</option>
        <option>Hair Cut</option>
        <option>Bridal Makeup</option>
        <option>Nail Art</option>
        <option>Manicure</option>
        <option>Pedicure</option>
      </select>

      <label class="block font-semibold mb-1">Choose Date:</label>
      <input type="date" id="date" class="w-full border p-2 rounded mb-3">

      <button onclick="generateSchedule()" class="bg-pink-500 hover:bg-pink-600 text-white w-full py-3 rounded-lg font-bold">
        Generate Schedule
      </button>

      <p id="output" class="mt-4 font-semibold text-center text-green-600"></p>
    </div>
  </section>

  <script>
    function generateSchedule() {
      let n = document.getElementById('name').value;
      let s = document.getElementById('service').value;
      let d = document.getElementById('date').value;

      if (!n || !d) {
        document.getElementById('output').innerText = "Please fill all fields.";
        return;
      }

      document.getElementById('output').innerText =
        `Hi ${n}, your appointment for ${s} is booked on ${d}.`;
    }
  </script>

  <!-- Contact -->
  <section id="contact" class="py-16 bg-gray-800 text-white">
    <h2 class="text-3xl font-bold text-center mb-10">Contact Us</h2>
    <div class="container mx-auto grid grid-cols-1 md:grid-cols-2 gap-10">
      <div>
        <h3 class="text-xl font-bold mb-3">Joshya Beauty Parlor</h3>
        <p>Near Main Road, City Center, India</p>
        <p>Phone: +91 98765 43210</p>
        <p>Email: joshya@beautyparlor.com</p>

        <!-- ⭐ Your 20-line plain passage (NO HEADING, NO BORDER) ⭐ -->
        <p class="mt-6 text-gray-300 leading-7">
          We provide a wide range of trusted beauty and grooming services designed to offer comfort, care, 
          and confidence to every customer. From threading, waxing, facials, and cleanup services to premium 
          hair treatments, spa therapies, and nail care, every service is performed with dedication and hygiene. 
          Our team believes in simple, honest beauty solutions that make you feel refreshed and confident. 
          Whether it is a quick grooming session or a full makeover, we ensure quality and care in every step. 
          We focus on clean tools, safe products, and a friendly environment that makes every visit peaceful 
          and relaxing. Over the years, we have proudly served many clients with love, consistency, and passion. 
          Thank you for trusting our services and being a part of our journey — your support motivates us to 
          do better every day.
        </p>

      </div>

      <form class="bg-white text-black p-6 rounded-xl shadow space-y-3">
        <input class="border w-full p-2 rounded" placeholder="Your Name">
        <input class="border w-full p-2 rounded" placeholder="Your Email">
        <textarea class="border w-full p-2 rounded" placeholder="Your Message"></textarea>
        <button class="bg-pink-500 w-full py-2 rounded text-white font-bold">Send Message</button>
      </form>
    </div>
  </section>

  <footer class="text-center p-4 bg-black text-white">© 2025 Joshya Beauty Parlor</footer>

</body>
</html>
