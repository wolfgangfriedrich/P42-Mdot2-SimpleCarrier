A carrier to connect to a M.2 2230/3030 or 2242/3042 Board through USB, UART or I2C. All other signals are broken out to to TH testpoints.

List of features:

    M.2 slot with all pads on the board to accept any key slot M.2 module, if the correct connector is mounted.
    Specifically made for A key and E key, targeting WiFi, Bluetooth, WWAN adapter.
    Works with a subset of signals for B key and M key, but not as a USB memory interface for SSDs.
    All signals available on through hole test points on a 2.54mm (0.1") grid.
    PCIe signals are routed as differential pairs.
    USB-C set up for 5V 3A max power draw.
    Switching regulator to generate 3.3V 1.5A to power the M.2 module.
    1.8V LDO regulator to be able to work with the 1.8V UART and I2C signals.
    Power switch for the 3.3V to the M.2 module with an enable jumper and 500mA over-current protection.
    LEDs for 1.8V, 3.3V and switched 3.3V; LED for over-current condition.
    4 mounting holes.
    Mounting holes for nuts to secure 2230 or 2242 modules.
    Level shifter and connector to make UART accessible on a 3-pin header.
    Level shifter and QWIIC connector to make I2C accessible on a 3-pin header.
    Extra testpoints for GND, VBUS, 3.3V, 1.8V
    Design in KiCAD.

Why did you make it?

The design came to life initially to test my M.2 RP2350 board (https://www.tindie.com/products/pier42/pico2-m2). I needed a test platform to access all signals of the M.2 interface with E or A key. Single Board Computers with a M.2 port often don't access all pins, so I built this board and think it is very useful.
What makes it special?

M.2 carrier boards are generally for B or M key SSDs to other internal interfaces. I am not aware of any breakout board for M.2 modules with enhanced functionality. There are a few passive breakout boards available that simply connect all pins to standard headers.
