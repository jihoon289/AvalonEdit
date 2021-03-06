﻿# AvalonEdit [![NuGet](https://img.shields.io/nuget/v/AvalonEdit.svg)](https://nuget.org/packages/AvalonEdit) [![Build status](https://ci.appveyor.com/api/projects/status/bvvux3y2b6tw272e/branch/master?svg=true)](https://ci.appveyor.com/project/icsharpcode/avalonedit/branch/master)


AvalonEdit is the name of the WPF-based text editor in SharpDevelop 4.x "Mirador" and beyond. It is also being used in ILSpy and many other projects.

Downloads
-------

AvalonEdit is available as [NuGet package](https://www.nuget.org/packages/AvalonEdit). Usage details, documentation and more
can be found on the [AvalonEdit homepage](http://avalonedit.net/)

How to build
-------

AvalonEdit is targeting netcoreapp3.0, net40 and net45 TFMs. Because of netcoreapp3.0 you must have .NET Core 3.0 SDK (currently in preview) installed 
on your machine. Visual Studio 2019 is required for working with the solution (global.json will select the proper SDK to use for building for you).


Documentation
-------

Check out the [official documentation](http://avalonedit.net/documentation/) and the [samples and articles wiki page](https://github.com/icsharpcode/AvalonEdit/wiki/Samples-and-Articles)

To build the Documentation you need to install Sandcastle from https://github.com/EWSoftware/SHFB/releases (currently validated tooling is
v2019.4.14.0)

The build of the Documentation can take very long, please be patient.

License
-------

AvalonEdit is distributed under the [MIT License](http://opensource.org/licenses/MIT).

Projects using AvalonEdit
-------

* https://github.com/icsharpcode/ILSpy/: .NET decompiler

Note: if your project is not listed here, let us know! :)