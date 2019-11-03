# SteamworksPy
Howdy!  This project originally started as a fork of Easimer's SteamworksForPython in an attempt to bring a fully-functional Python module for Steam out for the public.  Since then it has grown beyond that and added a lot of functionality.

Feel free to fork or contribute to this module.

Pre-builds for Windows and Linux here: https://github.com/Gramps/SteamworksPy/releases

Full documentation is now available here: https://gramps.github.io/SteamworksPy/

For a fuller (yet outdated) tutorial, with images, on SteamworksPy please read our post: http://coaguco.tumblr.com/post/128240756897/steamworks-for-python-tutorial-linux.

There is now an experimental branch for converting the project to match my [Godot Engine module](https://github.com/Gramps/GodotSteam) in functionality and fix some problems with the original.  Once completed, it will move to the master branch.

# Latest Updates
- Added: missing Utils functions
- Removed: docs folder as docs are now their own branch

# Some Notes
While I am still tinkering away with this, here are some things to note:

- You will need the Steamworks SDK
- You will most likely need a Steamworks account, with a valid AppID, to use more advanced functions (set achievements, set stats, etc.)
- You will need to be logged into Steam for anything to function, obviously.  As it assumes the game is run from Steam itself and is online.
- Steam Overlay will only work if your game is using OpenGL or D3D!  Overlay will only work if the game is actually launched from Steam itself.  Possible if the SteamRestart command is fired; however, this is not implemented yet in SteamworksPy.

# To Do
- Add in more features from the Steamworks SDK

From here you should be able to call various functions of the steamworks.py.  A (mostly complete) list of available functions is listed below; take a closer look at the steamworks.py for a better understanding.  In addition, you should be able to read the Steamworks API documentation to see what all is available and cross-reference with the steamworks.py!

# Further Usage
I recommend trying the included tests to get an idea of how it works. Opening the test files will give you some insight on how to use it in your game, as well as looking through the Steamworks.py file itself.  Also, don't hesitate to contact me for help or with questions. Or comment / open issue on GitHub.

# More To Come
I am still digging through the code and trying to get more functions working.  Some things like controller might not be necessary as Python can usually handle these; though they may have more to do with the new Steam Controller.
