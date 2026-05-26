# VOID TUNER • REAL BLE

**Advanced e-scooter tuning interface using Web Bluetooth**

Educational tool for modifying parameters on downgraded/private scooters.

![Void Tuner](https://via.placeholder.com/800x400/0a0a0a/00ff9d?text=VOID+TUNER)

---

## ⚠️ WARNING

**This project is for educational and private property use only.**

- Modifying rental scooters is **illegal** and against their terms of service.
- Tampering with safety systems can result in serious injury or death.
- Use **only** on your own scooters in controlled testing areas.

---

## Features

- Modern Apple-style dark UI with glassmorphism
- Full mobile responsive (works great on phones)
- Real Web Bluetooth connection
- Model selector (Downgraded Xiaomi/Ninebot + NIU support)
- Adjustable speed limit, power, regen, etc.
- Live command logging
- Parallax background effect
- Touch-friendly controls

---

## Supported Models

| Model                        | Status              | Notes |
|-----------------------------|---------------------|-------|
| Downgraded Xiaomi/Ninebot   | Best compatibility  | Highest success rate |
| Standard Ninebot (G30, ES, Max) | Partial          | Works better on older firmware |
| NIU KQi / NQi Series        | Limited             | Mostly read-only in browser |
| Generic BLE scooters        | Experimental        | Depends on protocol |

---

## How to Use

1. Save the code as `void-tuner.html`
2. Open the file on your phone using **Chrome** (Android recommended)
3. Turn on Bluetooth
4. Select your scooter model
5. Tap **"CONNECT VIA BLUETOOTH"**
6. Use the sliders and command buttons

> **Note**: Web Bluetooth is **not supported** on iOS Safari. Use an Android device for real connections.

---

## Technical Details

- Uses **Web Bluetooth API**
- Targets common scooter services (`0xFFE0`, `0xFFF0`)
- Sends raw byte commands (customizable)
- Works best with **downgraded** scooters that have reduced security

---

## Limitations

- Actual success depends on your scooter's BLE firmware version
- NIU scooters have very limited write access via browser
- Some newer scooters use encrypted communication (harder to hack)
- Commands are sent as best-effort (not guaranteed)

---

## Legal & Safety

This tool is provided **as-is** for educational purposes.  
The author is not responsible for any damage, injury, or legal consequences resulting from its use.

**Ride safe. Ride smart.**

---

## Want to go deeper?

- Packet crafting UI
- Firmware flashing simulation
- Specific model presets
- Native Android version (Kotlin)

Just say the word.

---

**Made with chaos by VOID TUNER**
