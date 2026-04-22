/*
====================================================
MODERN ENGINEERING PORTFOLIO (REACT VERSION)
Designed for IoT + AI Engineer Profile (Luqman)
====================================================
*/

import React from "react";

// =========================
// UI LAYOUT STRUCTURE
// =========================

/*
PAGE STRUCTURE (MODERN ENGINEER STYLE)

1. HERO SECTION
   - Name + Role (IoT + AI Engineer)
   - Short impact tagline
   - CTA buttons (GitHub / Resume / Projects)

2. ABOUT ENGINEER
   - Theory → Practice → Real-world mindset

3. FYP SHOWCASE (MAIN SECTION ⭐)
   - Project overview
   - System Architecture Diagram
   - Tech stack
   - Results & impact

4. SYSTEM ARCHITECTURE VISUAL
   - IoT → Cloud → AI → Dashboard flow

5. MINI PROJECTS
   - IoT + Embedded systems

6. ENGINEERING LAB (EXPERIMENTS)
   - sensor testing, LoRa range, ML comparison

7. FREELANCE WORK
   - real client-based engineering solutions

8. EXPERIENCE
   - internship + hardware repair

9. SKILLS MATRIX
   - grouped + proficiency levels

10. CONTACT
*/

// =========================
// HERO SECTION
// =========================
export function Hero() {
  return (
    <section className="hero">
      <h1>Luqman Al Hakim</h1>
      <h3>IoT & AI Engineer | Embedded Systems Developer</h3>
      <p>
        Building real-world engineering systems from sensors → data → AI → impact.
      </p>
      <div className="buttons">
        <button>View Projects</button>
        <button>Download Resume</button>
      </div>
    </section>
  );
}

// =========================
// ABOUT SECTION
// =========================
export function About() {
  return (
    <section>
      <h2>About Me</h2>
      <p>
        I am an engineering student focused on IoT systems, embedded hardware,
        and AI-driven applications. I specialize in transforming theoretical
        concepts into real-world working systems through experimentation,
        hardware integration, and machine learning models.
      </p>
    </section>
  );
}

// =========================
// FYP SECTION
// =========================
export function FYP() {
  return (
    <section>
      <h2>Final Year Project</h2>
      <h3>Smart Soil Sensing with Precise Agriculture System</h3>

      <p>
        An IoT-based precision agriculture system using multi-parameter soil
        sensors and LoRa communication to monitor real-time soil conditions.
      </p>

      <ul>
        <li>8-in-1 soil sensor (Moisture, pH, NPK, Temperature, etc.)</li>
        <li>LoRa long-range communication</li>
        <li>Cloud database storage</li>
        <li>AI prediction (LSTM + ML hybrid)</li>
        <li>Web dashboard visualization</li>
      </ul>
    </section>
  );
}

// =========================
// SYSTEM ARCHITECTURE DIAGRAM
// =========================
export function Architecture() {
  return (
    <section>
      <h2>System Architecture</h2>

      <pre>
{`
[ Soil Sensors ]
      ↓
[ ESP32 / Microcontroller ]
      ↓ (LoRa Transmission)
[ Gateway Receiver ]
      ↓
[ Cloud Database ]
      ↓
[ AI Engine (LSTM + ML Models) ]
      ↓
[ Web Dashboard (React UI) ]
      ↓
[ Farmer Decision Support System ]
`}
      </pre>
    </section>
  );
}

// =========================
// MINI PROJECTS
// =========================
export function Projects() {
  return (
    <section>
      <h2>Mini Projects</h2>

      <div>
        <h4>Smart Irrigation System</h4>
        <p>Automatic watering system using soil moisture sensor + relay control.</p>
      </div>

      <div>
        <h4>IoT Weather Station</h4>
        <p>ESP32-based weather monitoring with cloud dashboard.</p>
      </div>

      <div>
        <h4>AI Soil Prediction Model</h4>
        <p>Machine learning model predicting soil condition trends.</p>
      </div>
    </section>
  );
}

// =========================
// ENGINEERING LAB
// =========================
export function Lab() {
  return (
    <section>
      <h2>Engineering Lab (Experiments)</h2>

      <ul>
        <li>LoRa signal range testing (distance vs signal strength)</li>
        <li>Soil sensor calibration experiments</li>
        <li>ML model comparison (RF vs XGBoost vs LSTM)</li>
        <li>Hardware failure debugging (CPU, PCB, sensor faults)</li>
      </ul>
    </section>
  );
}

// =========================
// FREELANCE
// =========================
export function Freelance() {
  return (
    <section>
      <h2>Freelance Engineering Work</h2>

      <p>
        Delivered small-scale IoT prototypes, automation systems, and hardware
        repair solutions for real clients.
      </p>

      <ul>
        <li>Sensor-based monitoring systems</li>
        <li>Basic web dashboards for IoT devices</li>
        <li>Electronics troubleshooting & repair</li>
      </ul>
    </section>
  );
}

// =========================
// MAIN APP
// =========================
export default function App() {
  return (
    <div>
      <Hero />
      <About />
      <FYP />
      <Architecture />
      <Projects />
      <Lab />
      <Freelance />
    </div>
  );
}

/*
====================================================
UI DESIGN STYLE (MODERN ENGINEER LOOK)
====================================================

- Dark theme background (#0f172a / navy black)
- Accent color: cyan / green (tech feel)
- Clean grid layout (2-column sections)
- Card-based project display
- Minimal typography (Inter / Poppins)
- Animated section reveal (fade/slide)

====================================================
*/
