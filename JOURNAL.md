---
Title: Ducky Mouse
Author: MrDuck354
Description: A fully DIY mouse made using a custom PCB and a 3D printed case to replace my current broken one.
Created on: 25/08/2026
---

# August 25th: Starting my project

I started my project by doing some research into how a mouse works and how to create my own, I first started researching the PCB because designing my own is my first step due to the fact that I have to model my case around the PCB. Through my research I found a video by [wareya](https://www.youtube.com/watch?v=h-Cdl4Vq9H4&t=10s_) which documents his process through making his own DIY mouse and his GitHub repo was a big help. I looked through his PCB schematic and learned what I needed.
His PCB has the microcontroller built into the board but I decided to use a separate microcontroller instead. Because I wanted a wireless mouse I debated between an ESP32 and a nRF52840 based board which both have bluetooth HID capabilites which I need for a mouse. I ultimately decided upon the nRF52840 based board because it was smaller and less power hungry which would be ideal for me, I went for this board from Elecrow

<img width="939" height="902" alt="Screenshot 2026-08-25 192601" src="https://github.com/user-attachments/assets/e9c374e6-81e1-4223-b6e4-88167a4aa7f3" />

I then found 5 switches (for the two main ones, the middle one and the two side buttons), a rotary encoder (for the scroll wheel), a 300mAh battery (to power everything) and a TP4056 charging board (to charge the battery) on AliExpress (photos below)

<img width="1919" height="957" alt="Screenshot 2026-08-25 194514" src="https://github.com/user-attachments/assets/4208908b-998b-4480-bb20-4b26455e0d60" />
<img width="1919" height="958" alt="Screenshot 2026-08-25 195950" src="https://github.com/user-attachments/assets/01b25025-0094-48ac-bf00-1a76ff783806" />
<img width="1696" height="960" alt="Screenshot 2026-08-25 203735" src="https://github.com/user-attachments/assets/4adf5cbf-f8f8-4fa6-9936-75cd505d669a" />
<img width="1695" height="959" alt="Screenshot 2026-08-25 203623" src="https://github.com/user-attachments/assets/509067d1-94ed-48d8-a6d1-3ef6ee2d8e5e" />

Finally I added these to my KiCad schematic. I haven't done anything with them yet but that will be for tomorrow.

<img width="1919" height="1079" alt="Screenshot 2026-08-25 202644" src="https://github.com/user-attachments/assets/d278d611-d5bc-4384-8b01-7e561fd27065" />

Next Steps:
My next steps will be to continue on my research, adding the rest of the components I need and adding labels to them to prepare to actually create the pcb

**Total time spent: 2.5 hours**
