if you use arch by the way you can download this package from AUR ( yay -S helloworld )

compilation from source code:

step 1:
you need installed gcc and git package ( Gnu Complier Collection )

$ sudo apt install gcc git - debian-based

$ sudo pacman -S gcc git - arch-based

step 2:
download the project repository

$ git clone https://github.com/Nick-cpp/helloworld

step 3:
compilation & installation


$ cd helloworld/

$ g++ -std=c++17 helloworld.cpp -o helloworld

$ sudo install -Dm755 helloworld /usr/bin/helloworld

step 4:
program launch

$ helloworld
