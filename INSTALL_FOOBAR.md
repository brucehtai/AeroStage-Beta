# Installing AeroStage Beta in foobar2000

AeroStage Beta is a Windows VST3 plug-in. foobar2000 needs a VST adapter component before it can load VST3 plug-ins.

## 1. Install the foobar2000 VST adapter

Install the foobar2000 **VST 2.x/3.x Adapter** component.

After installing the component, restart foobar2000.

Then open:

```text
File -> Preferences -> Playback -> DSP Manager
```

You should see a VST adapter option in the available DSP list.

## 2. Download and unzip AeroStage Beta

Download the attached release file:

```text
AeroStageBeta-v0.2.0-beta-win64-vst3.zip
```

Unzip it.

Inside, you should see:

```text
AeroStageBeta.vst3
```

Important: `AeroStageBeta.vst3` is a folder bundle. Copy the whole folder. Do not copy only the inner DLL file.

## 3. Copy the VST3 folder

Copy the whole `AeroStageBeta.vst3` folder to one of these locations.

User-local VST3 folder:

```text
C:\Users\<your-user-name>\AppData\Local\Programs\Common\VST3
```

System-wide VST3 folder:

```text
C:\Program Files\Common Files\VST3
```

The user-local folder is usually easier because it does not require administrator permission.

## 4. Load it in foobar2000

In foobar2000, open:

```text
File -> Preferences -> Playback -> DSP Manager
```

Add the **VST 2.x/3.x Adapter** to the active DSP chain.

Open the VST adapter configuration, add or rescan the VST3 folder, then select:

```text
AeroStage Beta
```

Click **Apply** or **OK**.

## 5. Choose a level

The plug-in has six levels:

```text
0  Reference / Bypass
2  Comfort neutral
4  Diffusion width
6  Diffusion bloom
8  Atmosphere relaxed
10 Concert intimate
```

Start with Reference / Bypass, then compare the other levels.

## Troubleshooting

If AeroStage Beta does not appear, check that you copied the whole `AeroStageBeta.vst3` folder and then rescan the VST folder in foobar2000.

If duplicate entries appear, foobar2000 is probably scanning two folders that both contain AeroStage Beta. Remove one scan folder or delete the duplicate copy.

If you hear clipping, lower foobar2000 or system output level slightly and report the track/source.

This beta is intended for foobar2000 with a VST3 adapter. It is not intended for direct use in Peace / Equalizer APO.
