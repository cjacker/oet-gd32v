# Opensource toolchain for gd32vf103

## Overview of GD32VF103 RISC-V MCU

GD32VF103 SoC is the first general RISC-V MCU from GigaDevice Semiconductor which is based on Nuclei RISC-V Process Core.

If you want to learn more about it, please click https://www.gigadevice.com/products/microcontrollers/gd32/risc-v/

The GD32VF103 device is a 32-bit general-purpose micro controller based on the RISC-V core with best ratio in terms of processing power, reduced power consumption and peripheral set.

The RISC-V processor core is tightly coupled with an Enhancement Core-Local Interrupt Controller(ECLIC), SysTick timer and advanced debug support.

The GD32VF103 device incorporates the RISC-V 32-bit processor core operating at 108MHz frequency with Flash accesses zero wait states to obtain maximum efficiency.

It provides up to 128KB on-chip Flash memory and 32KB SRAM memory.

An extensive range of enhanced I/Os and peripherals connect to two APB buses.

The devices offer up to two 12-bit ADCs, up to two 12-bit DACs, up to four general 16-bit timers, two basic timers plus a PWM advanced timer, as well as standard and advanced communication interfaces: up to three SPIs, two I2Cs, three USARTs, two UARTs, two I2Ss, two CANs, an USBFS.

The SoC diagram can be checked as below GD32VF103 SoC Diagram

![gd32vf103_soc_diagram](https://user-images.githubusercontent.com/1625340/155824560-96b510b6-1613-4c9f-9c5b-7228ff2a6d80.png)

## Overview of Longan Nano development board

Longan Nano is a GD32VF103CBT6 based minimal development board based on GigaDevice's latest RISC-V 32-bit core microcontroller. Convenient for students, engineers, geeks and enthusiasts to access the latest generation of RISC-V processors.

In the heart of Longan Nano is a GigaDevice's GD32VF103CBT6, based on Nucleisys Bumblebee kernel (support RV32IMAC instruction sets and ECLIC rapid interrupt). You can download instruction set documents here: http://dl.sipeed.com/LONGAN/Nano/DOC/.

The chip has built-in 128KB Flash, 32KB SRAM, and peripherals listes below:

    4 x universal 16-bit timer
    2 x basic 16-bit timer
    1 x advanced 16-bit timer
    Watchdog timer
    RTC
    Systick
    3 x USART
    2 x I2C
    3 x SPI
    2 x I2S
    2 x CAN
    1 x USBFS(OTG)
    2 x ADC(10 channel)
    2 x DAC

Longan Nano development board is breadboard friendly. It has onboard 8M passive crystal, 32.768KHz RTC low-speed crystal, mini TF card slot, and use the latest Type-C USB interface.

![longan_nano_pinout_v1 1 0_w5676_h4000_large](https://user-images.githubusercontent.com/1625340/155824632-bb1fb2d2-301c-434b-b41c-b466d4aee71d.png)
