# VCO #

### Analogue Voltage-Controlled Oscillator ###

<!-- TODO: add a photo, e.g. pictures/vco_front.jpg
<p align="center">
  <img src="pictures/vco_front.jpg" alt="VCO front panel" width="50%">
</p>
-->

VCO is a compact, fully analogue oscillator in 6 HP. Its core is a classic exponential converter built around a matched transistor pair, thermally coupled to a tempco resistor for stable tracking, and based on the ENS-76 VCO design by Eddy Bergman.

It has three waveforms at the same time on separate outputs: sawtooth, square and triangle. Pitch is set with coarse and fine knobs, and can be modulated through the CV input and a linear FM input with its own attenuator.

## Get one
VCO is available from [Solisynth](https://solisynth.com/).

## Features
- Fully analogue exponential core with matched transistor pair and tempco compensation
- Simultaneous sawtooth, square and triangle outputs
- Coarse and fine tuning
- CV input
- Linear FM input with attenuator
- Trimmers for fine tuning the waveforms

## Specifications
| | |
|---|---|
| Width | 6 HP |
| Depth | 30 mm |
| Power +12 V | TBD |
| Power −12 V | TBD |
| Output level | TBD |

## Calibration
TBD

## Hardware
The schematics and PCB layouts are KiCad projects:

- `vco-main-pcb/`: main PCB
- `vco-frontpanel-pcb/`: front panel

The bill of materials is in [`vco-main-pcb/bom/VCO_BOM.csv`](vco-main-pcb/bom/VCO_BOM.csv), and an interactive BOM for assembly in [`vco-main-pcb/bom/ibom.html`](vco-main-pcb/bom/ibom.html). Gerbers can be generated from the KiCad projects.

## Repository structure
| Folder | Contents |
|---|---|
| `vco-main-pcb/` | KiCad project for the main PCB, BOM |
| `vco-frontpanel-pcb/` | KiCad project for the front panel |
| `pictures/` | Photos of the module |

## Credits
The oscillator core is based on the ENS-76 VCO (Option 1) by Eddy Bergman.

## License
VCO is open source:

- Hardware: [CERN-OHL-S-2.0](LICENSES/CERN-OHL-S-2.0.txt)
- Documentation: [CC-BY-SA-4.0](LICENSES/CC-BY-SA-4.0.txt)

If you share a modified version or hardware built from these files, it has to stay open source under the same license.
"Solisynth" and the Solisynth logo are not covered by these licenses: derivatives must use their own name and branding. See [LICENSE.md](LICENSE.md) for details.
