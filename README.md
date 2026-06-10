<img width="296" height="160" alt="composer (1)" src="https://github.com/user-attachments/assets/f8af7c35-ba58-4f81-88f1-cad8820fdb4d" /># My_Quantum-Projects
# Quantum Bell State Experiment

Welcome to my first quantum computing project! This repository contains the implementation of a **Bell State circuit** (specifically, the $\Phi^+$ state), which is a fundamental example of quantum entanglement.

## 🚀 Overview
This project demonstrates how to create a maximally entangled state between two qubits using **Qiskit**. It includes both the visual circuit design and the Python implementation to run simulations.

## 📂 Project Structure
- `/circuits`: Contains the circuit diagram in SVG format.
- `/code`: Contains the Python code and the Jupyter Notebook used for the experiment.

## 🛠️ Tools & Technologies
- **Qiskit**: The primary SDK for working with quantum computers.
- **Qiskit Aer**: Used for simulating quantum circuits with high precision.
- **IBM Quantum Composer**: Used for visual circuit design and prototyping.

## 🧪 Experiment Results
By running the simulation with 10,000 shots, the results show a clear entanglement between the two qubits, with a near-50/50 probability distribution between states `00` and `11`.

| State | Probability |
| :--- | :--- |
| 00 | ~50% |
| 11 | ~50% |


![Uploading composer <svg xmlns="http://www.w3.org/2000/svg" class="" viewBox="0 0 296.4 160" width="296.4" height="160" aria-label="Circuit visualization" style="display: block; user-select: none;"><defs xmlns="http://www.w3.org/1999/xhtml"><style type="text/css">&lt;!--/*--&gt;&lt;![CDATA[/*&gt;&lt;!--*/

  /* from https://fonts.googleapis.com/css2?family=IBM+Plex+Sans&amp;display=swap */
  @font-face {
    font-family: 'IBM Plex Sans';
    font-style: normal;
    font-weight: 400;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/ibmplexsans/v14/zYXgKVElMYYaJe8bpLHnCwDKhdHeFaxOedc.woff2) format('woff2');
  }

  /* from https://fonts.googleapis.com/css2?family=IBM+Plex+Mono&amp;display=swap */
  @font-face {
    font-family: 'IBM Plex Mono';
    font-style: normal;
    font-weight: 400;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/ibmplexmono/v12/-F63fjptAgt5VM-kVkqdyU8n1i8q131nj-o.woff2) format('woff2');
  }

