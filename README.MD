# MacOSX Transparent Icns

## Why

On Mac OSX there is a dock which has all the icons of the application that are open or have been pinned to the toolbar.

Navigating via the dock is much slower than using the Finder (Cmd + Space). Also because the dock has colorful icons for other applications, often times there is an impulse to click another application when that wasn't the original intent of being on the computer.

This repo has a transparent icon which you can turn the cluttered docker from this:
![Image of Cluttered Dock](https://tech-addiction.com/images/dock_with_one_empty.png)

To this:
![Image of Transparent Dock](https://tech-addiction.com/images/dock_all_empty.png)

## Usage

[Download the transparent.icns](https://github.com/tech-addiction/MacOSX-Transparent-Icns/archive/main.zip)

When an application is opened it will be in the dock.

Right Click the application -> Options -> Show in Finder

Then Right Click the highlighted application in the finder window and click Get Info

Then drag the transparent.icns over the application icon:
![Drag Transparent Icns](https://tech-addiction.com/images/replace_icon.png)

## Caveats

After Mac OSX 10.6 the icons for standard Mac OSX applications are read only and cannot be changed unless you turn off System Integrity Protection. I do not recommend doing that tho.
