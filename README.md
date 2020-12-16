# A Darker Arduino

This is a darker theme with pure black background for both the console output and the editor.  
There seems to be a bug with binary number formatting like 0b00011010 where the number and background
change color but I haven't figured out how to fix it.   

I decided to modify the original OneDarkArduino because I like darker themes for my coding work.  And
figuring there may be someone else in the Void who likes darker themes decided to make my changes public.

For this theme, all I did was play with the colors (in theme.txt) so that they met my personal preferences.
All credit for figuring this stuff out goes to [Jeff Thompson](https://github.com/jeffThompson/DarkArduinoTheme) and [Konrad91](https://github.com/konrad91/OneDarkArduino).

![screenshot](https://github.com/andrew-sz/A_Darker_Arduino_Theme/blob/main/screen_shot_super_dark.jpeg)

There is also now an [Arduino plugin for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino) that seems interesting to me but I have not yet tried to use it for any projects.  

For the moment, this theme is what works for me when I need to code with the Arduino IDE.  

**One more thought/note!** Another reason I made this repo public is that when the Arduino application is
updated on Mac OS X the theme will be replaced since the theme folder is part of the application contents.  
So it makes it easy to find and replace the theme after Arduino application updates.

The below is from the OneDarkArduino repo and still applies to this one including the license. 

Modern dark theme for the Arduino IDE, inspired by One Dark Pro for VSCode by binaryify: https://binaryify.github.io/OneDark-Pro/#/. Based on work done by Jeff Thompson: https://create.arduino.cc/projecthub/rahulkhanna/dark-theme-for-arduino-ide-17c001?ref=search&ref_id=theme&offset=0 



The following is credited to https://github.com/jeffThompson/DarkArduinoTheme 

### INSTALLATION  

* Mac users should look in `~/Applications/Arduino.app/Contents/Java/lib` and replace the `theme` folder inside (making a copy of the original in case want to revert back).  
* Windows is located in `C:\Program Files (x86)\Arduino\lib`.  
* Linux will be in `/usr/share/arduino/lib/`  

### CREATING YOUR OWN MODS
The newest version of the Arduino IDE makes creating custom themes trickier: you now need to edit the `theme.txt` file, an XML file inside the `syntax` folder, and the button files. Unfortunately, not all items in the `theme.txt` file actually work, so if you can't get an item to change, try another one of the files.

\- \- \-

Released under [Creative Commons BY-NC-SA license](http://creativecommons.org/licenses/by-nc-sa/3.0/) - feel free to use but [please let me know](http://www.jeffreythompson.org).
