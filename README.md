MusicStore (test application)
=============================

AppVeyor: [![AppVeyor][appveyor-badge]][appveyor-build]

Travis:   [![Travis][travis-badge]][travis-build]

[appveyor-badge]: https://ci.appveyor.com/api/projects/status/ja8a7j6jscj7k3xa/branch/dev?svg=true
[appveyor-build]: https://ci.appveyor.com/project/aspnetci/MusicStore/branch/dev
[travis-badge]: https://travis-ci.org/aspnet/MusicStore.svg?branch=dev
[travis-build]: https://travis-ci.org/aspnet/MusicStore

This project is part of ASP.NET Core. You can find samples, documentation and getting started instructions for ASP.NET Core at the [Home](https://github.com/aspnet/home) repo.

## About this repo

This repository is a test application used for ASP.NET Core internal test processes.
It is not intended to be a representative sample of how to use ASP.NET Core.

Samples and docs for ASP.NET Core can be found here: <https://docs.asp.net>.

## How to build

*These steps are for building from command-line on a machine without any developer tools installed.*

* Install NET Framework Developer Pack. Both [4.6.1](https://www.microsoft.com/en-in/download/details.aspx?id=49978) and
 [4.6.2](https://www.microsoft.com/en-us/download/details.aspx?id=53321) are required.
 * Download MSBuild. [MSBuild 2015](https://www.microsoft.com/en-in/download/details.aspx?id=48159) worked fine for me.
 
 ```
 .\build.cmd
 ```
