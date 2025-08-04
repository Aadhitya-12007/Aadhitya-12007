<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Aadhitya G – GitHub Profile</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f0f2f5;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
      padding: 2rem;
      text-align: center;
      color: white;
    }
    header h1 {
      margin: 0;
      font-size: 3rem;
    }
    header p {
      margin: 0.5rem 0;
      font-size: 1.2rem;
    }
    .container {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    .section {
      margin-bottom: 2rem;
    }
    .section h2 {
      font-size: 1.8rem;
      border-left: 5px solid #2575fc;
      padding-left: 0.5rem;
    }
    .grid {
      display: grid;
      gap: 1rem;
    }
    /* Two-column grid on wider screens */
    @media(min-width: 700px) {
      .grid-2 { grid-template-columns: repeat(2, 1fr); }
    }
    /* Three-column grid on wider screens */
    @media(min-width: 1000px) {
      .grid-3 { grid-template-columns: repeat(3, 1fr); }
    }
    .card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 1rem;
      transition: transform 0.3s, box-shadow 0.3s;
      cursor: pointer;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    }
    .card h3 {
      margin-top: 0;
    }
    .toggle-content {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.4s ease;
    }
    .card.open .toggle-content {
      max-height: 500px;
    }
    .competency-list {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
    }
    .badge {
      background: #2575fc;
      color: white;
      border-radius: 12px;
      padding: 0.3rem 0.8rem;
      font-size: 0.85rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Aadhitya G</h1>
    <p>Final-year ECE • Embedded Systems & IoT Enthusiast • CGPA: 9.2</p>
  </header>

  <div class="container">

    <!-- Professional Summary -->
    <section class="section">
      <h2>Professional Summary</h2>
      <p>Final year Electronics & Communication Engineering student with hands-on embedded systems and IoT experience. Skilled in microcontroller programming and PCB design, with strong communication and teamwork abilities. Passionate about building tech that makes a difference.</p>
    </section>

    <!-- Core Competencies -->
    <section class="section">
      <h2>Core Competencies</h2>
      <div class="competency-list">
        <span class="badge">Embedded C Programming</span>
        <span class="badge">PCB Design (Altium & KiCAD)</span>
        <span class="badge">Micropython</span>
        <span class="badge">Microcontroller Programming</span>
        <span class="badge">Arduino IDE</span>
        <span class="badge">TI CCS & MPLAB IDE</span>
        <span class="badge">Blynk & ThingSpeak</span>
        <span class="badge">MATLAB & Simulink</span>
        <span class="badge">Proteus</span>
        <span class="badge">RTOS Basics</span>
        <span class="badge">RV32I ISA</span>
      </div>
    </section>

    <!-- Internship Experience -->
    <section class="section">
      <h2>Internship Experience</h2>
      <div class="grid grid-2">
        <div class="card" onclick="toggleCard(this)">
          <h3>Taras Systems &amp; Solutions<br/><small>Jun 2025 – Present</small></h3>
          <div class="toggle-content">
            <ul>
              <li>Bare-metal programming on MSP430G2553 (TI Code Composer Studio)</li>
              <li>HAL programming on STM32 (STM32CubeIDE)</li>
              <li>IoT: Blynk & ThingSpeak integration</li>
            </ul>
          </div>
        </div>

        <div class="card" onclick="toggleCard(this)">
          <h3>Airports Authority of India (AAI), Chennai<br/><small>Dec 2024</small></h3>
          <div class="toggle-content">
            <ul>
              <li>Intern, CNS (Communication, Navigation & Surveillance)</li>
              <li>Learned aircraft–ATC communication protocols and nuances</li>
            </ul>
          </div>
        </div>

        <div class="card" onclick="toggleCard(this)">
          <h3>Integral Coach Factory, Chennai<br/><small>Jul 2024</small></h3>
          <div class="toggle-content">
            <ul>
              <li>Technical Intern – Shell & Furnishing</li>
              <li>Explored electronics in railway coach manufacturing</li>
            </ul>
          </div>
        </div>

        <div class="card" onclick="toggleCard(this)">
          <h3>ReTech Solutions Pvt Ltd.<br/><small>May 2024</small></h3>
          <div class="toggle-content">
            <ul>
              <li>Intern: ATmega-328P microcontrollers & sensor data processing</li>
              <li>IoT integration using Blynk</li>
              <li>SONAR detector project with Python plotting</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Projects -->
    <section class="section">
      <h2>Relevant Projects</h2>
      <div class="grid grid-2">
        <div class="card" onclick="toggleCard(this)">
          <h3>IoT-Based Fire Alarm</h3>
          <div class="toggle-content">
            <ul>
              <li>Raspberry Pi Pico W + fire sensors</li>
              <li>Telegram bot alerts with GPS for nearest fire station</li>
            </ul>
          </div>
        </div>
        <div class="card" onclick="toggleCard(this)">
          <h3>ESP32 Remedy Generator</h3>
          <div class="toggle-content">
            <ul>
              <li>ESP32, webcam & Python modules</li>
              <li>Temperature & pulse sensors</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Education -->
    <section class="section">
      <h2>Education</h2>
      <div class="card">
        <h3>SRM Easwari Engineering College</h3>
        <p>B.E. in Electronics & Communication Engineering, 2022 – 2026<br/>CGPA: 9.2</p>
      </div>
      <div class="card" style="margin-top:1rem;">
        <h3>National Public School</h3>
        <p>Class 12 – PCM, 2022</p>
      </div>
    </section>

    <!-- Courses & Workshops -->
    <section class="section">
      <h2>Courses & Workshops</h2>
      <div class="grid grid-3">
        <div class="card" onclick="toggleCard(this)">
          <h3>Online Courses</h3>
          <div class="toggle-content">
            <ul>
              <li>Embedded C Programming (Udemy)</li>
              <li>C & C++ Fundamentals (Coursera)</li>
              <li>PCB Design – Altium (Altium Edu)</li>
              <li>Micropython Basics (NIELIT)</li>
              <li>Entrepreneurship (NPTEL Top 1%)</li>
              <li>Leadership & Team Effectiveness (NPTEL Top 5%)</li>
              <li>Prompt Design (Vertex AI)</li>
            </ul>
          </div>
        </div>
        <div class="card" onclick="toggleCard(this)">
          <h3>Workshops</h3>
          <div class="toggle-content">
            <ul>
              <li>Embedded Systems & IoT (Taras Systems)</li>
              <li>TinkerCAD Circuits (SRM Easwari)</li>
            </ul>
          </div>
        </div>
        <div class="card" onclick="toggleCard(this)">
          <h3>Paper Presentations</h3>
          <div class="toggle-content">
            <ul>
              <li>FPGA AI Accelerators vs GPUs – Pragyotsav’24</li>
              <li>IoT Fire Alarm – ICMICC’25</li>
              <li>RTOS on RISC-V – ICMICC’25</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Memberships & Volunteering -->
    <section class="section">
      <h2>Membership & Contributions</h2>
      <ul>
        <li>Conducted TI Microcontroller workshop for 1st-year ECE students</li>
        <li>Member: IETE & ISTE</li>
        <li>Volunteer: YRC & Rotaract Club</li>
      </ul>
    </section>

  </div>

  <script>
    function toggleCard(card) {
      card.classList.toggle('open');
    }
  </script>
</body>
</html>
