# Dual-Egg Payload Rocket (800 ft)

A single-stage model rocket engineered to carry a fragile dual-egg payload to an exact target apogee of **800 ft (244 m)** with a target flight duration of **38.2 seconds**.

---

## Performance & Simulation Overview

Simulated via OpenRocket using an **AeroTech F23FJ-6** motor:

* **Apogee:** 800.52 ft (244.0 m)
* **Total Flight Time:** 38.2 s
* **Time to Apogee:** ~7.5 s
* **Liftoff Mass:** 434 g (including motor and payload)
* **Descent Mass (Post-Burnout):** ~404 g
* **Landing Velocity:** ~7.8 m/s (safe threshold for foam-cushioned egg recovery)
* **Stability Margin:** > 2.0 cal

---

## Airframe & Structural Architecture

The airframe uses a dual-diameter stepped design to minimize mass and aerodynamic drag while accommodating the payload volume:

* **Nose Cone:** 
  * **Geometry:** Tangent Ogive (200 mm length)
  * **Material:** 3D-printed PLA (1.6 mm shell)
  * **Function:** Low-drag aerodynamic profile with internal modular ballast bay (18 g trim mass).
* **Upper Body Tube (Payload Section):**
  * **Dimensions:** BT-80 (66 mm OD / 64.5 mm ID, 350 mm length)
  * **Material:** Spiral-wound kraft cardboard
  * **Payload:** 2 raw Grade-A eggs (oriented in-line with foam padding).
* **Transition:**
  * **Geometry:** Conical transition (BT-80 to BT-70, 50 mm taper length)
  * **Material:** 3D-printed PLA (shouldered fit)
  * **Function:** Aerodynamic diameter step-down and structural junction between bays.
* **Lower Body Tube (Booster & Recovery Section):**
  * **Dimensions:** BT-70 (56.4 mm OD / 54.9 mm ID, 350 mm length)
  * **Material:** Spiral-wound kraft cardboard
  * **Contents:** Parachute, tubular nylon shock cord, and 29 mm motor mount assembly.
* **Fin Set:**
  * **Configuration:** 3-fin trapezoidal set, $120^\circ$ radial spacing
  * **Material:** 3D-printed PLA / stiffened composite
  * **Function:** Passive aerodynamic stability keeping CP safely aft of CG through burnout and coast.

---

## Propulsion & Recovery Systems

### Propulsion
* **Motor:** AeroTech F23FJ-6 (Single-Use, 29 mm)
* **Total Impulse:** 40.7 N·s (F-class)
* **Burn Time:** 2.2 s
* **Delay:** 6 seconds (ejection near apogee)

### Recovery
* **Canopy:** 40.0–41.5 cm diameter ripstop nylon parachute ($C_D \approx 0.80$)
* **Shock Cord:** 200 cm of 11 mm (7/16 in) tubular nylon
* **Descent Control:** Sized for a ~30.5 s descent time post-apogee to meet target flight duration windows.

---

# BOM & Sourcing Guide
| Category | Component / Item | Spec / Part # | Qty | Source / Search Term | Unit Price (USD) | Extended Price (USD) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Airframe Tubes** | BT-80 Body Tube (Payload) | Semroc/Estes BT-80 (2.60" OD $\times$ 14.2" L)[cite: 1] | 1 | [eRockets.biz](https://www.erockets.biz/) (Search: `BT-80 body tube` / `SEM-ST-26-34`) | $8.25 | $8.25 |
| | BT-70 Body Tube (Booster) | Semroc/Estes BT-70 (2.217" OD $\times$ 18" L)[cite: 1] | 1 | [eRockets.biz](https://www.erockets.biz/) (Search: `BT-70 body tube` / `SEM-ST-20-18`) | $6.50 | $6.50 |
| | 29 mm Motor Mount Tube | 29 mm ID heavy-wall tubing (15 cm cut length)[cite: 1] | 1 | [ApogeeRockets.com](https://www.apogeerockets.com/) (Search: `29mm Heavy Duty Body Tube`) | $4.95 | $4.95 |
| **3D Printing** | PLA Filament (Nose, Transition, Fins) | 1.75 mm PLA (Black/Grey, 1 kg spool)[cite: 1] | 1 spool | [Polymaker PolyLite PLA](https://us.polymaker.com/products/polylite-pla) | $19.99 | $19.99 |
| **Centering Rings** | BT-70 to 29 mm Centering Rings | Laser-cut fiberboard/plywood (pair)[cite: 1] | 1 pair | [eRockets.biz](https://www.erockets.biz/) (Search: `CR-2029` / `BT-70 to 29mm`) | $2.85 | $2.85 |
| **Recovery System** | Ripstop Nylon Parachute | 16"–17" (40–43 cm) Hex Chute[cite: 1] | 1 | [Top Flight Recovery](https://topflightrecoveryllc.homestead.com/) (Product: `16" or 17" Thin Mill Nylon Chute`) | $12.50 | $12.50 |
| | Tubular Nylon Shock Cord | 7/16" (11 mm) $\times$ 10 ft length[cite: 1] | 1 | [OneBadHawk](https://onebadhawk.com/) (Product: `7/16" Tubular Nylon Harness`) | $7.00 | $7.00 |
| | Flameproof Recovery Wadding | Cellulose sheets (pack of 75) | 1 pack | [Estes Recovery Wadding](https://estesrockets.com/products/recovery-wadding) | $5.99 | $5.99 |
| **Payload & Trim** | Raw Grade-A Large Eggs | Standard grocery store eggs (55–60 g each)[cite: 1] | 1 dozen | Local Grocery / Supermarket | $2.80 | $2.80 |
| | Closed-Cell Egg Cushioning Foam | 1" thick polyethylene foam sheet | 1 sheet | [McMaster-Carr](https://www.mcmaster.com/) (Search: `8614K41` or `Firm Polyethylene Foam`) | $6.20 | $6.20 |
| | Lead / Steel Ballast Weights | 1/4 oz peel-and-stick adhesive weights[cite: 1] | 1 pack | [Amazon.com](https://www.amazon.com/) (Search: `1/4 oz adhesive wheel weights`) | $6.99 | $6.99 |
| **Motor & Hardware** | AeroTech F23FJ-6 Motor | 29 mm Single-Use Motor (F-class)[cite: 1] | 2-pack | [ApogeeRockets.com](https://www.apogeerockets.com/) (Search: `AeroTech F23-6FJ`) | $46.99 | $46.99 |
| | 29 mm Screw-on Motor Retainer | Billet aluminum threaded retainer | 1 | [ApogeeRockets.com](https://www.apogeerockets.com/) (Search: `Aero Pack 29mm Quick Turn Retainer`) | $18.50 | $18.50 |
| | 1/4" Launch Rail Buttons | Standard 1010 rail buttons + hardware (pair) | 1 pair | [ApogeeRockets.com](https://www.apogeerockets.com/) (Search: `1010 Standard Rail Buttons`) | $3.50 | $3.50 |

---

## Cost Summary

* **Reusable Airframe & Recovery Hardware:** $97.82
* **Consumables & Motors (2 Flights):** $49.79
* **Total Initial Build Cost:** **$147.61**

---
## Mass Budget Summary

* **Airframe & Structural Dry Mass:** ~220 g
* **Payload & Ballast:** 138 g (120 g eggs + 18 g trim ballast)[cite: 1]
* **Recovery & Internal Hardware:** ~46 g
* **Total Liftoff Mass:** **434 g**[cite: 1]
* **Descent Mass (Post-Burnout):** **~404 g**[cite: 1]
