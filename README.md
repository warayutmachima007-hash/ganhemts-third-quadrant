# GaN HEMT third-quadrant conduction

Interactive explainer: how a GaN HEMT conducts reverse current during dead time without a body diode — the inductor pulls the low-side drain below the gate until the channel turns on from the drain side.

**Live page:** https://warayutmachima007-hash.github.io/ganhemts-third-quadrant/

- Animated half-bridge, terminal-voltage ladder, switch-node waveform and device cross-section
- Governing equation: V_SD = V_th + |V_GS(off)| + I_L·R_DS(on)
- References: TI SNVAA94, TI SNOAA36, EPC AN009, Barba et al. (EPE'23), Infineon AN152548

Educational illustration. Values are representative of a 650 V, 40 mΩ-class e-mode GaN HEMT, not taken from any vendor datasheet. Views are my own.
