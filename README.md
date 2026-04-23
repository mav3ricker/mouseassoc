MouseAssoc — Advanced Mouse Button to Keyboard Mapping System
Overview

MouseAssoc is a lightweight, highly configurable input automation system designed to map extra mouse buttons to keyboard keys, characters, and dynamic behaviors. It provides a flexible architecture that allows full customization of input behavior through simple configuration files and runtime controls.

The system is designed to work with virtually any mouse, regardless of manufacturer or number of buttons, by using a universal intermediate mapping layer.

Core Features
Universal support for extra mouse buttons via numeric keypad mapping
Dynamic remapping of inputs during runtime
Mode-based behavior system (Turbo, Hold, Multi)
Configurable input profiles using simple text files
Optional GUI generator for interactive configuration
Lightweight batch/script-based architecture
Audio feedback for configuration confirmation
Portable and hardware-independent design
Requirements
A mouse capable of assigning extra buttons to keyboard keys (typically numpad keys via vendor software or driver utility)
Installation
Assign extra mouse buttons to numeric keypad keys using your mouse configuration software.
Edit the input_*.txt files to match the assigned numpad mappings (e.g., n1 for Numpad 1).
Create desktop shortcuts for the provided batch files (change_*.bat) and assign hotkeys in the format:
Ctrl + Alt + [mouse button mapping]
Set shortcuts to start minimized.
(Optional) Use gui/mouseassoc.htm to generate a custom graphical interface for managing mappings interactively.
Custom button identifiers such as:
mouseassoc-upbtn-rearcenter
mouseassoc-sidebtn-frontup
can be used during configuration.
Registry import is required for GUI functionality. A static GUI version can also be exported.
Usage
Launch _RUN.bat or individual press_*.lnk files.
Use Ctrl + Alt + [mapped button] to assign keyboard keys or special characters to mouse buttons in real time.
Single beep: waiting for key input
Double beep: assignment confirmed
System is ready for use in applications or games.
Input Modes

MouseAssoc includes dynamic behavior modes:

Turbo Mode: Repeated rapid input execution
Hold Mode: Continuous key state simulation
Multi Mode: Combined input/output triggering system

Modes can be switched during runtime for adaptive control behavior.

Hotkeys (System Control)<br>
Ctrl + Alt + Shift + T — Toggle Turbo Mode<br>
Ctrl + Alt + Shift + H — Toggle Hold Mode<br>
Ctrl + Alt + Shift + M — Toggle Multi Mode<br>
Ctrl + Alt + Shift + I — Stop MouseAssoc<br>
Ctrl + Alt + Shift + U — Restart MouseAssoc<br>
Ctrl + Alt + Shift + Y — Open Profile Creator<br>
Ctrl + Alt + Shift + N — Open Installation Directory<br>
Ctrl + Alt + Shift + 9 — Start Service Mode<br>
Ctrl + Alt + Shift + 0 — Stop Service Mode<br>
Ctrl + Alt + Shift + 7 — Open Service Configuration<br>
Ctrl + Alt + Shift + J — Check Button Registry<br>
Ctrl + Alt + Shift + O — Open Default GUI<br>
Ctrl + Alt + Shift + L — Open GUI Generator<br>
Ctrl + Alt + Shift + K — Open Hotkey Reference<br>
<br>
Design Philosophy

MouseAssoc is built as an open and modular input mapping framework. Instead of relying on fixed hardware-specific drivers, it abstracts mouse input into a universal configuration layer, allowing complete customization through lightweight external files and scripts.

It is particularly useful for users who require advanced input control, rapid reconfiguration, or extended functionality beyond standard mouse software limitations.

Optional Components
pressbtnturbo.exe: Enables automated repeated key triggering without sustained input hold behavior.
GUI Module (mouseassoc.htm): Provides visual configuration and profile management.
Registry Integration: Enables persistent GUI and advanced mapping storage.
Compatibility Notes
Designed to be compatible with a wide range of mouse hardware
Works alongside games and applications requiring customizable input
Requires initial manual mapping setup via numpad assignment
Summary

MouseAssoc provides a flexible, script-driven input automation framework that extends standard mouse functionality into a fully customizable control system. It is designed for users who require precision input mapping, runtime reconfiguration, and multi-mode input behavior in a lightweight and portable form.

<br>

[Win10 Lastest Release](https://github.com/mav3ricker/mouseassoc/releases/tag/Setup)
