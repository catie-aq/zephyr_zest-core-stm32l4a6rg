# Zest_Core_STM32L4A6RG

[Zest_Core_STM32L4A6RG](https://6tron.io/zest_core/zest_core_stm32l4a6rg_3_1_0) custom target for Zephyr OS.

## Supported Features

The Zephyr Zest Core STM32L4A6RG board configuration supports the following hardware features:

| Interface | Controller | Driver/Component                                           |
| :-------- | :--------- | :--------------------------------------------------------- |
| ADC       | on-chip    | adc                                                        |
| AES       | on-ship    | crypto                                                     |
| CAN       | on-ship    | can                                                        |
| COUNTER   | on-ship    | counter                                                    |
| DAC       | on-chip    | dac                                                        |
| DIE-TEMP  | on-chip    | sensor/stm32_temp                                          |
| DMA       | on-chip    | dma                                                        |
| EXTI      | on-ship    | external interrupt controller                              |
| FLASH     | on-chip    | flash                                                      |
| GPIO      | on-chip    | gpio                                                       |
| I2C       | on-chip    | i2c                                                        |
| LPTIM     | on-chip    | timer                                                      |
| NVIC      | on-chip    | nested vector interrupt controller                         |
| PINCTRL   | on-chip    | pinctrl                                                    |
| PWM       | on-chip    | pwm                                                        |
| QSPI      | on-ship    | flash                                                      |
| RNG       | on-chip    | entropy                                                    |
| RTC       | on-chip    | rtc                                                        |
| SDMMC     | on-chip    | disk                                                       |
| SMBUS     | on-chip    | smbus                                                      |
| SPI       | on-chip    | spi                                                        |
| UART      | on-chip    | serial                                                     |
| USB       | on-chip    | usb (OTGFS)                                                |
| VBAT      | on-chip    | sensor/stm32_vbat                                          |
| VREF      | on-chip    | sensor/stm32_vref                                          |
| WATCHDOG  | on-chip    | watchdog (independent watchdog, or system window watchdog) |


## Usage

1. Add the Zest Core STM32L4A6RG board to your workspace using the [6TRON module](https://github.com/catie-aq/zephyr_6tron-manifest.git)
2. Compile and flash application using west tool
   - Board name: `zest_core_stm32l4a6rg`
