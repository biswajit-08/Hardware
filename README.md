# AC-DC Converter PCB

A custom AC-DC converter circuit and PCB designed using **KiCad**.

This project contains the complete schematic and PCB layout, including component placement, routing, and design files.

> ⚠️ **Safety Warning:** This project may involve hazardous mains voltage. Do not build, modify, test, or operate the circuit unless you understand electrical safety practices and have appropriate isolation, protection, equipment, and supervision.

---

## 📌 Project Overview

The objective of this project is to design a compact and organized PCB for an AC-DC power conversion circuit.

The project covers:

- Circuit schematic design
- Component selection
- PCB layout
- Component placement
- PCB routing
- Design-rule checking
- KiCad project management

---

## 🛠️ Design Software

| Tool | Purpose |
|---|---|
| KiCad | Schematic and PCB design |
| Git | Version control |
| GitHub | Project hosting and collaboration |

---

## 📁 Project Files

```text
AC-DC Converter/
│
├── AC-DC Converter.kicad_pro   # KiCad project
├── AC-DC Converter.kicad_sch   # Schematic
├── AC-DC Converter.kicad_pcb   # PCB layout
└── README.md                   # Project documentation
```

### KiCad Files

**`.kicad_pro`**

Contains the KiCad project configuration.

**`.kicad_sch`**

Contains the complete circuit schematic.

**`.kicad_pcb`**

Contains the PCB layout, including:

- Board outline
- Component footprints
- Component placement
- Copper tracks
- Routing
- PCB layers
- Design rules

---

## ⚡ Electrical Specifications

> Replace the values below with the actual specifications of your design.

| Parameter | Value |
|---|---|
| Input Voltage | TBD |
| Input Frequency | TBD |
| Output Voltage | TBD |
| Output Current | TBD |
| Output Power | TBD |
| Converter Topology | TBD |
| Isolation | TBD |
| PCB Layers | TBD |
| PCB Dimensions | TBD |

---

## 🔌 Functional Block Diagram

```text
        AC INPUT
           │
           ▼
   ┌─────────────────┐
   │ Input Protection│
   └────────┬────────┘
            │
            ▼
   ┌─────────────────┐
   │ Rectification   │
   └────────┬────────┘
            │
            ▼
   ┌─────────────────┐
   │ AC-DC Conversion│
   │ / Switching     │
   └────────┬────────┘
            │
            ▼
   ┌─────────────────┐
   │ Filtering       │
   └────────┬────────┘
            │
            ▼
        DC OUTPUT
```

> Update this block diagram to match the actual topology of your converter.

---

## 🧩 Main Components

The PCB contains the major components required for the converter, including:

- Input protection components
- Rectifier section
- Switching/conversion stage
- Transformer or isolation stage, if applicable
- Filtering components
- Voltage regulation/control circuitry
- Output terminals/connectors

The exact component values and part numbers are available in the KiCad schematic.

---

## 🎨 PCB Design

The PCB was designed with attention to:

- Component placement
- Signal routing
- Power routing
- Ground connections
- Clearance
- Track width
- Thermal considerations
- High-voltage and low-voltage separation

### PCB Design Stages

```text
Schematic
    │
    ▼
Component Selection
    │
    ▼
Footprint Assignment
    │
    ▼
PCB Placement
    │
    ▼
Routing
    │
    ▼
Design Rule Check
    │
    ▼
Fabrication
    │
    ▼
Assembly & Testing
```

---

## 🔍 Design Validation

Before fabrication, the design should be checked for:

- [ ] Electrical Rule Check (ERC)
- [ ] Design Rule Check (DRC)
- [ ] Unconnected nets
- [ ] Clearance violations
- [ ] Track-width requirements
- [ ] Component orientation
- [ ] Polarity of components
- [ ] Connector pinout
- [ ] Thermal requirements
- [ ] High-voltage clearance and creepage

---

## 🏭 Fabrication

Gerber and drill files can be generated from KiCad when the PCB is ready for manufacturing.

Recommended fabrication outputs:

```text
Fabrication/
├── Gerber files
├── Drill files
├── Board outline
├── Copper layers
├── Solder mask
├── Silkscreen
└── Fabrication drawings
```

---

## 🧪 Testing Plan

After fabrication and assembly, testing should be performed progressively.

### 1. Visual Inspection

Check:

- PCB damage
- Solder bridges
- Component orientation
- Incorrect component values
- Polarity
- Connector placement

### 2. Continuity Testing

Verify:

- No unintended short circuits
- Ground continuity
- Expected connections

### 3. Power-Up Testing

Use appropriate current limiting and isolation equipment.

Verify:

- Input behavior
- Output voltage
- Output ripple
- Temperature
- Current consumption
- Protection behavior

### 4. Load Testing

Test the converter with progressively increasing loads while monitoring:

- Output voltage
- Output current
- Temperature
- Efficiency
- Stability

---

## 📷 Project Images

Add PCB renders, schematic screenshots, and photographs here.

Example:

```text
images/
├── schematic.png
├── pcb-layout.png
├── pcb-3d-front.png
└── pcb-3d-back.png
```

Then display them using:

```markdown
![PCB Layout](images/pcb-layout.png)
```

---

## 📈 Future Improvements

Possible future improvements include:

- Improved thermal management
- Better PCB isolation
- Improved EMI/EMC performance
- Additional protection circuitry
- Status indicators
- Improved enclosure design
- Efficiency optimization
- Production-ready component selection
- Automated testing

---

## 📜 Version History

| Version | Description |
|---|---|
| v0.1 | Initial schematic and PCB design |
| v0.2 | PCB routing completed |
| v0.3 | Testing and validation |
| v1.0 | Final release |

---

## 👨‍💻 Author

**Biswajit Sahu**

Electrical & Electronics Engineering  
VSSUT, Burla

GitHub: [biswajit-08](https://github.com/biswajit-08)

---

## 📄 License

Choose an appropriate license before distributing the design commercially or for reuse.

---

## ⚠️ Disclaimer

This project is provided for educational and engineering purposes.

If the circuit interfaces with hazardous voltages, appropriate electrical safety procedures must be followed. The designer/user is responsible for validating the design, component ratings, PCB clearances, isolation, protection, and compliance requirements before applying power.
