```
                    
               __  __     __    __     __  __     ______     __  __     ______    
              /\ \/\ \   /\ "-./  \   /\_\_\_\   /\  == \   /\ \/\ \   /\  ___\   
              \ \ \_\ \  \ \ \-./\ \  \/_/\_\/_  \ \  __<   \ \ \_\ \  \ \___  \  
               \ \_____\  \ \_\ \ \_\   /\_\/\_\  \ \_____\  \ \_____\  \/\_____\ 
                \/_____/   \/_/  \/_/   \/_/\/_/   \/_____/   \/_____/   \/_____/ 
                                         
                                   Universal Module eXplorer
                                                                 
```

The `UMXbus` is an open hardware project which goal is to establish a low-level computer development platform for educational purposes. This is also the name of its inter-module communication bus.

The platform is composed of eurocard modules mounted in a 3U rack.

## Compute Module

The **Compute module** is an SoPC development module that will interface with other modules on the `UMX` bus.
It includes :
- A Spartan 3E FPGA on which processing cores can be implemented
- A USB to JTAG interface providing ISP to the FPGA
- A USB to SPI interface for programing the FPGA configuration flash as well as a user available flash
- A USB to UART interface for debugging purposes
- A DIN41612 connector dedicated to the `UMX` bus
