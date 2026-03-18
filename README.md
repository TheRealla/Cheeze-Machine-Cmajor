# 🎹 Cheeze Machine & Vintage Organ Emulations in Cmajor

**A collection of high-quality, free, open-source Cmajor patches** recreating the warm, quirky, and legendary sounds of early 20th-century electronic organs and 1970s–80s cheesy string machines.

Built for **Amorph** (the blazing-fast Cmajor sandbox plugin) and any Cmajor-compatible host (Cmajor standalone, JUCE exports, etc.). Perfect for macOS users chasing authentic tube-drift, multi-rank additive voicing, Pultec-style EQ polish, and Stardust-style mastering glue — all in one lightweight, compile-on-the-fly package.

![Amorph Logo](https://raw.githubusercontent.com/cmajor-lang/cmajor/main/docs/amorph.png)  
*(Tested & optimized for Amorph v0.9+ — March 2026)*

## ✨ Features
- True per-voice oscillator instability & thermal drift (real 1929 tube behavior)
- Multi-rank additive synthesis (8′ / 4′ / 2′ stops with drawbar-style knobs)
- Vintage tube saturation modeled after Airwindows Tube2 + Hard Vacuum
- Classic Pultec EQP-1A passive shelves + low-end trick
- 8-band Stardust-style multiband compressor for transparent mastering glue
- Swirling ensemble chorus (Solina / Cheeze Machine vibe)
- One-click compile in Amorph → instant high-performance AU/VST3
- Extremely low CPU — runs at 48 kHz / 64-sample buffers with headroom to spare

## 📦 Patches Included

| Patch                        | Description                                                                 | Best For                          |
|-----------------------------|-----------------------------------------------------------------------------|-----------------------------------|
| **CheezeMachine.cmajor**    | Multi-rank “cheesy” strings/organ with improved pulse-saw hybrid, per-voice detune, tube grit & stereo ensemble swirl | Lush pads, Solina-style leads, 70s string machines |
| **OrgueDesOndes.cmajor**    | Faithful 1929 Coupleux-Givelet recreation — per-note RC oscillators, natural chorus drift, tube bloom | Authentic early electronic organ tones for church/cinema vibes |
| **PultecTubeEQ.cmajor**     | Pultec EQP-1A + Airwindows Tube2 saturation (low-end trick, silky air, asymmetric warmth) | Vocals, master bus, or inserted after any organ patch |
| **StardustMultibandComp.cmajor** | 8-band mastering compressor inspired by the legendary freeware Arguru Stardust (gentle ratios, progressive attack/release) | Final polish & glue |
| **UltimateVintagePolish.cmajor** | Full chain: Orgue/Cheeze → PultecTubeEQ → Stardust 8-band → extra Tube2 + Dark veil | “Highest quality” mastered sound straight out of the box |

## 🚀 Quick Start (macOS + Amorph)

1. Download the latest **Amorph Effect** from [Artists in DSP](https://artistsindsp.gumroad.com/l/amorph)
2. In your DAW (Logic, Ableton, GarageBand, etc.), load **Amorph** on an instrument or master track
3. Open the Amorph code editor
4. Copy-paste any `.cmajor` file from this repo (or the whole folder)
5. Hit **Compile** → Amorph auto-generates beautiful knobs & MIDI-learn
6. Play! (MIDI keyboard recommended)

**Pro tip**: Map the “Montre 8′ / Prestant 4′ / Doublette 2′” sliders to your MIDI controller faders for real drawbar feel.

## 🎛️ Recommended Starting Settings

**Cheeze Machine**  
- Montre 8′: 0.85  
- Prestant 4′: 0.55  
- Doublette 2′: 0.35  
- Tube Grit: 2.1  
- Ensemble Depth: 0.78  

**UltimateVintagePolish** (master bus)  
- Pultec Low Boost: +4 dB @ 60 Hz  
- Pultec Low Atten: –3 dB (same freq = magic!)  
- Pultec High Boost: +3.5 dB @ 10 kHz  
- Tube Drive: 0.48  
- Makeup: +2.8 dB  
- Output Trim: –1 dB  

## 📸 Screenshots & Demos
(Coming soon — add your own recordings here!)

- [Watch a 60-second demo on YouTube](https://youtu.be/placeholder)  
- [SoundCloud set](https://soundcloud.com/placeholder)

## 🛠️ Technical Notes
- All processors use high-precision `std::math` and soft-knee RMS detection
- Chorus uses modulated BBD-style delay lines (no aliasing at 48 kHz)
- Tube saturation is asymmetric tanh-based (Airwindows Tube2/Hard Vacuum inspired)
- Multiband crossovers are Linkwitz-Riley 24 dB/oct approximations for musical transparency

## 📝 License
MIT — free for personal and commercial use. Attribution appreciated but not required.

## ❤️ Credits & Inspiration
- Original Orgue des Ondes research: 120years.net
- Airwindows Tube2 / Hard Vacuum / Dark algorithms (Chris @ airwindows.com)
- Pultec & Stardust spirit: classic freeware golden era
- Cmajor language & Amorph host: Julian Storer & Artists in DSP
- Built with love by theRealla (realla_the)

## 🤝 Contributing
Want to add more ranks, a full Ondes Martenot mode, or convolution spring reverb?  
Fork the repo, open a Pull Request, or just drop ideas in Issues.  
Let’s keep the vintage flame alive!

---

**Made for the Cmajor & Amorph community** — March 2026  
Star ⭐ the repo if you enjoy the cheesy warmth!


cmajor, dsp, synthesizer, vintage-synth, organ-emulation, string-machine, amorph, audio-plugin 

