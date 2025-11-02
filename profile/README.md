# MZPico: Storage Cards for Sharp MZ-800

**MZPico** is a set of open-hardware and open-software projects that turn a  
**Raspberry Pi Pico into a universal storage system** for the  
**Sharp MZ-800** retro computer.

No cassette tapes. No original Floppy or Quick Disk needed.  
Just a Raspberry Pi Pico, a small PCB, solder a few pins — and you're ready.

---

## 🚀 Features

- **MZF Program Loader**  
  Load `.mzf` directly into the MZ-800 — instant, no audio cassette required.

- **Floppy Disk Emulator**  
  Mount `.dsk` images and emulate a floppy disk drive.

- **Quick Disk Emulator**  
  Use `.mzq` images *or*  
  **On-the-Fly Quick Disk mode** → a directory on internal Flash or SD behaves as a Quick Disk.

- **RAM Disk Emulator**  
  Applications that expect a RAM disk can use the emulated version seamlessly.

- **Minimal Hardware Required**  
  A Raspberry Pi Pico soldered to a small PCB is enough.  
  Micro SD slot is optional and will be used by firmware if present.

- **Highly Configurable**  
  - One shared firmware for all boards  
  - Editable configuration text file
  - Multiple virtual devices on user-defined ports

---

## 🧰 Hardware Options

| Board | Description | Who it's for |
|--------|-------------|--------------|
| **Frugal Board** | Pico soldered directly to PCB — internal flash used for storage. MicroSD optional. | Anyone wanting simplicity and lowest cost |
| **Deluxe Board** | Adds level shifters, microSD slot, I²S sound card, and optional Pico-W Wi-Fi | Power users / tinkerers |

Both boards use the **same firmware**.

---

## 📂 Repository Structure

| Repository | Purpose |
|------------|---------|
| **[MZPico-firmware](https://github.com/MZPico/MZPico-firmware)** | Firmware + usage documentation |
| [MZPico-800-Frugal-Board](https://github.com/MZPico/MZPico-800-Frugal-Board) | PCB files for the minimal build |
| [MZPico-800-Deluxe-Board](https://github.com/MZPico/MZPico-800-Deluxe-Board) | PCB files for the deluxe build |

> 📄 All build instructions and user documentation live in the  
> 👉 **[MZPico-firmware](https://github.com/MZPico/MZPico-firmware)** repository.
---

## 📖 Documentation / Getting Started

👉 **Start here:**  
➡ Firmware, configuration & how-to guides:  
**https://github.com/MZPico/MZPico-firmware**

PCB designs:

- **Frugal board:** https://github.com/MZPico/MZPico-800-Frugal-Board
- **Deluxe board:** https://github.com/MZPico/MZPico-800-Deluxe-Board

---

## 🧑‍🔧 Who is this for?

- MZ-800 users who want instant software loading
- Retro computing enthusiasts
- DIY hobbyists with basic soldering skills
- Firmware modders and experimenters

If you can solder a Raspberry Pi Pico to a PCB,  
**you can build MZPico.**

---

## ✅ Project Status

- Hardware prototypes: **working**
- Firmware: **actively developed**
- Documentation: **minimal but growing** *(inside firmware repo)*

Contributions are welcome — hardware, firmware, documentation, testing.

---

## 🤝 Contributing

Pull requests, feature ideas, and bug reports are appreciated.  
Please use Issues in the appropriate repository.

---

## 📬 Discussion / Contact

Use GitHub Issues to ask questions or start a discussion.

---

### 🧡 MZPico is open-source hardware and open software.

Retro computing should be accessible — without rare original hardware.
