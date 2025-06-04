<script type="text/javascript">
        var gk_isXlsx = false;
        var gk_xlsxFileLookup = {};
        var gk_fileData = {};
        function filledCell(cell) {
          return cell !== '' && cell != null;
        }
        function loadFileData(filename) {
        if (gk_isXlsx && gk_xlsxFileLookup[filename]) {
            try {
                var workbook = XLSX.read(gk_fileData[filename], { type: 'base64' });
                var firstSheetName = workbook.SheetNames[0];
                var worksheet = workbook.Sheets[firstSheetName];

                // Convert sheet to JSON to filter blank rows
                var jsonData = XLSX.utils.sheet_to_json(worksheet, { header: 1, blankrows: false, defval: '' });
                // Filter out blank rows (rows where all cells are empty, null, or undefined)
                var filteredData = jsonData.filter(row => row.some(filledCell));

                // Heuristic to find the header row by ignoring rows with fewer filled cells than the next row
                var headerRowIndex = filteredData.findIndex((row, index) =>
                  row.filter(filledCell).length >= filteredData[index + 1]?.filter(filledCell).length
                );
                // Fallback
                if (headerRowIndex === -1 || headerRowIndex > 25) {
                  headerRowIndex = 0;
                }

                // Convert filtered JSON back to CSV
                var csv = XLSX.utils.aoa_to_sheet(filteredData.slice(headerRowIndex)); // Create a new sheet from filtered array of arrays
                csv = XLSX.utils.sheet_to_csv(csv, { header: 1 });
                return csv;
            } catch (e) {
                console.error(e);
                return "";
            }
        }
        return gk_fileData[filename] || "";
        }
        </script><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="OptiThrive Solutions delivers expert solutions to help businesses, professionals, and homes create substantial savings with no upfront cost. Request a free consultation today!">
  <meta name="keywords" content="savings, consulting, no upfront cost, efficiency, business, home, OptiThrive Solutions">
  <meta name="author" content="Braeden">
  <title>OptiThrive Solutions - No Costs, Just Savings</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: #D4BEA8;
      color: #333333;
      margin: 0;
      overflow-x: hidden;
      position: relative;
      cursor: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="%23FFE87C" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/></svg>'), auto;
    }
    /* Particle Background with Full-Page Floating Balls */
    #particles {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -1;
      pointer-events: none;
    }
    .particle {
      position: absolute;
      width: 5px;
      height: 5px;
      background: #FFE87C;
      border-radius: 50%;
      opacity: 0.6;
      animation: floatUp 8s infinite ease-in-out;
    }
    @keyframes floatUp {
      0% { transform: translateY(100vh); opacity: 0.6; }
      50% { opacity: 0.9; }
      100% { transform: translateY(-100vh); opacity: 0; }
    }
    /* Swaying Palm Tree Pattern */
    body::after {
      content: '';
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: url('data:image/svg+xml,%3Csvg xmlns="http://www.w3.org/2000/svg" width="100" height="200" viewBox="0 0 100 200"%3E%3Cpath d="M50 0 Q40 50 30 0 Q60 50 70 0" fill="none" stroke="%232F4F4F" stroke-width="1" stroke-opacity="0.1"/%3E%3Ccircle cx="50" cy="0" r="5" fill="%232F4F4F" opacity="0.1"/%3E%3C/svg%3E') repeat-x;
      animation: sway 8s infinite ease-in-out;
      z-index: -2;
    }
    @keyframes sway {
      0% { transform: translateX(0); }
      50% { transform: translateX(-20px); }
      100% { transform: translateX(0); }
    }
    h1, h2, h3 {
      font-family: 'Playfair Display', serif;
      color: #2F4F4F;
      letter-spacing: 1px;
    }
    /* Preloader */
    #preloader {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: #D4BEA8;
      display: flex;
      justify-content: center;
      align-items: center;
      z-index: 9999;
    }
    #preloader::after {
      content: '';
      width: 60px;
      height: 60px;
      border: 6px solid #2F4F4F;
      border-top: 6px solid transparent;
      border-radius: 50%;
      animation: spin 1.5s linear infinite;
    }
    @keyframes spin {
      100% { transform: rotate(360deg); }
    }
    /* Animated Separator */
    .separator {
      width: 100%;
      height: 3px;
      background: linear-gradient(to right, #FFE87C, #FFD54F, #FFE87C);
      margin: 3rem 0;
      animation: rotateGradient 5s infinite linear;
    }
    @keyframes rotateGradient {
      0% { background-position: 0% 50%; }
      100% { background-position: 400% 50%; }
    }
    /* Header Styling - Full Width, Less Bulky */
    nav {
      background: #2F4F4F;
      box-shadow: 0 2px 15px rgba(0, 0, 0, 0.2);
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
      padding: 0.5rem 1rem;
      animation: fadeIn 1s ease;
      display: flex;
      justify-content: space-between;
      align-items: center;
      transition: transform 0.3s ease;
    }
    .logo {
      height: 52px;
      transition: transform 0.3s ease;
      filter: drop-shadow(0 2px 4px rgba(0, 0, 0, 0.2));
    }
    .logo:hover .globe {
      animation: spinGlobe 2s linear;
    }
    .logo:hover .globe {
      animation-fill-mode: forwards;
    }
    .nav-links {
      display: flex;
      align-items: center;
    }
    .nav-links li a {
      font-size: 1rem;
      color: #FFFFFF;
      position: relative;
      transition: color 0.3s ease;
    }
    .nav-links li a::after {
      content: '';
      position: absolute;
      width: 0;
      height: 2px;
      background: linear-gradient(to right, #FFE87C, #FFD54F);
      bottom: -4px;
      left: 50%;
      transform: translateX(-50%);
      transition: width 0.3s ease;
    }
    .nav-links li a:hover::after {
      width: 100%;
    }
    .nav-links li a:hover {
      color: #FFE87C;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    /* Hero Section with Pulsing Button */
    .hero {
      background: rgba(245, 245, 220, 0.8);
      padding: 10rem 0;
      text-align: center;
      position: relative;
      border-bottom: 1px solid rgba(47, 79, 79, 0.1);
    }
    .hero h2 {
      font-size: 5rem;
      margin-bottom: 1.5rem;
      display: inline-block;
      border-right: 4px solid #FFE87C;
      white-space: nowrap;
      overflow: hidden;
      animation: typing 3s steps(30, end), blink 0.75s step-end infinite;
    }
    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }
    @keyframes blink {
      50% { border-color: transparent; }
    }
    .hero p {
      font-size: 1.5rem;
      max-width: 4xl;
      margin-left: auto;
      margin-right: auto;
      margin-bottom: 2.5rem;
    }
    .hero .btn {
      animation: pulseGlow 2s infinite ease-in-out;
    }
    @keyframes pulseGlow {
      0% { transform: scale(1); box-shadow: 0 0 10px rgba(212, 160, 23, 0.5); }
      50% { transform: scale(1.05); box-shadow: 0 0 20px rgba(212, 160, 23, 0.8); }
      100% { transform: scale(1); box-shadow: 0 0 10px rgba(212, 160, 23, 0.5); }
    }
    /* Bouncing Cards with Rotating Border and Growing Content */
    .card {
      background: #F5F5DC;
      border: 1px solid transparent;
      border-radius: 1rem;
      padding: 2.5rem;
      transition: transform 0.5s ease, box-shadow 0.5s ease;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
      animation: bounceIn 1s ease;
      position: relative;
      overflow: hidden;
    }
    .card::before {
      content: '';
      position: absolute;
      top: -2px;
      left: -2px;
      right: -2px;
      bottom: -2px;
      border: 2px solid transparent;
      border-radius: 1rem;
      background: linear-gradient(45deg, #FFE87C, #FFD54F, #FFE87C);
      background-size: 400%;
      z-index: -1;
      transition: background 0.5s ease;
    }
    .card:hover::before {
      animation: rotateBorder 3s linear infinite;
    }
    .card-content {
      transition: transform 0.3s ease;
    }
    .card:hover .card-content {
      transform: scale(1.05);
    }
    @keyframes rotateBorder {
      0% { background-position: 0% 50%; }
      100% { background-position: 400% 50%; }
    }
    .card:hover {
      transform: translateY(-10px) scale(1.02);
      box-shadow: 0 20px 50px rgba(0, 0, 0, 0.2);
    }
    @keyframes bounceIn {
      0% { transform: scale(0.5); opacity: 0; }
      60% { transform: scale(1.1); opacity: 1; }
      100% { transform: scale(1); }
    }
    /* Vibrant Button */
    .btn {
      background: #FFE87C;
      color: #FFFFFF;
      padding: 1.2rem 2.5rem;
      border-radius: 0.75rem;
      transition: all 0.5s ease;
      font-weight: 600;
      text-transform: uppercase;
      border: none;
      position: relative;
      overflow: hidden;
    }
    .btn::after {
      content: '';
      position: absolute;
      width: 0;
      height: 100%;
      background: rgba(212, 160, 23, 0.3);
      top: 0;
      left: 0;
      transition: width 0.5s ease;
      z-index: 0;
    }
    .btn:hover::after {
      width: 100%;
    }
    .btn:hover {
      background: #FFD54F;
      transform: translateY(-3px);
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
    }
    .btn span {
      position: relative;
      z-index: 1;
    }
    /* Section Styling with Parallax Scroll */
    .section {
      padding: 5rem 2rem;
      background: rgba(245, 245, 220, 0.95);
      position: relative;
      overflow: hidden;
      background-image: url('data:image/svg+xml,%3Csvg xmlns="http://www.w3.org/2000/svg" width="400" height="200" viewBox="0 0 400 200"%3E%3Crect width="400" height="200" fill="%23F5F5DC"/%3E%3Cline x1="50" y1="50" x2="350" y2="50" stroke="%232F4F4F" stroke-width="0.5" stroke-opacity="0.1"/%3E%3Cpath d="M0 200 L400 200" stroke="%232F4F4F" stroke-width="1" stroke-opacity="0.05"/%3E%3C/svg%3E');
      background-size: cover;
      background-position: center;
    }
    .section h2 {
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.8s ease, transform 0.8s ease;
    }
    .section h2.visible {
      opacity: 1;
      transform: translateY(0);
    }
    .parallax-bg {
      background: linear-gradient(rgba(245, 245, 220, 0.9), rgba(212, 190, 168, 0.2)),
                  url('data:image/svg+xml,%3Csvg xmlns="http://www.w3.org/2000/svg" width="400" height="200" viewBox="0 0 400 200"%3E%3Crect width="400" height="200" fill="%23F5F5DC"/%3E%3Cline x1="50" y1="50" x2="350" y2="50" stroke="%232F4F4F" stroke-width="0.5" stroke-opacity="0.1"/%3E%3Cpath d="M0 200 L400 200" stroke="%232F4F4F" stroke-width="1" stroke-opacity="0.05"/%3E%3C/svg%3E');
      background-attachment: fixed;
      background-size: cover;
      background-position: center;
    }
    /* Fade-In Text */
    .fade-in-text {
      opacity: 0;
      animation: fadeInText 1.5s forwards;
    }
    @keyframes fadeInText {
      0% { opacity: 0; transform: translateY(10px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    /* Inline Links with Animated Underline */
    .inline-link {
      position: relative;
      transition: color 0.3s ease;
    }
    .inline-link::after {
      content: '';
      position: absolute;
      width: 0;
      height: 2px;
      background: linear-gradient(to right, #FFE87C, #FFD54F);
      bottom: -2px;
      left: 50%;
      transform: translateX(-50%);
      transition: width 0.3s ease;
    }
    .inline-link:hover::after {
      width: 100%;
    }
    .inline-link:hover {
      color: #FFE87C;
    }
    /* Input Fields */
    input, textarea {
      background: rgba(245, 245, 220, 0.7);
      border: 1px solid rgba(47, 79, 79, 0.1);
      color: #333333;
      transition: all 0.3s ease;
      border-radius: 0.75rem;
      padding: 1rem;
    }
    input:focus, textarea:focus {
      border: 1px solid #2F4F4F;
      box-shadow: 0 0 15px rgba(47, 79, 79, 0.1);
      background: rgba(245, 245, 220, 0.9);
    }
    /* Rotating Savings Icon */
    .savings-icon {
      display: inline-block;
      transition: transform 0.5s ease;
    }
    .savings-icon:hover {
      transform: rotate(360deg);
    }
    /* Modal Styling with Pulsing Button */
    .modal {
      display: none;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.5);
      z-index: 10000;
      justify-content: center;
      align-items: center;
    }
    .modal-content {
      background: #F5F5DC;
      padding: 2rem 3rem;
      border-radius: 1rem;
      width: 90%;
      max-width: 500px;
      text-align: center;
      animation: slideIn 0.5s ease;
      border: 2px solid #FFE87C;
    }
    .modal .btn {
      animation: pulse 2s infinite ease-in-out;
    }
    @keyframes slideIn {
      from { transform: translateY(-50px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    @keyframes pulse {
      0% { transform: scale(1); box-shadow: 0 0 0 0 rgba(212, 160, 23, 0.7); }
      70% { transform: scale(1.05); box-shadow: 0 0 0 10px rgba(212, 160, 23, 0); }
      100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(212, 160, 23, 0); }
    }
    .close {
      position: absolute;
      top: 1rem;
      right: 1rem;
      font-size: 1.5rem;
      cursor: pointer;
      color: #333333;
    }
    /* Footer Wave Animation (Removed Wave, Keeping Balls) */
    footer::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -2;
    }
    /* Logo Globe Animation */
    .globe {
      transform-origin: center;
      transition: transform 0.1s ease;
    }
    .logo:hover .globe {
      animation: spinGlobe 2s linear;
    }
    @keyframes spinGlobe {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
    /* Mobile Responsiveness */
    @media (max-width: 768px) {
      .nav-links {
        display: none;
      }
      .hero h2 {
        font-size: 3rem;
      }
      .section {
        padding: 3rem 1rem;
      }
      .modal-content {
        padding: 1.5rem;
      }
      .logo {
        height: 40px;
      }
      .nav-links li a {
        font-size: 0.875rem;
      }
    }
  </style>
</head>
<body>
  <!-- Preloader -->
  <div id="preloader"></div>

  <!-- Particle Background with Full-Page Floating Balls -->
  <div id="particles"></div>

  <!-- Floating Navigation -->
  <nav>
    <div class="flex items-center pl-4">
      <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 260 52' width='260' height='52'%3E%3Cdefs%3E%3CradialGradient id='oceanGradient' cx='50%25' cy='50%25' r='50%25'%3E%3Cstop offset='0%25' style='stop-color:%231E90FF;stop-opacity:0.8'/%3E%3Cstop offset='100%25' style='stop-color:%231E90FF;stop-opacity:0.5'/%3E%3C/radialGradient%3E%3CradialGradient id='glowGradient' cx='50%25' cy='50%25' r='50%25'%3E%3Cstop offset='0%25' style='stop-color:%23FFE87C;stop-opacity:0.3'/%3E%3Cstop offset='100%25' style='stop-color:%23FFE87C;stop-opacity:0'/%3E%3C/radialGradient%3E%3C/defs%3E%3Cg transform='translate(26, 26)'%3E%3Ccircle cx='0' cy='0' r='26' fill='url(%23oceanGradient)'/%3E%3Cg class='globe' transform-origin='center'%3E%3Ccircle cx='0' cy='0' r='24' fill='url(%23oceanGradient)' filter='drop-shadow(2px 2px 2px rgba(0,0,0,0.3))'/%3E%3Cpath d='M-12 -8 Q-10 -6 -8 -8 Q-6 -4 -4 -6 Q-2 -2 0 -4 Q2 -2 4 -6 Q6 -4 8 -8 Q10 -6 12 -8 M-15 0 Q-13 2 -11 0 Q-9 4 -7 2 Q-5 6 -3 4 Q-1 8 1 6 Q3 8 5 4 Q7 6 9 2 Q11 4 13 0 Q15 2 17 0 M-18 10 Q-16 12 -14 10 Q-12 14 -10 12 Q-8 16 -6 14 Q-4 18 -2 16 Q0 20 2 18 Q4 20 6 16 Q8 18 10 14 Q12 16 14 12 Q16 14 18 10' fill='%2332CD32'/%3E%3C/g%3E%3Cg transform='translate(0, -12)'%3E%3Cpath d='M0 -12 V0' fill='none' stroke='%238B4513' stroke-width='3' stroke-linecap='round'/%3E%3Cpath d='M-8 -10 Q-4 -14 0 -10 Q4 -14 8 -10 Q4 -6 0 -10 Q-4 -6 -8 -10 M-10 -8 Q-6 -12 0 -8 Q6 -12 10 -8 Q6 -4 0 -8 Q-6 -4 -10 -8' fill='%23228B22'/%3E%3C/g%3E%3Ccircle cx='0' cy='0' r='26' fill='url(%23glowGradient)'/%3E%3C/g%3E%3Ctext x='60' y='32' font-family='Playfair Display, serif' font-size='24' font-weight='bold' fill='%231A2E2E' text-shadow='0 0 2px rgba(255,255,255,0.8)'%3EOptiThrive Solutions%3C/text%3E%3C/svg%3E" alt="OptiThrive Solutions Logo" class="logo">
    </div>
    <ul class="nav-links pr-4 flex space-x-6">
      <li><a href="#home" class="hover:text-FFE87C transition-colors">Home</a></li>
      <li><a href="#services" class="hover:text-FFE87C transition-colors">Services</a></li>
      <li><a href="#results" class="hover:text-FFE87C transition-colors">Results</a></li>
      <li><a href="#savings" class="hover:text-FFE87C transition-colors">Calculator</a></li>
      <li><a href="#contact" class="hover:text-FFE87C transition-colors">Contact</a></li>
    </ul>
  </nav>

  <!-- Hero Section with Pulsing Button -->
  <section id="home" class="hero text-center" data-aos="fade-up">
    <div class="container mx-auto px-6 relative z-10">
      <h2 class="text-5xl md:text-6xl font-bold mb-6 leading-tight">No Costs, Just Savings</h2>
      <p class="text-xl mb-8 max-w-4xl mx-auto leading-relaxed fade-in-text">Struggling with inefficiencies? Our team leverages advanced analytics to unlock substantial savings for businesses, professionals, and homes with no upfront cost. A tailored plan is crafted post-consultation, credited only from the savings we generate.</p>
      <button class="btn px-12 py-6 rounded-xl font-semibold" onclick="openModal()">Request a Free Consultation: (401) 451-1035</button>
    </div>
    <div class="separator"></div>
  </section>

  <!-- Services Section -->
  <section id="services" class="section">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-4xl md:text-5xl font-bold mb-10" data-aos="fade-up">Our Expert Services</h2>
      <p class="text-lg mb-12 max-w-2xl mx-auto fade-in-text" data-aos="fade-up" data-aos-delay="100">We deliver precision-engineered solutions for any entity, utilizing cutting-edge strategies to maximize efficiency and savings. Compensation is tied solely to the results we achieve.</p>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
        <div class="card" data-aos="fade-right" data-aos-delay="200">
          <div class="card-content">
            <h3 class="text-2xl font-semibold mb-5">Process Optimization</h3>
            <p class="fade-in-text">Enhance workflows with AI-driven insights for businesses and homes, saving time and resources.</p>
          </div>
        </div>
        <div class="card" data-aos="fade-up" data-aos-delay="300">
          <div class="card-content">
            <h3 class="text-2xl font-semibold mb-5">Expense Reduction</h3>
            <p class="fade-in-text">Minimize costs with predictive analytics, tailored for any operation or household.</p>
          </div>
        </div>
        <div class="card" data-aos="fade-left" data-aos-delay="400">
          <div class="card-content">
            <h3 class="text-2xl font-semibold mb-5">Training & Tools</h3>
            <p class="fade-in-text">Deploy next-gen tools and training to sustain long-term efficiency gains.</p>
          </div>
        </div>
      </div>
      <button class="btn px-10 py-5 mt-12 rounded-xl" data-aos="fade-up" data-aos-delay="500" onclick="openModal()">Request a Free Quote Now</button>
    </div>
    <div class="separator"></div>
  </section>

  <!-- Results Section -->
  <section id="results" class="section parallax-bg">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-4xl md:text-5xl font-bold mb-10" data-aos="fade-down">Savings We Can Create</h2>
      <p class="text-lg mb-12 max-w-2xl mx-auto fade-in-text" data-aos="fade-down" data-aos-delay="100">Data-driven examples demonstrate our capacity to generate savings, with compensation credited only from achieved results.</p>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
        <div class="card" data-aos="fade-right" data-aos-delay="200">
          <div class="card-content">
            <h3 class="text-2xl font-semibold mb-5">Streamlined Operations</h3>
            <p class="fade-in-text">Businesses save millions annually via optimized processes, tracked with real-time analytics.</p>
          </div>
        </div>
        <div class="card" data-aos="fade-up" data-aos-delay="300">
          <div class="card-content">
            <h3 class="text-2xl font-semibold mb-5">Reduced Expenses</h3>
            <p class="fade-in-text">Professionals cut costs with AI forecasts, measured via financial dashboards.</p>
          </div>
        </div>
        <div class="card" data-aos="fade-left" data-aos-delay="400">
          <div class="card-content">
            <h3 class="text-2xl font-semibold mb-5">Home Efficiency</h3>
            <p class="fade-in-text">Homeowners reduce utility bills with smart systems, monitored via IoT integrations.</p>
          </div>
        </div>
      </div>
      <p class="mt-10 text-xl font-semibold text-2F4F4F fade-in-text" data-aos="fade-up" data-aos-delay="500">Be the first to transform your savings – let’s get started!</p>
    </div>
    <div class="separator"></div>
  </section>

  <!-- Savings Calculator Section -->
  <section id="savings" class="section">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-4xl md:text-5xl font-bold mb-10" data-aos="fade-up">Estimate Your Savings</h2>
      <p class="text-lg mb-12 max-w-2xl mx-auto fade-in-text" data-aos="fade-up" data-aos-delay="100">Project your potential savings with our advanced estimator.</p>
      <div class="max-w-lg mx-auto card p-10 rounded-xl" data-aos="zoom-in" data-aos-delay="200">
        <div class="card-content">
          <span class="savings-icon mb-4 inline-block">
            <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24" fill="#FFE87C"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8zm-1-13h2v2h-2zm0 4h2v6h-2z"/></svg>
          </span>
          <label class="block mb-3 text-left fade-in-text">Units Affected (e.g., employees, tasks)</label>
          <input id="units" type="number" placeholder="e.g., 10" class="w-full p-4 mb-5 rounded-lg">
          <label class="block mb-3 text-left fade-in-text">Hours Saved per Unit/Day</label>
          <input id="hours" type="number" placeholder="e.g., 1" class="w-full p-4 mb-5 rounded-lg">
          <label class="block mb-3 text-left fade-in-text">Value per Hour ($)</label>
          <input id="rate" type="number" placeholder="e.g., 30" class="w-full p-4 mb-5 rounded-lg">
          <button onclick="calculateSavings()" class="btn px-10 py-5 rounded-xl w-full">Calculate Savings Now</button>
          <p id="result" class="mt-8 text-2xl font-semibold fade-in-text"></p>
        </div>
      </div>
    </div>
    <div class="separator"></div>
  </section>

  <!-- Testimonials Section (Forward-Looking) -->
  <section id="testimonials" class="section parallax-bg">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-4xl md:text-5xl font-bold mb-10" data-aos="fade-down">What to Expect</h2>
      <p class="text-lg mb-12 max-w-2xl mx-auto fade-in-text" data-aos="fade-down" data-aos-delay="100">As a new client, you’ll experience personalized service, cutting-edge analytics, and measurable savings tailored to your needs. Expect dedicated support, including free overtime when needed, to maximize your savings—without any binding contracts. Let’s build your success story together!</p>
      <div class="card p-10 rounded-xl max-w-2xl mx-auto" data-aos="fade-up" data-aos-delay="200">
        <div class="card-content">
          <p class="italic text-lg fade-in-text">“Looking forward to partnering with OptiThrive Solutions to unlock savings and efficiency for my business.” – Your Future Client</p>
        </div>
      </div>
      <p class="mt-10 text-xl font-semibold text-2F4F4F fade-in-text" data-aos="fade-up" data-aos-delay="300">Be among the first to experience transformative savings – request your quote today!</p>
    </div>
    <div class="separator"></div>
  </section>

  <!-- Tips Section -->
  <section id="tips" class="section">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-4xl md:text-5xl font-bold mb-10" data-aos="fade-up">Efficiency Strategies</h2>
      <p class="text-lg mb-12 max-w-2xl mx-auto fade-in-text" data-aos="fade-up" data-aos-delay="100">Unlock next-level efficiencies for your operations or residence.</p>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-10">
        <div class="card" data-aos="fade-right" data-aos-delay="200">
          <div class="card-content">
            <h3 class="text-2xl font-semibold mb-5">AI-Optimized Workflows</h3>
            <p class="fade-in-text">Leverage AI to streamline processes. <a href="#contact" class="inline-link text-2F4F4F">Get a free quote</a> to begin.</p>
          </div>
        </div>
        <div class="card" data-aos="fade-left" data-aos-delay="300">
          <div class="card-content">
            <h3 class="text-2xl font-semibold mb-5">Cost-Saving Innovations</h3>
            <p class="fade-in-text">Adopt smart tech for savings. <a href="#contact" class="inline-link text-2F4F4F">Request a consultation</a>.</p>
          </div>
        </div>
      </div>
    </div>
    <div class="separator"></div>
  </section>

  <!-- About Section -->
  <section id="about" class="section parallax-bg">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-4xl md:text-5xl font-bold mb-10" data-aos="fade-down">About OptiThrive Solutions</h2>
      <p class="text-lg mb-12 max-w-2xl mx-auto fade-in-text" data-aos="fade-down" data-aos-delay="100">Founded by a Supply Chain Management graduate from URI (3.90 GPA, 2023) with a Lean Six Sigma Green Belt. At Garage Headquarters, I drove $2.2M+ in sales and optimized systems. OptiThrive Solutions now delivers AI-enhanced savings solutions with no upfront cost, credited from results. Committed to your success, OptiThrive Solutions offers free overtime support as needed to ensure results, with no binding contract required.</p>
      <a href="https://www.linkedin.com/in/braeden-cannon-96357b221/" target="_blank" rel="noopener noreferrer" class="inline-link text-2F4F4F font-semibold text-xl fade-in-text" data-aos="fade-up" data-aos-delay="200">Connect on LinkedIn</a>
    </div>
    <div class="separator"></div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-4xl md:text-5xl font-bold mb-10" data-aos="fade-up">Request a Quote</h2>
      <p class="text-lg mb-12 max-w-2xl mx-auto fade-in-text" data-aos="fade-up" data-aos-delay="100">Inefficiencies impacting your resources? I’ll conduct a virtual or on-site analysis to devise a custom savings plan. No fees—compensation is results-based. Call <a href="tel:+14014511035" class="inline-link underline text-2F4F4F">(401) 451-1035</a> or use the interface below.</p>
      <div class="max-w-md mx-auto" data-aos="zoom-in" data-aos-delay="200">
        <input type="text" id="contact-name" placeholder="Your Name" class="w-full p-4 mb-5 rounded-lg">
        <input type="email" id="contact-email" placeholder="Your Email" class="w-full p-4 mb-5 rounded-lg">
        <textarea id="contact-message" placeholder="Describe your challenges" class="w-full p-4 mb-5 rounded-lg" rows="4"></textarea>
        <button class="btn px-10 py-5 rounded-xl w-full" onclick="openModal()">Request Free Quote Today</button>
      </div>
      <p class="mt-10 text-lg fade-in-text" data-aos="fade-up" data-aos-delay="300">Or email <a href="mailto:OptiThriveSolutions@gmail.com" class="inline-link underline text-2F4F4F">OptiThriveSolutions@gmail.com</a></p>
    </div>
    <div class="separator"></div>
  </section>

  <!-- Footer -->
  <footer class="bg-2F4F4F py-8 text-center relative">
    <div class="container mx-auto px-6">
      <span class="text-xl font-bold text-FFE87C fade-in-text">OptiThrive Solutions</span>
      <p class="mt-4 text-white fade-in-text">Contact: <a href="tel:+14014511035" class="underline hover:text-FFE87C">(401) 451-1035</a> | <a href="mailto:OptiThriveSolutions@gmail.com" class="underline hover:text-FFE87C">OptiThriveSolutions@gmail.com</a></p>
      <p class="mt-4 text-sm text-white fade-in-text">© 2025 OptiThrive Solutions. All rights reserved.</p>
    </div>
  </footer>

  <!-- Modal -->
  <div id="modal" class="modal">
    <div class="modal-content">
      <span class="close" onclick="closeModal()">×</span>
      <h3 class="text-2xl font-bold mb-6">Request Your Exclusive Quote</h3>
      <input type="text" id="modal-name" placeholder="Your Name" class="w-full p-4 mb-4 rounded-lg">
      <input type="email" id="modal-email" placeholder="Your Email" class="w-full p-4 mb-4 rounded-lg">
      <textarea id="modal-message" placeholder="Describe your needs" class="w-full p-4 mb-6 rounded-lg" rows="4"></textarea>
      <button class="btn px-8 py-4 rounded-xl w-full" onclick="sendModalEmail()">Submit Request</button>
    </div>
  </div>

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

    // Particle Effect (Full-Page Floating Balls)
    const particleContainer = document.getElementById('particles');
    for (let i = 0; i < 100; i++) {
      const particle = document.createElement('div');
      particle.classList.add('particle');
      particle.style.left = Math.random() * 100 + 'vw';
      particle.style.top = Math.random() * 100 + 'vh';
      particle.style.animationDelay = Math.random() * 5 + 's';
      particleContainer.appendChild(particle);
    }

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
      const result = monthlySavings > 0 ? `Estimated Monthly Savings: $${monthlySavings.toFixed(2)}<br>Unlock your potential – request a quote now!` : "Please enter valid numbers to calculate savings.";
      document.getElementById('result').innerHTML = result;
    }

    // Modal functions
    function openModal() {
      document.getElementById('modal').style.display = 'flex';
    }
    function closeModal() {
      document.getElementById('modal').style.display = 'none';
    }
    window.onclick = function(event) {
      if (event.target == document.getElementById('modal')) {
        closeModal();
      }
    };

    // Email functionality for modal
    function sendModalEmail() {
      const name = document.getElementById('modal-name').value || 'Not provided';
      const email = document.getElementById('modal-email').value || 'Not provided';
      const message = document.getElementById('modal-message').value || 'No message provided';
      const subject = encodeURIComponent(`Exclusive Quote Request from ${name}`);
      const body = encodeURIComponent(`Name: ${name}\nEmail: ${email}\n\nMessage:\n${message}`);
      const mailtoLink = `mailto:OptiThriveSolutions@gmail.com?subject=${subject}&body=${body}`;
      window.location.href = mailtoLink;
      closeModal();
    }

    // Sequential Fade-In for Text
    document.querySelectorAll('.fade-in-text').forEach((el, index) => {
      el.style.animationDelay = `${index * 0.3}s`;
    });

    // Parallax Scroll Effect for Sections
    window.addEventListener('scroll', function() {
      const sections = document.querySelectorAll('.section:not(.parallax-bg)');
      sections.forEach(section => {
        const scrollPos = window.scrollY;
        const sectionPos = section.offsetTop - scrollPos;
        section.style.backgroundPositionY = `${sectionPos * 0.2}px`;
      });
    });

    // Scaling Header on Scroll
    window.addEventListener('scroll', function() {
      const nav = document.querySelector('nav');
      const scrollPos = window.scrollY;
      const scale = Math.max(0.9, 1 - scrollPos / 1000);
      nav.style.transform = `scale(${scale})`;
    });

    // Fading Section Titles on View
    const sectionTitles = document.querySelectorAll('.section h2');
    const observerOptions = {
      root: null,
      rootMargin: '0px',
      threshold: 0.2
    };
    const observer = new IntersectionObserver((entries, observer) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
          observer.unobserve(entry.target);
        }
      });
    }, observerOptions);
    sectionTitles.forEach(title => observer.observe(title));
  </script>
</body>
</html>
