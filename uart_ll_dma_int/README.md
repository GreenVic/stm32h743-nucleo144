# STM32H743ZI-Nucleo144 Example of STM32 LL UART3 driver with DMA TX and RX with IDLE detection 

This example demonstrates UART3 running using Low Level Drivers with DMA for TX and RX. RX also features IDLE detection
to allow variable length data reception using DMA.

The uart connection settings are 115200,8,n,1.

The example is meant to be as simple as possible and the HW initialization and handling code is interspersed with "application" code. This is meant to show how to deal with hardware and should not form the basis of any serious project.