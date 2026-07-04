# Corne Indian ⌨️

A split mechanical keyboard **inspired by the original [CRKBD (Corne)](https://github.com/foostan/crkbd)** by [foostan](https://github.com/foostan). While the overall keyboard layout, key positions, and form factor follow the Corne design, the **entire schematic and PCB layout have been redesigned from scratch**.

The hardware has been engineered with a focus on the **Indian maker ecosystem**, using components that are readily available from Indian suppliers. The PCB has been designed to simplify manufacturing, assembly, troubleshooting, and long-term maintenance. If a component fails, it can be replaced easily without requiring hard-to-source imported parts — making the keyboard highly repairable and practical for everyday use.

---

## Highlights

- **Inspired by the CRKBD (Corne) split keyboard design**
- **Complete schematic designed from scratch**
- **Complete PCB layout designed from scratch**
- **Powered by RP2040** — affordable, powerful, and widely available in India (replaces the Pro Micro / ATmega32U4)
- **Hot-swappable switches** — no soldering required for switches
- Optimized for components that are **easily available from Indian suppliers**
- Designed for **easy manufacturing and assembly**
- Simplified **rework and repair** with accessible component placement
- **Fully open-source hardware** — anyone can build, modify, and maintain

---

## Design Files

All design files are in [`pcbs/corne-indian/`](pcbs/corne-indian/):

```
pcbs/corne-indian/corne-inidan-hotswap/
├── corne-inidan-hotswap.kicad_pro    # KiCad project
├── corne-inidan-hotswap.kicad_sch    # Main schematic
├── corne-inidan-hotswap.kicad_pcb    # PCB layout
├── left.kicad_sch                    # Left half schematic
├── right.kicad_sch                   # Right half schematic
├── corne-inidan-hotswap.step         # 3D model
└── corne_ibom.html                   # Interactive BOM
```

> Designed in **KiCad**. Open the `.kicad_pro` file to get started.

---

## Images

### Original CRKBD (Corne) — The Inspiration

![crkbd-cherry](https://github.com/foostan/crkbd/assets/736191/f954ba89-a711-4866-a535-bad0bed937d1)
![crkbd-chocolate](https://github.com/foostan/crkbd/assets/736191/fb0e6962-76b3-4bd5-8093-83ccc1a17029)

### Corne Indian — Our Design

<!-- TODO: Add Corne Indian PCB render (top view) -->
![Corne Indian PCB Top](https://via.placeholder.com/800x600/1a1a2e/e0e0e0?text=Corne+Indian+-+PCB+Top+View)

<!-- TODO: Add Corne Indian PCB render (bottom view) -->
![Corne Indian PCB Bottom](https://via.placeholder.com/800x600/1a1a2e/e0e0e0?text=Corne+Indian+-+PCB+Bottom+View)

<!-- TODO: Add assembled Corne Indian keyboard photo -->
![Corne Indian Assembled](https://via.placeholder.com/800x600/16213e/e0e0e0?text=Corne+Indian+-+Assembled+Keyboard)

<!-- TODO: Add Corne Indian 3D render -->
![Corne Indian 3D Render](https://via.placeholder.com/800x600/0f3460/e0e0e0?text=Corne+Indian+-+3D+Render)

---

## Comparison: Original CRKBD vs Corne Indian

| Feature | Original CRKBD | Corne Indian |
|---|---|---|
| **Microcontroller** | Pro Micro (ATmega32U4) | RP2040 |
| **Switch mounting** | Soldered / Hotswap | Hot-swappable |
| **Component sourcing** | International | India-focused |
| **Schematic** | Original by foostan | Redesigned from scratch |
| **PCB Layout** | Original by foostan | Redesigned from scratch |
| **License** | MIT | MIT |

---

## Credits

This project stands on the shoulders of the excellent **[CRKBD (Corne)](https://github.com/foostan/crkbd)** by **foostan**. The Corne Indian retains the same split-keyboard layout and form factor that makes the Corne great, while re-engineering the hardware for the Indian maker community.

---

## License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.
