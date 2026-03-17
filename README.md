# OCTONION

**A portal into the mathematical structure of reality, controlled by your breath.**

OCTONION computes real modular forms from theoretical physics in real-time and renders them as a living visual universe. Your breathing becomes the parameter that explores the mathematical landscape where particle physics lives.

This is not a meditation app. This is not a screensaver. This is a direct window into the equations that describe why the universe has three generations of matter, why the Cabibbo angle is what it is, and why mass hierarchies exist.

---

## The Mathematics (real, not decorative)

Every visual you see is computed from actual physics:

- **Modular forms of Gamma(7)** — theta functions computed in real-time
- **chi-squared landscape** — 5 observables tested against experimental data (PDG)
- **epsilon = |Y2/Y1|** — the mass hierarchy parameter, changes with your breath
- **sin(pi/14)** — the Cabibbo angle, derived from PSL(2,7) eigenvalues
- **Coherence = inverse chi-squared** — when you breathe at 14s period (theta ~ 45 degrees), the mathematical fit to reality reaches its optimum

The geometry (heptagon, heptagrams {7/2} and {7/3}, 21-gon, 42-gon, 168-gon) reflects the actual group structure: Z7, PSL(2,7) with 168 elements, the Klein quartic with genus 3.

---

## Vision: The Super-Developed Stage

### Layer 1 — IMMERSION (current goal)
The visual must swallow consciousness. Not "pretty particles" — a space you fall into and forget you're holding a phone. This means:
- **WebGL2 raymarching**: SDF rendering of G2 manifold cross-sections, hyperbolic tilings of the Klein quartic, Mandelbulb-like structures generated from the actual modular forms
- **Generative audio synthesis**: not loops — sound generated from the same theta functions, so you HEAR the mathematics
- **60fps on iPhone 12 Pro**: every optimization matters — sprite atlases, instanced rendering, LOD, half-precision where possible

### Layer 2 — EMBODIMENT
Your body IS the controller:
- **Breath** (microphone): maps to theta on the unit circle, exploring the modular parameter space
- **Gamepad** (PS4/PS5/Xbox via Bluetooth): navigate through the mathematical manifold, rotate perspectives, zoom across scales
- **Gyroscope**: head-tracking-like effects — tilt your phone to shift perspective through the geometry
- **Heart rate** (if available via Web Bluetooth): second biological parameter, potentially mapping to Im(tau)

### Layer 3 — REVELATION
The experience teaches without lecturing:
- At coherence milestones, the actual mathematics appears — not as text overlay, but as structure that becomes visible in the geometry itself
- Three generations of matter = three rings that emerge from chaos as you approach resonance
- The Cabibbo angle = the specific rotation you can SEE between quark families
- Mass hierarchy = the ratio of ring sizes, controlled by epsilon
- Progressive unlocks reveal deeper mathematical structures: Z7 -> PSL(2,7) -> G2 -> the full octonionic algebra

### Layer 4 — MULTIPLAYER COHERENCE
Multiple breathers in the same mathematical space:
- WebSocket/WebRTC for real-time sync
- Each player's theta contributes to a shared modular parameter
- When multiple people achieve resonance simultaneously, geometry that no single player can unlock becomes visible
- The Klein quartic (genus 3 surface) rendered as a shared space players navigate together
- Collective chi-squared: the group can achieve better fit than any individual

### Layer 5 — CREATION
Players don't just observe — they leave traces:
- Resonance states can be "crystallized" as structures in the shared space
- Over time, a collective mathematical universe grows from players' breathing patterns
- The best resonance states are preserved as "theorems" — permanent structures
- Players can compose resonance sequences that others experience as "journeys"

---

## Technical Architecture (target)

```
INPUT LAYER
  Microphone (breath) -----> theta (20-80 deg)
  Gamepad (navigation) ----> camera position + rotation in 3D+
  Gyroscope (tilt) --------> perspective shift
  Heart rate (BLE) --------> Im(tau) modulation

COMPUTE LAYER (WebGL2 / WASM)
  Modular forms: theta_7r(r, tau) for r=0..6, N_trunc=12+
  Y1, Y2, Y3 from theta combinations
  epsilon = |Y2/Y1|, chi-squared against PDG
  SDF generation from modular form values
  Audio synthesis from theta functions

RENDER LAYER (WebGL2 fragment shader)
  SDF raymarching: fractals, Klein quartic, G2 cross-sections
  Particle systems: instanced, sprite-based, additive blending
  Post-processing: bloom, chromatic aberration, film grain
  Geometry overlays: sacred geometry from group theory

SOCIAL LAYER (WebSocket)
  Real-time theta broadcast
  Shared universe state
  Crystallized resonance persistence
```

---

## Development Compass

**When you open this project, ask:**

1. Does the current visual make you forget you're looking at a screen? If no — that's the priority.
2. Does the math compute correctly? If yes — the foundation holds. Build on it.
3. Is there a new input channel to add? (gamepad, gyro, heart rate)
4. Is there a new mathematical structure to reveal? (Klein quartic, G2 manifold, Calabi-Yau)
5. Can two people experience this together yet?

**Priority order: IMMERSION > EMBODIMENT > REVELATION > MULTIPLAYER > CREATION**

Never sacrifice immersion for features. A single raymarched fractal that swallows your mind is worth more than ten UI panels.

---

## The Philosophy

The diaphragm divides us into two states — vacuum above, pressure below. We breathe to mix them. OCTONION makes this mixing visible through the mathematics that describes how the universe itself mixes its fundamental states.

Wrestling is not competition — it's play that provokes perfection. OCTONION is not a game — it's play with the mathematical structure of reality itself.

The goal is not to teach physics. The goal is to create an experience so beautiful that people fall into it, and in falling, discover that the beauty comes from the actual equations of nature. That mathematical truth and aesthetic beauty are the same thing.

---

## Stack

- HTML5 Canvas / WebGL2
- Web Audio API (generative)
- Gamepad API
- DeviceMotion / DeviceOrientation
- JavaScript (real-time modular forms)
- Future: WebAssembly (heavy math), WebRTC (multiplayer), Web Bluetooth (heart rate)

## Origin

OCTONION grew from a Theory of Everything computation — an octonionic approach to particle physics where G2 = Aut(O) leads through PSL(2,7) to the Cabibbo angle, mass hierarchies, and three generations. The mathematics is not metaphor. It is the actual calculation, rendered live.

**Created by Alexandr Nedzvetskyi (vision, philosophy, direction) in collaboration with Claude (computation, implementation).**
