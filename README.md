# Bento Pad Design and Development
#### Client Name: Anthony Arii

## Project Requirements
Designing custom macropad keyboards called the Bento Pad, inspired by a bento box. It will come in 3 versions:
 
### 1. Bento Pad – No knobs, just keys
![image](https://github.com/user-attachments/assets/962930be-edaf-4ecb-b374-74b41a78daa5)

### 2. Bento Pad Plus – Includes 3 rotary encoders (knobs) in a vertical layout on the far right side
![image](https://github.com/user-attachments/assets/a9e90df3-122a-4d45-ae76-642d13f525df)

### 3. Bento Pad Mini - Small 5 key 1 knob layout
![image](https://github.com/user-attachments/assets/9d1c6854-b18a-4ce9-b619-432587009757)

Some core requirements are:
- PCB will be hot-swappable, allowing users to change their switches easily.
- PCB Dimensions & Layout – Based on the Figma prototypes (attached as images above)
- Number of Keys – 21 keys
- Hot-Swappable Sockets – Kailh or Mill-Max sockets preferred
- USB Connection – USB-C, positioned at the top center
- Rotary Encoders (Bento Pad Plus and Mini Only) – 3 encoders in a vertical row on the right side, 1 on the top right for the mini version
- Diodes for NKRO – To prevent ghosting and allow full key rollover
- Firmware Compatibility – QMK/VIA support for easy key remapping
- Mounting Style – Tray-mount or top-mount compatible
 
Deliverables Needed:
 
📁 Gerber files (for PCB manufacturing)
📁 BOM (Bill of Materials) – List of all components used
📁 KiCad or Altium Design Files (if applicable, for future modifications)
📁 Schematic & Board Layout Preview before finalizing the design
