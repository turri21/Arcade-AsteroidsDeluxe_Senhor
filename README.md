-=(AsteroidsDeluxe_Senhor notes)=-

Tested: Working Video 720p, 1080p & Sound.

Dev notes: The following settings have been added in Arcade-AsteroidsDeluxe.qsf:

set_global_assignment -name FITTER_AGGRESSIVE_ROUTABILITY_OPTIMIZATION NEVER

set_global_assignment -name ADVANCED_PHYSICAL_OPTIMIZATION OFF

set_global_assignment -name OPTIMIZE_MULTI_CORNER_TIMING OFF
___
# [Arcade: Asteroids Deluxe](https://www.arcade-museum.com/game_detail.php?game_id=6940) for [MiSTer](https://github.com/MiSTer-devel/Main_MiSTer/wiki)

The original source code was downloaded from: http://fpgaarcade.com/games.htm

## Description

This is a simulation model of the Asteroids Deluxe hardware which is a vector graphics based arcade system that utilized a 6502 processor along with a proprietary display.

This Arcade Core only runs Asteroids Deluxe. There is a separate core for the original Asteroids arcade game: https://github.com/MiSTer-devel/Arcade-Asteroids_MiSTer

## ROM Files Instructions

**ROMs are not included!** In order to use this arcade core, you will need to provide the correct ROM file yourself.

To simplify the process .mra files are provided in the releases folder, that specify the required ROMs with their checksums. The ROMs .zip filename refers to the
corresponding file from the MAME project.

Please refer to https://github.com/MiSTer-devel/Main_MiSTer/wiki/Arcade-Roms for information on how to setup and use the environment.

Quick reference for folders and file placement:

```
/_Arcade/<game name>.mra  
/_Arcade/cores/<game rbf>.rbf  
/_Arcade/mame/<mame rom>.zip  
/_Arcade/hbmame/<hbmame rom>.zip  
```
