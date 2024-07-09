# WSL3
WSL2 rewrite aiming to match the functionality of WSL2 one-to-one whilst keeping filesize down 


# Installation

### [``gcc toolchain``  is required]

simply run 
``g++ main.cpp -o wsl3``
to build WSL3

for optimal performance you also may run 
``g++ main.cpp -march=native -mtune=native -fomit-frame-pointer -ffast-math -o wsl3 ``.

once the building step succeeded simply run 
``./wsl3``. 
