# Glint
Cmajor implementation of Geraint Luff (SignalSmith)'s [Reverb](https://signalsmith-audio.co.uk/writing/2021/lets-write-a-reverb/)

## Usage
You can either download the Cmajor runtime and load the patch in the Cmajor plugin, or you can download one of the
pre-built plugins (AUv2, VST3 - macOS x86_64/arm64). If you download the pre-built plugins you'll need to run the
following to remove the macOS security block on the files since they are not code signed.
```
xattr -c ~/Library/Audio/Plug-Ins/VST3/Glint.vst3
xattr -c ~/Library/Audio/Plug-Ins/Components/Glint.component
```