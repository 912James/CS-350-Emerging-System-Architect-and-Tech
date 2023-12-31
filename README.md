# CS-350-Emerging-System-Architect-and-Tech
SNHU CS-350 Emerging System Architect and Technology

# Summarize the project and what problem it was solving.

The global smart thermostat market is forecast to reach almost $9 billion by 2026. The CEO of SysTec wants to get into this lucrative market and has tasked your engineering department with creating a smart thermostat using the TI board. SysTec develops analytics software for servers, but the CEO remembers from your interview that you took an embedded systems course and asks you to build a prototype. The final goal is to develop a thermostat that sends data to SysTec’s server software over Wi-Fi, but first they need a prototype of the low-level thermostat functionality working.

For the prototype, you will use the TMP006 temperature sensor to read the room temperature (via I2C), an LED to indicate the output to the thermostat where LED on = heat on (via GPIO), two buttons to increase and decrease the set temperature (via GPIO interrupt), and the UART to simulate the data being sent to the server.

You will also create a written report for your team to ensure that the system you created is based on SysTec’s business requirements and technical specifications. While your team is testing your code, you have been asked to architect the next phase of the project in your report: connecting the thermostat to the cloud. Although you prototyped on the TI development board, other manufacturers make integrated Wi-Fi solutions. In this next phase, you are going to analyze various hardware architectures (from TI, Microchip, and Freescale) and recommend and justify the architecture decision based on the following business requirements:

*** The thermostat must support the peripherals used in the project. ***
*** The thermostat must connect to the cloud via Wi-Fi. ***
*** The architecture chosen must have enough Flash and RAM to support the code. ***

# What did you do particularly well?

In this project, I believe my biggest strength was in coding the thermostat to perform the necessary requirerments. I worked on the project for a couple weeks to esnure that the functions that were needed, performed beyond expectations. I also did a good job creating the task scheduler and displayng the different functionalities.

# Where could you improve?

I could improve in writing more comments for all the code i write. I have the tendency to assume that the person reading the code knows what the implemntation of the software is intended to perform. Throughout the project I had to remind myself to go back and write comments to, remind myself of what steps ive taken and to show the readers what the code does.

# What tools and/or resources are you adding to your support network?

I enjoyed using Code Composer to create the different systems throuhgout this course. I liked that we had the ability to pick many different projects from within the IDE, only requiring that the microcontroller was connected and the code was functional. Texas instruments provides a wealth of information on how to code the microcontrollrs but also how to make them into functional devices that meet the users requirements.

# What skills from this project will be particularly transferable to other projects and/or course work?

The skills I learned from this project and course overall is how to take code, a microcontroller and create an embedded system using the C language. I was able to learn about programming microcontrollers, as well as learning about how to use the drivers, hardware and software together. This course was the first time I utilzed C and Code Composer, which allowed me to learn another programming language and its many capabilities.

# How did you make this project maintainable, readable, and adaptable?

For this project we reused the code from a previous milestone as the starter code, which made the project adaptable. I tried to have good coding practices in place when creating the projects by using descriptive names for variabes and functions, commenting the code, and properly using functions grouped together to perform the necessary tasks. I also utilzied the avaialble libraries and drivers to ensure the code and hardweare worked as intended.
