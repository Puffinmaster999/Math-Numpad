# Math Numpad
This is a [**Hack Club**](https://hackclub.com) project!

This is a math-focused numpad designed in [Ergogen](https://ergogen.xyz/) and [KiCad](https://www.kicad.org/)

---

## Why I Made This
I first saw this amazing [YouTube video](https://youtu.be/7UXsD7nSfDY) where Christian Selig made a custom keyboard that suited his liking perfectly! However, the keyboard that I am using is so good for my personal liking that I didn't want to change my entire keyboard. Rather as a student still doing math, I thought that it would be nice to have a numpad that would be custom made for me! 

The layout of the numpad was inspired by the **Casio FX-300ES PLUS 2nd Edition calculator**. It has a lot of the necessary math functions and I was able to use this as my base to add my personal functions on top of. If you look at the overall layout of the keyboard it will be similar to the math functions that exist on this calculator! However, the most important thing for me was the ability for the numpad to be able to do some math! This way if I want to use this as a calculator, I can! the only issue that I see is that this might not be allowed for online tests, for personal use however I think this is a perfect tool!

## Screenshots & Layout Plan
<img width="769" height="654" alt="Screenshot 2026-11-20 at 10 17 24 PM" src="https://github.com/user-attachments/assets/9458d817-cfd4-49b0-9459-d69d48f8604e" />
<img width="1121" height="402" alt="Screenshot 2026-11-20 at 10 17 35 PM" src="https://github.com/user-attachments/assets/a40ed69e-6c31-4806-86c9-91438a964017" />
<img width="694" height="605" alt="Screenshot 2026-11-20 at 9 13 09 PM" src="https://github.com/user-attachments/assets/29a54aae-23c2-4cec-8a73-3bcabb44c79d" />
<img width="1004" height="879" alt="Screenshot 2026-11-22 at 10 30 17 AM" src="https://github.com/user-attachments/assets/da119aa9-7fd5-430c-a413-35931cb92cae" />

## Tech Stack & How It Was Made
- Layout: Ergogen
- PCB Design: KiCAD
- Firmware: ZMK (**WIP**)

Following the YouTube video I first got used to how Ergogen worked and designed a rough outline. Although that rough outline wasn't the worst, looking back I feel like I could have thought out my design better. That file is located [here](math_numpad.dxf). I brought that into KiCAD and that's where most of the thinking began. Here I decided to do some real design choices and figured out how I really wanted the keyboard to feel like. I even used some paper to see if I would like the feel. After all of that is done I needed to make sure that the work that I did is reproducible and someone else can use! This is this GitHub project! Hope you enjoy!~

## BOM (Bill of Materials)
|Part|Quantity|Link/Notes|
|---|---|---|
|Microcontroller|1|[nice!nano](https://typeractive.xyz/products/nice-nano)|
|Rotary Encoder (Knob)|2|[Bourns PEC11R](https://www.digikey.com/en/products/detail/bourns-inc/PEC11R-4220F-S0024/4499660)|
|MX Switches|27|Any MX-style switches you prefer!|
|Keycaps|27|MX compatible keycaps! (2 2u size switches)|
|Diodes|27|Any standard 2-pin SOD-123 package diode|

## Repo Files & How to Build It
- KiCAD Project: math_numpad.kicad_pcb, math_numpad.kicad_prl, math_numpad.kicad_pro
- Gerbers: production/math_numpad_gerbers.zip

1. Download [production/math_numpad_gerbers.zip](production/math_numpad_gerbers.zip) and upload it to a PCB manufacturer (like JLCPCB or PCBWay).
2. Solder the diodes, switches, rotary encoders, and nice!nano onto the PCB
3. **WIP** flash the firmware

## AI disclosure
A very small amount of ai was used during the research phase! No ai was used during the PCB, and shipping process of this project!
