# Eva-LedsAnimations
 Implementation of the Eva social robot leds animations.

 ## Installation
Packages required to develop and compile the animations of the led light arrangement.

```bash
sudo apt-get install matrixio-creator-init libmatrixio-creator-hal libmatrixio-creator-hal-dev
```

## Compilación
To compile the animations for the Matrix Voice's leds array we need to execute the following command, where we must change <app> to the name of the files that we want to obtain as a result of the compilation process and <app.cpp> to the name of the file that contains the implementation of the animation that we want to compile.
 
```bash
g++ -o app app.cpp -std=c++11 -lmatrix_creator_hal
```

## Usage
For Eva main app uses the compiled animations, these need to be found on leds's folder.
