# Unit 1 - Designing a Computer-Controlled Reaction Game

Current circuits used in Tech and Design have been made of discrete or separate components. Integrated circuits are complete circuit in themselves.

The inventions of the IC was of great significance because it allowed complex electronic circuits to be made in a single small component.

The first working IC was produced in 1958. These first chips were used in defence and space equipment - they were at this tage very expensive to produc and could only be afforded by governments of more wealthy countries.

By 1963 ICs were starting to appear in commercial products such as hearing aids and calculators.

Even today, manufacturers are getting better at miniaturising ICs - think how small and intelligent your mobile phone is. This is achieved by packing complex circuitry onto a number of tiny ICs inside your phone.

## Construction of an IC

Silicon Chip - Using precision equipment, the various components which make up the circuit are formed on the tiny piece of silicon. A layer of metal is then printed on to connect up the components.

Plastic Case - This protects the silicon chip from damage and dust/dirt.

Notch/Dot - helps user to identify pin numbers on IC.

Metal Pins - Allow the IC to be plugged into a PCB

### Pin Layouts

In order to use an IC, we must be able to identify the legs or pins of the component. The IC we will use in the reaction game project has 8 legs but it is not unusal for an IC to have more.

<img width="301" height="360" alt="image" src="https://github.com/user-attachments/assets/d918edde-747e-44ad-9607-989571a457d1" />

The pins on the IC are numbered 1-8. Pin 1 is below the notch and next to the dot on the chip. The legs are then numbered as shown. We say that the IC comes in an 8-pin DIL package (dual in-line).

## The Microcontroller

A microcontroller is an electronic device, made in integrated circuit form, which is a small computer. It is sometimes called a computer on a chip. It can be connected to input and output devices (e.g. switches, light sensors, LEDs, motors) and it then controls what happens to these devices by means of a program created by a designer. Microcontrollers can be found in virtually all modern electronic devices. 

The Microcontroller that you will be using is known as a PIC. This stands for Peripheral Interface Controller. To use a PIC, you first build a circuit in which a number of input and output devices are interfaced (or connected) to the PIC. The circuit at first will not do anything - the PIC is purchased blank and has no programmed instructions. The user then writes a computer program to make the circuit work the way they want. When it has been finished and tested, the program can be downloaded onto the PIC and the circuit will now perform according to the program.

The overall process can be broken down into a number of steps:
1. The computer program is created using 'Circuit Wizard' software
2. The program is downloaded or burnt onto the PIC chip
3. The PIC chip circuit can now be disconnected from the computer and it will then control the outputs as instructed by program which has been downloaded onto it.

### What are the advantages of using Microcontrollers?

PICs are relatively recent technological innovation. They have a number of advantages over more old-fashioned electronics.

1. They can be reprogrammed as many times as you'd like. If you get the program wrong the first time you can just download a new one over the old. Smartphone manufacturers do this all the time. You reprogram the microcontroller in your phone by downloading the latest version of the operating system e.g. iOS or Android
2. You can attach a number of inputs and outputs to a single PIC and control them exactly as you want. The PIC Genie E24 can handle twelve inputs and eight outputs.
3. You don't have to be an electronics expert to use a PIC. It is possible to get familiar with software in a short period of time.

## Common Circuit Wizard Commands

Start - Begin the program

Outputs - Sets the outputs to a pattern

Wait - Pause for a period of time

Digital - Test inputs with questions

Sound - Play sound effect of musical note

Tune - Play built-in tune

Learn the Shapes.

All outputs have the same shape (outputs, sound, tune)
Start and End have the same shape