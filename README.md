# Kingmaker CoTW Mod Maker

## Credits

* All credits go to Holic75 [https://github.com/Holic75]

## Install

1. Create KINGMAKER_HOME system environment variable and set it to the folder where Kingmaker.exe resides (i.e: C:\GOG\Games\Pathfinder Kingmaker)

## Build a Mod

* Pathfinder Kingmaker Mods heavily use Blueprints to define new game behaviors. More details on Blueprints here [https://github.com/spacehamster/KingmakerCustomBlueprints]

* CoTW Helpers can automatically create Blueprints IDs which makes Mod creation much easier. To do so you need to build your code in DEBUG mode and let it create a blueprints.txt file in the Mod folder. Copy this file back to your project before building in RELEASE mode

* You can define settings on Settings.json, and have them read on Main.cs. There is already placeholder code to do that

