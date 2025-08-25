
# Racer: An Educational Bot

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Purpose: Educational](https://img.shields.io/badge/Purpose-Educational%20Use%20Only-yellow.svg)
![Status: Non-Functional Exploit](https://img.shields.io/badge/Status-Non--Functional%20Exploit-red.svg)

This project is a **de-weaponized, educational tool** designed to demonstrate a common web security vulnerability: the bypass of simple image-based CAPTCHAs using Optical Character Recognition (OCR). The bot is fully featured for racing on TypeRacer but is **intentionally designed to fail the anti-cheat "Typing Challenge."**

The goal is to provide a safe, hands-on learning experience for developers, students like me, without providing a tool that can be used for actual cheating.

---

### The Vulnerability Explained: Image CAPTCHAs vs. OCR

Many systems rely on showing users an image of distorted text to prove they are human. The assumption is that computers cannot "read" text inside an image.

This assumption is no longer safe. Modern, open-source OCR libraries like **Tesseract.js** can be integrated directly into browser scripts. With minimal image pre-processing, these libraries can achieve high accuracy in converting image text back into character strings, allowing a bot to programmatically solve the challenge.

This project demonstrates this entire process, but stops short of submitting the correct answer, ensuring it remains an educational tool.

### Demonstration

This video shows the bot in action: it performs a race at a configured speed, encounters the "Typing Challenge," and then visibly fails the check in a controlled manner.



https://github.com/user-attachments/assets/b39ea5a7-16a6-4a3a-8cb5-433f2c7d37b6


https://github.com/user-attachments/assets/31b19b71-5ed6-46c2-b0ca-18f3a5498808


---

## ⚠️ Ethical Disclaimer & Terms of Service

This project is for learning and responsible disclosure. Using automated tools to gain an unfair advantage on TypeRacer is **strictly against their Terms of Service.**

> **From the TypeRacer Terms of Service (Section 2. Cheating):**
>
> Dishonest competition between players will not be tolerated. You shall not:
> - cheat during gameplay or carry out any action to artificially enhance your typing speed or other statistics
> - use any third-party software to modify TypeRacer to change gameplay, including, but not limited to cheats and/or hacks;

**This project and its author do not condone cheating.** By using this code, you agree that you will not modify it to create a functional cheat and will only use it for educational purposes on your own accounts. Any consequences of violating TypeRacer's ToS are your own responsibility.

---

## Features

- **WPM & Accuracy Control:** Configure the bot's speed and precision to simulate different typing styles.
- **Human-like Behavior:** Simulates mistakes and corrections, making its typing pattern more realistic.
- **Intelligent Pause/Resume:** Stop the bot, type manually, and the bot can resume from where you left off.
- **Full UI Control:** A clean, draggable UI to manage the bot's settings and state.
- **(Non-Functional) CAPTCHA Bypass:** Demonstrates the full logic of detecting and reading the CAPTCHA, but intentionally fails to solve it.

---

## Getting Started

### Prerequisites

You need a userscript manager browser extension.
- [**Tampermonkey**](https://www.tampermonkey.net/) (Recommended for Chrome, Firefox, Edge, Safari)

### Installation

1.  Make sure you have one of the managers above installed.
2.  Click here to install the script: [DOWNLOAD](https://greasyfork.org/en/scripts/547245-typeracer-racer-v3-4)
3.  Once you installed it, open your userscript manager and make sure the script is enabled.
---

## How to Use

1.  Navigate to [https://play.typeracer.com/](https://play.typeracer.com/).
2.  Join a race. The bot's UI will appear in the bottom-right corner.
3.  Adjust the **WPM** and **Accuracy** sliders to your desired settings.
4.  Click **"Start"** to activate the bot. It will wait for the race to begin and then start typing.
5.  Click **"Stop"** at any time to pause the bot.
6.  Click **"Clear"** to instantly stop all actions and reset the bot for a new race.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
