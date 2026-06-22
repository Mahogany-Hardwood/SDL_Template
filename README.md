Project setup for SDL using Cmake.

How to compile:
  clone the repo:
    git clone https://github.com/Mahogany-Hardwood/SDL_Template.git && cd SDL_Template

  compile the source:
    cmake -S . -B build && cmake --build build

  run the executable:
    ./build/src/game

  If it said "Couldn't load bitmap: Couldn't open /home/skype/Garage/project/build/src/sample.png: No such file or directory"
  copy the sample.png file under the src to the build/src, then you are good to go.
  
