# EX-01 INTERFACING DIGITAL OUTPUT FOR ARM DEVELOPMENT BOARD 
### Aim: 
To Interface a Digital output (LED) to ARM development board and write a blink code.
### Components required: 
STM32 CUBE IDE, NUCLEO ARM DEVELOPMENT BOARD.
### Theory: 
The full form of an ARM is an advanced reduced instruction set computer (RISC) machine, and it is a 32-bit processor architecture expanded by ARM holdings. The applications of an ARM processor include several microcontrollers as well as processors. The architecture of an ARM processor was licensed by many corporations for designing ARM processor-based SoC products and CPUs. This allows the corporations to manufacture their products using ARM architecture. Likewise, all main semiconductor companies will make ARM-based SOCs such as Samsung, Atmel, TI etc.
What is an ARM7 Processor?
ARM7 processor is commonly used in embedded system applications. Also, it is a balance among classic as well as new-Cortex sequence. This processor is tremendous in finding the resources existing on the internet with excellence documentation offered by NXP Semiconductors. It suits completely for an apprentice to obtain in detail hardware & software design implementation.
LPC2148 Microcontroller
 The LPC2148 microcontroller is designed by Philips (NXP Semiconductor) with several in-built features & peripherals. Due to these reasons, it will make more reliable as well as the efficient option for an application developer. LPC2148 is a 16-bit or 32-bit microcontroller based on ARM7 family.
Features of LPC2148
The main features of LPC2148 include the following.
•	The LPC2148 is a 16 bit or 32 bit ARM7 family based microcontroller and available in a small LQFP64 package.
•	ISP (in system programming) or IAP (in application programming) using on-chip boot loader software.
•	On-chip static RAM is 8 kB-40 kB, on-chip flash memory is 32 kB-512 kB, the wide interface is 128 bit, or accelerator allows 60 MHz high-speed operation.
•	It takes 400 milliseconds time for erasing the data in full chip and 1 millisecond time for 256 bytes of programming.
•	Embedded Trace interfaces and Embedded ICE RT offers real-time debugging with high-speed tracing of instruction execution and on-chip Real Monitor software.
•	It has 2 kB of endpoint RAM and USB 2.0 full speed device controller. Furthermore, this microcontroller offers 8kB on-chip RAM nearby to USB with DMA.
•	One or two 10-bit ADCs offer 6 or 14 analogs i/ps with low conversion time as 2.44 μs/ channel.
•	Only 10 bit DAC offers changeable analog o/p.
•	External event counter/32 bit timers-2, PWM unit, & watchdog.
•	Low power RTC (real time clock) & 32 kHz clock input.
•	Several serial interfaces like two 16C550 UARTs, two I2C-buses with 400 kbit/s speed.
•	5 volts tolerant quick general purpose Input/output pins in a small LQFP64 package.
•	Outside interrupt pins-21.
•	60 MHz of utmost CPU CLK-clock obtainable from the programmable-on-chip phase locked loop by resolving time is 100 μs.
•	The incorporated oscillator on the chip will work by an exterior crystal that ranges from 1 MHz-25 MHz
•	The modes for power-conserving mainly comprise idle & power down.
•	For extra power optimization, there are individual enable or disable of peripheral functions and peripheral CLK scaling.<br>
### Procedure:
<table>
  <tr>
    <td width="50%">
      1. click on STM 32 CUBE IDE, the following screen will appear.
    </td>
    <td>
      <img height=7% width=90% src="https://user-images.githubusercontent.com/36288975/226189166-ac10578c-c059-40e7-8b80-9f84f64bf088.png">
    </td>
  </tr>
  <tr>
    <td width="50%">
      2. click on FILE, click on new stm 32 project.
    </td>
    <td width="50%">
  <img src="https://user-images.githubusercontent.com/36288975/226189215-2d13ebfb-507f-44fc-b772-02232e97c0e3.png">
    <img src="https://user-images.githubusercontent.com/36288975/226189230-bf2d90dd-9695-4aaf-b2a6-6d66454e81fc.png">
    </td>
  </tr>
  <tr>
    <td width="50%">
      3. select the target to be programmed  as shown below and click on next.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189280-ed5dcf1d-dd8d-43ae-815d-491085f4863b.png">
    </td>
  </tr>
   <tr>
    <td width="50%">
      4.select the program name.
    </td>
    <td >
      <img height=10% width=50% src="https://user-images.githubusercontent.com/36288975/226189316-09832a30-4d1a-4d4f-b8ad-2dc28f137711.png">
    </td>
  </tr>
     <tr>
    <td width="50%">
      5. corresponding ioc file will be generated automatically.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189378-3abbdee2-0df6-470f-a3cd-79c74e3d3ad8.png">
    </td>
  </tr>
    <tr>
    <td width="50%">
      6.select the appropriate pins as gipo, in or out, USART or required options and configure.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189403-f7179f1a-3eae-4637-826b-ab4ec35ba1e1.png">
    </td>
  </tr>
    <tr>
    <td width="50%">
      7.click on cntrl+S , automaticall C program will be generated.
    </td>
    <td width="50%">
