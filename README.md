# MouseVolume
An AutoHotkey script for controlling Windows OSD display controls using only the mouse buttons on a mouse with two side buttons.  

Has volume control, play/pause, and skip forward/back.  
Also allows for volume adjustment using the scroll wheel.  

This script functionally allows a wireless mouse to be used like a remote control when listening to music or watching movies. It can also be used to control music tracks without having to navigate the mouse while working.

Warning: this script may or may not break side button keybinds in other programs!

## Installation

Install [AutoHotkey](https://www.autohotkey.com/).  

Save Volume.ahk to a file and run the script. You may place a shortcut to the script in your startup folder if you want the script to begin running at startup.

## Usage

| Key                               | Function      |
|-----------------------------------|---------------|
| Forward Side Button               | Volume Up     |
| Back Side Button                  | Volume Down   |
| Either Side Button + Left Click   | Skip Backward |
| Either Side Button + Right Click  | Skip Forward  |
| Either Side Button + Scroll Press | Play/Pause    |
| Either Side Button + Scroll Up    | Volume Up     |
| Either Side Button + Scroll Down  | Volume Down   |

Holding either of the side buttons down allows the scroll wheel to be used like a volume rotary encoder.  
Side buttons will not increment volume by more than one step per press, even when held down.  

Warning: this script may or may not break side button keybinds in other programs!
