# AirDot

AirDot is an open-source, low-cost wireless Morse code communication device designed to make radio communication more accessible to makers, students, and hobbyists.

Using low-power ISM-band radio modules, AirDot allows users to experiment with real radio-frequency communication and learn the fundamentals of wireless technology without requiring an amateur radio license when operated within applicable regulations.

AirDot combines the simplicity of traditional Morse code with modern electronics, creating a hands-on platform for exploring radio, embedded systems, and digital communication.

---

## Project Goals

AirDot was created with the goal of making radio communication approachable and interactive.

Many modern communication systems hide the technology behind layers of software and infrastructure. AirDot takes a different approach by allowing users to directly interact with a radio signal, send messages, and understand how information travels through the air.

The project aims to:

- Encourage interest in electronics and radio technology
- Provide a hands-on introduction to Morse code
- Teach the basics of wireless communication
- Inspire people to explore amateur radio and RF engineering
- Create an accessible platform for experimentation

---

## Features

Current and planned features include:

- Low-cost ISM-band radio communication
- Morse code transmission and reception
- Open-source hardware and software
- Arduino-compatible development
- Portable battery-powered operation
- Real-time communication between AirDot devices
- Optional audio output for audible Morse code
- Expandable display and decoding features

---

## How It Works

A basic AirDot system consists of:

```
Morse Key
    |
    v
Microcontroller
    |
    v
Radio Module
    |
    v
Wireless Transmission
    |
    v
Receiving AirDot
    |
    v
Audio / Display Output
```

The device converts Morse code input into radio transmissions. A receiving AirDot can decode the signal and reproduce the message through audio output or a display.

---

## Hardware

AirDot is designed around low-cost, widely available components.

Current prototype hardware:

- Arduino-compatible microcontroller platform
- RFM69 433 MHz ISM-band radio module
- Morse key input
- Optional speaker output
- Optional display interface

Future hardware revisions may include:

- Custom PCB designs
- Integrated microcontroller
- Battery management
- Built-in display
- Improved antenna systems
- Rugged enclosures

---

## Software

The AirDot firmware is designed to be simple, understandable, and easy to modify.

Planned software features:

- Morse code encoding
- Morse code decoding
- Radio packet handling
- Signal status information
- User interface support
- Device-to-device communication

---

## Project Status

AirDot is currently in the prototype stage.

Completed:

- [x] Project concept created
- [x] GitHub repository created
- [x] Initial Arduino communication testing
- [x] Initial RF module testing
- [x] Hardware design started

In progress:

- [ ] First working radio communication
- [ ] Morse transmission
- [ ] Morse reception
- [ ] Custom PCB design

Future:

- [ ] Portable AirDot units
- [ ] Display-based decoding
- [ ] Educational demonstration version
- [ ] Open Sauce exhibit prototype

---

## Repository Structure

```
AirDot/
├── Hardware/
│   └── AirDot_RevA/
│
├── Firmware/
│   └── Arduino/
│
├── Documentation/
│
├── Releases/
│
├── README.md
├── CHANGELOG.md
└── LICENSE
```

---

## Contributing

Contributions, ideas, and improvements are welcome.

If you would like to contribute:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

Please keep contributions focused on improving the accessibility, reliability, and educational value of AirDot.

---

## Attribution

If you use, modify, or build upon AirDot, please provide credit to:

**Dingus Tech Amateur Radio Solutions**  
**AirDot Project**

---

## License

AirDot is open source.

See the `LICENSE` file for complete licensing information.

---

## Contact

Project organization:

**Dingus Tech Amateur Radio Solutions**

Project:

**AirDot**
