SRM module
==========

**SRM modules** provide a secure resource management layer for IoT products build with widely-adopted Web technologies. Its core is the SRM module firmware that provides a seamless networking experience with strong TLS encryption (HTTPS), HTTP authentication and fine-grained resource permissions, REST API interface to its physical and logical resources, and connectivity with all common physical interfaces (GPIO, I2C, SPI, UART, PWM, ADC, DAC). These unique abilities make it a universal modular IoT solution for fast prototyping, but also suitable for big and complex systems.


General
-------

**SRM module** consists of:

- *target application* (`apps/maintained/user_apps/common/srmmodule/`): main entry point, HTTP server initialization, minimal Web interface
- *SRM resources* (`system/srm`): components of the SRM resource tree
- *SRM system* (`system/`): system implementation, hardware abstraction, and board-specific implementations
- *external libraries* (`external/`): external libraries
- *Marvell WMSDK* (`marvell-sdk/wmsdk-3.2.12/`): SDK with FreeRTOS, Boot2 bootloader, WiFi firmware


Getting started
---------------

**Setup development environment** instructions:

- [Console setup on Ubuntu](docs/console-setup-on-ubuntu.md) (see `docs/console-setup-on-ubuntu.pdf`)

**Compile and run** instructions for your target platform:

- [Compile for Unix](docs/compile-for-unix.md) (see `docs/compile-for-unix.pdf`)
- [Compile for OrangePiZero](./docs/compile-for-orangepizero) (see `docs/compile-for-orangepizero.pdf`)
- [Compile for HF-LPB300](./docs/compile-for-lpb300) (see `docs/compile-for-lpb300.pdf`)


License
-------

Copyright &copy; 2012-2020 *CR-tech d.o.o.* [http://cr-tech.eu/] &lt;<info@cr-tech.eu>&gt;

All rights reserved. Everything is prohibited without an explicit permission from the copyright holder.

The copyright holder retains all rights in the copyright work, including without limitation, the right to copy, distribute, publish, sell, display or modify the copyright work, and to transfer, assign or grant license of any such rights. If explicitly noted, some libraries are subject to a different copyright and licensing restrictions.

