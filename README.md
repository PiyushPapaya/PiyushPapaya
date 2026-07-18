<div align="center">

<img src="./header.svg" alt="Piyush Nagpal — hardware meets machine learning, running on the chip itself" width="100%">

<br><br>

<a href="https://www.linkedin.com/in/piyush-nagpal-a0b2761b4/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://instagram.com/YOUR_INSTAGRAM"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
<a href="https://your-workbench-url.dev"><img src="https://img.shields.io/badge/The_Workbench-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Website"></a>
<a href="mailto:nagpal.2352@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://discord.com/users/lil.papayaa"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
<a href="https://www.reddit.com/user/Suitable_Fix6669/"><img src="https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white" alt="Reddit"></a>

</div>

---

## What I'm after

There are two sides to what I do. On the software side I build, code and train ML models and push them for better accuracy. On the hardware side I build with microcontrollers and sensors. The thing I keep coming back to is putting those two together: running a trained model directly on a microcontroller so a small, cheap chip can read a sensor stream and work out what it means on its own, with no cloud and no phone attached. Get that right and it drops into almost any piece of electronics.

Outside of that goal I just like poking at both worlds. On the hardware side I'll pick up a component I've never used, run it until I find where it breaks, then wire a few of them into something of my own. Sometimes that means rebuilding a device that already exists, but as my own system from scratch. On the software side I keep up with where AI is heading and pay close attention to the startup side of it.

---

## Things I've built

Roughly oldest to newest, so the arc shows.

**IC Calculator.** My first real build. A working calculator from two ICs (a binary counter and an impulse/clock generator), wired together by hand.
&nbsp;&nbsp;![Digital Logic](https://img.shields.io/badge/Digital_Logic-1f6f78?style=flat-square) ![74xx ICs](https://img.shields.io/badge/74xx_ICs-1f6f78?style=flat-square)

**DIY Flipper Zero.** A CC1101 radio, a PN532 NFC reader and a stronger IR stage on one board. I used it to read our school cafeteria cards, clone a few keys and drive the building's IR devices (all with permission).
&nbsp;&nbsp;![CC1101](https://img.shields.io/badge/CC1101-1f6f78?style=flat-square) ![PN532](https://img.shields.io/badge/PN532_NFC-1f6f78?style=flat-square) ![RF](https://img.shields.io/badge/Sub--GHz_RF-1f6f78?style=flat-square) ![IR](https://img.shields.io/badge/IR-1f6f78?style=flat-square)

**Claude Usage Display.** A small physical readout of my live Claude token usage and when the limit resets, because hitting the cap mid-task with no warning is genuinely maddening.
&nbsp;&nbsp;![ESP8266](https://img.shields.io/badge/ESP8266-1f6f78?style=flat-square) ![OLED](https://img.shields.io/badge/OLED-1f6f78?style=flat-square) ![REST API](https://img.shields.io/badge/REST_API-4a5568?style=flat-square)

**Datasheet → Register Map.** Takes a chip's datasheet PDF and turns it into a verified register map plus a working driver. This one leans software/SaaS.
&nbsp;&nbsp;![Python](https://img.shields.io/badge/Python-4a5568?style=flat-square) ![PDF Parsing](https://img.shields.io/badge/PDF_Parsing-4a5568?style=flat-square) ![Codegen](https://img.shields.io/badge/Codegen-4a5568?style=flat-square)

**Gestura** *(capstone)*. A wrist-worn wearable that reads hand gestures from IMU motion data, with the model trained and then run entirely on the microcontroller. The clearest version of the thing I'm after.
&nbsp;&nbsp;![ESP32](https://img.shields.io/badge/ESP32-1f6f78?style=flat-square) ![TinyML](https://img.shields.io/badge/TinyML-1f6f78?style=flat-square) ![IMU](https://img.shields.io/badge/IMU-1f6f78?style=flat-square)

**Tiny Tapeout** *(next)*. Taking a small digital design all the way to fabricated silicon.
&nbsp;&nbsp;![Digital Design](https://img.shields.io/badge/Digital_Design-1f6f78?style=flat-square) ![Verilog](https://img.shields.io/badge/Verilog-1f6f78?style=flat-square) ![ASIC](https://img.shields.io/badge/ASIC-1f6f78?style=flat-square)

---

## Stack

The things I actually reach for, not everything I've touched.

**Embedded**
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-FF7F00?style=flat-square&logo=platformio&logoColor=white)

**ML**
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**3D web**
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)

---

## Off the screen

Licensed table tennis coach, still training most weeks. Chess, and strength work on the days I'm not soldering.

<br>

<div align="center">
<sub>Currently building <b>Gestura</b> and taking my first design to silicon. &nbsp;·&nbsp; Say hi: <a href="mailto:nagpal.2352@gmail.com">nagpal.2352@gmail.com</a></sub>
</div>

<!-- Optional live GitHub stats. The shared server rate-limits and shows a broken image (that's what you saw),
     so it's left out on purpose. To add reliable stats, self-host the widget and drop the card in here:
     https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own -->
