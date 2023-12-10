# MusicApp-C-plusplus
A Music App Using C++ (Singly Linked list) can be played on your CLI.

 # **build using()** 

 * **C++ : **Ensure you have a C++ compiler installed (TDM GCC 4.9.2 64-bit)
 * ** SFML Lib : ** Must install 2.4.2

 * 1) Download SFML LIB
```bash
https://www.sfml-dev.org/download/sfml/2.4.2/
```

2) Clone this project or Download the zip and extract it.

```bash
otw
```

** 3) Add the required parameters **

for Linkers : `-lsfml-audio
              -lsfml-graphics
              -lsfml-window
              -lsfml-system`
              
```Only  -lsfml-audio is required but add all of them just in case ```

for C++ Compiler :` -std=gnu++0x
                   -std=c++11
                   -std=gnu++11`
                   
```You can use -std=c++0x (latest) instead of -std=gnu++0x whatever is good for you.```

** 4) Convert the songs you want to play **

** Must convert .mp3 => .ogg (Just type  `mp3 to ogg ` on google)**

** 5) Add the songs to /songs dir and run the program **

* Add your music (.ogg) files in /songs dir.
* Compile the program and run
* log.txt will be created. and the logs will be imported with respect to your song activity.
* timestapms will be shows in log.txt and cli as well.










