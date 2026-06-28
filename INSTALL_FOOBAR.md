# Installing AeroStage Beta in foobar2000

This guide assumes Windows 10/11 and foobar2000.

## 1. Install the foobar2000 VST adapter

AeroStage Beta is a **VST3** plug-in. foobar2000 needs a VST adapter component before it can load VST3 plug-ins.

In foobar2000:

1. Install the **VST 2.x/3.x Adapter** component for foobar2000.
2. Restart foobar2000 after installing the component.
3. Open:

```text
File → Preferences → Playback → DSP Manager
```

You should see something like:

```text
VST 2.x/3.x Adapter
```

in the available DSP list.

## 2. Install the AeroStageBeta VST3 folder

Unzip:

```text
AeroStageBeta-v0.1.0-beta-win64-vst3.zip
```

Inside it should be a folder named:

```text
AeroStageBeta.vst3
```

Copy the **whole folder** into one of these VST3 locations.

User-local folder, usually no administrator permission needed:

```text
C:\Users\<your-user-name>\AppData\Local\Programs\Common\VST3
```

System-wide folder, may require administrator permission:

```text
C:\Program Files\Common Files\VST3
```

Important: `AeroStageBeta.vst3` is a folder bundle. Do not copy only the inner `.dll` or binary file.

## 3. Add the VST3 folder in foobar2000

In foobar2000:

```text
File → Preferences → Playback → DSP Manager
```

1. Add **VST 2.x/3.x Adapter** to the active DSP chain.
2. Open its configuration.
3. Click **Folders...**
4. Add the folder where you copied `AeroStageBeta.vst3`.
5. Rescan if needed.
6. Select **AeroStageBeta** from the VST effect list.
7. Click **Apply** or **OK**.

## 4. Choose a level

The plug-in has five levels:

```text
0  Bypass / Reference
1  Transparent / Fatigue reducer
2  Diffuse
3  Atmosphere
4  Concert
```

Recommended first test:

1. Start with Level 0.
2. Switch to Level 1.
3. Then compare Levels 2, 3, and 4.
4. Do not judge only by the first few seconds. Some levels are meant for longer listening comfort, not instant effect.

## 5. Troubleshooting

### I do not see AeroStageBeta in foobar2000

Check that you copied the whole folder:

```text
AeroStageBeta.vst3
```

not just a file inside it.

Then reopen the VST adapter configuration and rescan the VST folder.

### I see duplicate AeroStageBeta entries

foobar2000 is probably scanning two folders that both contain the plug-in. Remove one scan folder or delete the duplicate copy.

### The GUI opens but looks too large or too small

This is a beta GUI. Audio processing should still work. Report your Windows display scaling value if the layout looks wrong.

### I hear clipping

The current beta includes output attenuation, but some online material is extremely hot. Lower foobar2000 volume or system output level slightly and report the track/source.

### The plug-in does not work in Peace / Equalizer APO

This release is intended for foobar2000 through a VST3 adapter. Peace / Equalizer APO is not the target host for this VST3 beta.
