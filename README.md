# GBAWebEmulator
## Alejandro Morillo Troya

## Proyecto:
En este proyecto me gustaría realizar un emulador online de la videoconsola Game Boy.

La finalidad de este proyecto es crear una aplicación web donde las personas puedan acceder al emulador sin necesidad de tener la consola, solo necesitará ROMs de los juegos (pueden ser propias o conseguidas de internet) y usarlas en la web para jugar.

La idea es permitir que los usuarios tengan su propia cuenta, con sus juegos, sus datos guardados de los mismos en una aplicación web evitando así que al formatear un ordenador propio, o un dispositivo en el que jueguen pierdan sus avances, sólo necesitan la ROM del juego, que eso no puedo almacenarlo por copyright.

## Hardware y software:
Utilizaré el framework de Django y Python para gestionar el back-end de la aplicación web, aunque si veo que necesito sólo algunas funcionalidades y no todas las del framework Django posiblemente use Flask, con la idea de hacer la aplicación lo más liviana posible y así asegurar una emulación más estable.
 
Como front-end y para la interfaz utilizaré en principio JavaScript, aunque me gustaría usar React.

Para el emulador intentaría buscar y adaptar algún emulador ya existente, a menos que ya esté adaptado a JavaScript, sino tendría que usar WebAssembly para realizar el emulador cosa que me tomaría más tiempo.

También me gustaría usar una imagen Docker con la aplicación completa y desplegarla en una instancia AWS.

Como hardware utilizaría mi ordenador personal para programar y probar la aplicación, ya que no requiere de dispositivos adicionales.

## Planificación:
La primera parte sería el emulador, comprobar que ya exista alguno que me pueda servir o si en su caso no existe realizar uno con WebAssembly. **(De 2 semanas a 1 mes)**

Una vez el emulador esté funcional, crearía la aplicación web, es decir, usar Django para crear la base de datos de los usuarios, la lógica de la aplicación e insertar el emulador en la misma.**(2 semanas a 1 mes)**

Por último crearía la interfaz para usar la aplicación intentando tener un estilo minimalista y funcional, con la idea de que sea sencilla de usar. **(2 semanas)**

Si todo ha ido bien y el tiempo que he estimado es correcto, tendría más o menos un par de semanas para depurar y solucionar errores menores que vayan surgiendo. 
  
