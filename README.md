EnlistmentInfo
=================

[![Build status](https://ci.appveyor.com/api/projects/status/lcawxbl6blrbo5ha/branch/master?svg=true)](https://ci.appveyor.com/project/AArnott/enlistmentinfo/branch/master)
[![NuGet Pre Release](https://img.shields.io/nuget/vpre/EnlistmentInfo.svg)](https://www.nuget.org/packages/EnlistmentInfo)

This project produces a NuGet package that you can add to your MSBuild project to
automatically import EnlistmentInfo.props at the top of your project file and
import EnlistmentInfo.targets at the bottom of your project file.

These EnlistmentInfo.* files may be present in your project directory, or any
directory that is an ancestor to it. A recursive search toward the root directory
will stop and import the first match of each file it finds.
