# MDX LabPanel
Scilab-Programmed GUI Control Panel for Roland MODELA MDX-15/20 CNC Machine For Windows

## [Go to Homepage](https://craftweeks.github.io/modela_mdx-15_20_control_panel_scilab/)

## Usage
A custom control panel developed for Roland MODELA MDX-15/20 desktop CNC milling machine.
- GUI buttons and indicators for manipulating the tool position of this 3-axis CNC milling machine
- Enables to input the ZO value (custom zero position for z-axis) accurately
  * Instead of leveling the tool with your eyes and UP and DOWN buttons on the machine
  * Useful for resuming interrupted machining processes with exact the same ZO setting, no matter the machine has been powered off or reset accidentally 
- Quick access of *Printer Queue* and *Start/Stop Printer Spooler*
 
#Screenshot

<a href='https://kl7.info/img-59328e6e79dd9.html'><img src='https://kl7.info/thumb/59328e6e79dd9.png' alt='image'><br />v0.4</a>

## Prerequisite
* Scilab 5.5 or above (recommended, also compatible with Scilab 6.0 for v0.4 or later)
> **What is Scilab ?** 
> Scilab is free and open source software for numerical computation providing a powerful computing environment for engineering and scientific applications. Official Site of Scilab (http://www.scilab.org/)
* MDX-15/20 is connected with port **COM1 (also COM2 or COM3 for v0.3 or later)**

## How To Install
1. If you do not install Scilab, please install it on the computer
2. Download the Zip file of our repository, and then extract the files

## How To Use
1. Launch Scilab
2. Choose **File** > **Execute**, and then select **__main__.sce** (v0.4 or later) in the file selection dialog
	- Execute **ControlPanel.sce** for v0.3
3. Press **Reset** to zero out z-axis
4. Press **Home** to zero out x- and y-axes

## YouTube:
Please visit and subscribe our YouTube channel [**[DTClub.swc.HK](https://www.youtube.com/channel/UCGlT2itihZuRxMckNcfcA3A)**]

* Introduction for v0.1. - 
[Open Source GUI Control Panel for Roland MODELA MDX-15/20 CNC Machine (Scilab-Programmed GUI)](https://youtu.be/1qtFWHFQnls)

* New feature highlight for v0.3 - 
[Introduce New Features in our DIY Control Panel V0.3 for Roland MODELA MDX-15/20 CNC Machine](https://youtu.be/dMVLkgNrw48)

## Version History

v0.4 2017-6-4
- Enabled the setting for MDX-15
- Added Spindle on/off
- Added Feed rate control
- Added graphical display for indicating tool position
- Integrated Reset to the first Home operation
- Optimized the code for X0, XMAX, Y0, YMAX homing
- Fixed the wrong direction of the Y0 and YMAX homing buttons
- Fixed the filepath issue
- Fixed the compatibility with Scilab 6.0.0 or later

<a href='https://kl7.info/img-59328e6e79dd9.html'>v0.4<img src='https://kl7.info/thumb/59328e6e79dd9.png' alt='image'  width="250"></a>

v0.3 2017-4-8
- Enable to choose the COM port for the machine
- One click to open *Print Queue* by pressing **Printer**
- Start/Stop *Windows Printer Spooler* service by pressing **Start/Stop Spool**
- Added **Help** button that link to our webpage
- Changed background color and button style

<a href='https://kl7.info/img-58e88857deb42.html'>v0.3<img src='https://kl7.info/thumb/58e88857deb42.png' alt='image' width="250"></a>

v0.2 2017-1-6
- Enable to move to a target position at once, by toggling **Direct Go**
- Added buttons for homing +X, -X, +Y and -Y position

<a href='https://kl7.info/img-58f0e64bdbbe5.html'>v0.2<img src='https://101img.com/upload/small/2017/04/14/58f0e64bdbb42.png' alt='image' width="250"/></a>

v0.1 2016-12-23 (The version shown in the introduction video in YouTube)
- Move instantly after press a direction button
- Set custom Z0 level

## Give me a little help
- [Donate via PayPal.Me](https://www.paypal.me/chrisfungky/50)

## Copyright and License

![Logo of Craftweeks - DTClub.swc.HK](https://yt3.ggpht.com/-pWuRX2_jcLk/AAAAAAAAAAI/AAAAAAAAAAA/K3QMmnUWSf8/s100-c-k-no-mo-rj-c0xffffff/photo.jpg) 

**Copyright 2016 - 2017, Chris KY FUNG and the contributors in [DTClub.swc.HK CNC group](https://www.facebook.com/dtclubswchk/)**

**License** GNU AFFERO GENERAL PUBLIC LICENSE Version 3 (GNU AGPLv3)
