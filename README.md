# Sugary Spire Web Port
A Web Port of Sugary Spire (based off Playtest 3.2 Source Code)

Demo Site: https://www.autistici.org/burnedprojects/sugaryspire/SugarySpire.html

## Downloads
Source Code and Compiled Web Build can be Downloaded From the Releases Tab

### Current Issues
There are Issues, such as:
- Color Palettes don't display correctly or at all
- Audio plays Only on the Right Speaker
> ez fix, just some audio setting in gm

## For Compiling
- Use GameMaker Studio Version 2023.4.0.84 to compile for Web
- Compile using GX.GAMES + VM options (or + YYC)
> [!IMPORTANT]
> YYC is Recommended, as it runs slightly faster

- After the game has ALREADY compiled and loaded on your browser, steal the temp files from

```C:\Users\ (YOUR USER) \AppData\Local\GameMakerStudio2\GMS2TEMP```

    - In where you will find folders called `SugarySpire_( SOME NUMBERS )_VM` (or _YYC if you chose that option)
    - Steal the `/runner` sub-directory from the most recent one, as that folder contains the important files
- After that, you have the compilied files ready for use in a server

## Thanks to
- Tour de Pizza for the base game
