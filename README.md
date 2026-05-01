<div align="center">
  <h1>🎭 Phishing Awareness Prank: "Free Data" Scam Simulator</h1>
  <p><i>An interactive, highly realistic frontend simulation designed to educate users about the dangers of online phishing scams.</i></p>
  
  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
    <img src="https://img.shields.io/badge/Security-Awareness-brightgreen?style=for-the-badge&logo=security" alt="Security Awareness" />
  </p>
</div>

---

## 📖 Table of Contents
- [About the Project](#-about-the-project)
- [How the Simulation Works](#-how-the-simulation-works)
- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [Privacy & Safety](#-privacy--safety)
- [Disclaimer](#-disclaimer)

---

## 🧐 About the Project

Social media platforms are frequently flooded with malicious links promising "Free Data," "Lottery Wins," or "Exclusive Gifts." Unfortunately, many innocent users fall victim to these phishing attacks, resulting in compromised personal data, lost social media accounts, and financial theft.

**This project was created to fight back through education.** 

By mimicking the exact flow of a real-world phishing scam, this simulator tricks the user into believing they are about to receive 50GB of free data. However, instead of stealing their information, it delivers a harmless but impactful "scare" (a simulated device hack), followed by a crucial lesson on cybersecurity.

---

## 🚀 How the Simulation Works (The User Journey)

The psychological flow of this application is meticulously designed to mirror real malicious campaigns:

### 1. The Bait 🎣
The user lands on a clean, legitimate-looking promotional page. It asks for simple, seemingly harmless information: **Name, Age, and Phone Number**. 
> *Tech Note: The app dynamically detects Sri Lankan mobile networks (Dialog, Mobitel, etc.) in real-time as the user types their number, increasing the illusion of authenticity.*

### 2. The Viral Factor 🦠
To claim the reward, the user is instructed to share the link with 5 WhatsApp groups or 15 contacts. This replicates the viral mechanics of real scams that spread like wildfire.

### 3. The Hook & The Trap 🎁
A realistic loading bar simulates a "Verification Process." Upon completion, a beautifully animated 3D Gift Box appears. The user is instructed to tap it to claim their prize.

### 4. The Shock (The Prank Sequence) 💀
Once the gift box explodes, the trap springs. The site automatically enters fullscreen mode and simulates a catastrophic security breach:
- 🟢 **Matrix Rain:** A cinematic digital rain effect takes over the screen.
- 💻 **Fake Terminal Logs:** Rapidly typing console logs display terrifying messages like `"Storage bypass successful"`, `"Disk Full! Deleting internal cache..."`, and `"Sending gallery photos to WhatsApp groups..."`.
- 🔋 **Battery Drain:** A fake battery indicator rapidly drops to 1%.
- 📍 **Data Exposure:** To maximize the psychological impact, the site fetches and displays the user's **real IP address, device type, browser, and timezone** using public APIs.

### 5. The Awareness Phase (The Lesson) 🎓
After the adrenaline rush, the screen transitions to an educational dashboard. It presents:
- **The Hacker's Receipt:** A breakdown of what this "free" data would actually cost in real life (e.g., Bank Accounts: -Rs. 250,000, Private Photos: Leaked).
- **The Vow:** To "recover" their device, the user must check a box promising they will never click suspicious links or chase "free" internet scams again.

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| **Dynamic Network Detection** | Instantly identifies telecom providers based on input prefixes. |
| **Custom Animations** | Interactive CSS3 3D gift box with explosion and confetti effects. |
| **Realistic Hack UI** | HTML5 Canvas-based Matrix digital rain and dynamic terminal logs. |
| **Live Device Fingerprinting** | Uses `ipify` and `User-Agent` parsing to display real user data for shock value. |
| **Zero Dependencies** | Built entirely with Vanilla JS. No heavy frameworks or libraries. |

---

## 💻 Technology Stack

This is a pure **Frontend Web Application**.

- **Structure:** `HTML5`
- **Styling & Animations:** `CSS3` (Flexbox, Keyframes, CSS Transitions)
- **Logic & DOM Manipulation:** `Vanilla JavaScript` (ES6+)
- **Graphics:** Inline `SVG` and `HTML5 Canvas`

---

## 🗄️ Privacy & Safety: "Is this safe?"

**YES. This project is 100% safe and secure.**

* **No Backend / No Database:** There is no server receiving or storing data. Everything typed into the input fields is processed locally within the browser and immediately discarded.
* **No Malware:** It is impossible for this website to delete files, hack a phone, or access a photo gallery. It relies entirely on visual tricks and JavaScript animations.
* **Local IP Fetching:** The IP address shown during the prank is fetched by the user's browser for display purposes only. It is never logged or sent to the developer.

---

## ⚠️ Disclaimer

> This project was created **strictly for educational purposes, cybersecurity awareness, and harmless pranking**. The developer assumes no responsibility for any misuse, emotional distress, or damage caused by hosting or sharing this application. Always ensure your audience understands it is a prank after the sequence ends.

<div align="center">
  <p><i>Stay Safe Online. Think Before You Click.</i></p>
  <p>Created by <a href="https://github.com/idusha-manaka">@idusha-manaka</a></p>
</div>
