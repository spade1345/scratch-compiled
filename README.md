# scratch-compiled

This is a collection of games from the Scratch website (<https://scratch.mit.edu>) compiled for HTML and native platform usage.

## Games in this collection

- [`griffpatch`'s Terraria (stamped) v6](<https://scratch.mit.edu/projects/322341152>)
  - `terraria-modified` is a version of this with minor graphical improvements
- [planned] [`griffpatch`'s Paper Minecraft](<https://scratch.mit.edu/projects/10128407/>)

## Plan of support

The plan is to create packaged versions in the following formats:

- Local HTML: Run an HTML file in your browser to play the game
- Web version: Currently unused. Meant for online web hosting.
- Standalone: Standalone apps for certain platforms.

## List of projects

- griffpatch-terraria: local-html, web, standalone (windows-zip, linux-zip)
  - completely untouched from the original
- terraria-modified: currently undergoing updates
  - modified version of the griffpatch-terraria with visual improvements
  - features a basic adaptive music system, the day theme will change if you are on low HP
  - credit to Anuke, creator of open source factory RTS game [Mindustry](https://github.com/anuken/mindustry) and its original soundtrack, for additional music for the adaptive music system!
- paper-minecraft: planned

## How?

Projects were compiled using the Turbowarp Packager. Turbowarp can be found [here.](https://turbowarp.org) A desktop standalone app with packager included can be found [here.](https://desktop.turbowarp.org/)

The packager can be found [here](https://packager.turbowarp.org/) and is included in the desktop distribution of Turbowarp Desktop.

The output of the packager for standalone versions of projects have been modified using [turbowarp-packager-extras](https://github.com/TurboWarp/packager-extras) for Windows.

Extra assets used are located in an assets folder in each project folder.