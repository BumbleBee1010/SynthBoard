# SynthBoard
Synth board is a cross between a synthesiser and a soundboard. There is two rotary encoders, for volume and frequency, and 9 Mx switches the bottom 3 will control play/pause and scrubbing backwards and forward. The other 6 button will play custom prerecorded sounds upon pressing them, like a soundboard.
## Goals
My goal for the project is to help make or edit music. The rotary encoders will probably control volume and frequency. The MX switches will pause and play the audio and skip it forward and backward. I still need to decide exactly what the other MX switches will do but they will have a function. I took inspiration from other macro pads on the internet.

## PCB design 
At first I laid the switches in a 3 by 3 grid on the left, and the rotary encoders in the bottom right with the RP and ARGB ring above in the top right. The whole PCB was 110mm by 70mm. But it cost more than I thought. I looked at it and it was because the board was over 100mm by 100mm. Because of this, I narrowed my PCB to fit within the dimensions and I also added and moved some of the screw holes. I tried ordering it again and it was less, and it was at the cheaper price I expected.

<img width="700" height="462" alt="Screenshot 2026-10-16 074323" src="https://github.com/user-attachments/assets/82212503-533f-42e2-9d07-671591fcdc28" />

<img width="944" height="524" alt="Screenshot 2026-10-16 163836" src="https://github.com/user-attachments/assets/3955365b-3ea8-4033-940e-cd80103f6efe" />

## BOM
I found parts cheaply in AliExpress and the PCB on JLCPCB. This way I can maximise my $30 budget.


| Item | Qty | Supplier | Cost/item | Total Cost | Link |
| :--- | :---: | :--- | :---: | :---: | :--- |
| Gateron Milky Yellow Pro Switches 5 Pin(21pcs) | 1 | AliExpress | $7.56 | $7.56 | [Link](https://www.aliexpress.com/item/1005006605714880.html) |
| 20Pcs PBT Blank Keycaps | 1 | AliExpress | $5.55 | $5.55 | [Link](https://www.aliexpress.com/item/1005007683242914.html) |
| RP2040-Zero Microcontroller | 1 | AliExpress | $3.21 | $3.21 | [Link](https://www.aliexpress.com/item/1005008738491752.html) |
| 5PCS 20 Position Rotary Encoder EC11 blue with 15mm plum handle | 1 | AliExpress | $3.06 | $3.06 | [Link](https://www.aliexpress.com/item/1005007643925677.html) |
| Synth macro pad PCB (x5) | 1 | Jlc3dp | $4.00 | $4.00 | [Link](https://jlc3dp.com/shopcart/cart?source=3D) |
| Estimated total shipping | 1 | — | — | $5.04 | — |
| **Project Total** | | | | **$28.42** | |

## Code
Code will be done in the future (in a few weeks), I will use open source community library and will update when I have done it.
