# Phishing reCAPTCHA – Educational Simulation

**Author:** Rubahilang  
**Date:** February 18, 2025

---

## Overview

This document explains an educational simulation of a phishing lure that mimics a reCAPTCHA interface. The simulation leverages a copy–paste mechanism to trick users into executing a command. **This project is for educational purposes only.**

---

## Real-World Inspiration

In actual phishing campaigns, attackers have used the guise **"Verify you are human"** to instruct users to:

1. Press `Win+R` to open the Run dialog.
2. Paste a pre-copied command using `Ctrl+V`.
3. Hit Enter to execute the command.

While simplistic, this method has reportedly been effective in some cases.

**Reference Image:**  
![Verify You Are Human](https://github.com/user-attachments/assets/56be51b9-e58d-40e9-bdb1-54bcc11d4180)

---

## Demo Video

Below is a demo video showcasing the simulation in action:

[![Demo Video](https://img.youtube.com/vi/VIDEO_ID/maxresdefault.jpg)](https://github.com/rubahilang/recaptcha-phish-v2/blob/main/video/demo.mp4)

---

## Features Overview

### 1. Realistic Interface Simulation
- **Authentic Look & Feel:**  
  The simulation replicates a genuine reCAPTCHA interface with a checkbox, spinner, and verification prompt.

### 2. Sequential Challenge Presentation
- **Ordered Challenges:**  
  Challenges are presented in a fixed order. After several image grid challenges, a fallback challenge with detailed instructions appears.

### 3. Preloaded Visual Assets
- **Smooth Performance:**  
  All images are preloaded during initialization to ensure a smooth user experience without delays.

### 4. Interactive Grid Challenge
- **Grid Verification:**  
  The simulation divides a preloaded image into a 4×4 grid. Users must select the correct cells (randomly determined for demonstration). Incorrect selections cause the simulation to automatically move to the next challenge.

### 5. Fallback Challenge with Auto-Copy
- **Enhanced Instructions:**  
  The fallback challenge displays detailed instructions with larger text and ample margins for clarity.
- **Automatic Clipboard Copy:**  
  When the fallback challenge is shown, the following text is automatically copied to the clipboard:
  
✅ "I am not a robot - reCAPTCHA Verification ID: 146820"

### 6. Dynamic Button Behavior
- **Interactive Controls:**  
The "Verify" button remains disabled until the user interacts with the simulation. Upon successful verification, a visual cue is provided by changing the checkbox to green.

---

## How to Run

Simply open this file with your browser. This simulation is entirely self-contained and designed for educational demonstration.

---

## Important Considerations

- **Educational Use Only:**  
This simulation is intended solely for research and educational purposes. Do not use these techniques for any unauthorized or malicious activities.

- **Legal and Ethical Use:**  
Always adhere to legal guidelines and ethical practices when studying social engineering and phishing techniques.

- **Customization:**  
The simulation is modular and can be modified to suit your educational needs. Adjust the grid challenge parameters, fallback content, or styling as desired.

---

## Final Thoughts

This simulation provides insight into the mechanics behind phishing lures that mimic trusted interfaces like reCAPTCHA. The goal is to educate users about social engineering attacks and enhance cybersecurity awareness.

Stay informed, stay safe, and use this knowledge responsibly!

---

Happy learning!
