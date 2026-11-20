# Hi, I'm Voòng Đăng Hưng 👋

4th-year IoT Engineering student at PTIT (Ho Chi Minh City Campus) focused on **Embedded/Firmware Development (STM32/FreeRTOS, ESP32)** and **Hardware Integration**.

---

### 🔧 Featured Embedded / Firmware Projects
- **[TripGuard AI](https://github.com/DangHung-rbg/TripGuard_STM32F411_FULL_SYSTEM)** *(Semifinalist, VEDC)*
  - STM32F411 + FreeRTOS multitasking firmware (96 MHz, C, STM32CubeIDE/HAL) with single-owner resource queues.
  - UART DMA RX-to-IDLE (115200 baud, ≤128-byte frames, CRC16, sequence numbers, ACK, 3 retries), 6-state FSM, safe Raspberry Pi shutdown handshake, NEO-M8L GPS, SPI2 slave, PWM servo, EXTI buttons.
- **[CoffeeSorter_AI](https://github.com/DangHung-rbg/CoffeeSorter_AI)** *(Student Scientific Research)*
  - ESP32 (WROOM-32) firmware & hardware for a 3-lane × 2-stage coffee bean sorter (6 active-LOW sensors, 6 MOSFET-driven solenoids with flyback diodes).
  - Per-lane FIFO queues, 115200-baud UART protocol (`COFFEE3`), sensor debounce, pulse-overlap protection, queue expiration timeouts, and fault/watchdog solenoid shutdown.

### 🛠 Core Skills & Tools
- **Languages & MCU/RTOS:** C, STM32F411 (STM32CubeIDE, HAL), FreeRTOS, ESP32
- **Protocols & Peripherals:** UART (DMA RX-to-IDLE, RX Interrupt), SPI (Slave), PWM, EXTI, MOSFET/Solenoid, CRC16/ACK
- **Hardware Debugging:** ST-Link/SWD, Logic Analyzer, Multimeter

---

📫 **Contact:** voongdanghungptit@gmail.com
