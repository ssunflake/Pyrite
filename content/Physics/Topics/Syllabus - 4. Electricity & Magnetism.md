# ⚡ 4. Electricity & Magnetism

> [[Physics IGCSE Index|← Back to Index]] | [[Syllabus - 3. Waves, Light & Sound|← Waves]]

---

## 4.1 Simple Phenomena of Magnetism

### Magnetic Poles
- Every magnet has a **North** and **South** pole
- Like poles **repel**, unlike poles **attract**
- A magnetic field is the region where a magnetic force is experienced

### Magnetic Field Lines
- Direction: from North to South (outside the magnet)
- Closer lines = stronger field
- Never cross each other

### Magnetic Materials
- **Ferromagnetic materials** can be magnetised: iron, steel, nickel, cobalt
- Iron → **soft** (easy to magnetise/demagnetise) → used in electromagnets
- Steel → **hard** (holds magnetism) → used in permanent magnets

### Making & Destroying Magnets
| Method | Effect |
|--------|--------|
| Stroking with a magnet | Magnetise |
| Hammering | Demagnetise |
| Heating | Demagnetise |
| AC current | Demagnetise |

### Earth's Magnetic Field
- Earth behaves like a giant bar magnet
- Magnetic North ≠ Geographic North
- Compasses align with Earth's magnetic field

---

## 4.2 Electrical Quantities

### Electric Charge
- Two types: **positive (+)** and **negative (−)**
- Measured in **coulombs (C)**
- Like charges repel, unlike charges attract

### Electric Current
$$I = \frac{Q}{t}$$

- $I$ = current (A, amperes)
- $Q$ = charge (C, coulombs)
- $t$ = time (s)

> Conventional current flows from + to − (opposite to electron flow)

### Potential Difference (Voltage)
$$V = \frac{W}{Q}$$

- $V$ = voltage (V, volts)
- $W$ = work done (J)
- $Q$ = charge (C)

> Voltage is the energy transferred per unit charge.

### Resistance
$$R = \frac{V}{I}$$

- $R$ = resistance (Ω, ohms)
- $V$ = voltage (V)
- $I$ = current (A)

**Ohm's Law:** V ∝ I (for a conductor at constant temperature)

$$V = IR$$

### Factors Affecting Resistance of a Wire
| Factor | Effect on resistance |
|--------|---------------------|
| Length ↑ | R ↑ |
| Cross-sectional area ↑ | R ↓ |
| Temperature ↑ | R ↑ (for metals) |
| Material | Depends on resistivity |

### I-V Characteristics

| Component | I-V Graph Shape |
|-----------|----------------|
| Resistor (Ohmic) | Straight line through origin |
| Filament bulb | Curved (resistance increases with temp) |
| Diode | Conducts in one direction only |

### Electromotive Force (EMF)
- **EMF** = total energy supplied per unit charge by a source (battery/cell)
- Different from terminal voltage due to **internal resistance**

$$\text{EMF} = V + Ir$$

---

## 4.3 Electric Circuits

### Series Circuits
- Components connected in a single loop
- Same current through all components
- Voltage shared between components

$$I_{total} = I_1 = I_2 = I_3$$
$$V_{total} = V_1 + V_2 + V_3$$
$$R_{total} = R_1 + R_2 + R_3$$

### Parallel Circuits
- Components connected in branches
- Voltage same across all branches
- Current splits between branches

$$V_{total} = V_1 = V_2 = V_3$$
$$I_{total} = I_1 + I_2 + I_3$$
$$\frac{1}{R_{total}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3}$$

### Circuit Components & Symbols

| Component | Function |
|-----------|---------|
| Cell/Battery | Provides EMF |
| Switch | Opens/closes circuit |
| Resistor | Opposes current |
| Variable resistor (rheostat) | Adjustable resistance |
| Lamp | Converts electrical to light energy |
| Voltmeter | Measures voltage (connected in **parallel**) |
| Ammeter | Measures current (connected in **series**) |
| Diode | Allows current in one direction only |
| LED | Light-emitting diode |
| LDR | Resistance decreases as light increases |
| Thermistor | Resistance decreases as temperature increases |
| Capacitor | Stores charge |
| Fuse | Melts to break circuit if current too high |

### Electrical Power & Energy
$$P = IV = I^2R = \frac{V^2}{R}$$
$$E = Pt = IVt$$

