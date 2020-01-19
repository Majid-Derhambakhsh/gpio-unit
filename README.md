# gpio-unit
Driver for working with GPIO unit of AVR microcontroller.

#### Version : 0.2.0
- 	Improve Code for CVAVR compiler
#### Version : 0.2.0

- #### Type : Embedded Software.

- #### Support : Supported ATtiny & ATmega series.

- #### Program Language : C/C++

- #### Properties :

- - Supported CodevisionAVR & GCC Compilers.

- #### Functions:
- - void GPIO_WritePin(volatile uint8_t *GPIOx , uint8_t GPIO_Pin , uint8_t PinState);
- - void GPIO_ClearPin(volatile uint8_t *GPIOx , uint8_t GPIO_Pin);
- - uint8_t GPIO_ReadPin(volatile uint8_t *GPIOx , uint8_t GPIO_Pin);
- - uint8_t GPIO_ReadPort(volatile uint8_t *GPIOx);
- - void GPIO_TogglePin(volatile uint8_t *GPIOx , uint8_t GPIO_Pin);
- - uint8_t GPIO_ReadRegister(volatile uint8_t *REGISTERx);

#### Developer: Majid Derhambakhsh
