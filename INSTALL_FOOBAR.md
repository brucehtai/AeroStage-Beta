# Installing AeroStage Beta in foobar2000

This guide assumes Windows 10/11 and foobar2000.

## 1. Install the foobar2000 VST adapter

AeroStage Beta is a **VST3** plug-in. foobar2000 needs a VST adapter component before it can load VST3 plug-ins.

In foobar2000:

1. Install the **VST 2.x/3.x Adapter** component.
2. Restart foobar2000 after installing the component.
3. Open:

```text
File -> Preferences -> Playback -> DSP Manager
```

You should see a VST adapter option in the available DSP list.

## 2. Download and unzip AeroStage Beta

Download the release file:

```text
AeroStageBeta-v0.2.0-beta-win64-vst3.zip
```

Unzip it.

Inside, you should see a folder named:

```text
AeroStageBeta.vst3
```

Important: `AeroStageBeta.vst3` is a folder bundle. Copy the whole folder. Do not copy only the inner DLL or binary file.

## 3. Copy the VST3 folder

Copy the whole `AeroStageBeta.vst3` folder to one of these locations.

User-local VST3 folder, usually no administrator permission needed:

```text
C:\Users\<your-user-name>\AppData\Local\Programs\Common\VST3
```

System-wide VST3 folder, may require administrator permission:

```text
C:\Program Files\Common Files\VST3
```

## 4. Load it in foobar2000

In foobar2000, open:

```text
File -> Preferences -> Playback -> DSP Manager
```

1. Add **VST 2.x/3.x Adapter** to the active DSP chain.
2. Open the VST adapter configuration.
3. Add or rescan the VST3 folder where you copied `AeroStageBeta.vst3`.
4. Select **AeroStage Beta**.
5. Click **Apply** or **OK**.

## 5. Choose a level

The plug-in has six public levels:

```text
0  Reference / Bypass
1  Comfort
2  Diffusion
3  Bloom
4  Atmosphere
5  Concert
```

Recommended first test:

1. Start with Level 0.
2. Switch to Level 1.
3. Then compare Levels 2-5.
4. Do not judge only by the first few seconds. Some settings are intended for long listening comfort rather than instant effect.

## Troubleshooting

### I do not see AeroStage Beta in foobar2000

Check that you copied the whole folder:

```text
AeroStageBeta.vst3
```

Then reopen the VST adapter configuration and rescan the VST folder.

### I see duplicate AeroStage Beta entries

foobar2000 is probably scanning two folders that both contain the plug-in. Remove one scan folder or delete the duplicate copy.

### The old five-level version still appears

Remove the old AeroStage Beta entry from the VST adapter, delete the old `AeroStageBeta.vst3` copy from the scanned VST folder, copy the new one, and rescan.

### I hear clipping

Lower foobar2000 volume or system output level slightly and report the track/source.

### The plug-in does not work in Peace / Equalizer APO

This release is intended for foobar2000 through a VST3 adapter. Peace / Equalizer APO is not the target host for this VST3 beta.
