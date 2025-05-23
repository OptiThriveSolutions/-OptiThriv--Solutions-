# Continuous-Cannon
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Continuous Cannon Consulting delivers expert solutions to help businesses, professionals, and homes create substantial savings with no upfront cost. Request a free consultation today!">
  <meta name="keywords" content="savings, consulting, no upfront cost, efficiency, business, home, Continuous Cannon Consulting">
  <meta name="author" content="Braeden Cannon">
  <title>Continuous Cannon Consulting - No Costs, Just Savings</title>
  <link href="https://fonts.googleapis.com/css2?family=Lora:wght@700&family=Open+Sans:wght@400;600;700&display=swap" rel="stylesheet">
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body {
      font-family: 'Open Sans', sans-serif;
      background: linear-gradient(135deg, #F3F4F6 0%, #E5E7EB 100%);
      color: #1F2937;
      margin: 0;
      overflow-x: hidden;
    }
    h1, h2, h3 {
      font-family: 'Lora', serif;
      color: #1E3A8A;
    }
    /* Preloader (placeholder without logo) */
    #preloader {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: #1E3A8A;
      display: flex;
      justify-content: center;
      align-items: center;
      z-index: 9999;
    }
    #preloader::after {
      content: '';
      width: 40px;
      height: 40px;
      border: 4px solid #10B981;
      border-top: 4px solid transparent;
      border-radius: 50%;
      animation: spin 2s linear infinite;
    }
    @keyframes spin {
      100% { transform: rotate(360deg); }
    }
    /* Hero Section with Parallax */
    .hero {
      background: linear-gradient(rgba(30, 58, 138, 0.85), rgba(30, 58, 138, 0.85)), url('data:image/svg+xml,%3Csvg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"%3E%3Cg fill="%231E3A8A" fill-opacity="0.1"%3E%3Ccircle cx="50" cy="50" r="35"/%3E%3C/g%3E%3C/svg%3E');
      background-attachment: fixed;
      background-size: cover;
      background-position: center;
      color: white;
      padding: 8rem 0;
      position: relative;
    }
    .hero::after {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(45deg, rgba(212, 175, 55, 0.1), transparent);
    }
    .hero h2 {
      background: linear-gradient(45deg, #D4AF37, #F4D03F);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
      font-size: 4.5rem;
      font-weight: 700;
    }
    .hero p {
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.2);
    }
    /* Glassmorphism for Cards */
    .card {
      background: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(10px);
      border: 1px solid rgba(255, 255, 255, 0.2);
      border-radius: 1rem;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 15px 25px rgba(0, 0, 0, 0.2);
    }
    /* Button with Pulse and Glow */
    .btn {
      background: linear-gradient(45deg, #10B981, #34D399);
      color: white;
      padding: 0.75rem 1.5rem;
      border-radius: 0.5rem;
      transition: all 0.3s ease;
      position: relative;
      animation: pulse 2s infinite;
    }
    .btn:hover {
      background: linear-gradient(45deg, #D4AF37, #F4D03F);
      transform: translateY(-3px);
      box-shadow: 0 5px 15px rgba(212, 175, 55, 0.5);
    }
    @keyframes pulse {
      0% { box-shadow: 0 0 0 0 rgba(16, 185, 129, 0.7); }
      70% { box-shadow: 0 0 0 15px rgba(16, 185, 129, 0); }
      100% { box-shadow: 0 0 0 0 rgba(16, 185, 129, 0); }
    }
    /* Section Styling */
    .section {
      padding: 5rem 1.25rem;
      position: relative;
    }
    /* Parallax Background for Sections */
    .parallax-bg {
      background-attachment: fixed;
      background-size: cover;
      background-position: center;
    }
    /* Mobile Responsiveness */
    @media (max-width: 768px) {
      .nav-links {
        display: none;
      }
      .hero h2 {
        font-size: 2.5rem;
      }
      .section {
        padding: 3rem 1rem;
      }
    }
  </style>
</head>
<body>
  <!-- Preloader -->
  <div id="preloader"></div>

  <!-- Navbar -->
  <nav class="bg-blue-900 text-white shadow-md sticky top-0 z-50">
    <div class="container mx-auto px-6 py-3 flex justify-between items-center">
      <div class="flex items-center">
        <span class="text-2xl font-bold text-gold-600">Continuous Cannon Consulting</span>
      </div>
      <ul class="nav-links flex space-x-6 text-lg">
        <li><a href="#home" class="hover:text-green-400 transition-colors">Home</a></li>
        <li><a href="#services" class="hover:text-green-400 transition-colors">Services</a></li>
        <li><a href="#results" class="hover:text-green-400 transition-colors">Results</a></li>
        <li><a href="#savings" class="hover:text-green-400 transition-colors">Calculator</a></li>
        <li><a href="#contact" class="hover:text-green-400 transition-colors">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="hero text-center" data-aos="zoom-in">
    <div class="container mx-auto px-6 relative z-10">
      <h2 class="text-4xl md:text-5xl font-bold mb-6 leading-tight">No Costs, Just Savings</h2>
      <p class="text-xl mb-8 max-w-3xl mx-auto leading-relaxed">Struggling with inefficiencies? Our team helps businesses, professionals, and homes unlock substantial savings with no upfront cost. After a complimentary consultation, we craft a tailored plan, credited only from the savings we generate together.</p>
      <a href="#contact" class="btn px-8 py-4 rounded-lg font-semibold">Request a Free Consultation: (401) 451-1035</a>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="section bg-white">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-8 text-gray-900" data-aos="fade-up">Our Expert Services</h2>
      <p class="text-lg mb-10 max-w-2xl mx-auto text-gray-600" data-aos="fade-up" data-aos-delay="100">We deliver customized solutions for any business, professional service, or home, leveraging proven strategies to drive efficiency and savings. Our compensation is tied solely to the results we achieve together.</p>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="card p-6 rounded-lg" data-aos="flip-left" data-aos-delay="200">
          <h3 class="text-xl font-semibold mb-4 text-blue-900">Process Optimization</h3>
          <p class="text-gray-700">Streamline workflows, from business operations to home projects, to save time and money.</p>
        </div>
        <div class="card p-6 rounded-lg" data-aos="flip-left" data-aos-delay="300">
          <h3 class="text-xl font-semibold mb-4 text-blue-900">Expense Reduction</h3>
          <p class="text-gray-700">Cut costs with smarter tools or strategies, customized for your business or home.</p>
        </div>
        <div class="card p-6 rounded-lg" data-aos="flip-left" data-aos-delay="400">
          <h3 class="text-xl font-semibold mb-4 text-blue-900">Training & Tools</h3>
          <p class="text-gray-700">Equip your team or household with skills and systems to sustain savings.</p>
        </div>
      </div>
      <a href="#contact" class="btn px-6 py-3 mt-8 rounded-lg" data-aos="fade-up" data-aos-delay="500">Request a Free Quote</a>
    </div>
  </section>

  <!-- Results Section -->
  <section id="results" class="section bg-gray-100 parallax-bg" style="background-image: url('data:image/svg+xml,%3Csvg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"%3E%3Cg fill="%231E3A8A" fill-opacity="0.05"%3E%3Ccircle cx="50" cy="50" r="35"/%3E%3C/g%3E%3C/svg%3E');">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-8 text-gray-900" data-aos="fade-down">Savings We Can Create</h2>
      <p class="text-lg mb-10 max-w-2xl mx-auto text-gray-600" data-aos="fade-down" data-aos-delay="100">These examples show how we can generate savings for any business or home, with clear data you can trust, and I’m credited only from the results we achieve.</p>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="card p-6 rounded-lg" data-aos="slide-up" data-aos-delay="200">
          <h3 class="text-xl font-semibold mb-4 text-blue-900">Streamlined Business Operations</h3>
          <p class="text-gray-700">A small business could save thousands monthly by optimizing workflows, tracked with time logs or expense reports. We create lasting savings; my compensation comes from the results.</p>
        </div>
        <div class="card p-6 rounded-lg" data-aos="slide-up" data-aos-delay="300">
          <h3 class="text-xl font-semibold mb-4 text-blue-900">Reduced Professional Expenses</h3>
          <p class="text-gray-700">A service provider could cut costs with smarter tools, measured with financial data. We generate ongoing savings; my compensation is from the results.</p>
        </div>
        <div class="card p-6 rounded-lg" data-aos="slide-up" data-aos-delay="400">
          <h3 class="text-xl font-semibold mb-4 text-blue-900">Home Efficiency Gains</h3>
          <p class="text-gray-700">A homeowner could save on utilities or projects with tailored strategies, tracked with bills or time logs. We create savings; my compensation is from the results.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Savings Calculator Section -->
  <section id="savings" class="section bg-white">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-8 text-gray-900" data-aos="fade-up">Estimate Savings We Can Create</h2>
      <p class="text-lg mb-10 max-w-2xl mx-auto text-gray-600" data-aos="fade-up" data-aos-delay="100">See the savings we could generate for your business, service, or home.</p>
      <div class="max-w-lg mx-auto card p-8 rounded-lg" data-aos="zoom-in" data-aos-delay="200">
        <label class="block mb-2 text-left text-gray-700">Units Affected (e.g., employees, tasks, or projects)</label>
        <input id="units" type="number" placeholder="e.g., 10" class="w-full p-3 mb-4 rounded border-gray-300 focus:border-green-600 focus:ring-2 focus:ring-green-200">
        <label class="block mb-2 text-left text-gray-700">Hours Saved per Unit/Day</label>
        <input id="hours" type="number" placeholder="e.g., 1" class="w-full p-3 mb-4 rounded border-gray-300 focus:border-green-600 focus:ring-2 focus:ring-green-200">
        <label class="block mb-2 text-left text-gray-700">Value per Hour ($)</label>
        <input id="rate" type="number" placeholder="e.g., 30" class="w-full p-3 mb-4 rounded border-gray-300 focus:border-green-600 focus:ring-2 focus:ring-green-200">
        <button onclick="calculateSavings()" class="btn px-6 py-3 rounded-lg w-full">Calculate Savings</button>
        <p id="result" class="mt-6 text-xl text-gray-900 font-semibold"></p>
      </div>
    </div>
  </section>

  <!-- Testimonials Section -->
  <section id="testimonials" class="section bg-gray-100">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-8 text-gray-900" data-aos="fade-down">What Clients Say</h2>
      <p class="text-lg mb-10 max-w-2xl mx-auto text-gray-600" data-aos="fade-down" data-aos-delay="100">I’m new to consulting but passionate about creating savings for you. Early clients get personalized service and clear results. Share your feedback after we work together!</p>
      <div class="card p-6 rounded-lg max-w-2xl mx-auto" data-aos="fade-up" data-aos-delay="200">
        <p class="italic text-gray-700">“Excited to work with Braeden to create savings for our operations!” – Future Client</p>
      </div>
    </div>
  </section>

  <!-- Tips Section -->
  <section id="tips" class="section bg-white">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-8 text-gray-900" data-aos="fade-up">Tips to Save Money</h2>
      <p class="text-lg mb-10 max-w-2xl mx-auto text-gray-600" data-aos="fade-up" data-aos-delay="100">Learn how to create efficiencies for your business or home.</p>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div class="card p-6 rounded-lg" data-aos="slide-right" data-aos-delay="200">
          <h3 class="text-xl font-semibold mb-4 text-blue-900">5 Ways to Streamline Operations</h3>
          <p class="text-gray-700">Proven methods can generate savings for any business or home. <a href="#contact" class="text-blue-600 hover:text-blue-800">Get a free quote</a> to start.</p>
        </div>
        <div class="card p-6 rounded-lg" data-aos="slide-left" data-aos-delay="300">
          <h3 class="text-xl font-semibold mb-4 text-blue-900">Cutting Costs on a Budget</h3>
          <p class="text-gray-700">Smart strategies can create savings for businesses or homes. <a href="#contact" class="text-blue-600 hover:text-blue-800">Request a free call</a>.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="section bg-gray-100 parallax-bg" style="background-image: url('data:image/svg+xml,%3Csvg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"%3E%3Cg fill="%231E3A8A" fill-opacity="0.05"%3E%3Ccircle cx="50" cy="50" r="35"/%3E%3C/g%3E%3C/svg%3E');">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-8 text-gray-900" data-aos="fade-down">About Braeden Cannon</h2>
      <p class="text-lg mb-10 max-w-2xl mx-auto text-gray-600" data-aos="fade-down" data-aos-delay="100">I’m a Supply Chain Management graduate from URI (3.90 GPA, 2023) and Lean Six Sigma Green Belt. At Garage Headquarters, I drove $2.2M+ in sales and streamlined processes. I help businesses, professionals, and homes create massive savings with no upfront cost, credited only from the results we generate.</p>
      <a href="https://www.linkedin.com/in/braeden-cannon-96357b221/" target="_blank" rel="noopener noreferrer" class="text-blue-600 hover:text-blue-800 font-semibold" data-aos="fade-up" data-aos-delay="200">Connect on LinkedIn</a>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section bg-blue-900 text-white">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-8" data-aos="fade-up">Get a Free Quote</h2>
      <p class="text-lg mb-10 max-w-2xl mx-auto" data-aos="fade-up" data-aos-delay="100">Sounds like inefficiencies are draining your resources? I’ll visit your site or hop on a call for free to create a custom plan for your savings. No upfront cost or fees—my compensation comes only from the savings we create. Call <a href="tel:+14014511035" class="underline hover:text-green-300">(401) 451-1035</a> or fill out the form.</p>
      <div class="max-w-md mx-auto" data-aos="zoom-in" data-aos-delay="200">
        <input type="text" id="contact-name" placeholder="Your Name" class="w-full p-4 mb-4 rounded border-gray-300 bg-white text-gray-900 focus:border-green-600 focus:ring-2 focus:ring-green-200">
        <input type="email" id="contact-email" placeholder="Your Email" class="w-full p-4 mb-4 rounded border-gray-300 bg-white text-gray-900 focus:border-green-600 focus:ring-2 focus:ring-green-200">
        <textarea id="contact-message" placeholder="Tell me about your challenges" class="w-full p-4 mb-4 rounded border-gray-300 bg-white text-gray-900 focus:border-green-600 focus:ring-2 focus:ring-green-200" rows="4"></textarea>
        <a href="#" id="send-email" class="btn px-6 py-3 rounded-lg w-full">Request Free Quote</a>
      </div>
      <p class="mt-6" data-aos="fade-up" data-aos-delay="300">Or email <a href="mailto:continuouscannon@gmail.com" class="underline hover:text-green-300">continuouscannon@gmail.com</a></p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white py-6">
    <div class="container mx-auto px-6 text-center">
      <span class="text-lg font-semibold text-gold-600">Continuous Cannon Consulting</span>
      <p class="mt-2">Contact: <a href="tel:+14014511035" class="underline hover:text-green-300">(401) 451-1035</a> | <a href="mailto:continuouscannon@gmail.com" class="underline hover:text-green-300">continuouscannon@gmail.com</a></p>
      <p class="mt-2 text-sm">© 2025 Continuous Cannon Consulting. All rights reserved.</p>
    </div>
  </footer>

  <!-- AOS and Custom Scripts -->
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    // Initialize AOS
    AOS.init({
      duration: 1000,
      once: true,
    });

    // Preloader
    window.addEventListener('load', function() {
      document.getElementById('preloader').style.display = 'none';
    });

    // Smooth scrolling for nav links
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });

    // Savings calculator
    function calculateSavings() {
      const units = parseInt(document.getElementById('units').value) || 0;
      const hours = parseInt(document.getElementById('hours').value) || 0;
      const rate = parseInt(document.getElementById('rate').value) || 0;
      const monthlySavings = units * hours * rate * 5 * 4;
      const result = monthlySavings > 0 ? `Estimated Monthly Savings: $${monthlySavings.toFixed(2)}<br>Let’s unlock this value together—request a free quote!` : "Please enter valid numbers to calculate savings.";
      document.getElementById('result').innerHTML = result;
    }

    // Email functionality for contact section
    document.getElementById('send-email').addEventListener('click', function(e) {
      e.preventDefault();
      const name = document.getElementById('contact-name').value || 'Not provided';
      const email = document.getElementById('contact-email').value || 'Not provided';
      const message = document.getElementById('contact-message').value || 'No message provided';
      const subject = encodeURIComponent(`Free Quote Request from ${name}`);
      const body = encodeURIComponent(`Name: ${name}\nEmail: ${email}\n\nMessage:\n${message}`);
      const mailtoLink = `mailto:continuouscannon@gmail.com?subject=${subject}&body=${body}`;
      window.location.href = mailtoLink;
    });
  </script>
</body>
</html>
