# Glint
[Cmajor](https://cmajor.dev) implementation of Geraint Luff (Signalsmith Audio)'s [reverb](https://signalsmith-audio.co.uk/writing/2021/lets-write-a-reverb/).

<img width="546" alt="Glint" src="https://github.com/user-attachments/assets/2f065736-fe0d-4d10-bb35-a58930b9c4b2" />

## Usage
You can either download the Cmajor runtime and load the patch in the Cmajor plugin, or you can download one of the
pre-built plugins (AUv2, VST3 - macOS x86_64/arm64). If you download the pre-built plugins you'll need to run the
following to remove the macOS security block on the files since they are not code signed.
```
xattr -c ~/Library/Audio/Plug-Ins/VST3/Glint.vst3
xattr -c ~/Library/Audio/Plug-Ins/Components/Glint.component
```
