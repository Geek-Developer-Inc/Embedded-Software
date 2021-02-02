# Embedded-software

## Introduction 

   An embedded system is a combination of computer hardware and software designed for a specific function. Embedded systems may also function within a larger system. 

#### Embedded systems basics

   It may be asked what is an embedded system. With many processor based systems and computers it is useful to define what an embedded system is. A convenient definition for an embedded system is: An embedded system is any computer system contained within a product that is not described as a computer.

   Using this embedded system definition it is possible to understand the various basic characteristics one. Typically they are:

   --Embedded systems are designed for a specific task. Although they use computer techniques, they cannot be used as a general purpose computer using a variety of different programmes for different task. In this way their function can be focussed onto what they need to do, and they can accordingly be made cheaper and more efficiently.
   
   --The software for embedded systems is normally referred to as firmware. Rather than being stored on a disc, where many programmes can be stored, the single programme for an embedded system is normally stored on chip and it is referred to as firmware.
   
   Embedded systems contain two main elements:

##### Embedded system hardware:

   As with any electronic system, an embedded system requires a hardware platform on which to run. The hardware will be based around a microprocessor or microcontroller. The embedded system hardware will also contain other elements including memory, input output (I/O) interfaces as well as the user interface, and the display.
   
##### Embedded system software:   

   The embedded system software is written to perform a particular function. It is typically written in a high level format and then compiled down to provide code that can be lodged within a non-volatile memory within the hardware.

#### Embedded systems hardware

   When using an embedded system there is a choice between the use of a microcontroller or a microprocessor.

   --Microcontroller based systems:   A microcontroller is essentially a CPU, central processor unit, or processor with integrated memory or peripheral devices. As fewer external components are needed, embedded system using microcontrollers tend to be more widely used
   
   --Microprocessor based systems:   Microprocessors contain a CPU but use external chips for memory and peripheral interfaces. As they require more devices on the board, but they allow more expansion and selection of exact peripherals, etc, this approach tends to be used for the larger embedded systems.
   
   Whatever type of processor is used in the embedded system, it may be a very general purpose type of one of the many highly specialised processors intended for a particular application. In some cases custom designed chips may be viable for a particular application if quantities are sufficiently high. One common example of a standard class of dedicated processor is the digital signal processor, DSP. This type of processor is used for processing audio and image files in particular. Processing is required very quickly as they may be used in applications such as mobile phones and the like.

#### Embedded systems software

   One of the key elements of any embedded system is the software that is used to run the microcontroller.

   There is a variety of ways that this can be written:

   --Machine code:   Machine code is the most basic code that is used for the processor unit. The code is normally in hex code and provides the basic instructions for each operation of the processor. This form of code is rarely used for embedded systems these days.
   
   --Programming language:   Writing machine code is very laborious and time consuming. It is difficult to understand and debug. To overcome this, high level programming languages are often used. Languages including C, C++, etc are commonly used.
   
   The code for the embedded system will typically be stored on a form of non-volatile memory held on the processor board. The code is called firmware - the idea is that it is not updated in the same way that software is, being held in the embedded system and it cannot be changed by the user. Often it is possible to update the software, but this can mean changing the memory card on which the firmware is held, or by updating it in another way.

   Often additional tools may be used to help with the development of the firmware. Often programmes can become complicated and it is necessary to ensure the firm ware for the embedded system operates correctly.

## Contribute

    Azure RTOS:    https://github.com/azure-rtos
   
    µC/OS-II and µC/OS-III:       https://www.micrium.com/downloadcenter/
   
 
## Cloning the repo

    $ git clone https://github.com/GeekDevelope/Embedded-software.git

   
