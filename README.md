Thejashrii Bathulaa — Embedded Firmware Engineer

Embedded Firmware Engineer with nearly 2 years of experience designing, debugging, and deploying production firmware in Embedded C / C++ for ESP32 (ESP-IDF) industrial IoT products using FreeRTOS.

Based in Hyderabad, Telangana | Open to Embedded Firmware / RTOS roles

Technical Expertise

Languages: Embedded C, C++, Python.

Platforms & MCUs: ESP32 (ESP-IDF, dual-core Xtensa), ARM7 (LPC2129),STM32.

RTOS & Concurrency: FreeRTOS (tasks, queues, mutexes, semaphores, event groups, task notifications)

Protocols & Buses: Modbus (RTU / TCP / ASCII), CAN, MQTT (TLS), RS-485, UART (circular ring buffers, DMA), SPI, I2C

Firmware Concepts: Dual-partition OTA & rollback, flash/NVS partitioning, ISRs, memory-mapped I/O, watchdog timers

Debug & Toolchain: Logic Analyzer, DSO, ST-Link, JTAG/SWD, GDB, Wireshark, STM32CubeIDE, Keil uVision, VS Code, Git

Experience & Key Projects

1. Industrial Multi-Protocol IoT Gateways (Production Firmware)

Developed dual-core ESP-IDF + FreeRTOS firmware for concurrent sensor acquisition and cloud telemetry with NVS configuration caching.

Implemented a fail-safe dual-partition (ota_0 / ota_1 / otadata) OTA update pipeline with cryptographic verification and watchdog-triggered rollback.

Built a Modbus RTU/TCP-to-MQTT bridge converting PLC register data into JSON payloads with zero hardware changes.

Wrote interrupt-driven UART and RS-485 drivers with circular ring buffers and DMA for loss-free high-baud capture.


2. Multi-Node Vehicle Control over CAN (ARM7 / LPC2129)

Implemented a distributed ECU network on a CAN bus with custom bit timing, hardware acceptance filters, and prioritized arbitration for speed alerts, turn indicators, and reverse proximity sensing.

Stack: Embedded C, CAN, LPC2129, Keil uVision

3. Vehicle Accident Impact & Emergency Alert System (ECIL Internship)

Built bare-metal firmware interfacing a 3-axis accelerometer to detect impact thresholds, log GPS coordinates, and transmit automated GSM emergency alerts.

Stack: Embedded C, GPS/GSM interfacing

Public Code Repositories

CortexCraftt — Custom algorithmic logic and embedded C practice modules.

Contact

Email: bathulaathejashrii@gmail.com

