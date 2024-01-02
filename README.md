# Voice-assistant

The name of this voice assistant is "Wake" and the wake word/phrase is "hey wake".
For this to work one has to have voices installed onto the device. Normally, voices are already installed onto a windows device when installing the language packages for the display and keyboard language.

However, the voices used for this voice assistant are Hedda(German) and Hazel(British English) which can be downloaded from the following link:
https://www.microsoft.com/en-us/download/details.aspx?id=27224

Also for these new voices to work one also has to install the Microsoft Speech Platform from the following link:<br>
https://www.microsoft.com/en-us/download/details.aspx?id=27225

The installed voices have an index which are required for the voice assistant to work. <br>
The "Voices" section contains a code which prints the voices on ones devices in index order which means the first one that is printed has the index 0, the second one 1 and so on.

Then the lines 39 and 42 in the "Voice Assistant" code have to be adapted to the corresponding indexes of ones device.
