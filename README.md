# CaesarShift
A Console program to Encrypt/Decrypt using the Caesar shift algorithm
#####-Created by Alwyn Owen
CaesarShift by Alwyn Owen is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

##How to install program
Just download the zip file and then extract the contents to a folder on your computer. The application is now installed, to use it just run the exe file.

##User guide
The user interface of this Caesar shift application is designed to be easy to use and end user friendly. But that is never a guarentee of anything, so here is the user guide :)
Much of this guide can also be found inside the help section of the program.

###General use
This program uses a menu based system within the console. The program will present you with a couple options with numbers to the side of them. In order to select an option type the corresponding number and press enter. This program also has commands which can be used to do certain functions at any point in the program.

###Main Menu Options
####Encrypt
This allows you to take readable plain text and convert it into encrypted text. This will allow you to make your messages unreadable to anyone who doesn't know how to decrypt them. Note that the Caeser shift method used by this software is not very secure due to the method being widely known and there only being 26 possible keys which makes it very fast to brute force. Use at your own risk!
####Decrypt
Providing that you know the key this allows you to convert Caeser shifted nonsense into something readable (provided the source text was readable!).
####Brute Force Decrypt
This will do all 26 possible decryption keys at once to provide you with all 26 possible results, you can then scroll through the results to find whichever one makes the most sense. Note that saving the result to a text file (\\s) and opening it externally might make your life easier.
####Frequency Analysis
This takes the brute force one step further. The software will look at the frequency of each letter within the text to guess what the correct decryption key is. This only works with English documents, It also works best with longer documents.
####Load
The load function of this program will allow you to load a text file for use. You can either enter the file path or drag the file onto the console window to load a file. Note that you can also drag a file onto this programs executable to load a file while launching the program at the same time.

###Commands
This program makes use of a command system, this makes the program more flexible. These commands can be used at any point within the program. All commands have a "\" in front of them, this is to tell the program that you are using a command.
####"\h"
Brings up the help menu, "\?" and "\help" also work.
####"\x"
A very quick way to close the application at any point.
####"\s"
This will save the output of the program to a file in the output folder.
####"\w"
This will save the output to a snazzy web page that you may find easier to view. Note that if you wish to share the web page you will also need to bundle the "mainstyle.css" file with it if you wish for it to remain pretty. You can also modify the "mainstyle.css" to format the webpage output however you would like it.
####"\f"
This command is used whenever you wish to use a file that you have loaded as your input.
####"\e"
If you encouter an error this command can be used to get a full description of the error. Note that using this command will overwrite the programs output to become the error message, this is useful for writing the error message to a file easily.
