### **Getting Started with ESP32 - Step-By-Step Tutorial**
#### by Tomasz Tarnowski of Tomasz Tarnowski

[Youtube Video Link][Tomasz Tarnowski]

---


<br  />

**Hardware**
1. Microcontroller Development Board
1. Male USB A to Male USB Micro B Data Cable

<br  />

**USB to UART Bridge Driver Setup**
1. Check the Bridge used in the Microcontroller Development Board
    <br  />
    <br  />
    ![github](https://raw.githubusercontent.com/lorenzmiranda05/PlatformIoEsp32Tutorial/main/Assets/Images/CP210xVSCH340.png)
    <br  />
    <br  />
    ![github](https://raw.githubusercontent.com/lorenzmiranda05/PlatformIoEsp32Tutorial/main/Assets/Images/ESP8266%20ESP-12E%20MCU.png)
1. Download the USB to UART Bridge Drivers:
    * For CP210X, download [here][CP210X Driver].
    * For CH340, download [here][CH340 Driver].
1. Install the USB to UART Driver.

<br  />

**Visual Studio Code Setup**
1. Install Visual Studio Code
1. Open Visual Studio Code
1. In Extensions, install PlatformIO IDE by PlatformIO
    * This should install it's dependency, the extension C/C++ by Microsoft
1. Close Visual Studio Code
1. Open Visual Studio Code
1. In Extensions, install Clang-Format by xaver
1. Open File>Preferences>Settings or press [Ctrl+,]
1. Set *Editor: Default Formatter* to Clang-Format
1. Tick *Editor: Format On Paste*
1. Tick *Editor: Format On Save*
1. Tick *Editor: Format On Type*

<br  />

**Tasks**
* [x] USB to UART Driver Installation
* [x] IDE Installation (VS Code, Platform IO, C/C++ extension)
* [x] Create a new project
* [x] Program an Microcontroller Unit (MCU) Hello World program: Blink Diode


<!-- Reusable and Invisible URL Definitions  -->
[Github]: https://github.com
[Tomasz Tarnowski]: https://www.youtube.com/watch?v=tc3Qnf79Ny8
[CP210X Driver]: https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads
[CH340 Driver]: http://www.wch-ic.com/downloads/CH341SER_ZIP.html