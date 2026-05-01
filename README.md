<div align="center">

# 🎭 Phishing Awareness Prank
### "Free Data" Scam Simulator

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:ff0000&height=150&section=header&text=Stay%20Safe%20Online&fontSize=40&fontColor=ffffff&animation=fadeIn" width="100%" alt="Header Banner" />

*An interactive, highly realistic frontend simulation designed to educate users about the dangers of online phishing scams.*

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Security_Awareness-brightgreen?style=for-the-badge&logo=spring-security&logoColor=white" alt="Security Awareness" />
</p>

<h3>
  <a href="https://vesak-dansala.vercel.app/">🔴 TRY THE LIVE DEMO HERE 🔴</a>
</h3>

[Explore The Project](#-about-the-project) • [How It Works](#-how-the-simulation-works) • [Key Features](#-key-features) • [Privacy](#-privacy--safety)

</div>

---

## 🧐 About the Project

Social media platforms are frequently flooded with malicious links promising **"Free Data," "Lottery Wins,"** or **"Exclusive Gifts."** Unfortunately, many innocent users fall victim to these phishing attacks, resulting in compromised personal data, lost social media accounts, and financial theft.

> **Our Mission:** To fight back through education. 

By mimicking the exact flow of a real-world phishing scam, this simulator tricks the user into believing they are about to receive `50GB of free data`. However, instead of stealing their information, it delivers a harmless but impactful "scare" (a simulated device hack), followed by a crucial lesson on cybersecurity.

> 🚨 **Experience it yourself:** [https://vesak-dansala.vercel.app/](https://vesak-dansala.vercel.app/) *(Don't worry, it's 100% safe!)*

---

## 🚀 How the Simulation Works (The User Journey)

The psychological flow of this application is meticulously designed to mirror real malicious campaigns. Here is what the user experiences:

<details>
<summary><b>1. The Bait 🎣</b> (Click to expand)</summary>
<br>
The user lands on a clean, legitimate-looking promotional page. It asks for simple, seemingly harmless information: Name, Age, and Phone Number. <br><br>
<i>💡 Tech Note: The app dynamically detects Sri Lankan mobile networks (Dialog, Mobitel, etc.) in real-time as the user types their number, increasing the illusion of authenticity.</i>
</details>

<details>
<summary><b>2. The Viral Factor 🦠</b></summary>
<br>
To claim the reward, the user is instructed to share the link with 5 WhatsApp groups or 15 contacts. This replicates the viral mechanics of real scams that spread like wildfire.
</details>

<details>
<summary><b>3. The Hook & The Trap 🎁</b></summary>
<br>
A realistic loading bar simulates a "Verification Process." Upon completion, a beautifully animated 3D Gift Box appears. The user is instructed to tap it to claim their prize.
</details>

<details>
<summary><b>4. The Shock (The Prank Sequence) 💀</b></summary>
<br>
Once the gift box explodes, the trap springs. The site automatically enters fullscreen mode and simulates a catastrophic security breach:<br>
<ul>
  <li>🟢 <b>Matrix Rain:</b> A cinematic digital rain effect takes over the screen.</li>
  <li>💻 <b>Fake Terminal Logs:</b> Rapidly typing console logs display terrifying messages like <code>"Storage bypass successful"</code> and <code>"Disk Full! Deleting internal cache..."</code></li>
  <li>🔋 <b>Battery Drain:</b> A fake battery indicator rapidly drops to 1%.</li>
  <li>📍 <b>Data Exposure:</b> To maximize the psychological impact, the site fetches and displays the user's <b>real IP address, device type, browser, and timezone</b> using public APIs.</li>
</ul>
</details>

<details>
<summary><b>5. The Awareness Phase (The Lesson) 🎓</b></summary>
<br>
After the adrenaline rush, the screen transitions to an educational dashboard. It presents:<br>
<ul>
  <li><b>The Hacker's Receipt:</b> A breakdown of what this "free" data would actually cost in real life (e.g., Bank Accounts: -Rs. 250,000, Private Photos: Leaked).</li>
  <li><b>The Vow:</b> To "recover" their device, the user must check a box promising they will never click suspicious links or chase "free" internet scams again.</li>
</ul>
</details>

---

## ✨ Key Features

| 🛠️ Feature | 📝 Description |
| :--- | :--- |
| **Dynamic Network Detection** | Instantly identifies telecom providers based on input prefixes. |
| **Custom Animations** | Interactive `CSS3` 3D gift box with explosion and confetti effects. |
| **Realistic Hack UI** | `HTML5 Canvas`-based Matrix digital rain and dynamic terminal logs. |
| **Live Device Fingerprinting** | Uses `ipify` and `User-Agent` parsing to display real user data for shock value. |
| **Zero Dependencies** | Built entirely with `Vanilla JS`. No heavy frameworks or external libraries. |

---

## 💻 Technology Stack

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="50" alt="HTML5" title="HTML5" />
  <img width="20" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="50" alt="CSS3" title="CSS3" />
  <img width="20" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="50" alt="JavaScript" title="JavaScript" />
</div>

<br>

- **Structure:** `HTML5` (Semantic layout and structuring)
- **Styling & Animations:** `CSS3` (Flexbox, Keyframes, CSS Transitions)
- **Logic & DOM Manipulation:** `Vanilla JavaScript` (ES6+)
- **Graphics:** Inline `SVG` and `HTML5 Canvas`

---

## 🗄️ Privacy & Safety: "Is this safe?"

### ✅ YES. This project is 100% safe and secure.

* 🚫 **No Backend / No Database:** There is no server receiving or storing data. Everything typed into the input fields is processed locally within the browser and immediately discarded.
* 🛡️ **No Malware:** It is impossible for this website to delete files, hack a phone, or access a photo gallery. It relies entirely on visual tricks and JavaScript animations.
* 👁️ **Local IP Fetching:** The IP address shown during the prank is fetched by the user's browser for display purposes only. It is **never** logged or sent to the developer.

---

## ⚠️ Disclaimer

> This project was created **strictly for educational purposes, cybersecurity awareness, and harmless pranking**. The developer assumes no responsibility for any misuse, emotional distress, or damage caused by hosting or sharing this application. Always ensure your audience understands it is a prank after the sequence ends.

---

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=FF0000&center=true&vCenter=true&width=435&lines=Think+Before+You+Click.;Stay+Safe+Online." alt="Typing SVG" />

  <br>
  
  **Made with ❤️ by [@idusha-manaka](https://github.com/idusha-manaka)**
</div>