/*]]&gt;*/--&gt;</style></defs><rect x="0" y="0" width="296.4" height="160" style="fill: rgb(33, 39, 42);"/><g><g transform="translate(20, 0)"><g><g><text x="38.4" y="36" dy=".3em" style="fill: rgb(135, 141, 150); font-family: &quot;IBM Plex Mono&quot;, monospace; font-weight: 400; text-anchor: end; font-size: 14px;"><tspan>q[0]</tspan></text><text x="38.4" y="76" dy=".3em" style="fill: rgb(135, 141, 150); font-family: &quot;IBM Plex Mono&quot;, monospace; font-weight: 400; text-anchor: end; font-size: 14px;"><tspan>q[1]</tspan></text></g><g><text x="38.4" y="116" dy=".3em" style="fill: rgb(135, 141, 150); font-family: &quot;IBM Plex Mono&quot;, monospace; font-weight: 400; text-anchor: end; font-size: 14px;">c4</text></g></g></g><g><g><line x1="68.4" x2="276.4" y1="36" y2="36" style="fill: none; stroke: rgb(77, 83, 88); stroke-width: 1; stroke-linecap: round;"/><line x1="68.4" x2="276.4" y1="76" y2="76" style="fill: none; stroke: rgb(77, 83, 88); stroke-width: 1; stroke-linecap: round;"/></g><line x1="68.4" x2="276.4" y1="114" y2="114" style="fill: none; stroke: rgb(77, 83, 88); stroke-width: 1; stroke-linecap: round;"/><line x1="68.4" x2="276.4" y1="118" y2="118" style="fill: none; stroke: rgb(77, 83, 88); stroke-width: 1; stroke-linecap: round;"/></g><g><rect x="76.4" y="60" width="32" height="32" style="fill: rgb(250, 77, 86); stroke-width: 0; stroke: transparent; paint-order: stroke;"/><text x="92.4" y="76" dy=".3em" style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px; font-style: normal; fill: rgb(18, 22, 25); font-weight: 400; text-anchor: middle;">H</text></g><line x1="132.4" y1="36" x2="132.4" y2="76" style="stroke-width: 1; stroke: rgb(69, 137, 255);"/><circle r="4" cx="132.4" cy="76" style="fill: rgb(69, 137, 255);"/><g transform="translate(132.4, 36)"><g><circle cx="0" cy="0" r="16" style="fill: rgb(69, 137, 255); stroke-width: 0; stroke: transparent; paint-order: stroke;"/><line x1="0" y1="-8" x2="0" y2="8" style="stroke-width: 1.25; stroke: rgb(18, 22, 25);"/><line x1="8" y1="0" x2="-8" y2="0" style="stroke-width: 1.25; stroke: rgb(18, 22, 25);"/></g></g><g transform="translate(172.4, 36)"><line x1="0" y1="-16" x2="0" y2="-2" style="stroke-width: 1; stroke: rgb(242, 244, 248);"/><line x1="0" y1="2" x2="0" y2="16" style="stroke-width: 1; stroke: rgb(242, 244, 248);"/></g><g transform="translate(172.4, 76)"><line x1="0" y1="-16" x2="0" y2="-2" style="stroke-width: 1; stroke: rgb(242, 244, 248);"/><line x1="0" y1="2" x2="0" y2="16" style="stroke-width: 1; stroke: rgb(242, 244, 248);"/></g><g transform="translate(196.4, 0)"><line x1="16" y1="36" x2="16" y2="116" style="stroke-width: 1.5; stroke: rgb(141, 141, 141); stroke-dasharray: 3;"/><g transform="translate(16, 118)"><path d="M0,0 L8,0 L4,8 z" fill="#8d8d8d" transform="translate(-4, -8)"/></g><text x="24" y="104" dy=".3em" style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 12px; fill: rgb(242, 244, 248); font-weight: 700; text-anchor: middle;">0</text><g transform="translate(0, 20)"><rect x="0" y="0" width="32" height="32" style="fill: rgb(162, 169, 176); stroke-width: 0; stroke: transparent; paint-order: stroke;"/><path d="M25.2941 11.584H22.7981L25.2301 8.008V7H21.6141V8H23.9101L21.4861 11.576V12.584H25.2941V11.584ZM15.5662 23.4664C15.5662 24.0836 15.0658 24.584 14.4485 24.584C13.8313 24.584 13.3309 24.0836 13.3309 23.4664C13.3309 22.8621 13.8104 22.3699 14.4096 22.3494L17.1775 17.9208C16.3359 17.5757 15.4144 17.3855 14.4485 17.3855C10.4729 17.3855 7.25 20.6084 7.25 24.584H6C6 19.918 9.78254 16.1355 14.4485 16.1355C15.658 16.1355 16.8081 16.3896 17.8483 16.8474L19.5068 14.1939L20.5668 14.8564L18.9545 17.4361C21.3236 18.9327 22.8971 21.5746 22.8971 24.584H21.6471C21.6471 22.0216 20.3082 19.7719 18.2919 18.4962L15.4698 23.0116C15.5317 23.1505 15.5662 23.3044 15.5662 23.4664Z" fill="#121619"/></g></g><g transform="translate(236.4, 0)"><line x1="16" y1="76" x2="16" y2="116" style="stroke-width: 1.5; stroke: rgb(141, 141, 141); stroke-dasharray: 3;"/><g transform="translate(16, 118)"><path d="M0,0 L8,0 L4,8 z" fill="#8d8d8d" transform="translate(-4, -8)"/></g><text x="24" y="104" dy=".3em" style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 12px; fill: rgb(242, 244, 248); font-weight: 700; text-anchor: middle;">1</text><g transform="translate(0, 60)"><rect x="0" y="0" width="32" height="32" style="fill: rgb(162, 169, 176); stroke-width: 0; stroke: transparent; paint-order: stroke;"/><path d="M25.2941 11.584H22.7981L25.2301 8.008V7H21.6141V8H23.9101L21.4861 11.576V12.584H25.2941V11.584ZM15.5662 23.4664C15.5662 24.0836 15.0658 24.584 14.4485 24.584C13.8313 24.584 13.3309 24.0836 13.3309 23.4664C13.3309 22.8621 13.8104 22.3699 14.4096 22.3494L17.1775 17.9208C16.3359 17.5757 15.4144 17.3855 14.4485 17.3855C10.4729 17.3855 7.25 20.6084 7.25 24.584H6C6 19.918 9.78254 16.1355 14.4485 16.1355C15.658 16.1355 16.8081 16.3896 17.8483 16.8474L19.5068 14.1939L20.5668 14.8564L18.9545 17.4361C21.3236 18.9327 22.8971 21.5746 22.8971 24.584H21.6471C21.6471 22.0216 20.3082 19.7719 18.2919 18.4962L15.4698 23.0116C15.5317 23.1505 15.5662 23.3044 15.5662 23.4664Z" fill="#121619"/></g></g></g></svg>(1).svg…]()

<img width="550" height="411" alt="Capture" src="https://github.com/user-attachments/assets/808ff8e9-e6fa-4998-8ff1-878edfcf9c55" />
