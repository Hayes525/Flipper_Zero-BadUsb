<img src="https://github.com/UNC0V3R3D/ressources/blob/main/badusbpic.png" height="380" width="1050" >

# Badusb Collection for the FlipperZero
![GitHub all releases](https://img.shields.io/github/downloads/UNC0V3R3D/Flipper_Zero-BadUsb/total?logo=GitHub) ![GitHub commit activity](https://img.shields.io/github/commit-activity/w/UNC0V3R3D/Flipper_Zero-BadUsb) ![GitHub repo size](https://img.shields.io/github/repo-size/UNC0V3R3D/Flipper_Zero-BadUsb) ![GitHub release (release name instead of tag name)](https://img.shields.io/github/v/release/UNC0V3R3D/Flipper_Zero-BadUsb?include_prereleases)

# Before you start!

Before you start ``you have to agree`` with the "Usage Agreement" down below. This project ``is just for learning purposes``. Always ask for ``permission`` before running one of the scripts provided by me. I ``won't`` be responsible for any damage that you may cause.
![](header.png)
## Installation

Windows:

```sh
1. Download the latest Release.
2. Extract the files.
3. Use the qFlipper app to drag the files into the "BadUsb" folder on your Flipper.
```

## Usage example

First, you can try out a few scripts on your own PC.
Most scripts are relatively harmless, but you should first read the description in the respective file.
Some scripts can also cause damage. Therefore, I am **NOT** responsible for any damage you cause.

## Release History

* v1.0
    * Released all the files
* v1.1
    * CHANGE: More options on storing the grabbed Wifi Passwords (WifiPassStealer.txt)
    * Added ``MEMZ.exe script``
* v1.2
    * Added ``NoMoreSound.txt`` Script
* v1.3
    * A few delay_time errors ``fixed``
* v1.4
    * Added a lot of new files to repo
* v1.5
    * Added ``DeleteMicrosoftStore.txt`` and fixed link to MEMZ.exe
* v1.6
    * Added a bunch of new files
* v1.7 (BIG UPDATE)
    * Added ``a lot`` of new files, fixed a few files
* v1.7.1 
    * Few fixes due to delay errors
* v1.8 
    * Added ``ChangeWinUsername.txt`` and ``setWinPass.txt``
* v1.9 
    * Added a bunch of new files
* v2.0 
    * Added ``DownLoadASCII`` and seperated ``Selfwriting`` Ascii
    * Instant-download Ascii is about ``20x faster``
      
## Usage Agreement

By using/downloading the scripts provided by UNC0V3R3D,
you automatically agree to the following usage agreement. If you do not
agree to all the terms of this agreement, you aren't allowed to use/download the scripts.
1. If you download and use the scripts provided by UNC0V3R3D, you agree that, UNC0V3R3D isn't responsible for your actions or any damage you cause.
2. You are allowed to share all of the files.
3. Copying the files without giving credits will lead to bad luck.


# Instructions for newbies
In this quick instruction you are going to learn how to setup the scripts and use them properly.
If you have any questions after reading this instruction, just DM me on Discord (UNC0V3R3D#8662).

## Installation

``` sh
1. Download the files directly from the repo or download the latest release.
2. Extract the files anywhere you like
3. Now you need to somehow get the files on your Flipper
4. If you are using a phone, just install the Flipper Zero mobile app.
5. If you are using a PC, just install the qFlipper app: https://flipperzero.one/update
6. Connect your Flipper via Bluetooth if you are using a phone, or connect it via usb if you are on PC.
7. Open qFlipper --> SD Card --> badusb --> Move the files here.
8. Now you are done with moving the files to your Flipper.
 ```

## Explanation of the files

So now that you've moved the files to your Flipper, you first want to understand them before actually using them.
If you're using the files from my BadUsb repository, 60% of the files are kind of harmless.
But some files can actually be dangerous and cause serious damage, so be aware of that.

<h3> Understanding DuckyScript </h3>

* All BadUsb-Scripts are written in the ``DuckyScript`` language.
* The language is kind of ``easy`` to understand and to learn.
* If you really want to look further into this please refer to this [Documentation].
* The kind of ``hard part`` are the PowerShell scripts.
* We use PowerShell or PowerShell scripts in ``97%`` of all DuckyScripts.
* PowerShell or PowerShell scripts give us ``full power`` over the machine.
* If you want to learn how to write PowerShell scripts after learning the DuckyScript basics please refer to this [PowerShell-Guide].
* In BadUsb scripts, you will most likely find comments every few lines, that start with the command ``REM`` at the beginning.
* Those comments often ``explain the whole process`` and help you a lot.
* That's how you understand certain BadUsb scripts, but you can also often already identify the script by its file name.

<h3> Using the scripts properly </h3>

* So now that we have prepared everything, we can start to test our first script!
* We are going to run the first script on our ``own`` PC.
* Of course, you don't want to cause damage to your PC, so we are going to choose a harmless script.
* Let's choose a script that will draw something in the Notepad.
* I chose a [script] from my ASCII repository.
* If you want to open the text file on your phone or pc to see what is inside feel free to do so.
* To start you are going to start the Flipper and find the ``Bad USB`` category.
* There you will see all the scripts you have imported from your PC or phone.
* Now choose a harmless script and wait until the Flipper tells you to connect to a PC via the USB cable.
* Just press the middle button to start the script.
* Now the script should open Notepad and write a simple sentence "Hacked by UNC0V3R3D".
* If you succeeded congrats! You have just run your very first script.
* If something went wrong then please scroll further down to see the ``Troubleshooting section`` and follow the steps.

<h3> Troubleshooting Problems </h3>

First of all, you have to identify the problem. Then you can look at the list below and maybe you will recognize your problem.

* ``1.0`` <b> The script open random things and typed the text somewhere, where it shouldn't be. </b>
  * <em> So this is often caused by ``too short delays`` between the commands. In the BadUsb script file, you should see some commands, that start with ``DELAY``
       and then there is a number behind it. ``Example: DELAY 500``. The number stands for ``milliseconds``. Changing the delay to a ``higher number`` than the current number should solve the problem ``(DELAY 500 --> DELAY 700)`` </em>
       
* ``1.1`` <b> The Flipper shows an error like this: ``ERROR: line 5`` </b>
  * <em> If the Flipper prints random errors like this you should check the ``text file``. The most common thing causing this error is apparently a ``random blank line``
  between the commands. Otherwise, make sure there is no line containing the ``"LOCALE .."`` command. It doesn't properly work on the Flipper, yeah I do not know why that is. If there is still an error, look at the line where the error is coming from and make sure there is no ``space`` at the beginning of the line. </em>

* I hope that you find a a solution for your problem. If you need help feel free to always contact me via Discord or Email.

## Meta

If you have any idea on how to make this Instruction to BadUsb scripts better feel free to open an Issue or contact me via Discord. :)

[PowerShell-Guide]: https://www.youtube.com/watch?v=IABNJEl2ZWk
[Documentation]: https://hakshop.zendesk.com/hc/en-us/articles/360010555153-Ducky-Script-the-USB-Rubber-Ducky-language
[script]: https://github.com/UNC0V3R3D/Flipper_Zero-BadUsb/blob/main/BadUsb-Collection/ASCII/Selfwriting/SimpleTroll.txt
[qFlipper]: https://flipperzero.one/update

## Meta

UNC0V3R3D – [@GitHub](https://github.com/UNC0V3R3D) – unc0v3r3d@proton.me

Distributed under the MIT license. See ``LICENSE.md`` for more information. 

[https://github.com/UNC0V3R3D/Flipper_Zero-BadUsb](https://github.com/UNC0V3R3D/)


## Credits

* [UberGuidoZ] and [FalsePhilosopher] 


[release]: https://github.com/UNC0V3R3D/Flipper_Zero-BadUsb/releases
[UberGuidoZ]: https://github.com/UberGuidoZ
[FalsePhilosopher]: https://github.com/FalsePhilosopher
