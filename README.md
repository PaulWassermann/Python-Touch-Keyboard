# Python-Touch-Keyboard

This keyboard was developped with the Python GUI library Tkinter and the assets were created with paint3D, and can be integrated in Tkinter application running on touch sensitive devices (it also responds to mouse inputs but that is not its primary purpose).

### Installation

Download the folder, and put the assets folder and the python file in the same directory for the keyboard to work. If you don't, be sure to change the self.path_to_assets attribute.

### Integration 

You can create an instance of the TouchKeyboard class, passing it the instance of your GUI (to access the size of the application). You then can bind all your entry/text widgets with the display and hide methods of the keyboard depending on if they get or lose focus. 

The Keyboard is compatible with both Entry and Text widgets. 

The size of the keyboard is defined according to the size of the application. However, you may want to adapt it to the format of your application, so that the keys aren't deformed.

### How to use

The keyboard works pretty much like an Android device touchkeyboard:
- holding a letter for 800 milliseconds will make variations of that letter appear (extended Latin characters)
- holding the shift button for 800 milliseconds will shiftlock. To unlock it, just press the button.
