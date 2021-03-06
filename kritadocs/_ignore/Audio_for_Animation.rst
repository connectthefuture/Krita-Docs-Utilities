You can add audio files to your animation to help sync lips or music.
This functionality is available in the timeline docker.

Importing Audio Files
~~~~~~~~~~~~~~~~~~~~~

Krita supports MP3, OGM, and WAV audio files. When you open up your
timeline docker, there will be a speaker button in the top left area.

[timeline with speaker button highlighted (image)]

If you press the speaker button, you will get the available audio
options for the animation.

-  Open
-  Mute
-  Remove audio
-  Volume slider

Krita saves the location of your audio file. If you move the audio file
or rename it, Krita will not be able to find it. Krita will tell you the
file was moved or deleted the next time you try to open the Krita file
up.

Using Audio
~~~~~~~~~~~

After you import the audio, you can scrub through the timeline and it
will play the audio chunk at the time spot. When you press the Play
button, the entire the audio file will playback as it will in the final
version. There is no visual display of the audio file on the screen, so
you will need to use your ears and the scrubbing functionality to
position frames.

Exporting with Audio
~~~~~~~~~~~~~~~~~~~~

To get the audio file included when you are exporting, you need to
include it in the Render Animation options. In the File > Render
Animation options there is a checkbox“Include Audio”. Make sure that is
checked before you export and you should be good to go.

Packages needed for Audio on Linux
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The following packages are necessary for havng the audio support on
Linux:

For people who build Krita on Linux:

-  libasound2-dev
-  libgstreamer1.0-dev gstreamer1.0-pulseaudio
-  libgstreamer-plugins-base1.0-dev
-  libgstreamer-plugins-good1.0-dev
-  libgstreamer-plugins-bad1.0-dev

For people who use Krita on Linux:

-  libqt5multimedia5-plugins
-  libgstreamer-plugins-base1.0
-  libgstreamer-plugins-good1.0
-  libgstreamer-plugins-bad1.0

Category:Unstable_Features
