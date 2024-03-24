The Advanced Microcontroller Bus Architecture (AMBA) is a system-on-chip protocol bus for high performance buses to communicate with low power devices. 
There are two AMBA communication protocols which are Advanced High-performance Bus (AHB) and Advanced Peripheral Bus (APB).
AHB protocol is used to communicate with a fast processor, a DSP or a high performance memory controllers (high performance systems)
APB protocol is used to communicate with low-bandwidth peripherals such as Universal Asynchronous Receiver Transmitter (UART).
AMBA system also contains a bridge which connects the AHB and APB buses 
Bridges are standard bus to bus interfaces that allows IPS connected to different buses to communicate with each other in a standardized way.
![image](https://github.com/kero-mina/AHB-to-APB-bridge/assets/92053143/d3818bef-0c10-46af-9a4b-3a033b9d3197)

For implementing the bridge function, it is done by implementing a simple finite state machine of 8 states as illustrated (image is from state machine viewer of quartus prime tool)
![image](https://github.com/kero-mina/AHB-to-APB-bridge/assets/92053143/12494c04-11e4-429b-a911-6530a698b39e)
