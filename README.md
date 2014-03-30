# Twitch Plays Hardware #

**v0.0** Built at Hack Into The BemyApp Factory


### Built for Windows, written in Python 3 ###

My goal with this project is to take the open source clone of the program Twitch channel "Twitch Plays Pokemon" uses, and abstract it such a way we can control hardware.  Basically control hardware via IRC on a Twitch Channel.

For the hackathon we created a method to control a Nintendo3Ds via Arduino.

### Pre requisists: ###

- **Python 3.3.4** [64 bit](http://www.python.org/ftp/python/3.3.4/python-3.3.4.amd64.msi "64 bit") / [32 bit](http://www.python.org/ftp/python/3.3.4/python-3.3.4.msi "32 bit")
- **PyWin32** [64 bit](http://sourceforge.net/projects/pywin32/files/pywin32/Build%20218/pywin32-218.win-amd64-py3.3.exe/download "64 bit") / [32 bit](http://sourceforge.net/projects/pywin32/files/pywin32/Build%20218/pywin32-218.win32-py3.3.exe/download "32 bit")
- *If you have any dll related issues make sure you're using the right version!*
- [**VisualBoyAdvance**](http://coolrom.com/emulators/gba/14/Visual_Boy_Advance.php "VBA")  Set gbc files to open with this by default
- [**Download**](https://github.com/sunshinekitty5/TwitchPlaysPokemon/archive/master/twitchplayspokemon.zip "Twitch Plays Pokemon") and extract the bot

Keybindings for Visual Boy Advance (turn numb-lock on):
 
	A:			z
	B:			x
	Start: 		enter
	Select:		backspace
	Up: 		Numpad 8
	Right: 		Numpad 6
	Down: 		Numpad 2
	Left: 		Numpad 4

### How to use ###

- Put your .gbc (game file) into the game folder
- Remove the text document from the game folder
- Double click on Launch.py
- The bot will walk you through first-time configuration

Still having trouble? Check out the [How-To Video](http://youtu.be/LvBU9SJ8sfE)

### My Channel ###

- My channel will be available [**here**](http://www.twitch.tv/twitchplaysgameboyadvance "Twitch Plays Gameboy Advance")
- On my channel I have the following internet speeds on a dedicated server (*tested while streaming*):
![Server Speeds](http://i.imgur.com/VSKyN7f.png)
- I truly believe it will have the least amount of delay possible, you can use it as a benchmark
