---
layout: page
permalink: /arduino/arduino-ide-themes
---

# Arduino IDE Themes

## How to change your Arduino IDE theme

Changing your theme is very easy.

1. First, open the Arduino IDE preferences:

On Windows or Linux go to:

``File > Preferences``

On Mac go to:

``Arduino > Preferences``

2. In the window that appears, next to "Theme" is a dropdown menu showing the list of available themes. Choose the one you want and save your preferences.

3. Close and reopen the IDE.

## Installing New Themes

By default there are just two themes, but maybe you want something different. Arduino IDE supports [Microsoft VS Code themes](https://marketplace.visualstudio.com/search?target=VSCode&category=Themes) and there are [various sites that offer quick previews of available themes](https://vscodethemes.com/).

1. When you find one that you like, in the right-hand sidebar under "Resources" choose "Download Extension". This will download a **.vsix** theme extension file.

2. Make sure your Arduino IDE is closed and navigate to the folder on your computer where the Arduino IDE stores its preferences. This is a different folder than where the IDE itself is installed.

On Windows:

``C:\Users\<username>\.arduinoIDE\``

On Linux and Mac:

``~/.arduinoIDE/``

By default this folder may be hidden on your system. If that is the case, you will need to follow the appropriate steps to make it visible: [Windows](https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5) / [Linux](https://www.geeksforgeeks.org/how-to-view-and-create-hidden-files-in-linux/) / [Mac](https://www.macworld.com/article/671158/how-to-show-hidden-files-on-a-mac.html).

3. Once you have located the folder, inside it create a new subfolder named "plugins". Inside this plugins folder is where you can place your .vsix files to have them recognized by Arduino IDE. 

4. Copy your downloaded **.vsix** theme file here, then open the Arduino IDE.

5. Now when you open the Arduino IDE preferences your newly downloaded theme will appear as an option in the dropdown.
