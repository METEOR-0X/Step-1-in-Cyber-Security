# Before learning about security, we need to understand the computer we use and how it works
## 1- Inside a computer :
Inside a computer, all the elements are like our body: the motherboard is the skeleton and nerves, RAM is short-term memory, the PSU is the heart and lungs, the HDD or SSD is long-term memory, the GPU is the visual cortex, and the CPU is the brain.
## 2- when you click in start button :
- When you press the power button, a signal is sent to the PSU to allow power to flow.
- When the components start running, they lack the awareness to know what to do. That is made possible by a program already stored on the motherboard, which is UEFI, or what we can also call BIOS.
- Now, all components need to be fully functional and present. This is also something UEFI or BIOS can do for us; it tests all the components to make sure they are working properly and that everything the system needs is available.
- In the 'Select Boot Device' step, UEFI is involved again. Now it starts prioritizing and specifying which storage devices to check first in order to boot up our operating system.
- Once the system identifies the boot device, the bootloader is initiated to copy the Operating System from storage into Random Access Memory (RAM). After the OS is fully loaded, UEFI relinquishes hardware control to the Operating System.
