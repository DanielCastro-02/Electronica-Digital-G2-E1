# Laboratorio 2 - Sumador de 1 y 4 bits

Para este laboratorio se utilizo el sumador de 1 bit del laboratorio #1 con el objetivo de poder representarlo de manera activa en la fpga, para esto, fue necesario asignarle a cada entrada y a cada salida un pin de la fpga.

![alt text](https://github.com/DanielCastro-02/Electronica-Digital-G2-E1/blob/main/Lab2/imagenes/WhatsApp%20Image%202024-03-17%20at%2010.11.47%20PM.jpeg)

La asignación de los pines se dio en ese orden ya que, para las entradas se asignaron los interruptores de la fpga (PIN_58, PIN_59, PIN_60), para las salidas se utilizaron los leds (PIN_106, PIN_110), al asignar un pin a cada uno se compilo para que este subiera la asignacion de los pines al programa, posteriormente se conecto a las fpga y se subio la informacion antes mencionada a esta misma (fpga) para que obtuviera la informacion de cada una de los pines.

![alt taxt](https://github.com/DanielCastro-02/Electronica-Digital-G2-E1/blob/main/Lab2/imagenes/WhatsApp%20Image%202024-03-17%20at%209.38.44%20PM.jpeg)

Como se puede ver la fpga recibió todo la informacion con exito y ya se puede interactuar de manera activa en la fpga (https://youtu.be/phVZOsEvMsc).

Ahora para el sumador de 4 bits se utilizo el sumador de 1 bit pero 4 veces, esto quiere decir que ahora tenemos 4 veces mas entradas, por lo tanto toca asignar a cada entrada un interruptor, para las salidas solo hay 4 ya que es una por sumador entonces a cada uno se le asignara un led.

![alt taxt](https://github.com/DanielCastro-02/Electronica-Digital-G2-E1/blob/main/Lab2/imagenes/WhatsApp%20Image%202024-03-17%20at%2010.24.09%20PM.jpeg)
Al asignar un pin a cada una de nuestras entradas y salidas se puede compilar y subir la informacion al programa. Repetimos el paso anterior como en el sumador de 1 bit y subimos toda la informacion a la fpga y este nos dice que todo esta correcto.

![alt taxt](https://github.com/DanielCastro-02/Electronica-Digital-G2-E1/blob/main/Lab2/imagenes/WhatsApp%20Image%202024-03-17%20at%209.38.44%20PM.jpeg)


