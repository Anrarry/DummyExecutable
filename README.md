# DummyExecutable
A dummy program that does nothing without creating any windows. Simple .exe file I made in order to replace certain Windows files (CrossDeviceResume.exe), since the operating system throws a visible UI error on every startup if it can't find it. Also my first experience with C#.

# Installing
Grab the latest version from the releases and you are good to go!

# Building
You need to have:
  * .NET SDK 10.0
  
Download the source code, extract it, go into the extracted folder and run:
```
dotnet build [PATH/TO/.SLNX/FILE]
```
The compiled .exe will be in the bin folder under the name "Main.exe"
