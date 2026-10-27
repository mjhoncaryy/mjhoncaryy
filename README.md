<div align="center">
  <img src="https://github.com/mjhoncaryy.png?size=220" width="112" height="112" alt="Michael Jhoncary">

  <h1>Michael Jhoncary</h1>

  <p><strong>Electrical Engineering student at Universitas Pendidikan Indonesia.<br>I build sensor and IoT prototypes, then analyze the data they produce.</strong></p>

  <p>
    R&amp;D Staff, IEEE UPI Student Branch · Bandung, Indonesia
  </p>

  <p>
    <a href="https://www.linkedin.com/in/michaeljhoncary/">
      <img src="https://img.shields.io/badge/LinkedIn-michaeljhoncary-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
    </a>
    <a href="https://github.com/mjhoncaryy?tab=repositories">
      <img src="https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub repositories">
    </a>
  </p>
</div>

---

I started in software. I studied Computer Software Engineering at SMK Gracia (2021 to 2023) and did a front-end internship at CyberLabs in 2022. In 2024 I moved to Electrical Engineering at UPI, and most of my projects since then sit where hardware meets code: an ESP32 reading water sensors, an FM transmitter built from discrete parts, and Python notebooks that make sense of measurements.

- **Now:** Research and Development Staff at IEEE UPI Student Branch (since Aug 2026), working on project feasibility and prototypes.
- **Before:** Media and Publication Staff at Himpunan Mahasiswa Elektro UPI (Aug 2025 to May 2026), where I ran the EGC graphics program and the HME website.
- **Certified:** freeCodeCamp Data Analysis with Python (Jun 2026).

## Featured: Real-Time Water Quality Monitoring

<table>
  <tr>
    <td width="62%" valign="top">
      <p>
        Team project, Dec 2025 to Jan 2026. Analog and digital sensors measure <strong>pH, temperature, and turbidity</strong>. An <strong>ESP32</strong> programmed in <strong>C++</strong> reads them and sends the data over Wi-Fi to <strong>Blynk</strong>. The Blynk dashboard shows live readings and sends an alert when a value leaves its safe range.
      </p>
      <p>
        The system sent readings continuously during testing. Two problems took most of the debugging time: calibrating the pH sensor, and keeping the Wi-Fi connection stable.
      </p>
      <p>
        <a href="https://www.linkedin.com/in/michaeljhoncary/details/projects/">
          <img src="https://img.shields.io/badge/Project_write--up-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="Project write-up on LinkedIn">
        </a>
      </p>
    </td>
    <td width="38%" valign="top">
      <strong>Stack</strong><br><br>
      ESP32 · C++<br>
      pH, temperature, turbidity sensors<br>
      Wi-Fi to Blynk Cloud<br>
      Dashboard and threshold alerts
    </td>
  </tr>
</table>

```mermaid
flowchart LR
    S1[pH sensor] --> MCU
    S2[Temperature sensor] --> MCU
    S3[Turbidity sensor] --> MCU
    MCU[ESP32 · C++] -->|Wi-Fi| B[Blynk Cloud]
    B --> D[Live dashboard]
    B --> A[Alert when out of range]
```

## Hardware and Lab Work

**Mini FM Transmitter** (Oct to Dec 2025). A transmitter built from a transistor, resistors, capacitors, a hand-wound coil, a microphone, and an antenna. An LC oscillator generates the carrier, the microphone signal modulates its frequency, and a transistor stage amplifies it before the antenna. A regular FM radio tuned to the same frequency plays the audio back.

<details>
  <summary><strong>Coursework studies (2024)</strong></summary>
  <br>

  | Study | What I did |
  |---|---|
  | Liquid cooling for electronics | Compared nanofluids and water-glycol mixtures using the Hagen–Poiseuille equation and heat transfer principles |
  | Microplastic separation | Compared sedimentation, flotation, hydrocyclone, and filtration; the best result came from a dual-inlet hydrocyclone at 70 ml/s |
  | Conveyor kinematics | Modeled constant-velocity and constant-acceleration motion of a conveyor with the PhET Moving Man simulation |
</details>

## Code on GitHub

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Resiscolor</h3>
      <p><strong>4-band resistor calculator</strong> · Nov to Dec 2024</p>
      <p>
        Pick the four color bands and the page shows the resistance and tolerance. Built as a team project in Teknik Elektro with plain HTML, CSS, and JavaScript, and deployed on Vercel.
      </p>
      <p>
        <a href="https://github.com/mjhoncaryy/Resiscolor_4_Bands_Calculator_Resistor"><strong>Repository</strong></a>
        &nbsp;·&nbsp;
        <a href="https://resiscolor.vercel.app"><strong>Live demo</strong></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>Data Analysis with Python</h3>
      <p><strong>freeCodeCamp certification projects</strong> · 2026</p>
      <p>
        Four required projects built with Pandas, NumPy, Matplotlib, and Seaborn:
        <a href="https://github.com/mjhoncaryy/Sea_Level_Predictor">Sea Level Predictor</a> (linear regression on EPA sea-level data),
        <a href="https://github.com/mjhoncaryy/Medical_Data_Visualizer">Medical Data Visualizer</a>,
        <a href="https://github.com/mjhoncaryy/Page_View_Time_Series_Visualizer">Page View Time Series Visualizer</a>, and
        <a href="https://github.com/mjhoncaryy/Demographic_Data_Analyzer">Demographic Data Analyzer</a>.
      </p>
    </td>
  </tr>
</table>

<details>
  <summary><strong>Web projects</strong></summary>
  <br>

  | Project | Notes |
  |---|---|
  | [Income–Expense Tracker v1.3](https://github.com/mjhoncaryy/income-expense-tracker-v1.3) | Monorepo with a React + Vite frontend (mock data for now), a backend in progress, and shared Zod schemas |
  | [Campwise](https://github.com/mjhoncaryy/campwise-landing-page) | Frontend-only camping rental site with Next.js 16, React 19, TypeScript, and Tailwind CSS 4 |
</details>

## Tools

<p align="center">
  <img src="https://cdn.simpleicons.org/espressif/E7352C" width="40" title="ESP32" alt="Espressif ESP32">
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg" width="40" title="C++" alt="C++">
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="40" title="Python" alt="Python">
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg" width="40" title="Pandas" alt="Pandas">
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" width="40" title="NumPy" alt="NumPy">
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original.svg" width="40" title="Matplotlib" alt="Matplotlib">
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="40" title="JavaScript" alt="JavaScript">
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" width="40" title="TypeScript" alt="TypeScript">
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" width="40" title="React" alt="React">
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" width="40" title="Git" alt="Git">
</p>

| Area | Tools and skills |
|---|---|
| Embedded and IoT | ESP32, C++, analog and digital sensors, Blynk, sensor calibration |
| Circuits | PCB design, Proteus, discrete RF circuits (LC oscillator, transistor amplifier) |
| Data | Python, Pandas, NumPy, Matplotlib, Seaborn, SQL, regression |
| Web | HTML, CSS, JavaScript, TypeScript, React, Next.js, PHP, Laravel |
| Design | Adobe Photoshop, Adobe Illustrator |

## Next

- Fix the two weak points from the water-quality build: a repeatable pH calibration routine and automatic Wi-Fi reconnection.
- Put the firmware and wiring of my hardware projects on GitHub, not only the write-ups.
- Build prototypes with the R&D team at IEEE UPI Student Branch.

---

<div align="center">
  <p>Interested in embedded systems, IoT, or student research collaboration? Message me on <a href="https://www.linkedin.com/in/michaeljhoncary/">LinkedIn</a>.</p>
</div>
