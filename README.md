
![81kDixD6qNL _AC_UF1000,1000_QL80_](https://github.com/barry006/KeyBoardDetector/assets/120657043/9fa0e32c-cdf0-4f91-b853-fb8815ac835b)


This C# script utilizes Windows native functions via DllImport to detect and display the current keyboard layout within a Unity environment. 

It employs GetKeyboardLayout and GetKeyboardLayoutName from user32.dll to retrieve the layout identifier (layoutId) and map it to descriptive names such as "QWERTY" or "AZERTY" using a predefined dictionary. 

The OnGUI method updates Unity's graphical user interface to visually present the current keyboard layout and its identifier.


Window keyboard identifier :
https://learn.microsoft.com/en-us/windows-hardware/manufacture/desktop/default-input-locales-for-windows-language-packs?view=windows-11


An untested Macintosh and Linux version is also available.
