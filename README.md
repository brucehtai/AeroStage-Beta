# AeroStage Beta

**AeroStage Beta** is a six-level headphone spatial-texture VST3 plug-in for Windows.

It is intended for normal two-channel headphone listening. It is not virtual surround, not Dolby-style spatial audio, and not an HRTF externalization simulator. The goal is subtler: changing the spatial texture of headphone playback, including diffusion, density, depth, and long-listening comfort.

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

| Button | AeroStage level | Name | Intended use |
|---:|---:|---|---|
| 0 | 0 | Reference / Bypass | Gain-matched reference for comparison. |
| 1 | 2 | Comfort neutral | Mild, natural, everyday fatigue reduction. |
| 2 | 4 | Diffusion width | Adds lateral diffusion and width. |
| 3 | 6 | Diffusion bloom | Fuller diffusion and spatial bloom. |
| 4 | 8 | Atmosphere relaxed | More relaxed ambience and spatial density. |
| 5 | 10 | Concert intimate | Stronger concert-like spatial presentation. |

## Installation

Detailed foobar2000 instructions are in [`INSTALL_FOOBAR.md`](INSTALL_FOOBAR.md).

Short version:

1. Install the foobar2000 VST 2.x/3.x Adapter component.
2. Download and unzip `AeroStageBeta-v0.2.0-beta-win64-vst3.zip`.
3. Copy the whole `AeroStageBeta.vst3` folder into a VST3 folder.
4. Add the VST adapter in foobar2000 DSP Manager.
5. Select AeroStage Beta and choose one of the six levels.

## Feedback requested

Please report:

- headphone model
- DAC/amp or audio interface
- music used for testing
- favorite level
- best level for natural tone
- best level for spatial texture
- best level for long listening comfort
- any clipping, loading, or host problems

## AeroStage Pro

This public beta contains six levels selected for most music listeners. A larger AeroStage Pro version with the full level set can be kept as a premium/audiophile edition.
