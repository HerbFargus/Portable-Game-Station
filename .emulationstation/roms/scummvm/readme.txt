To get scummvm games to run from emulationstation you need to install scummvm and then create a batch script for each game e.g.

Create a file title.bat:

Pajama Sam 1 No Need to Hide When It's Dark Outside.bat

Contents:

pushd "%HOMEPATH%\.emulationstation\roms\scummvm\Pajama Sam 1 No Need to Hide When It's Dark Outside"
%HOMEPATH%\.emulationstation\systems\scummvm\scummvm.exe -f "pajama-us"