![Alt text](images/logo.png?raw=true&=200x "ochin_CM4")
![Alt text](images/BartopArcade_ochin_CM4v2_side.jpg?raw=true&=200x "Bartop Arcade ochin_CM4v2")
# Bartop Arcade ochin_CM4v2

The Bartop Arcade ochin_CM4v2 is a retro-console based on [Retropie](https://retropie.org.uk/), a software that allows the user to emulate various consoles from years gone by, it's a bit retro and geeky, but also romantic for those like me who lived through those times.

I wanted to make this retro-console in such a way that it was reminiscent of video games from the old days, but at the same time modern and elegant enough to be installed in a flat.

This project concerns the construction of the cabinet and the connection of the electronic devices necessary for its operation. Of course, this is not meant to be an exhaustive or even generic guide for creating a retro-console... it is just my interpretation, and anyone who likes it can copy it and even improve on it.

## Woodwork
The cabinet was handmade by me. In this repository you will find both the design source files, made with [Freecad](https://www.freecad.org) in case you want to make changes. There are also pdf files of the design views with measurements shown, should you want to get right to work!

![Alt text](images/project_drawing_ISO.jpg?raw=true&=200x "Bartop Arcade ochin_CM4v2 ISO")

The cabinet consists of three wooden parts, the front panel and the two side panels. The front panel is made of 10mm plywood, while the two side panels were made of OSB (as a matter of aesthetic taste).

To make the bending of the front panel, I made longitudinal cuts near the bends, so as to weaken the panel and be able to bend it. This technique is called Kerf Cut.

![Alt text](images/BartopArcade_ochin_CM4v2_inside_dwn.jpg?raw=true&=200x "Bartop Arcade ochin_CM4v2 kerf")

To add strength to the structure, at the back I mounted two wooden slabs attached to the side walls.

![Alt text](images/BartopArcade_ochin_CM4v2_back.jpg?raw=true&=200x "Bartop Arcade ochin_CM4v2 back")


## Hardware
As a microprocessor board I decided to use a [Raspberry Pi CM4 module](https://www.raspberrypi.com/products/compute-module-4/?variant=raspberry-pi-cm4001000) , this is the industrial Raspberry Pi 4 module, mounted on a carrier board of my own design. 

![Alt text](images/Ochin_CM4_main_top_back.jpg?raw=true&=200x "ochin_CM4v2")
![Alt text](images/IMG_20230827_132848.jpg?raw=true&=200x "ochin_CM4v2")

If you are wondering why not use a normal RPI4... the answer is that having purchased several CM4 modules for my ochin_CM4 project and given the near-impossibility of finding Raspberry Pi, I found it logical to use what I had at home. 

It was also interesting to test my ochin_CM4 project in a completely new environment such as gaming. In fact, the ochin_CM4 project was made for the purpose of managing robots, drones, planes, IOT devices... but why not also use it for gaming! Being very small in size, it could be useful for those who want to make small consoles for example...

If you are interested in learning more about my [ochin_CM4v2](https://github.com/ochin-space/ochin-CM4v2) project, you can consult the github repo dedicated to it and possibly purchase it from the [marketplace of Seeedstudio](https://www.seeedstudio.com/), the company that produces and sells it.

## Important!!
In case you are interested in the board be very careful to look for the ochin_CM4v2, which provides a uHDMI port as a digital video output. As of today's date (09/2023), version v2 is not yet available for purchase, and version v1 is not compatible with this project, as it does not have uHDMI output.