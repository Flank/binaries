# binaries

Binaries used in Flank's iOS test sharding.

# update Linux or MacOS

Update to new versions by modifying and running `update.sh` for Linux or MacOs only!

# update Windows

To update for Windows support download the latest Swift for windows from [Here:](https://swift.org/download/) 
Install it and navigate to binary folder found at __%SystemDrive%\Library\Developer\Toolchains\ {swift_version_here}\usr\bin__
Copy the swift swift-demangle.exe from here.

nm.exe is a more complicated to retrieve. nm.exe found here is located from the project [SwiftForWindows](https://github.com/SwiftForWindows/SwiftForWindows)
This also requires a download of the entire release and locatating the nm.exe file found in C:\Swift\mingw64\bin.