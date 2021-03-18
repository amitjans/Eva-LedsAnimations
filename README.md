# Eva-LedsAnimations
 Implementation of the Eva leds animations.

 ## Intalación
Paquetes requeridos para desarrollar y compilar las animaciones del arreglo de luces led.
```bash
sudo apt-get install matrixio-creator-init libmatrixio-creator-hal libmatrixio-creator-hal-dev
```

## Compilación

Para compilar las animaciones del arreglo de leds de la Matrix Voice debemos ejecutar el siguiente comando, donde deberemos cambiar <app> por el nombre del archivos que queremos obtener como resultado del proceso de compilación y el <app.cpp> por el nombre del archivo que contenga la implementacion de la animación que deseamos compilar.
```bash
g++ -o app app.cpp -std=c++11 -lmatrix_creator_hal
```
