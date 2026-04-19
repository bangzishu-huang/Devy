# Devy
My own first-ever custom devboard! It will also include a LED which turns on and off.

This project was one of the first times I designed a complex PCB and I'm going to be honest it was really hard to learn how to create this at first. I think I spent around 3-4 days trying to understand how to do everything, from the schematics to the actual PCB design. In the end, though, I'm really happy that I was able to learn how to create it and this will probably be one of those projects I'll remember for a very long time.

# Final Pictures
Here are the pictures of my devboard after it was successfully soldered!
- Front
- <img width="3024" height="4032" alt="IMG_5330" src="https://github.com/user-attachments/assets/41023fd1-53b7-4f3e-8803-7735bd06ec50" />

- Back
- <img width="3024" height="4032" alt="IMG_5331" src="https://github.com/user-attachments/assets/445c4329-8185-4edf-9685-cba40b85e96c" />


# PCB
I used KiCad for every step of creating Devy, and it saved me a lot of time I would say.

- Schematic
- <img width="945" height="678" alt="Schematic" src="https://github.com/user-attachments/assets/894d7000-241c-4217-b31d-16445d5cfa58" />

- PCB with zones (GND as net)
- <img width="388" height="766" alt="PCB" src="https://github.com/user-attachments/assets/8ab8116f-a6b5-4643-9353-7ba41f703e6a" />

# 3D Model
Below are views of Devy taken through KiCad's 3D model viewer. I have to say my silkscreen is the best.

- Front
- <img width="2162" height="1256" alt="Front" src="https://github.com/user-attachments/assets/46daed17-c47b-41f3-a47f-65515dc43232" />

- Back
- <img width="2162" height="1256" alt="Back" src="https://github.com/user-attachments/assets/9ef11b9d-b611-431f-8dee-6d6c06855829" />

# Firmware
Here, I used KMK to just make the LED turn on and off. It acts as a check up on the devboard to make sure everything would work.

# BOM (Bill of Materials)
|Quantity|Footprint|
|---|---|
|15|C_0402_1005Metric|
|8|R_0402_1005Metric|
|2|C_0603_1608Metric|
|2|PinHeader_1x20_P2.54mm_Vertical|
|1|PinHeader_1x03_P2.54mm_Vertical|
|1|Crystal_SMD_3225-4Pin_3.2x2.5mm|
|1|SW_Push_SPST_NO_Alps_SKRK|
|1|USB_C_Receptacle_HRO_TYPE-C-31-M-12|
|1|QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm|
|1|LED_WS2812B-2020_PLCC4_2.0x2.0mm|
|1|Winbond_USON-8-1EP_3x2mm_P0.5mm_EP0.2x1.6mm|
|1|SOT-23|




