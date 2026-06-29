# AeroStage Beta

**AeroStage Beta** is a six-level headphone spatial-texture VST3 plug-in for Windows.

It is intended for normal two-channel headphone listening with ordinary stereo recordings. It is not virtual surround, not Dolby-style spatial audio, and not an HRTF externalization simulator. The goal is subtler: changing the spatial texture of headphone playback, including diffusion, density, depth, bloom, atmosphere, and long-listening comfort.

## Download

Use the latest GitHub release asset:

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
| 0 | Reference / Bypass | Gain-matched reference for comparison. Minimal processing. |
| 1 | Comfort | The mildest spatial setting. Everyday listening and fatigue reduction. |
| 2 | Diffusion | Adds lateral diffusion and width while staying broadly natural. |
| 3 | Bloom | Adds more spatial bloom and density around sound sources. |
| 4 | Atmosphere | Stronger ambience-like spatial texture and loudspeaker-like presentation. |
| 5 | Concert | Strongest setting, intended for a more hall-like presentation. |

## Installation

Detailed foobar2000 instructions are in [`INSTALL_FOOBAR.md`](INSTALL_FOOBAR.md).

Short version:

1. Install the foobar2000 VST 2.x/3.x Adapter component.
2. Download and unzip `AeroStageBeta-v0.2.0-beta-win64-vst3.zip`.
3. Copy the whole `AeroStageBeta.vst3` folder into a VST3 folder.
4. Add the VST adapter in foobar2000 DSP Manager.
5. Select AeroStage Beta and choose one of the six levels.

## Feedback

A copyable feedback form is in [`FEEDBACK_TEMPLATE.md`](FEEDBACK_TEMPLATE.md).

Useful feedback includes:

- headphone model
- DAC/amp or audio interface
- music used for testing
- favorite level
- best level for tonal naturalness
- best level for spatial texture
- least fatiguing level
- any clipping, loading, or host problems

## Known limitations

- Windows VST3 beta only.
- The plug-in is for two-channel headphone listening.
- Speaker playback is not the current target.
- The GUI is intentionally simple and shows only real available controls.
- Some hosts may require rescanning the VST3 folder after updating the plug-in.

## Project status

This is a public beta build. The 13-level AeroStage Pro version is a separate extended/audiophile evaluation build.
The bottons 1-5 in this release correspond to AeroStage 2, 4, 6, 8, 10 in the Pro version. 
