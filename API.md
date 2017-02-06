# mbed OS APIs

## Peripheral APIs
Driver Group - mbed-os/tools/mbed-docs/html/classmbed_1_1*

- [AnalogIn]() - Read an external voltage applied to an analog input pin.
- [AnalogOut]() - Description goes here.
- [BusIn]() - Description goes here.
- [BusInOut]() - Description goes here.
- [BusOut]() - Description goes here.
- [CANMessage]() - Description goes here. [Note: I have not seen this before.]
- [CAN]() - Description goes here.
- [DigitalIn]() - Description goes here.
- [DigitalInOut]() - Description goes here.
- [DigitalOut]() - Description goes here.
- [DirHandle]() - Description goes here. [Note: I have not seen this before.]
- [FileHandle]() - Description goes here. [Note: I have not seen this before.]
- [FileSystemLike]() - Description goes here. [[Note: I have not seen this before.]
- [I2C]() - Description goes here.
- [I2CSlave]() - Description goes here.
- [InterruptIn]() - Description goes here.
- [InterruptManager]() - Description goes here. [Note: I have not seen this before.]
- [LocalFileSystem]() - Description goes here. [Note: I have not seen this before.]
- [LowPowerTicker]() - Description goes here. [Note: I have not seen this before.]
- [LowPowerTimeout]() - Description goes here. [Note: I have not seen this before.]
- [LowPowerTimer]() - Description goes here. [Note: I have not seen this before.]
- [PortIn]() - Description goes here.
- [PortInOut]() - Description goes here.
- [PortOut]() - Description goes here.
- [PwmOut]() - Description goes here.
- [Serial]() - Description goes here.
- [SPI]() - Description goes here.
- [SPISlave]() - Description goes here. [Note: Added.]
- [Ticker]() - Description goes here.
- [Timeout]() - Description goes here.
- [Timer]() - Description goes here.
- [TimerEvent]() - Description goes here. [Note: I have not seen this before.]
- [Time]() - Description goes here. [Note: Added.]
- [Wait]() - Description goes here. [Note: Added.]
 
## NetworkSocket APIs
  /mbed-os/tools/mbed-docs/html/classNetworkInterface.html
  
- [Network sockets]() - Learn a common interface for using sockets on network devices. [Note: Added.]
- [Ethernet]() - Description goes here.
- [Mesh networking]() - Description goes here. [Note: Added.]
- [Wifi]() - Description goes here.
- [Cellular]() - Description goes here.

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
