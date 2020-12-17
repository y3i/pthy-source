# pthy-source
Minecraft ParTicle HolographY engine in C#.

Here's the source code people asked for.

**Installation:**
  Public release:
   - Release is pre-prepared. Simply extract the .zip and run.

  Source:
   - You need to install the [Emgu.CV](https://www.nuget.org/packages/Emgu.CV/4.4.0.4099), [Emgu.CV windows runtime](https://www.nuget.org/packages/Emgu.CV.runtime.windows/) and [System.Drawing.Common](https://www.nuget.org/packages/System.Drawing.Common/) NuGet packages.
   - Standard VS2019 solution in C#. Pretty straightforward.

**Additional info:**
  PTHY accesses the following directories without user input:
   - %appdata%\.minecraft\pthy

The *exit* command should be used to quit the software, as it ensures file cleanup.
   
PTHY is the first, kinda user friendly software to create particle holograms easily.
Currently, there is support for video and image export - both are being updated and made better constantly.

PTHY uses Emgu.CV with the open source license. 

(u/timetobecomeegg)
