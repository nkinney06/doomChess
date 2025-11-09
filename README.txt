
Proof of concept mod for the classic videogame DOOM. Click and drag doomChess.pk3 to run with GZDoom.

Zombie and Imp deaths trigger chess puzzles. The menu is a bit clunky but works well with GZDoom g4.14.2-m.
I've also been able to run it on gzdoom-bin-3-3-2-x64 but the menu needs work. 

SLADE project files are included: I'm using SLADE v3.2.8. You need to unzip SLADE_PROJECT_FILES/graphics.zip

If you modify SCRIPTS I needed to do the following:
    1. save as SCRIPTS.acs
	2. compile with acc-1.60-win32. In windows that involved opening cmd followed by something like this
	   D:\Desktop\doomChess>"D:\Desktop\doomChess\acc-1.60-win32\acc.exe" SCRIPTS.acs doomChess.o
	3. move doomChess.o to the slade acs directory.
	4. make sure to save the project so the .pk3 updates

