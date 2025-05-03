# mt32-pi-bay
A 5.25" bay panel overlay to control the mt32-pi. 
\
\
![front](front.png)
\
![front2](front-real.png)
## Info
The core project design is attributed to Dale Whinham and his awesome mt32-pi project. Repo link: https://github.com/dwhinham/mt32-pi
\
\
This PCB I designed is a 5.25" bay front panel overlay to control the mt32-pi system. It features a power LED, 1.3" OLED, two push buttons, rotary encoder knob, MIDI input jack, and a 3.5mm headphone output jack.
\
\
I have included the full KiCad project along with the Mouser Cart, BOM, and Gerber files for ease of upload.
\
\
This is designed for use with my mt32-pi-zero-breakout project found here: https://github.com/wiretap-retro/mt32-pi-zero-breakout/

## Parts
The parts in the BOM and Mouser Cart are for building a blue illuminated unit. You can easily choose other colors, however you will need to change the resistors to different values since the forward voltage of the LED will be different.
\
\
Please read the original mt32-pi repository linked in the information section for compatibility of parts if you fork the design or deviate from the chosen parts.

## Assembly
- First solder all the components to the board. To keep the screen low-profile, no pin header socket should be used.
- Solder your wire pigtails to the DIN connector and 3.5mm connector.
- Next, insert the DIN and 3.5mm receptacles into the panel and secure them with the lock nuts.
- Test fit the assembled PCB to the StarTech bay adapter. If there are any interfernces, trim the bay adapter face with side cutters, a dremel or other cutting tool.
- Smear a thin layer of silicone caulk on the bay panel face.
- Set the PCB onto the wet caulk and apply a small amount of force to allow the caulk to adhere. Align it with the edges.
- Allow a dry time of 24hrs so it fully cures to the bay adapter. You may want to use small rubberized clamps to assist with the holding force during the cure time.
- Mount your mt32-pi into the StarTech bay adapter and connect the 2.54mm pitch DuPont connectors to the panel header.

## License
This project uses the UNLICENSE. Feel free to do what you want with it. Check over the project before ordering. Build at your own risk.
