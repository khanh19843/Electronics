Link: https://learnesp32.com/videos/course-introduction/course-introduction
Link: https://microsacademy.ezycourse.com/course-detail/learnesp32/17870/
###### Module 1 - Introduction
Course introduction
Course Summary and Basic Definitions
Dev Boards

###### Module 2 - Setting up Your Environment
 Introduction to Setting Up Your Environment
 WINDOWS - Installing the ESP-IDF
 UBUNTU - Installing the ESP-IDF
 Installing and Configuring VS Code
 Project Walk Through
 Multiple IDF Versions
##### Module 3 - ESP32 Types
Introduction to ESP32 Types
Comparing ESP32 Types
VSCode ESP32 Target
##### Module 4 - A First Look - Introduction
A First Look
Logging
Delays
Random Number
Blinkey
Keyboard Input
Using IDF Examples
##### Module 5 - Working With C
Working With C - Intro
Structure and Pointer Primer
Function Pointers
##### Module 6 - Headers, Components and Libraries
Referencing C and H Files
Components
External Components
IDF Components Register Library
##### Module 7 - Fundamentals in FreeRTOS
Fundamentals in FreeRTOS - Intro
FreeRTOS Resources
FreeRTOS Tasks
Using the Second Core
FreeRTOS Tasks Decision Tree
Task Notifications Part 1
Task Notifications 2
Mutex - Mutual Exclusion Object
Binary Semaphore
Queue
Event Groups
FreeRTOS Timer
High Resolution Timer
##### Module 8 - Debugging with OpenOCD
> [!NOTE] Note
> The Open On-Chip Debugger (OpenOCD) is an open source software development tool supporting the debugging and programming of embedded applications.

Debugging with OpenOCD
Manual Debugging
OpenOCD Overview
Debug walk-through
Wiring the FT2232
OpenOCD Software Configuration
Introduction to QEMU
##### Module 9 - Configuration and Menuconfig
> [!NOTE] Note
> ESP32 MenuConfig provides a user-friendly way to configure various aspects of an ESP32 project like Wi-Fi settings, serial communication parameters, flash memory allocation, and more without needing to manually edit complex configuration files.

Menuconfig Introduction
Menu Basics
Custom Configuration
Menu Details
##### Module 10 - Understanding Memory
 Understanding Memory - Intro
 SRAM 1 - Understanding RAM Allocation
 SRAM 2 - Dynamic Memory
 SRAM 3 - Stack Memory
 PSRAM
 Flash Partition
##### Module 11 - Storage
Storage - Introduction
Loading Files Directly into Flash
NVS - Simple Data
NVS Custom Partition
NVS Structured Data
Introduction to SPIFFS - Serial Peripheral Interface Flash File System
SPIFFS - Uploading with Flash
SPIFFS - Looping Through Files
SPIFFS - Uploading Data Scripts
SPIFFS - CRUD (Create, Read, Update, Delete)
FAT - Wear Leveling and CRUD
FAT - Read Only
SD Card - SPI (Serial Peripheral Interface)
SD Card - MMC (Multi Media Card)
##### Module 12 - GPIO
GPIO Intro
GPIO Output
GPIO Input
Interrupts
De-Bouncing
Configuring GPIO
Digital to Analogue Conversion - DAC
Analogue to Digital Converter - ADC
LED Control (LEDC) and Pulse Width Modulation (PWM)
Hall-effect Sensor (detect and measure magnetic fields)
Touch Sensor
##### Module 13 - I2C SPI UART
> [!NOTE] Note
> I2C - The I2C bus, or Inter-Integrated Circuit bus, is a serial communication bus that uses two wires to connect devices. It's a standard interface for low-speed communication in embedded systems. SPI - Serial Peripheral Interface - A communication protocol that allows devices to send and receive data over short distances. SPI is used to connect a master device, like a microcontroller, to slave devices, like sensors or SD cards. UART - Universal Asynchronous Receiver/Transmitter - defines a protocol, or set of rules, for exchanging serial data between two devices. UART is very simple and only uses two wires between transmitter and receiver to transmit and receive in both directions. Both ends also have a ground connection

