![Geehy Semiconductor](https://user-images.githubusercontent.com/110007518/224920727-7dd0e2db-2925-4535-8e1f-d754c35dc238.jpeg)

<p align="center">
  <a href="#english">English</a> ·
  <a href="#中文">中文</a> ·
  <a href="https://global.geehy.com/">Global Website</a> ·
  <a href="https://www.geehy.com/">中文官网</a>
</p>

# English

## About Geehy Semiconductor

Geehy Semiconductor is a fabless IC company specializing in industrial- and automotive-grade microcontrollers, mixed-signal analog ICs, and system-on-chip products. This GitHub organization hosts official SDKs, development tools, open-source ports, reference projects, and application examples for APM32 microcontrollers.

## Official APM32 SDKs

| Device family | SDK repository | Current package | Main coverage |
| --- | --- | --- | --- |
| APM32F00x | [APM32F00x SDK](https://github.com/GeehySemi/APM32F00x_SDK) | V1.5.1 | APM32F003 family |
| APM32F0xx | [APM32F0xx SDK](https://github.com/GeehySemi/APM32F0xx_SDK) | V1.8.7 | APM32F030, APM32F051, APM32F072 and related devices |
| APM32F10x | [APM32F10x SDK](https://github.com/GeehySemi/APM32F10x_SDK) | V2.0.0 | APM32F103, APM32F105 and APM32F107 |
| APM32F4xx | [APM32F4xx SDK](https://github.com/GeehySemi/APM32F4xx_SDK) | V1.5.3 | APM32F4 series |

SDK versions shown here follow the package information in each repository. Check the repository README and Releases for the latest available package.

## Ecosystem and Development Tools

| Resource | Description |
| --- | --- |
| [LVGL port for APM32F427](https://github.com/GeehySemi/lv_port_apm32f427) | LVGL v9.4.0 demonstration project for APM32F427 and ILI9341 |
| [OpenOCD package](https://github.com/GeehySemi/Openocd) | Debugging and programming resources for APM32 devices |
| [IAR device support packages](https://github.com/GeehySemi/IAR-Package) | Device support packages for IAR Embedded Workbench |
| [GCC Makefile example](https://github.com/GeehySemi/APM32F103_GCC_Makefile_Example) | Reference APM32F103 project using GCC and Make |
| [DAPLink hardware firmware assets](https://github.com/GeehySemi/mbed-os-DAPLINK-Hardware) | DAPLink-related firmware and hardware resources |
| [Mbed OS](https://github.com/GeehySemi/mbed-os) | Mbed OS repository containing APM32-related support |
| [All public repositories](https://github.com/orgs/GeehySemi/repositories?type=public) | Browse all public GeehySemi projects |

## Examples by Device Family

### APM32F00x and APM32F0xx

- [APM32F003 low-power example](https://github.com/GeehySemi/APM32F003_Low_Power_Example)
- [APM32F003 cascaded 32-bit timer](https://github.com/GeehySemi/APM32F003_Timer_Cascade_32bit_Example)
- [APM32F003 Flash EEPROM emulation](https://github.com/GeehySemi/APM32F003_Flash_EEPROM_Emulation)
- [APM32F0xx I2C EEPROM](https://github.com/GeehySemi/APM32F0xx_I2C_EEPROM_Example)
- [APM32F030 IAP Bootloader](https://github.com/GeehySemi/APM32F030_IAP_Bootloader_Example)
- [APM32F072 USB touch keyboard](https://github.com/GeehySemi/APM32F072-USB-TSC-KEYBOARD)
- [APM32F072 USB touch mouse](https://github.com/GeehySemi/APM32F072-USB-TSC-MOUSE)

### APM32E103 and APM32F103

- [APM32E103 Flash EEPROM emulation](https://github.com/GeehySemi/APM32E103_Flash_EEPROM_Emulation)
- [APM32E103 GPIO-emulated I2C](https://github.com/GeehySemi/APM32E103_GPIO_Emulated_I2C_Example)
- [APM32E103 PCF8563 RTC](https://github.com/GeehySemi/APM32E103-PCF8563)
- [APM32E103 AHT10 sensor](https://github.com/GeehySemi/APM32E103_AHT10_Example)
- [APM32E103 ILI9341 LCD](https://github.com/GeehySemi/APM32E103_ILI9341_Example)
- [APM32F103 USART idle-line and DMA](https://github.com/GeehySemi/APM32F103_USART_Idle_DMA_Example)
- [APM32F103 USB CDC Virtual COM Port](https://github.com/GeehySemi/APM32F103_USB_CDC_VirtualCOMPort_Example)
- [CAN porting guide for APM32F103](https://github.com/GeehySemi/APM32F103_CAN_Porting_Guide)

### APM32F4xx

- [LVGL port for APM32F427](https://github.com/GeehySemi/lv_port_apm32f427)
- [ADC multi-channel scan with DMA and timer trigger](https://github.com/GeehySemi/APM32F407_ADC_MultiChannel_Scan_DMA_TMR8_CC1_Example)
- [ADC internal temperature sensor with DMA](https://github.com/GeehySemi/APM32F407_ADC_DMA_Temperature_Example)
- [ADC temperature, VREF and VBAT](https://github.com/GeehySemi/APM32F407_ADC_Temperature_VREF_VBAT_Example)
- [DAC and ADC voltage test](https://github.com/GeehySemi/APM32F407_DAC_ADC_Voltage_Example)
- [SPI2 DMA transmission](https://github.com/GeehySemi/APM32F4xx_SPI2_DMA_TX_Example)
- [USART DMA transmission](https://github.com/GeehySemi/APM32F4xx_USART_DMA_TX_Example)
- [USB MSC firmware-upgrade Bootloader](https://github.com/GeehySemi/APM32F407_USB_MSC_Firmware_Upgrade_Bootloader_Example)

## Repository Status and Support

Official SDK repositories contain the current package version stated in their README. Example repositories are intended for development reference and may target a specific device, board, SDK version, or toolchain. Validate the design against the latest datasheet, user manual, SDK, and actual hardware before production use.

For technical questions, open an Issue in the relevant repository and include the device model, development board, SDK and toolchain versions, reproduction steps, and key logs.

For products, documentation, development tools, and additional support, visit the [Geehy global website](https://global.geehy.com/).

## Request Samples

![Ask for Samples](https://raw.githubusercontent.com/GeehySemi/.github/main/profile/contact-en-v2.png)

---

# 中文

## 关于极海半导体

极海半导体是一家专注于工业级与车规级微控制器、混合信号模拟芯片及系统级芯片的集成电路设计企业。本 GitHub 组织集中提供 APM32 微控制器的官方 SDK、开发工具、开源移植项目、参考工程和应用示例。

## APM32 官方 SDK

| 芯片系列 | SDK 仓库 | 当前软件包 | 主要覆盖产品 |
| --- | --- | --- | --- |
| APM32F00x | [APM32F00x SDK](https://github.com/GeehySemi/APM32F00x_SDK) | V1.5.1 | APM32F003 系列 |
| APM32F0xx | [APM32F0xx SDK](https://github.com/GeehySemi/APM32F0xx_SDK) | V1.8.7 | APM32F030、APM32F051、APM32F072 等产品 |
| APM32F10x | [APM32F10x SDK](https://github.com/GeehySemi/APM32F10x_SDK) | V2.0.0 | APM32F103、APM32F105、APM32F107 |
| APM32F4xx | [APM32F4xx SDK](https://github.com/GeehySemi/APM32F4xx_SDK) | V1.5.3 | APM32F4 系列 |

这里显示的版本来自各仓库中的软件包信息。请进入对应仓库查看 README 和 Releases，以获取当前可用的软件包。

## 开源生态与开发工具

| 资源 | 说明 |
| --- | --- |
| [APM32F427 LVGL 移植](https://github.com/GeehySemi/lv_port_apm32f427) | 基于 APM32F427、ILI9341 和 LVGL v9.4.0 的演示工程 |
| [OpenOCD 工具包](https://github.com/GeehySemi/Openocd) | APM32 调试与程序下载相关资源 |
| [IAR 器件支持包](https://github.com/GeehySemi/IAR-Package) | 适用于 IAR Embedded Workbench 的器件支持包 |
| [GCC Makefile 示例](https://github.com/GeehySemi/APM32F103_GCC_Makefile_Example) | 基于 GCC 和 Make 的 APM32F103 参考工程 |
| [DAPLink 硬件固件资源](https://github.com/GeehySemi/mbed-os-DAPLINK-Hardware) | DAPLink 相关固件和硬件资源 |
| [Mbed OS](https://github.com/GeehySemi/mbed-os) | 包含 APM32 相关支持的 Mbed OS 仓库 |
| [全部公开仓库](https://github.com/orgs/GeehySemi/repositories?type=public) | 浏览 GeehySemi 的全部公开项目 |

## 按芯片系列查找示例

### APM32F00x 与 APM32F0xx

- [APM32F003 低功耗示例](https://github.com/GeehySemi/APM32F003_Low_Power_Example)
- [APM32F003 级联 32 位定时器](https://github.com/GeehySemi/APM32F003_Timer_Cascade_32bit_Example)
- [APM32F003 Flash 模拟 EEPROM](https://github.com/GeehySemi/APM32F003_Flash_EEPROM_Emulation)
- [APM32F0xx I2C EEPROM](https://github.com/GeehySemi/APM32F0xx_I2C_EEPROM_Example)
- [APM32F030 IAP Bootloader](https://github.com/GeehySemi/APM32F030_IAP_Bootloader_Example)
- [APM32F072 USB 触摸键盘](https://github.com/GeehySemi/APM32F072-USB-TSC-KEYBOARD)
- [APM32F072 USB 触摸鼠标](https://github.com/GeehySemi/APM32F072-USB-TSC-MOUSE)

### APM32E103 与 APM32F103

- [APM32E103 Flash 模拟 EEPROM](https://github.com/GeehySemi/APM32E103_Flash_EEPROM_Emulation)
- [APM32E103 GPIO 模拟 I2C](https://github.com/GeehySemi/APM32E103_GPIO_Emulated_I2C_Example)
- [APM32E103 PCF8563 RTC](https://github.com/GeehySemi/APM32E103-PCF8563)
- [APM32E103 AHT10 传感器](https://github.com/GeehySemi/APM32E103_AHT10_Example)
- [APM32E103 ILI9341 LCD](https://github.com/GeehySemi/APM32E103_ILI9341_Example)
- [APM32F103 USART 空闲中断与 DMA](https://github.com/GeehySemi/APM32F103_USART_Idle_DMA_Example)
- [APM32F103 USB CDC 虚拟串口](https://github.com/GeehySemi/APM32F103_USB_CDC_VirtualCOMPort_Example)
- [APM32F103 CAN 移植指南](https://github.com/GeehySemi/APM32F103_CAN_Porting_Guide)

### APM32F4xx

- [APM32F427 LVGL 移植](https://github.com/GeehySemi/lv_port_apm32f427)
- [ADC 多通道扫描、DMA 与定时器触发](https://github.com/GeehySemi/APM32F407_ADC_MultiChannel_Scan_DMA_TMR8_CC1_Example)
- [ADC 内部温度传感器与 DMA](https://github.com/GeehySemi/APM32F407_ADC_DMA_Temperature_Example)
- [ADC 温度、VREF 与 VBAT](https://github.com/GeehySemi/APM32F407_ADC_Temperature_VREF_VBAT_Example)
- [DAC 与 ADC 电压测试](https://github.com/GeehySemi/APM32F407_DAC_ADC_Voltage_Example)
- [SPI2 DMA 发送](https://github.com/GeehySemi/APM32F4xx_SPI2_DMA_TX_Example)
- [USART DMA 发送](https://github.com/GeehySemi/APM32F4xx_USART_DMA_TX_Example)
- [USB MSC 固件升级 Bootloader](https://github.com/GeehySemi/APM32F407_USB_MSC_Firmware_Upgrade_Bootloader_Example)

## 仓库状态与技术支持

官方 SDK 仓库提供 README 中所列的当前软件包。示例仓库主要用于开发参考，可能对应特定芯片、开发板、SDK 版本或工具链。用于量产项目前，请结合最新的数据手册、用户手册、SDK 和实际硬件完成验证。

如需反馈技术问题，请在对应仓库提交 Issue，并尽量附上芯片型号、开发板、SDK 与工具链版本、复现步骤和关键日志。

产品信息、文档、开发工具和更多技术支持，请访问[极海半导体官网](https://www.geehy.com/)。

## 样品申请

![Ask for Samples](https://raw.githubusercontent.com/GeehySemi/.github/main/profile/contact-zh-v3.png)
