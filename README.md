# AeroStage Beta

**AeroStage Beta** is a six-level headphone spatial-texture VST3 plug-in for Windows.

It is intended for normal two-channel headphone listening with ordinary stereo recordings. It is not virtual surround, not Dolby-style spatial audio, and not an HRTF externalization simulator. The goal is subtler: changing the spatial texture of headphone playback, including diffusion, density, depth, and long-listening comfort.

## Download

Use the release asset:

```text
AeroStageBeta-v0.2.0-beta-win64-vst3.zip
```

## Requirements

- Windows 10/11, 64-bit
- foobar2000
- foobar2000 VST 2.x/3.x Adapter component
- Stereo headphone playback

## Levels

| Button | Name | Intended use |
|---:|---|---|
| 0 | Reference / Bypass | Gain-matched reference for comparison. No spatial processing. |
| 1 | Comfort | Almost transparent, everyday fatigue reduction. |
| 2 | Diffusion | Adds lateral diffusion and width. |
| 3 | Bloom | Spatial bloom around sound sources. |
| 4 | Atmosphere | Loudspeaker-like spatial texture that resembles room ambience. |
| 5 | Concert | Stronger concert-like spatial presentation, designed for classical music. |

## Installation

Detailed foobar2000 instructions are in [`INSTALL_FOOBAR.md`](INSTALL_FOOBAR.md).

Short version:

1. Install the foobar2000 VST 2.x/3.x Adapter component.
2. Download and unzip `AeroStageBeta-v0.2.0-beta-win64-vst3.zip`.
3. Copy the whole `AeroStageBeta.vst3` folder into a VST3 folder.
4. Add the VST adapter in foobar2000 DSP Manager.
5. Select AeroStage Beta and choose one of the six levels.

## Note
Buttons 1-5 in this release corresponds to AeroStage 2, 4, 6, 8, and 10 in a more complete package tentatively named AeroStage Pro. 
