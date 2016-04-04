EnlistmentInfo
=================

This project produces a NuGet package that you can add to your MSBuild project to
automatically import EnlistmentInfo.props at the top of your project file and
import EnlistmentInfo.targets at the bottom of your project file.

These EnlistmentInfo.* files may be present in your project directory, or any
directory that is an ancestor to it. A recursive search toward the root directory
will stop and import the first match of each file it finds.
