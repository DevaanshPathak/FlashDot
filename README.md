# 🔦 FlashDot — Light-Controlled Morse Code Flasher

**FlashDot** is a simple analog circuit that lets you transmit Morse code using your hand and light. Wave your fingers over an LDR (photoresistor), and an LED blinks in response. It's tactile, visual, and powered by nothing but a transistor and your creativity.

This project was built for Hack Club’s [Solder Program](https://github.com/hackclub/solder)!

---

## ✨ What It Does

FlashDot reacts to light changes — when you cover the photoresistor, it flips on an NPN transistor, causing the LED to light up. With a single finger, you can tap out Morse code, send signals, or just vibe with light.

You can replace the LED with a vibration motor to make a **tactile flasher** too.

---

## 📦 Bill of Materials

| Component         | Quantity | Notes                             |
|------------------|----------|-----------------------------------|
| Photoresistor (LDR - GL5528) | 1 | Senses ambient light            |
| 2N3904 NPN Transistor         | 1 | Main switch                     |
| 220Ω Resistor                 | 1 | LED current limiting            |
| 47kΩ Resistor                 | 1 | Forms voltage divider with LDR |
| 10µF Electrolytic Capacitor   | 1 | Debounces fast flickers         |
| 5mm LED                       | 1 | Light output                    |
| CR2032 Coin Cell + Holder     | 1 | Power source                    |
| PCB / Breadboard              | 1 | Custom-designed PCB             |

---

## 📐 Circuit Design

### 🧠 Schematic
![Schematic](https://hc-cdn.hel1.your-objectstorage.com/s/v3/5575c1a80b1f5b70a031b5f64ae826be50f14af0_schematic.png)

### 🧩 PCB Layout
![PCB](https://hc-cdn.hel1.your-objectstorage.com/s/v3/351ecb2458c5308662ba37b8f6732e3e9ee6896a_pcb.png)

### 🔭 3D View 1
![3D View 1](https://hc-cdn.hel1.your-objectstorage.com/s/v3/cb5ac5b21e113990b0580e8fff5f09fa288346d7_pcb_3d_1.png)

### 🔬 3D View 2
![3D View 2](https://hc-cdn.hel1.your-objectstorage.com/s/v3/1f2cbfb4f6b5305f7c9d8f8a9baf214dab5c307d_pcb_3d_2.png)

> All files live in the `kicad/` and `gerbers/` folders.

---

## 🛠️ Files in This Repo

```

flashdot/
├── kicad/         → KiCad project, schematic, PCB layout
├── gerbers/       → Gerber + drill files (for fabrication)
├── imgs/          → Screenshots: schematic, PCB, 3D views
├── LICENSE        → MIT
└── README.md      → You’re here!

```

---

## 🧪 Testing It

Power the circuit using a coin cell.  
Then:
- ✅ Leave the LDR uncovered → LED stays off
- ✅ Cover the LDR briefly → LED blinks
- ✅ Try long and short covers → Manual Morse code!

---

## 🙋 Slack Username

Devaansh Pathak

U091678RUNB

---

## 🚀 Why I Made This

I wanted to make something dead simple, no microcontroller, no code — just light, your hand, and physics. FlashDot is my second analog PCB and my second time using KiCad. I learned about debounce circuits, transistor switching, and footprint alignment.

---

## 📎 License

MIT — remix, learn, and solder your own.

---

## 📣 Bonus Ideas

- Swap LED with motor for silent signaling
- Make it wearable with a coin cell backpack
- Add a potentiometer for adjustable sensitivity

---

Built for [Hack Club Solder](https://github.com/hackclub/solder) 💚