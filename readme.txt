board info:
STM32F401RE NUCLEO

note:
in drivers/stm32f4xx_conf.h
 /* Redefine the HSE value; it's equal to 8 MHz on the STM32F4-DISCOVERY Kit */
 #define HSE_VALUE    ((uint32_t)8000000)