- $P$ = power (W)
- $E$ = energy (J)
- $t$ = time (s)

---

## 4.4 Digital Electronics

### Logic Gates

| Gate | Symbol | Operation | Truth Table |
|------|--------|-----------|-------------|
| NOT | Triangle + bubble | Output = NOT input | 0→1, 1→0 |
| AND | D-shape | Output = 1 only if ALL inputs = 1 | 11→1, else 0 |
| OR | Curved shape | Output = 1 if ANY input = 1 | 00→0, else 1 |
| NAND | AND + bubble | NOT AND | 11→0, else 1 |
| NOR | OR + bubble | NOT OR | 00→1, else 0 |

### Binary Numbers
- Digital systems use **binary (base 2)**: only 0s and 1s
- **0** = low voltage, **1** = high voltage

| Binary | Decimal |
|--------|---------|
| 0000 | 0 |
| 0001 | 1 |
| 0010 | 2 |
| 0100 | 4 |
| 1000 | 8 |
| 1111 | 15 |

---

## 4.5 Dangers of Electricity

### Household Electricity
- AC (alternating current) supply: **230 V, 50 Hz** in most countries
- Three wires in UK plug:

| Wire | Colour | Function |
|------|--------|---------|
| Live | Brown | Carries current at high voltage |
| Neutral | Blue | Completes circuit at 0V |
| Earth | Green/yellow | Safety — carries current if fault |

### Safety Devices

**Fuse:**
- Thin wire that melts if current too high
- Rated in amps (e.g. 3A, 5A, 13A)
- Choose fuse slightly above normal operating current
- Connected in the **live** wire

**Circuit Breaker:**
- Electromagnet trips a switch when current too high
- Can be reset (unlike fuse which must be replaced)

**Earth wire:**
- Connected to metal casing of appliances
- If live wire touches casing → large current flows → fuse blows → circuit breaks

**Double Insulation:**
- Some appliances have no earth wire
- Two layers of insulation on all live parts

---

## 4.6 Electromagnetic Effects

### The Motor Effect
- A current-carrying conductor in a magnetic field experiences a **force**
- **Fleming's Left-Hand Rule:**
  - **F**irst finger = **F**ield direction
  - Se**C**ond finger = **C**urrent direction
  - Thu**M**b = **M**otion (force direction)

$$F = BIl$$

- $F$ = force (N)
- $B$ = magnetic flux density (T)
- $I$ = current (A)
- $l$ = length of conductor (m)

**Applications:** Electric motor, loudspeaker, moving-coil meter

### Electromagnetic Induction
- A **changing magnetic field** induces an **EMF** in a conductor
- Requires **relative motion** between conductor and magnetic field

**Factors increasing induced EMF:**
- Stronger magnet
- Faster movement
- More coil turns
- Smaller coil area? → No, larger area increases EMF

**Fleming's Right-Hand Rule** (generators):
- Used to find direction of induced current

### Generators (Dynamos)
- Convert mechanical energy to electrical energy
- **AC generator (alternator):** coil rotates in magnetic field → produces AC
- **DC generator:** uses a commutator → produces DC

### Transformers
- Change the voltage of AC electricity

$$\frac{V_p}{V_s} = \frac{N_p}{N_s}$$

$$\frac{V_p}{V_s} = \frac{I_s}{I_p}$$ (for ideal transformer)

- $V_p$ = primary voltage, $V_s$ = secondary voltage
- $N_p$ = primary turns, $N_s$ = secondary turns

| Type | Turns | Voltage | Current |
|------|-------|---------|---------|
| Step-up | $N_s > N_p$ | $V_s > V_p$ | $I_s < I_p$ |
| Step-down | $N_s < N_p$ | $V_s < V_p$ | $I_s > I_p$ |

**Power in ideal transformer:** $P_{input} = P_{output}$

$$V_pI_p = V_sI_s$$

**National Grid:** Uses step-up transformers for transmission (high V, low I, less energy loss) then step-down for homes.

---

## 🔑 Key Formulas Summary

| Formula | Equation |
|---------|----------|
| Current | $I = Q/t$ |
| Ohm's Law | $V = IR$ |
| Power | $P = IV = I^2R = V^2/R$ |
| Energy | $E = Pt$ |
| Motor force | $F = BIl$ |
| Transformer | $V_p/V_s = N_p/N_s$ |

> [[Syllabus - 5. Nuclear Physics|Next Topic →]]
