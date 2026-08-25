# DJI D-Log2 to ACES IDT for DaVinci Resolve

A mathematical ACES Input Device Transform (IDT) written in DCTL, designed to bridge DJI D-Log2 / D-Gamut2 footage natively into ACES workflows (ACES2065-1 / AP0 Linear).

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

# Examples