Bus Systems - Intro
Bluetooth Logging JDY-31
UART 1 Basic Echo
UART to PC Communication
UART Queue
i2c - Introduction
i2c LM75A
12c with RTC - Part 1
12c with RTC - Part 2
SPI - Intro
SSD Code
SPI - SSD Wire up
SPI - Wiring up the Display
SPI - Show Display
##### Module 14 - Sleep Modes
> [!NOTE] Note
> In Light-sleep mode, the digital peripherals, most of the RAM, and CPUs are clock-gated and their supply voltage is reduced. Upon exit from Light-sleep, the digital peripherals, RAM, and CPUs resume operation and their internal states are preserved. In Deep-sleep mode, the CPUs, most of the RAM, and all digital peripherals that are clocked from APB_CLK are powered off. The only parts of the chip that remain powered on are: RTC controller ULP coprocessor RTC FAST memory RTC SLOW memory ESP32 Hibernate mode is very similar to deep sleep. The only difference is that in hibernation mode, the chip disables the internal 8 MHz oscillator as well as the ULP-coprocessor, leaving only one RTC timer (on slow clock) and a few RTC GPIOs to wake the chip up.

Sleep Modes - Intro
Sleep Modes - Overview
Light Sleep with Timer
Light Sleep with GPIO
Deep Sleep with Timer
Deep Sleep with EXT0
Deep Sleep with EXT1
Hibernation
##### Module 15 - Internet Connection [IDF 4.X]
Internet Intro
Example Connection
Wi-Fi Scanner
NTP Time
Wi-Fi Connect 1
Wi-Fi Connect 2 event loop
Wi-Fi Connect 3 - init
Wi-Fi Connect 4 - STA
Wi-Fi Connect 5 - Error
Wi-Fi Connect 6 - AP
##### Module 15 - Internet Connection [IDF 5.X]
WiFi Overview
Example Connect
HTTP Client
NTP Client - (Network Time Protocol)
WiFi Scanner
WiFi-Init - 1
WiFi Station - 2
WiFi Error-3
WiFi AP-4
WiFi Disconnection-5
##### Module 16 - Internet REST Client
> [!NOTE] Note
> REST stands for "Representational State Transfer" and is a standardized way of designing web APIs, allowing clients to access data through simple HTTP requests like GET, POST, PUT, and DELETE.

Introduction to REST
Simple GET
Chunking Data
HTTPS
Large JSON
Creating JSON - Send Email
##### Module 17 - Internet Server
Creating a Server
MDNS - Multicast DNS (Domain Name System)
Toggling an LED with POST (Power-On Self-Test)
Introduction to WebSocket
WebSocket Continued
##### Module 18 - Website on Chip
Introduction - Hosting a Website on a Chip
Website Creation and Flashing
Serving a Page
Serving all pages with wildcards
Types of Mime (Multipurpose Internet Mail Extensions)
Developing the React site
##### Module 19 - MQTT
> [!NOTE] Note
> MQTT - Message Queuing Telemetry Transport - is widely used in IoT (Internet of Things) embedded applications, where every sensor is connected to a server, and we have access to control them over the internet. ESP32 is an open-source IoT platform. It is a firmware which runs on ESP32 series of SoCs from Espressif Systems.
Message Queuing Telemetry Transport (MQTT) - Intro
MQTT Test Client
MQTT Setup and Connect
Subscription and Receiving Data
Sending Data
Retain
Last Will
##### Module 20 - ESP-NOW
> [!NOTE] Note
> ESP-NOW is a kind of connectionless Wi-Fi communication protocol that is defined by Espressif. It provides a flexible and low-power data transmission to all interconnected devices. It can also be used as an independent protocol that helps with device provisioning, debugging, and firmware upgrades.

ESP-NOW Intro
Basic ESP-NOW
ESP-Now Automatic Registration
ESP-NOW Push Button
ESP-NOW - Encrypted Messages
##### Module 21 - OTA - Over the Air Updates
> [!NOTE] Note
> The OTA update mechanism allows a device to update itself based on data received while the normal firmware is running (for example, over Wi-Fi, Bluetooth or Ethernet).

Introduction to OTA
Overview of OTA
OTA with Google Drive
Versions of OTA
Advanced OTA
##### Module 22 - Course Completion
Congratulations! You made it!
##### Module 23 - Bluetooth BLE
Bluetooth - Intro
Classic vs BLE Bluedoid vs Nimble
BLE stack and comms protocol
BLE iBeacon
BLE Eddy Stone
BLE GAP
BLE GATT Theory
BLE GATT Read
BLE GATT Write
BLE Battery Read
BLE Event and Descriptor
BLE Client GAPP
BLE Client GATT