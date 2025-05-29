<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hemp Wellness Hub</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Basic meta for SEO -->
  <meta name="description" content="Explore hemp wellness products and learn about their benefits. For individuals 21+ only.">
</head>
<body class="bg-gray-100 font-sans">
  <!-- Header -->
  <header class="bg-green-600 text-white py-4">
    <div class="container mx-auto px-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold">Hemp Wellness Hub</h1>
      <nav>
        <a href="#home" class="px-4">Home</a>
        <a href="#about" class="px-4">About</a>
        <a href="#contact" class="px-4">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="home" class="bg-green-100 py-16 text-center">
    <div class="container mx-auto px-4">
      <h2 class="text-4xl font-bold mb-4">Discover Hemp Wellness</h2>
      <p class="text-lg mb-6">Learn about the benefits of hemp-derived products for a balanced lifestyle. For individuals 21+ only.</p>
      <a href="#contact" class="bg-green-600 text-white py-2 px-6 rounded hover:bg-green-700">Get Started</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-16">
    <div class="container mx-auto px-4">
      <h3 class="text-3xl font-bold mb-4 text-center">About Us</h3>
      <p class="text-lg text-gray-700">We provide educational resources and high-quality hemp-derived products to support wellness. Our offerings comply with all state regulations and are intended for adults 21 and older.</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="bg-gray-200 py-16">
    <div class="container mx-auto px-4 text-center">
      <h3 class="text-3xl font-bold mb-4">Contact Us</h3>
      <p class="text-lg mb-6">Interested in learning more? Reach out to us!</p>
      <div class="max-w-md mx-auto">
        <input type="email" id="email" placeholder="Enter your email" class="w-full p-2 mb-4 border rounded">
        <button onclick="submitEmail()" class="bg-green-600 text-white py-2 px-6 rounded hover:bg-green-700">Submit</button>
      </div>
      <p class="text-sm text-gray-600 mt-4">For individuals 21+ only. Products contain ≤0.3% THC as per state regulations.</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-green-600 text-white py-4">
    <div class="container mx-auto px-4 text-center">
      <p>&copy; 2025 Hemp Wellness Hub. All rights reserved.</p>
      <p class="text-sm">For use by individuals 21+ only. Always consult a healthcare professional before using hemp products.</p>
    </div>
  </footer>

  <!-- Basic JavaScript for interactivity -->
  <script>
    function submitEmail() {
      const email = document.getElementById('email').value;
      if (email) {
        alert('Thank you for signing up! We’ll be in touch.');
        document.getElementById('email').value = '';
      } else {
        alert('Please enter a valid email address.');
      }
    }
  </script>
</body>
</html>
