# AeroStage Beta

**AeroStage Beta** is a five-level headphone spatial-texture VST3 plug-in for Windows.

This beta is intended for listening feedback. It is not virtual surround, not Dolby-style spatial audio, and not an HRTF/externalization simulator. The goal is subtler: to change the *spatial texture* of headphone playback—how dense, diffuse, relaxed, or speaker-like the stereo field feels—while keeping normal two-channel music playback.

## Download

Use the release asset:

`AeroStageBeta-v0.1.0-beta-win64-vst3.zip`

SHA-256:

```text
abdc3adaa008360f2cf50a0b34b3b4a4599c29836974877ef264a439498c0069
```

## Requirements

- Windows 10/11, 64-bit
- foobar2000
- foobar2000 VST 2.x/3.x Adapter component
- Stereo headphone playback

## Quick install summary

1. Install the foobar2000 VST 2.x/3.x Adapter component.
2. Unzip `AeroStageBeta-v0.1.0-beta-win64-vst3.zip`.
3. Copy the whole `AeroStageBeta.vst3` folder into a VST3 folder.
4. In foobar2000, add the VST adapter in **Preferences → Playback → DSP Manager**.
5. Point the adapter to the VST3 folder and select **AeroStageBeta**.
6. Open the plug-in window and choose Level 0–4.

Detailed instructions are in [`INSTALL_FOOBAR.md`](INSTALL_FOOBAR.md).

## Levels

| Level | Name | Description |
|---:|---|---|
| 0 | Bypass / Reference | Gain-matched reference level for comparison. Minimal processing. |
| 1 | Transparent / Fatigue reducer | Mildest processing. Intended to reduce headphone fatigue while staying close to the original tonal balance. |
| 2 | Diffuse | Moderate spatial diffusion and depth. A useful everyday spatial-texture setting. |
| 3 | Atmosphere | Stronger sense of ambience and relaxed spatial density. More obviously processed than Level 2. |
| 4 | Concert | Most spacious and colored setting. Intended for a more hall-like, concert-style presentation. Best suited to some recordings rather than all music. |

## Suggested feedback

When posting impressions, please include:

- Headphone model
- DAC/amp or audio interface
- foobar2000 output mode, if known
- Music used for testing
- Favorite level overall
- Best level for spatial texture
- Best level for tonal naturalness
- Best level for long listening / fatigue
- Any clipping, instability, or loading problems

A copyable feedback form is in [`FEEDBACK_TEMPLATE.md`](FEEDBACK_TEMPLATE.md).

## Known limitations

- Windows VST3 beta only.
- The GUI is intentionally simple.
- Some hot online material may still clip depending on source level and playback chain. Lower foobar2000 or system volume if needed.
- The plug-in is for two-channel headphone listening. Speaker use is not the current target.

## Files in this release kit

- `AeroStageBeta-v0.1.0-beta-win64-vst3.zip` — the VST3 binary package to upload as the GitHub release asset
- `README.md` — repository README
- `INSTALL_FOOBAR.md` — foobar2000 installation instructions
- `FEEDBACK_TEMPLATE.md` — listening-test form
- `GITHUB_RELEASE_TEXT.md` — text to paste into the GitHub release page
- `THIRD_PARTY_NOTICES.md` — third-party notices placeholder
