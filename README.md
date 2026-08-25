# DJI D-Log2 to ACES IDT for DaVinci Resolve

A mathematical ACES Input Device Transform (IDT) written in DCTL, designed to bridge DJI D-Log2 / D-Gamut2 footage natively into ACES workflows (ACES2065-1 / AP0 Linear).
Filling the gap until an official implementation is released


Transfer Function:

  * Decodes D-Log2 into unscaled scene-linear values ($0.18$ gray = $0.18$).

Color Primary Alignment: 

  * Converts D-Gamut2 directly to ACES AP0 primaries.

Native IDT Integration: 

  * Registers as a native drop-down option in DaVinci Resolve’s ACES Color Management and ACES Transform FX nodes.


---
Install Location:

macOS:
```
~/Library/Application Support/Blackmagic Design/DaVinci Resolve/ACES Transforms/IDT/
```
Windows:
```
%APPDATA%\Blackmagic Design\DaVinci Resolve\Support\ACES Transforms\IDT\
```

# Example

<img width="1280" height="720" alt="DLog2_IDT_example" src="https://github.com/user-attachments/assets/df69fd97-ceaf-40b7-8be3-cfac2716118f" />


<img width="731" height="453" alt="resolve_idt_usgae" src="https://github.com/user-attachments/assets/e0e6792f-5f99-49fe-aed6-6e179c4951c6" />
