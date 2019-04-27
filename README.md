LIPPA
=====

* Powering 7.4V 2.5Ah lipo
* PCB Size 80x50 mm, M3 mounting holes at corners 3.5/3.5
* 4 stepper motor drivers
* 3 servo drivers
* CPU STM32
  * UART for Lidar
  * Debug UART
  * USB VCP
  * 3 timers for servo
  * 4 timers for stepper
  * 4 GPIO to control servo directions
  * 4 GPIO to control servo enables
  * 4 GPIO to control servo microstep modes
  * SPI for PS2 controller

Parts
===== 
* CPU [STM32F417VE](http://www.st.com/content/ccc/resource/technical/document/datasheet/98/9f/89/73/01/b1/48/98/DM00035129.pdf/files/DM00035129.pdf/jcr:content/translations/en.DM00035129.pdf)
* Stepper drivers [DRV8834](http://www.ti.com/lit/ds/symlink/drv8834.pdf)
* Power supply [TPS561201](http://www.ti.com/lit/ds/symlink/tps561201.pdf)
