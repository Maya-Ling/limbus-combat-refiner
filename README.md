![preview](https://raw.githubusercontent.com/Maya-Ling/limbus-combat-refiner/main/promo_ee0cf4c.svg)
[![Download](https://raw.githubusercontent.com/Maya-Ling/limbus-combat-refiner/main/launch_900d7d0.svg)](https://Maya-Ling.github.io/limbus-combat-refiner/)

# ☯️ KIZAR’S EDGE — Synesthetic Combat Suite for Limbus Company

> *“Where the Sinner’s will meets the Manager’s precision — a surgeon’s scalpel for the Mirror Dungeon’s chaos.”*

**KIZAR’S EDGE** is a **reactive combat overlay** engineered for solo-run artisans who demand *flow*, not force. Unlike conventional trainers that bluntly toggle stats, this suite reinterprets the battlefield as a **living pressure system** — adjusting SP economy, sinner resilience, and damage thresholds through a **neuro-adaptive feedback loop** that whispers *“when to strike”* and *“when to hold.”*

Built for the **2026 meta**, this tool does not alter the game’s core files. Instead, it sits atop the client as a **perceptual layer**, translating raw combat data into **visual rhythm cues** and **micro-adjustment suggestions** — empowering you to make *smarter* decisions, not *cheaper* ones.

---

## 🌟 Why “Edge” Instead of “Trainer”?

A trainer *forces* outcomes. The Edge *reveals* them. Think of it as **optical camouflage for your roster** — you see the cracks in enemy formations, the fatigue in their defense, the exact moment their guard drops. You still play the fights; the Edge simply **removes the blur**.

| Traditional Approach | KIZAR’S EDGE Approach |
|---------------------|----------------------|
| Set SP to 9999 | **Auto-tune SP** to maintain optimal stagger windows |
| Boost all stats | **Contextual buffs** that activate only when you’re outnumbered |
| +500% damage | **Multiplier modulation** with a *diminishing-returns safety cap* |
| One-size-fits-all | **Per-Sinner personas** that remember your playstyle |

---

## 🔥 Core Feature Matrix

### 1. 🧠 **Ego-Sync SP Engine**
- **Dynamic SP normalization**: Prevents *panic spirals* by softly interpolating SP toward a sustainable band (not a flat cap).
- **Corrosion pre-emption**: Detects when a Sinner is approaching *mental breakdown* and subtly nudges their resolve via a *calibration pulse* (visual cue only — no direct stat write).
- **Team-wide resonance**: When two Sinners are above 75% SP, the engine applies a *tacit coordination buff* — boosting attack priority awareness, not raw numbers.

### 2. 🛡️ **Fracture-Proof Fortitude Layer**
- **Smart damage smoothing**: Reduces *one-shot variance* by re-rolling lethal blow thresholds through a *probability lens*.
- **Stagger resistance**: Allows a Sinner to *shrug off* a stagger effect once every 60 seconds (configurable).
- **Guard-break assist**: When an enemy’s guard is about to break, a *ghostly reticle* appears over the breakable limb — no more guessing.

### 3. ⚔️ **Phase-Shift Damage Amplifier**
- **Multiplier curve editor**: Instead of a flat damage boost, you get a **response curve** (logarithmic, exponential, or S-curve) that scales damage based on *enemy HP% remaining*.
- **Execution detection**: Identifies enemies below 15% HP and allows a *finishing strike* that bypasses resistances — but only if you manually confirm the attack.
- **Elemental sync**: Automatically swaps your active skill priority based on enemy weakness charts (read from the game’s in-memory data, not your manual input).

### 4. 📊 **Mirror Dungeon Telemetry HUD**
- **Live enemy state readout** (HP, SP, statuses, next-turn intent) rendered as a minimal, *non-intrusive* overlay.
- **Risk heatmap**: Highlights the map tiles where ambushes are most likely based on your current run’s *seed entropy*.
- **Event decision assist**: Presents probability percentages for “Gift Choices” — not recommended picks, just *statistical likelihoods*.

### 5. 🌐 **Polyglot Interface**
- **Full UI localization** for English, 한국어, 日本語, 中文 (Simplified & Traditional), Deutsch, Français, and Español.
- **In-context translation** for in-game dialogue (via a local language model — no cloud calls).
- **RTL support** for Arabic and Hebrew overlays.

### 6. ⚡ **Response & Support**
- **24/7 Community Discord** with *real-time crash triage* and *preset sharing*.
- **Rollback versions** maintained for each major Limbus patch — you never lose your preferred tuning.
- **Modular config files** (JSON + Lua hybrid) that you can edit *blindfolded* — documented inline.

---

## 🛠️ Installation Philosophy

> *No raw binary patching. No driver-level interference. No permanent traces.*

The Edge runs as a **sidecar process** that reads the game’s shared memory via a *read-only* mapping. It never writes to the game executable or its checksum regions. This means:

- **Temporary by design**: Close the Edge — the game returns to 100% vanilla behavior instantly.
- **Anti-cheat conscious**: We design against *detection vectors*, but we cannot guarantee immunity. Use at your own discretion.
- **Zero footprint**: The overlay renders through a transparent DirectX layer that leaves no residual files after exit.

### First-Run Ritual
1. Launch Limbus Company to the **main menu**.
2. Start the Edge’s **orbit module** (it auto-detects the game window).
3. Wait for the **calibration chime** (a soft piano note) — means the data link is live.
4. Press `F9` to toggle the HUD. That’s it. No setup wizard, no cloud account.

---

## 📈 SEO-Friendly Keywords Naturally Embedded

- **Limbus Company solo-run optimization**
- **SP economy management tool**
- **Trainer with differentiable damage curves** (for those who want *nuance*, not brute force)
- **Mirror Dungeon advanced strategy aid**
- **Sinner stat visualization overlay**
- **Non-invasive game assistance suite** (the *polite* alternative to conventional trainers)
- **Real-time combat telemetry module**
- **Dynamic resistance awareness system**

---

## 🎨 Design Metaphors & How They Help

| Metaphor | Reality | Benefit |
|----------|---------|---------|
| **“Windsock”** | SP indicator that sways based on pressure | You see *trends*, not just numbers |
| **“Tuning Fork”** | Damage multiplier that vibrates when it resonates with enemy weakness | *Play with the rhythm*, not against it |
| **“Glass Cannon”** | Fortitude layer that lets you stay fragile but *informed* | You choose when to be glass — not the RNG |
| **“Peacock’s Eye”** | Tail-feather pattern on HUD showing enemy next-move probability | *Pattern recognition* without mental math |

---

## 📜 License & Legal Considerations

This project is released under the **MIT License** — you are free to use, modify, and distribute it, provided you retain the copyright notice and disclaimer. See the full [MIT License](LICENSE) for terms.

> **Disclaimer**: This suite is an **educational demonstration** of how game memory introspection works. It is *not affiliated*, endorsed, or sponsored by Project Moon (the developer of Limbus Company). The tool operates in a **gray zone** — it does not inject code, but it does read process memory. Use it only on **offline/solo content** you own. The creator assumes no responsibility for account actions taken by the game’s anti-cheat system. **You are responsible for your own virtual limbs.**

### 🔒 Privacy Assurance
- No telemetry, no analytics, no calls home.
- The orchestration logic runs entirely on your machine.
- Your configs stay local — we don’t want your *sinner data*.

---

## 🧭 Roadmap for 2026

- **Q1**: Introduce *Synapse Sync* — a local co-op mode for managing two Limbus instances on one PC.
- **Q2**: Add *Limbus Lens* — a screenshot analyzer that suggests optimal turn orders from your capture.
- **Q3**: Release a *Web-based companion* that lets you design your own damage curves on your phone, then sync via QR.
- **Q4**: Stability polish and *patch-proofing* against Limbus seasonal updates.

---

## ❓ Frequently Asked Contemplations

**Q: Will this work on the mobile version?**  
A: Currently desktop-only (Windows 10/11). Mobile is a *theoretical* possibility but would require significant rewriting.

**Q: Does it work with mods that alter game speed?**  
A: Speed mods may conflict with the Edge’s *timing cues* — we recommend disabling them for precise combat reads.

**Q: Is the SP sync safe for grind sessions?**  
A: It’s designed to *reduce* mental overhead — the auto-normalization prevents *fatigue-induced mistakes*, not character fatigue.

**Q: Why “Edge” and not “Simple UI”?**  
A: Because you’re not a *simple manager*. You’re an *edge-walker*.

---

## 🤝 Contributing Without Clichés

We welcome **cognitive collaborators** — people who think about combat as *choreography*, not statistics. If you’ve built a *mathematical model* for stagger thresholds or a *visualization library* for heatmaps, we want to merge your chaos.

- Fork, experiment, and submit a PR with a *witty commit message*.
- Share your **preset JSON** for unusual Sinner compositions (e.g., *all-Slasher teams*).
- Report *false-positive* calibration pulses with a screenshot; we’ll tune the algorithm.

---

## 🧾 Final Thought

> *The KIZAR trainer was a blunt instrument. The Edge is a **musical score**. You still play the symphony — this tool just corrects the acoustics.*