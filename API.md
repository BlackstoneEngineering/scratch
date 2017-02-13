# mbed OS APIs

## Peripheral APIs
Driver Group - mbed-os/tools/mbed-docs/html/classmbed_1_1*

- [AnalogIn]() - Read an external voltage applied to an analog input pin.
- [AnalogOut]() - Set the voltage of an analog output pin in the range of VSS to VCC.
- [BusIn]() - Create DigitalIn pins that can be read as one value.
- [BusInOut]() - Collect DigitalInOut pins that can be read and written as one value.
- [BusOut]() - Create DigitalOut pins that you can write as one value.
- [CANMessage]() - Description goes here. [Note: I have not seen this before.]
- [CAN]() - Communication two directions between microcontrollers and devices without going through a host computer.
- [DigitalIn]() - Read the value of a digital input pin.
- [DigitalInOut]() - Read the value of a digital pin when set as input, and write the value when set as output.
- [DigitalOut]() - Configure and control a digital output pin.
- [DirHandle]() - Description goes here. [Note: I have not seen this before.]
- [FileHandle]() - Description goes here. [Note: I have not seen this before.]
- [FileSystemLike]() - Description goes here. [Note: I have not seen this before.]
- [I2C]() - Communicate with I2C devices such as serial memories, sensors and other modules or integrated circuits.
- [I2CSlave]() - Communicate with I2C master.
- [InterruptIn]() - Trigger an event when a digital input pin changes.
- [InterruptManager]() - Description goes here. [Note: I have not seen this before.]
- [LocalFileSystem]() - Description goes here. [Note: I have not seen this before.]
- [LowPowerTicker]() - Description goes here. [Note: I have not seen this before.]
- [LowPowerTimeout]() - Description goes here. [Note: I have not seen this before.]
- [LowPowerTimer]() - Description goes here. [Note: I have not seen this before.]
- [PortIn]() - Read an underlying GPIO port as one value.
- [PortInOut]() - Read and write to an underlying GPIO port as one value.
- [PortOut]() - Write to an underlying GPIO port as one value.
- [PwmOut]() - Control the frequency and mark-to-space ratio of a digital pulse train.
- [Serial]() - Use this generic protocol that computers and electronic modules to send and receive control information and data.
- [SPI]() - Communicate with SPI slave devices, such as FLASH memory, LCD screens and other modules or integrated circuits.
- [SPISlave]() - Description goes here. [Note: Added.]
- [Ticker]() - Set up a recurring interrupt.
- [Timeout]() - Set up an interrupt to call a function after a specified delay.
- [Timer]() - Create, start, stop and read a timer for measuring small times (between microseconds and seconds).
- [TimerEvent]() - Description goes here. [Note: I have not seen this before.]
- [Time]() - Use date and time functions that provide support for time acquisition, conversion between date formats and formatted output to strings. [Note: Added.]
- [Wait]() - Use wait capabilities. [Note: Added.]
 
## NetworkSocket APIs
  /mbed-os/tools/mbed-docs/html/classNetworkInterface.html
  
- [Network sockets]() - Learn a common interface for using sockets on network devices. [Note: Added.]
- [Ethernet]() - Connect to the internet over an Ethernet connection using this C++ API.
- [Mesh networking]() - Learn how to use two IPv6 based mesh networks. [Note: Added.]
- [Wifi]() - Connect to the internet over a Wi-Fi device with this C++ API.
- [Cellular]() - Description goes here. [Note: I have not see nthis before.]

## Communication APIs
    /mbed-os/tools/mbed-docs/html/classNetworkInterface.html
    
- [Bluetooth Low Energy]() - Use Bluetooth Low Energy (BLE), a very low-power wireless technology standard for personal area networks.
- [LoRA]() - Description goes here.

## RTOS APIs

- [Interrupt service routines]() - Use a message from the queue to trigger an interrupt. [Note: Added.]
- [Mail]() - Use `mail` like a queue with the added benefit of providing a memory pool for allocating messages (not only pointers). [Note: Added.]
- [Mutex]() - Synchronize the execution of threads to protect the access to a shared resource, for example.
- [Queue and MemoryPool]() - Queue pointers to data from producer threads to consumer threads and define and manage fixed-size memory pools. [Note: Added "and MemoryPool".]
- [RTOS timer]() - Create and control time functions in the system.
- **[Semaphore](semaphore.md) - Manage thread access to a pool of shared resources of a certain type.**
- [Signals]() - Make threads wait for signals and be notified of events. [Note: Added.]
- [Thread]() - Use two separate threads to blink two LEDs.

## Event APIs

- [Event]() - Description goes here.
- [Event Queue]() - Description goes here.

## Other APIs

Note: This section taken from [here](https://docs.mbed.com/docs/arm-ipv66lowpan-stack/en/latest/06_API_introduction/).
- [Data structures, types and variables]() - Description goes here. [Note: Added.]
- [Device driver]() - Description goes here. [Note: Added.]
- [Dynamic memory]() - Description goes here. [Note: Added.]
- [Event-driven scheduling model & eventing]() - Description goes here. [Note: Added.]
- [IPv6/6LoWPAN Stack Initialization]() - Description goes here. [Note: Added.]
- [Library timer]() - Description goes here. [Note: Added.]
- [Network debug statistics]() - Description goes here. [Note: Added.]
- [Network definition]() - Description goes here. [Note: Added.]
- [Network layer control]() - Description goes here. [Note: Added.]
- [Platform]() - Description goes here. [Note: Added.]
- [Socket]() - Description goes here. [Note: Added.]
- [Thread stack]()- Description goes here. [Note: Added.]


## Further reading and examples

- [API Documentation](https://docs.mbed.com/docs/mbed-os-api-reference/en/latest/APIs/API_Documentation/) - Read about how to use the API documentation. [Note: To-do Move elsewhere.]
- [Further reading and examples](https://docs.mbed.com/docs/mbed-os-api-reference/en/latest/further_reading/) - Review more resources that may help you start working with mbed OS 5. [Note: To-do Move elsewhere.]
