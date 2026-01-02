# Cell430  
**Open LTE Modem Plug-In Board with MSP430F5529**

Cell430 is an **open, engineer-built LTE modem plug-in board** designed for low-power IoT, remote monitoring, and industrial embedded systems. At its core is a TI **MSP430F5529 MCU**, responsible for modem control, power sequencing, and application logic.

This project is intentionally **not a black box**. The goal is to provide a transparent, hackable cellular building block that can survive real-world deployments—not just the lab bench.

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
- **Plug-in LTE modem interface**
  - Modem-agnostic by design
  - Explicit power and reset control
- **Standalone or Host-Controlled Operation**
  - Can act as a self-contained LTE node
  - Or as a cellular interface for an external host
- **Industrial-Oriented Design**
  - Explicit power sequencing
  - Watchdog-friendly architecture
  - Designed for unattended field use
- **Open Hardware / Open Firmware**
  - Schematics, layout, and firmware developed in the open

---

## Repository Structure

