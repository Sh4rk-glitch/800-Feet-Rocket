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
