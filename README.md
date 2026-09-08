# NEON BREACH // Neural Firewall Infiltration
> *A high-performance, retro-futuristic 2D cyberpunk arcade game engineered for 60/120 FPS Retina displays.*
> *Developed as a flagship portfolio project for the Apple Developer Academy (ADA).*

[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20iOS%20%7C%20macOS%20%7C%20iPadOS-00f0ff?style=flat-square)](#)
[![Display](https://img.shields.io/badge/Display-Retina%20%2F%20High--DPI%20Ready-ff007f?style=flat-square)](#)
[![Audio](https://img.shields.io/badge/Audio-Procedural%20Web%20Audio%20Synthesizer-00ff88?style=flat-square)](#)
[![Dependencies](https://img.shields.io/badge/Dependencies-Zero%20External%20Libraries-ffaa00?style=flat-square)](#)

---

## ⚡ Overview & Vision

**Neon Breach** is an adrenaline-fueled cyberpunk arcade shooter that places players in the cockpit of a neural infiltration craft tasked with breaching corporate megastructure firewalls. 

Built with pure **HTML5 Canvas 2D**, **CSS Glassmorphism**, and the **Web Audio API**, the project is designed with an uncompromising focus on **game feel ("juice")**, **Apple Human Interface Guidelines (HIG)** aesthetic sensibilities, and zero-dependency reliability.

---

## 🎮 Core Game Features

### 1. Flight Dynamics & Game Feel ("Juice")
- **8-Way Directional Inertia**: Aeronautic flight model with smooth acceleration damping and real-time wing-banking tilt.
- **Phase Shift (Invulnerability Dash)**: Trigger a high-speed warp dash (`Shift` / Right-Click / Touch Button) granting brief invulnerability frames (i-frames) and leaving chromatic ghost silhouettes.
- **Dynamic Camera System**: Responsive tracking with directional recoil, trauma-decay screen shake, and micro-freeze hit-stops (3-4 frames) on critical impacts.
- **Overdrive EMP Blast**: Harvest data cores to charge a screen-clearing shockwave (`E` / `F`) that neutralizes incoming hostile fire and devastates surrounding firewalls.
- **Graze (Near-Miss) Scoring**: Skimming closely past hostile laser bolts and homing missiles triggers near-miss graze telemetry, rewarding extra combo multiplier, EMP charge, and crisp synthesizer feedback.

### 2. Thermal Heat & Overheat Management
- **Skill-Based Heat Budgeting**: Primary firing generates thermal heat. Firing in disciplined bursts maintains steady DPS.
- **Overheat Lockout**: Overheating locks out weapons for 1.5 seconds, flashing emergency warning telemetry and requiring tactical evasion.
- **Emergency Coolant Venting**: Destroying enemies or claiming airdropped Coolant Pods instantly purges weapon heat to 0% for immediate counter-attack.

### 3. Structured Wave Director & Roguelite Card Drafting
- **Cinematic Wave Announcements**: High-tech sliding warning banners herald incoming threat tiers (`WAVE 01`, `CRITICAL WARNING: TITAN MK-II DETECTED`).
- **Mid-Run Neural Overclock (3-Card Draft)**: Clearing a wave pauses combat and presents pilots with 3 randomized tactical perks:
  - ❄️ **Overclock Heatsinks**: -25% weapon heat generation.
  - ⚡ **Rapid Cycle Servos**: +20% primary fire rate.
  - 🔧 **Nano-Repair Injector**: Repairs +1 hull pip immediately.
  - 🚀 **Thruster Afterburner**: -25% Phase Dash cooldown.
  - 🌀 **Overdrive Dynamo**: +35% EMP charging rate.
  - 🧲 **Magnetic Pulse Amp**: +40% data crystal attraction range.
  - 🛡️ **Kinetic Coolant**: Dashing instantly flushes -40% weapon heat.

### 4. Telegraphed Enemy Archetypes & Destruction Physics
- **Dynamic Debris & Explosion Shockwaves**: Destroying hostiles instantly obliterates their chassis with multi-phase radial shockwaves, 22 high-velocity fiery sparks, and tumbling angular metallic hull debris shards.
- **Stationary Data Nodes**: Defeated targets selectively drop grid-anchored holographic data nodes (35% scout, 60% heavy, 20% shards, 100% boss) that remain stable at their drop coordinates without drifting away until collected.
- **Cyber Turret**: Tracks the player with a telegraphed, pulsing red dashed laser sight line before discharging targeted twin plasma bolts.
- **Shielded Sentinel**: Heavy armored cruiser flanked by an active kinetic shield arc that deflects forward shots, rewarding strategic flanking maneuvers.
- **Hex Splitter & Shards**: Segmented chassis designed with structural fracture lines that divides into twin agile diamond fragments upon destruction.
- **Cyber Sniper & Glitch Phantom**: Precision long-range beam snipers and shifting stealth predators.
- **Tactical Airdrop Pods**: Descending supply capsules granting Forcefield Shields (`🛡️`), Triple Spread Cannons (`⚡`), Hyper Speed (`🚀`), Chrono Time Dilation (`⏱️`), and Thermal Coolant (`❄️`).

### 5. Operative Ship Hangar
Choose between three distinct operatives, each with unique chassis geometry, weapon archetypes, and handling profiles:
| Operative | Archetype | Signature Weapon | Thermal & Handling Specs |
| :--- | :--- | :--- | :--- |
| **Viper Mk-IV** | Interceptor | Twin Pulse Blasters | Rapid heat dissipation, high agility, low cooldown |
| **Aegis Titan** | Vanguard | Heavy Spread Shot | Expanded hull pips, high thermal capacity, wide coverage |
| **Spectre Zero** | Phantom | Piercing Particle Beam | High burst damage, extended i-frames, critical precision |

### 6. Procedural Synthwave Audio Engine
- **100% Code-Synthesized Music**: Generates real-time 80s basslines, four-on-the-floor kick drums, snappy snare hits, and arpeggiated synth leads with low-pass resonance filters.
- **Dynamic Sound Effects**: Frequency-modulated lasers, sub-bass explosion rumbles, shield harmonics, thermal overheat buzzers, coolant purges, graze pings, and Apple-style tactile UI audio clicks.
- **Zero Asset Failures**: Never encounters broken MP3 or audio asset loading delays.

### 7. Neural Upgrade Lab (Meta-Progression)
Spend collected **Data Bits** across runs to permanently enhance your craft:
- **Magnetic Data Compressor**: Enhances auto-pull magnetic radius for collectibles.
- **Hyper-Drive Coolant**: Reduces Phase Dash cooldown by 25%.
- **Reinforced Chassis Plating**: Expands maximum hull capacity.
- **Overdrive Resonator**: Accelerates EMP Super charging from combat combos.

### 8. Multi-Phase Boss Encounter: *Dreadnought Titan MK-II*
- **Phase 1 (100% - 66% HP)**: Sweeping triple-laser salvos guarded by a rotating kinetic barrier.
- **Phase 2 (66% - 33% HP)**: Telegraphed Mega-Beam death ray locking onto player coordinates, followed by a blinding screen-clearing plasma beam.
- **Phase 3 (< 33% HP)**: Triple homing swarm missiles with smoke trails, escort support drones, smoking damaged chassis, and catastrophic reactor meltdown shockwaves.

---

## 🕹️ Controls & Accessibility

Designed from the ground up for seamless cross-platform play on **Mac, iPad, iPhone, and PC**:

| Action | Keyboard / Mouse | Touch / iPad | Gamepad (Xbox/PlayStation/MFi) |
| :--- | :--- | :--- | :--- |
| **Movement** | `WASD` / Arrow Keys | Virtual Analog Thumbstick | Left Analog Stick / D-Pad |
| **Primary Fire** | `Spacebar` / Left Click | `FIRE` Button | `A` / `Cross` / Right Trigger |
| **Phase Dash** | `Shift` / Right Click | `DASH` Button | `B` / `Circle` / Right Bumper |
| **Overdrive EMP** | `E` / `F` | `EMP` Button | `X` / `Square` / Left Trigger |
| **Pause Game** | `Escape` / `P` | Pause Icon (`⏸`) | `Menu` / `Options` |
| **Touch Controls** | Toggle via `📱` Icon | Active by default on mobile | Toggle via `📱` Icon |
| **CRT Filter** | Toggle via `📺` Icon | Toggle via `📺` Icon | Toggle via `📺` Icon |

---

## 🍎 Alignment with Apple Developer Academy Values

1. **Human Interface Guidelines (HIG) & Aesthetic Polish**:
   - Tailored cyber dark-mode palette using precise HSL tokens and frosted glassmorphism (`backdrop-filter: blur(24px)`).
   - Apple Game Center-style animated achievement banners sliding down from the dynamic island / top viewport.
   - Discrete, legible hull pips and animated heat telemetry gauges that communicate critical game state at a glance.
   - Non-punishing edge boundaries: replaces crude instant-death borders with fluid, tactile inertia cushioning.

2. **Retina & ProMotion Display Fidelity**:
   - Automatically detects `window.devicePixelRatio` to dynamically scale canvas backing buffers, achieving razor-sharp vector graphics on 60 Hz and 120 Hz ProMotion Retina displays (MacBook Pro, iPad Pro, iPhone).

3. **Performance, Reliability & Zero Bloat**:
   - Consistent 60/120 FPS execution with minimal garbage collection overhead.
   - 100% self-contained single-file architecture: zero external image or audio files needed, guaranteeing 0ms latency and foolproof offline execution during academy evaluations.

---

## 🚀 Quick Start / How to Run

1. Simply double-click `neonbreach.html` to open it in **Safari**, **Chrome**, **Arc**, or any modern web browser.
2. Alternatively, run a lightweight local static server:
   ```bash
   # Using Python 3
   python -m http.server 8080
   # Open in browser: http://localhost:8080/neonbreach.html
   ```

---

*Engineered with precision for the Apple Developer Academy application.*
