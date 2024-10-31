# ESP-PROG Stick

![ESP-PROG Stick](images/esp-prog-stick.png)

This project implements a compact and portable tool for programming ESP8266 modules, using ESP-Prog in a USB stick form factor. The design features a detachable cable for ease of use and transport, allowing for quick and efficient programming of ESP8266 modules.

View the Schematics and Layout online at [KiCanvas](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2FHarexeW%2Fesp-prog-stick%2Ftree%2Fmain%2Fkicad).

## Features

- **Compact USB Stick Format:** The tool is designed to be portable, fitting easily into a USB port.
- **Detachable Cable:** Comes with a detachable cable for easy connection and disconnection, making it more versatile and durable.
- **ESP-Prog Functionality:** Enables seamless programming and debugging of ESP8266 modules, using the widely supported ESP-Prog standard.

## Hardware Details

- **Design Software**: Created using **KiCad 8.0.6**.
- **Components**: The device consists of a USB stick PCB form factor for ESP-Prog functionalities and a detachable cable to connect directly to ESP8266 modules for programming and debugging.

### Hardware Features

- **Onboard 3.3V Regulator**
- **USB to UART Bridge CH340G**
- **Auto Reset and Programming Circuit**

## Connector

The connector is a **6-pin JST SHL connector**. More details can be found [here](https://www.jst.com/products/crimp-style-connectors-wire-to-board-type/shl-connector/).

### Pinout

1. **GND** - Ground
2. **TX** - Transmit Data
3. **RX** - Receive Data
4. **GPIO0** - General Purpose I/O, used for programming
5. **EN** - Enable Pin
6. **3.3V** - 3.3V Power Output


## Windows Driver Installation

For Windows users, a driver is required to use the USB to UART Bridge (CH340G). The driver can be downloaded from [this link](https://www.wch.cn/download/ch341ser_exe.html).

## Bill of Materials (BOM)

- [Interactive Bill of Materials](bom/ibom.html)

The BOM includes part numbers for components available at [LCSC](https://lcsc.com), where you can order them.

## License

This project is licensed under the GPL v3 License.

## Contributing

Feel free to submit issues or contribute to this project. Fork the repository and make a pull request with detailed information about your changes.

## Acknowledgments

- [Espressif Systems](https://www.espressif.com/) for ESP-Prog and ESP8266 documentation.
- Community resources on ESP8266 programming and USB hardware designs.
