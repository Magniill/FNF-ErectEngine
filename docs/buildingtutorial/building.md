# Building Friday Night Funkin': Erect Engine

**Please note** that these instructions are for compiling/building the game. If you just want to play Erect Engine, download the game from gamebanana or gamejolt or in the releases, if you want to build the game, continue reading.

**Also note**: you should be familiar with the commandline. If not, read this [quick guide by ninjamuffin](https://ninjamuffin99.newgrounds.com/news/post/1090480).

**Also also note**: This is only for *Windows*, not *Linux*, *MacOS* or *Chromebook*.

## Dependencies
 1. [Install The Latest version of Haxe](https://haxe.org/download). Stop using 4.1.5 it misses stuff/
 2. After installing Haxe, [Install HaxeFlixel](https://haxeflixel.com/documentation/install-haxeflixel/).
 3. Install `git`.
	 - Install from the [git-scm](https://git-scm.com/downloads) website.
 4. Run the [installation batch file](installation.bat) to install all of the commands, it should work properly.

It will automatically install Visual Studio 2019. This will install about 4 GB of crap, but is necessary to build for Windows.

## Building
Finally, we are ready to build.

- Run [the builder batch file](build.bat)
- The build will be in `Erect-Engine/export/release/windows/bin`
- Only the `bin` folder is necessary to run the game. The other ones in `export/release/windows` are not.
