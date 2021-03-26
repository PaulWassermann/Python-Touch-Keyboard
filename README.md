# Python-Touch-Keyboard

This keyboard was developped with the Python GUI library Tkinter and the assets were created with paint3D, and can be integrated in Tkinter application running on touch sensitive devices (it also responds to mouse inputs but that is not its primary purpose).

### Installation

Download the folder, and put the assets folder and the python file in the same directory for the keyboard to work.

### Integration 

You can create an instance of the TouchKeyboard class and bind all your entries with the display and hide methods of the keyboard depending on if they get or lose the focus.
The Keyboard is compatible with both Entry and Text widgets. The size of the keyboard is defined according to the size of the application. However, you may want to adapt it to the format of your application so that the keys aren't deformed.
