# Discover new possibilities with the ESP32-C3 UNO Development Board.

_Unlock a world of innovative possibilities with the ESP32-C3 Breadboard Development Board. This versatile platform empowers developers to create cutting-edge applications, leveraging its advanced features and robust performance. Whether you're working on IoT projects, embedded systems, or automation tasks, the ESP32-C3 Development Board offers the flexibility, power and quick implementation needed to bring your ideas to life._

Explore its capabilities and push the boundaries of your creativity and technical expertise. https://gitea.techquadbit.net/alex/ESP32-C3_Breadboard-Adapter

## Key Features

  - compact size; requires a very little space on a breadboard
  - flash a firmware without external adapters as you work with your project
  - supplies 3.3V or 5V to the breadboard power rails can be powered either by USB-C or external power supply
  - GPIOs are arranged into 4 groups for easier identification
  - on-board power and user-controlled LEDs
  - on-board RESET and BOOT push-button switches

## Features and Specifications of the ESP32-C3 WROOM Module

Core Components:
Microprocessor: RISC-V® single-core 32-bit microprocessor, operating up to 160 MHz.
Memory:
384 KB ROM
400 KB SRAM
8 KB SRAM in RTC
Connectivity:
Wi-Fi:
802.11b/g/n, up to 150 Mbps (802.11n), frequency range: 2412 ~ 2484 MHz
Four virtual Wi-Fi interfaces
simultaneous support SoftAP mode, Station + SoftAP mode and promiscuous mode
Bluetooth:
Bluetooth 5, Bluetooth mesh, 125 Kbps, 500 Kbps, 1 Mbps, 2 Mbps
Features: Advertising extensions, multiple advertisement sets, channel selection algorithm #2
Co-existence mechanism: Internal co-existence mechanism between Wi-Fi and Bluetooth to share the same antenna
Security:
RSA-3072-based secure boot and the AES-128/256-XTS flash encryption Peripherals:
GPIOs: Up to 22 GPIOs, including 4 strapping GPIOs
Interfaces:
SPI
Two UART
I2C
I2S
LED PWM, up to 6 channels
Full-speed USB 2.0 OTG
USB Serial/JTAG controller
TWAI® controller (compatible with ISO 11898-1)
12-bit ADC, up to 6 channels
Touch sensor
Temperature sensor
Two 54-bit general purpose timers
Three digital and one analog watchdog timers
Integrated Components:
Crystal Oscillator: 40 MHz
Flash: Up to 16 MB Quad SPI flash
Antenna: on-board PCB antenna
Operating Conditions:
Operating Voltage: 3.0 ~ 3.6 V
Ambient Temperature: –40 ~ 65 °C
Certifications: RF Certification: Various certifications available Green Certification: RoHS/REACH compliant
Applications: Ideal for AI and Artificial Intelligence of Things (AIoT) applications such as: Wake word detection Speech commands recognition Face detection and recognition Smart home devices Smart appliances Smart control panels Smart speakers.
Reserved GPIOs and Pins
<table>
    <thead>
      <tr>
        <th scope="col">GPIO</th>
        <th scope="col">ESP32-C3 Module Pin</th>
        <th scope="col">DevBoard Pin</th>
        <th scope="col">Designation</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td data-label="GPIO">EN</td>
        <td data-label="ModulePin">1</td>
        <td data-label="DevBoardPin">2</td>
        <td data-label="Designation">Enable Pin</td>
      </tr>
      <tr>
        <td data-label="GPIO">IO9</td>
        <td data-label="ModulePin">8</td>
        <td data-label="DevBoardPin">8</td>
        <td data-label="Designation">Strapping Pin</td>
      </tr>
      <tr>
        <td data-label="GPIO">IO8</td>
        <td data-label="ModulePin">5</td>
        <td data-label="DevBoardPin">7</td>
        <td data-label="Designation">Strapping Pin</td>
      </tr>
      <tr>
        <td data-label="GPIO">IO18</td>
        <td data-label="ModulePin">11</td>
        <td data-label="DevBoardPin">13</td>
        <td data-label="Designation">USB D-</td>
      </tr>
      <tr>
        <td data-label="GPIO">IO19</td>
        <td data-label="ModulePin">9</td>
        <td data-label="DevBoardPin">14</td>
        <td data-label="Designation">USB D+</td>
      </tr>
      <tr>
        <td data-label="GPIO">IO10</td>
        <td data-label="ModulePin">7</td>
        <td data-label="DevBoardPin">10</td>
        <td data-label="Designation">On-board user LED</td>
      </tr>
      <tr>
        <td data-label="GPIO">IO3</td>
        <td data-label="ModulePin">13</td>
        <td data-label="DevBoardPin">15</td>
        <td data-label="Designation">On-board user button</td>
      </tr>
    </tbody>
  </table>



## I2C Pins

The schematic excerpt provided below illustrates the wiring configuration for the SDA and SCL lines. Specifically, the SDA line is connected to GPIO 8, while the SCL line is connected to GPIO 9 on the ESP32-C3 Wroom module.
The image of the PCB board below depicts the physical locations of the SDA and SCL terminals.
