# GROUP1_FREERTOS_STM32
This is the repository of group 1 for the insights of RTOS with FREERTOS using STM32F407 Board.

* Team Details

| Sr.No. |    Member Name      | PS Number | Photo |
|:------:|:-------------------:|:---------:|:-----:|
|    1   |    Kartik Burele    |  99007835 | <img src= "https://user-images.githubusercontent.com/98891749/159463146-8c404739-b2b2-4ba1-ae54-dd242e9775f0.jpg" width="40%" height="40%">|
|      2 |    Saujandu Roy     |  99007834 | <img src="https://user-images.githubusercontent.com/98866279/159470500-f3bc65ac-dbe3-4c06-9d10-f3c71cd2f19c.jpg" width="40%" height="40%">|
|3 | Vaishnavi Ankar| 99007867 | <img src = "https://user-images.githubusercontent.com/93757351/168029291-5a3f3a98-f5df-4491-a129-7661eb199670.png" width="40%" height="40%">    |
|4 | Aniket Nagpure | 99007871 |<img src = "https://user-images.githubusercontent.com/46985114/160232999-d73ce6a1-9ed8-4dac-8acc-d3ebb74128c0.jpg" width="40%" height="40%" >            |
          



![image](https://user-images.githubusercontent.com/93757351/168005423-b8122d0f-9a8b-44af-80fe-296a8958c247.png)

## About discovery kit with STM32F407VG MCU

- The Arm® Cortex®-M4 32-bit STM32F407VG high-performance mcu core is easily developed with the STM32F4DISCOVERY Discovery kit. It comes with everything a new user or an expert user needs to get started. rapidly.
- It features an ST-LINK/V2-A embedded debug tool, one STMEMS digital accelerometer, one digital microphone, and one audio DAC with integrated class D and is based on the STM32F407VG microcontroller.
- There are LEDs, pushbuttons, and a USB OTG Micro-AB connector.
Extension header connectors can be used to connect specialized add-on boards. The Discovery kit for the STM32F4DISCOVERY comprises the STM32 free software package.
- The STM32CubeF4 MCU Package includes the libraries and examples.

## RTOS
### Definition: FreeRTOS Port
- FreeRTOS can be built with approximately twenty different compilers, and can run on more
than thirty different processor architectures. Each supported combination of compiler and
processor is considered to be a separate FreeRTOS port.

### Building FreeRTOS
- FreeRTOS can be thought of as a library that provides multi-tasking capabilities to what would
otherwise be a bare metal application.
- FreeRTOS is supplied as a set of C source files. Some of the source files are common to all
ports, while others are specific to a port. Build the source files as part of your project to make
the FreeRTOS API available to your application. To make this easy for you, each official
- FreeRTOS port is provided with a demo application. The demo application is pre-configured
to build the correct source files, and include the correct header files.
- Demo applications should build ‘out of the box’, although some demos are older than others,
and sometimes a change in the build tools made since the demo was released can cause an
issue. Section 1.3 describes the demo applications.



