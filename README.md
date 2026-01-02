# Cell430  
**Open LTE Modem Plug-In Board with MSP430F5529**

Cell430 is an **open, engineer-built LTE modem plug-in board** designed for low-power IoT, remote monitoring, and industrial embedded systems. At its core is a TI **MSP430F5529 MCU**, responsible for modem control, power sequencing, and application logic.

The board features a **plug-in LTE modem connector designed for Airgain LTE modems**, providing a clean and well-defined electrical and mechanical interface. While optimized for Airgain modules, the design philosophy emphasizes transparency and control rather than black-box integration.

---

## Why This Project Exists

Many LTE IoT solutions hide critical behavior behind closed firmware, cloud dependencies, or fragile reference designs. Cell430 was created to:

- Give engineers **full control** over LTE modem behavior
- Enable **long-term, unattended deployments**
- Provide a **clean, understandable hardware + firmware stack**
- Serve as a reusable LTE building block for custom systems

If you want to know exactly what your cellular hardware is doing—and be able to change it—this project is for you.

---

## Key Features

- **Onboard MSP430F5529 MCU**
  - Low-power operation
  - USB, UART, SPI, I²C support
- **Airgain LTE Modem Plug-In Interface**
  - Connector and pinout designed for Airgain LTE modems
  - Explicit control of modem power, reset, and status signals
  - Clear separation between MCU and modem power domains
- **Standalone or Host-Controlled Operation**
  - Can act as a self-contained LTE node
  - Or as a cellular interface for an external host system
- **Industrial-Oriented Design**
  - Explicit power sequencing
  - Watchdog-friendly architecture
  - Designed for unattended field deployments
- **Open Hardware / Open Firmware**
  - Schematics, layout, and firmware developed in the open

---

## Repository Structure

/IoT_Dev_v0.00
├── schematics
├── pcb

/firmware
├── msp430
└── modem_control

/docs/UG
├── MSP Debuggers User's Guide.pdf
├── MSP430F5529 LaunchPad Development Kit User's Guide and Sch.pdf
└── 
