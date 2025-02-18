# Phishing reCAPTCHA – Educational Simulation

**Author:** John Hammond  
**Date:** September 13, 2024

---

## Summary

This document explains an educational simulation of a phishing lure that mimics a reCAPTCHA interface. The simulation employs a copy–paste mechanism designed to trick users into executing a command. **This project is strictly for educational purposes only.**

---

## Background

In real-world phishing scenarios, attackers have used the guise of "Verify you are human" to instruct users to:
- Press a specific key combination to open a dialog (e.g., "Run" on Windows).
- Paste a command that was automatically copied to their clipboard.
- Execute the command by pressing Enter.

Though simplistic in design, this approach has been effective in certain phishing campaigns.

*Reference image:*  
`https://github.com/user-attachments/assets/56be51b9-e58d-40e9-bdb1-54bcc11d4180`

---

## Features Overview

### 1. Realistic Interface Simulation
- **Authentic Appearance:**  
  The simulated interface mimics the look of a genuine reCAPTCHA form, featuring a checkbox, a loading spinner, and a verification prompt.

### 2. Sequential Challenge Presentation
- **Fixed Order:**  
  Instead of random selection, challenges are presented sequentially. After a series of image-based grid challenges, the simulation transitions to a fallback challenge.

### 3. Preloaded Visual Assets
- **Optimized Experience:**  
  All images used in the simulation are preloaded during initialization, ensuring that users experience smooth transitions without delays.

### 4. Interactive Grid Challenge
- **Grid Verification:**  
  The simulation divides a preloaded image into a 4×4 grid. Users are prompted to select the correct cells (with the correct ones determined randomly for demonstration). Incorrect selections cause the simulation to advance to the next challenge.

### 5. Fallback Challenge with Auto-Copy
- **Enhanced Instructions:**  
  In the fallback challenge, detailed instructions are displayed using increased margins and larger text for clarity.
- **Automatic Clipboard Copy:**  
  As soon as the fallback challenge is presented, the following text is automatically copied to the clipboard:
✅ "I am not a robot - reCAPTCHA Verification ID: 146820"

### 6. Dynamic Button Behavior
- **Interactive Controls:**  
The "Verify" button remains disabled until the user interacts with the simulation. Upon successful verification, a visual cue is given by changing the checkbox color to green.

---

## How to Run

Since this is a single-file simulation for educational demonstration, simply open the file with your web browser. (Note: Do not expect server-specific features like Python server integration in this simulation.)

---

## Important Considerations

- **Educational Use Only:**  
This simulation is intended solely for research and educational purposes. It demonstrates social engineering techniques and phishing lure mechanics in a controlled environment.

- **Legal and Ethical Use:**  
The techniques showcased here must not be used for any unauthorized or malicious activities. Always adhere to legal guidelines and ethical practices.

- **Further Customization:**  
The simulation is modular and designed to be easily modified. You may adjust the grid challenge parameters, fallback content, or visual styling to suit your educational needs.

---

## Final Thoughts

This simulation provides insight into the mechanics behind phishing lures that impersonate trusted interfaces like reCAPTCHA. The goal is to educate users about potential social engineering attacks and to foster better cybersecurity awareness.

Stay informed, stay safe, and use this knowledge responsibly!

---

Happy learning!
