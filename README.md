# rfl-db-extracter
Extracts Miis from RFL_DB.dat from a Wii

## Requirements 
`kaitai-struct` for reading names of Miis

## Some of my Miis are random numbers! What does this mean?
This means that the name was an invalid file name, so it was replaced with a number.
How is this number generated? Well, it's the Miis position in `RFL_DB.dat`, so for instance:
1 - zurgeg's Mii (filename would be zurgeg's Mii.mii)
2 - ? (filename would be 2.mii, as ?.mii is an invalid filename)

## Where did the Mii Kaitai come from?
See https://github.com/RiiConnect24/kaitai-files and https://github.com/RiiConnect24/mii2studio.

## Where can I find RFL_DB.dat and how do I extract it?
For a real Wii, use WiiXplore and navigate to sys2/FaceLib/RFL_DB.dat and copy it to your SD.
For Dolphin Emulator, navigate to your User folder (usually in Documents/Dolphin Emulator), then go to Wii/sys2/FaceLib/RFL_DB.dat and copy it to the directory the program is running in.