<img src="https://user-images.githubusercontent.com/36288975/226189443-8b43451d-0b14-47e4-a20b-cc09c6ad8458.png">
    </td>
  </tr>
    <tr>
    <td width="50%">
      8. edit the program and as per required.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189461-a573e62f-a109-4631-a250-a20925758fe0.png">
    </td>
  </tr>
    <tr>
    <td width="50%">
      8. edit the program and as per required.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189461-a573e62f-a109-4631-a250-a20925758fe0.png">
    </td>
  </tr>  
  <tr>
    <td width="50%">
      9. Add necessary library files of LCD 16x2 , write the program and use project and build.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189554-3f7101ac-3f41-48fc-abc7-480bd6218dec.png">
    </td>
  </tr>   
  <tr>
    <td width="50%">
      10. once the project is bulild.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189577-c61cc1eb-3990-4968-8aa6-aefffc766b70.png">
    </td>
  </tr>  
  <tr>
    <td width="50%">
      11. click on debug option.
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/226189625-37daa9a3-62e9-42b5-a5ce-2ac63345905b.png">
    </td>
  </tr>  
  
  <tr>
    <td width="50%">
      
  12.  Creating Proteus project and running the simulation.
  We are now at the last part of step by step guide on how to simulate STM32 project in Proteus.
13. Create a new Proteus project and place STM32F40xx i.e. the same MCU for which the project was created in STM32Cube IDE. 
14. After creation of the circuit as per requirement as shown below
    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/233856847-32bea88a-565f-4e01-9c7e-4f7ed546ddf6.png">
    </td>
  </tr>  
  <tr>
    <td width="50%">
      15. Double click on the the MCU part to open settings. Next to the Program File option, give full path to the Hex file generated using STM32Cube IDE. Then set the external crystal frequency to 8M (i.e. 8 MHz). Click OK to save the changes.
https://engineeringxpert.com/wp-content/uploads/2022/04/26.png

16. click on debug and simulate using simulation as shown below 


    </td>
    <td width="50%">
      <img src="https://user-images.githubusercontent.com/36288975/233856904-99eb708a-c907-4595-9025-c9dbd89b8879.png">
    </td>
  </tr>  
  
</table>

### STM 32 CUBE PROGRAM :
```
ROHIT JAIN D
212222230120
```
```C
#include "main.h"
void SystemClock_Config(void);
static void MX_GPIO_Init(void);
int main(void)
{
  HAL_Init();
  SystemClock_Config();
  MX_GPIO_Init();
  while (1)
  {
	  HAL_GPIO_WritePin(GPIOA, GPIO_PIN_5, GPIO_PIN_RESET);
	  HAL_Delay(3000);
	  HAL_GPIO_WritePin(GPIOA, GPIO_PIN_5, GPIO_PIN_SET);
	  HAL_Delay(3000);   
  }
}
```
## Output  :
<img height=30% width=40% src="https://github.com/ROHITJAIND/INTERFACING-DIGITAL-OUTPUT-FOR-ARM-DEVELOPMENT-BOARD/assets/118707073/9fd535a7-6d28-413b-afd9-fbf2412a0699"> <img height=30% width=40% src="https://github.com/ROHITJAIND/INTERFACING-DIGITAL-OUTPUT-FOR-ARM-DEVELOPMENT-BOARD/assets/118707073/e3b499b6-24f4-4fc5-b139-ebdeaef9bae8">

## Result :  
Interfacing a digital output with ARM microcontroller is executed and the results are verified.
