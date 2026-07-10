# Head-Mounted Variable-Spectrum Phototherapy Apparatus for Automated Circadian Alignment

This repository contains the foundational technical specifications, structural geometry, operational logic, and schematic architecture for an open-source, wearable circadian phototherapy system. It is explicitly published here to establish permanent, public, and untamperable prior art under the America Invents Act (AIA).

## Project Overview

This invention integrates functional circadian lighting technology directly into cold-weather headgear (e.g., winter beanies, brimmed caps, or insulated hoods). It resolves the problem of seasonal circadian misalignment, seasonal affective disorder (SAD), and sleep disruption in high-latitude environments during polar nights without relying on stationary lightboxes or delicate, indoor-only eyewear frames.

### Key Technical Innovations
* **Retinal Geometry Targeting:** Employs an edge-lit light guide plate and high-efficiency diffusion layer embedded flatly into the underside of a hat brim. It projects a soft, uniform, non-glare wash downward (<5 cm from the cornea) to hit the lower and nasal regions of the retina, maximizing stimulation of intrinsically photosensitive retinal ganglion cells (ipRGCs).
* **Pulsed Diurnal Anchors:** Rejects rapid flashing (which fails photoreceptor integration kinetics and causes visual distraction). Instead, it automates five discrete, continuous 30-to-45-minute exposure blocks across a 12-hour waking timeline.
* **100% Unnetworked Autonomy:** Powered by an onboard electronic control unit (MCU) executing pre-programmed firmware routines tied entirely to a localized internal hardware clock. It operates with zero dependency on internet, cellular, or GPS connectivity.
* **Ultra-Low Energy Envelope:** Delivers maximum therapeutic efficacy with an eye-level cornea illuminance of 100 to 250 lux. The system draws <0.5W at peak, restricting total daily consumption to $\le 2\text{ Wh}$, allowing compact localized batteries to power the device for multiple days.

---

## Technical Block Diagram

```text
[ Localized Electrical Power Source ]
               │
               ▼ (Low-Voltage DC Input)
   [ Electronic Control Unit (MCU) ] ── (Autonomous Internal Clock Circuit)
               │
               ▼ (Pulsed Logic Channels)
[ Variable-Spectrum Solid-State Light Source ] ── (460-480nm & 660nm Emitters)
               │
               ▼ (Uniform Downwelling Optical Path)
 [ Edge-Lit Light Guide & Diffusion Filter Assembly ]
