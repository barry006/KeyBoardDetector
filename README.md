This C# script utilizes Windows native functions via DllImport to detect and display the current keyboard layout within a Unity environment. 

It employs GetKeyboardLayout and GetKeyboardLayoutName from user32.dll to retrieve the layout identifier (layoutId) and map it to descriptive names such as "QWERTY" or "AZERTY" using a predefined dictionary. 

The OnGUI method updates Unity's graphical user interface to visually present the current keyboard layout and its identifier.



