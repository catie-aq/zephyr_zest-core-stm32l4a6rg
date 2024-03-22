# Zest_Core_STM32L4A6RG

[Zest_Core_STM32L4A6RG](https://6tron.io/zest_core/zest_core_stm32l4a6rg_3_1_0) custom target for Zephyr OS.

## Supported Features

The Zephyr Zest Core STM32L4A6RG board configuration supports the following hardware features:

| Interface | Controller | Driver/Component                                |
| :-------- | :--------- | :---------------------------------------------- |
| ADC       | on-chip    | ADC controller                                  |
| AES       | on-ship    | crypto                                          |
| CAN       | on-ship    | CAN controller                                  |
| COUNTER   | on-ship    | timers                                          |
| DAC       | on-chip    | DAC controller                                  |
| DIE-TEMP  | on-chip    | internal die temperature sensor                 |
| DMA       | on-chip    | DMA controller                                  |
| EXTI      | on-ship    | external interrupt controller                   |
| FLASH     | on-chip    | flash memory                                    |
| GPIO      | on-chip    | gpio (using PINCTRL)                            |
| I2C       | on-chip    | i2c controller                                  |
| LPTIM     | on-chip    | low power timer / counter                       |
| NVIC      | on-chip    | nested vector interrupt controller              |
| PINCTRL   | on-chip    | pin controller                                  |
| PWM       | on-chip    | timers                                          |
| QSPI      | on-ship    | quad spi                                        |
| RNG       | on-chip    | random number generator                         |
| RTC       | on-chip    | real time clock                                 |
| SDMMC     | on-chip    | memory storage controller (SD/SDIO/MMC)         |
| SMBUS     | on-chip    | system management bus (using i2c)               |
| SPI       | on-chip    | spi controller                                  |
| UART      | on-chip    | uart or lpuart controller                       |
| USB       | on-chip    | external "USB Device" port on Zest Core (OTGFS) |
| VBAT      | on-chip    | monitoring battery voltage                      |
| VREF      | on-chip    | internal voltage reference                      |
| WATCHDOG  | on-chip    | independent watchdog, or system window watchdog |


## Usage

1. Add the Zest Core STM32L4A6RG board to your workspace using the [6TRON module](https://github.com/catie-aq/zephyr_6tron-manifest.git)
2. Compile and flash application using west tool
   - Board name: `zest_core_stm32l4a6rg`
