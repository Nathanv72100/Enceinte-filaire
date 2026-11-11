# USB-C Powered Audio Amplifier 🔊

A custom audio amplifier project designed with EasyEDA. The circuit combines two XPT8871-TCY amplifier modules with a USB-C Power Delivery input stage.

The goal of this project is to create a compact audio amplification board with a dedicated audio input and separate speaker outputs.

---

### 🛠️ Features

- **Dual amplifier modules:** Two XPT8871-TCY modules for audio amplification.
- **USB-C power input:** USB-C connector with a CH224K Power Delivery trigger controller.
- **Audio input:** LCK-PJ-001 audio connector with MIC, Left (L), Right (R), and GND connections.
- **Speaker connections:** Two 2-pin output connectors.
- **Custom PCB:** Designed using EasyEDA.

---

### 🔌 Main Components

| Component | Quantity | Reference |
|---|---:|---|
| XPT8871-TCY amplifier module | 2 | U1, U5 |
| CH224K PD trigger controller | 1 | U2 |
| USB-C connector (GT-USB-7100A) | 1 | USB2 |
| Audio connector (LCK-PJ-001) | 1 | CN1 |
| 2-pin connectors (HX-XH2.54-2PZZ) | 2 | CN2, CN3 |
| 1 µF capacitor | 1 | C1 |
| 10 kΩ resistor | 1 | R1 |
| 1 kΩ resistor | 1 | R6 |
<img width="923" height="266" alt="Capture d&#39;écran 2026-11-11 145519" src="https://github.com/user-attachments/assets/04a9039c-cb52-40f5-9e13-19e80b32c905" />

---

### ⚡ Power & Audio Connections

**Power input**
- USB-C connector for power delivery.
- CH224K controller for USB-C PD negotiation.
- 5V and GND connections are provided on the amplifier modules.

**Audio input**
- MIC
- Left channel (L)
- Right channel (R)
- Ground (GND)

**Audio output**
- Two separate 2-pin speaker connectors.
- Each amplifier module provides OUT+ and OUT- connections.

---

### 📁 Project Files

- `enceinte.json` — EasyEDA schematic.
- `PCB_enceinte.json` — EasyEDA PCB design.

---

### 🧰 Tools Used

- EasyEDA — Schematic and PCB design.
- USB-C Power Delivery — Power input and negotiation.
- XPT8871-TCY — Audio amplifier modules.
<img width="923" height="266" alt="Capture d&#39;écran 2026-11-11 145519" src="https://github.com/user-attachments/assets/c63812ed-d056-46d8-a81c-298e76159c6a" />

---

### ⚠️ Notes

The maximum output power, supported speaker impedance, USB-C PD voltage profiles, and measured audio performance have not yet been documented.

Check the component datasheets and verify the power supply and speaker compatibility before connecting the board.

---

### 👨‍💻 Author

**Nathan** — [GitHub](https://github.com/Nathanv72100/)

