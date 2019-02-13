# KeyCastOW
keystroke visualizer for Windows, lets you easily display your keystrokes while recording screencasts.

* small footprint (one 100kb executable file)
* green and portable, only depends on windows system dlls
* prenty of settings for keystroke display
* hotkey to turn on/off


## build

  msbuild /p:platform=win32 /p:Configuration=Release /p:PlatformToolset=v110

## reference
https://stackoverflow.com/questions/33380128/visual-studio-2015-command-line-retarget-solution/33386141#33386141

```
You can find the PlatformToolset by run: msbuild /version

Visual Studio .NET 2002 (Platform Toolset = 'v70')
Visual Studio .NET 2003 (Platform Toolset = 'v71')
Visual Studio 2005      (Platform Toolset = 'v80')
Visual Studio 2008      (Platform Toolset = 'v90')
Visual Studio 2010      (Platform Toolset = 'v100')
Visual Studio 2012      (Platform Toolset = 'v110')
Visual Studio 2013      (Platform Toolset = 'v120')
Visual Studio 2015      (Platform Toolset = 'v140')
Visual Studio 2017      (Platform Toolset = 'v141')
```

## License

MIT License
