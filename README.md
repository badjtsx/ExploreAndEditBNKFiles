# Exploring

[Ravioli game tools](#https://www.scampers.org/steve/sms/other.htm#ravioli_download) allows you to view and extract the contents of archives.

# Editing

To edit a .BNK file you have to replace the .WEM file inside of it. There is no way to tell which WEM file is which, you just have to listen to all of them and figure out which to replace (The files aren't always WEM files).\
To replace an audio file within the BNK file with another check out [this](#https://github.com/marieismywaifu/BNKEditor)tool.

# Converting to a .WEM file

To convert and audio file to a WEM file, you have to use [Audio Kinetic Wwise Launcher](#https://www.audiokinetic.com/download/). You'll have to download the wwise app inside the launcher (You only need the Authoring package so don't download the other packages of you don't want them).\

### How to use Wwise

1. Open wwise and make a new project (Default settings are fine, just give it a name).
2. Press Shift+i or go to ```Project > import audio file...``` and add the files you wan to convert (Only .amb, .mid and .wav are supported).
   > You can convert from mp3, ogg etc. to wav on any website
4. Go to ```Project > Convert All Audio Files...``` (any platform will do).
5. The converted audios will be saved in the wwise project cache directory. If you don't know how to get there, Press Shift+F1 or go ```Project > File Manager``` and where it says ```Project Folder```, right-click on the path and choose "Open containing folder". Now in file explorer, your wem files should be in the .cache directory under whichever platform you chose.
