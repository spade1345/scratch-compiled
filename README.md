# scratch-compiled

This is a collection of games from the Scratch website (<https://scratch.mit.edu>) compiled for HTML and native platform usage.

## Games in this collection

- [`griffpatch`'s Terraria (stamped) v6](<https://scratch.mit.edu/projects/322341152>)
  - `terraria-modified` is a version of this with minor graphical improvements
- [`griffpatch`'s Paper Minecraft](<https://scratch.mit.edu/projects/10128407/>)
  - [planned] [`Aaryanthepro`'s Paper Minecraft Modded.](https://scratch.mit.edu/projects/407871564/) Yes, the one with nukes.
  - `paper-minecraft-modded` will have extra visual improvements as well

## Plan of support

The plan is to create packaged versions in the following formats:

- Local HTML: Run an HTML file in your browser to play the game
- Web version: For web hosting. Currently unused
- Standalone: Standalone apps for certain platforms via Electron

## List of projects

- griffpatch-terraria: local-html, web, standalone (windows-zip, linux-zip)
  - completely untouched from the original
- terraria-modified: local-html, web, standalone (windows-zip, linux-zip)
  - modified version of the griffpatch-terraria with UI improvements
  - features a basic adaptive music system, the game plays different, darker themes if you are low on HP
  - credit to Anuken, creator of open source factory RTS game [Mindustry](https://github.com/anuken/mindustry) and its original soundtrack, for additional music for the adaptive music system!
  - credit to Blockage for the track Encounter, a music track used in their awesome ROBLOX game Neon Knights!
- paper-minecraft: local-html, web, standalone (windows-zip, linux-zip)
- paper-minecraft-modded: planned, if I can find the right one

## How?

Projects were compiled using the Turbowarp Packager. Turbowarp can be found [here.](https://turbowarp.org) A desktop standalone app with packager included can be found [here.](https://desktop.turbowarp.org/)

The packager can be found [here](https://packager.turbowarp.org/) and is included in the desktop distribution of Turbowarp Desktop.

The output of the packager for standalone versions of projects have been modified using [turbowarp-packager-extras](https://github.com/TurboWarp/packager-extras) for Windows.

Extra assets used are located in an assets folder in each project folder.
