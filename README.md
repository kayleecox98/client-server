# client-server
basic command line TCP/IP client and server

Installing gcc compiler:
* checking the version: gcc --version
* extra details about the version: gcc -v
* Find what gcc package was install: rpm -qa | grep gcc

Compiling and Running a C++ program:
* Open a new terminal window or cmd if you are on windows.
* Change the directory to the directory in which you have your source.cpp file.
* Now enter the following command to compile the source file using g++: g++ -o name-you-want-to-give source.cpp
* ./name-of-program

Using the server program:
* Compile and run it with the C++ compiler of your choice.
* Once the script is running, open a console and type: telnet localhost 54000
* This will create a connection from the client (your console) to the server script. 
* Type a message and submit with enter to see it get sent to the server and back!
