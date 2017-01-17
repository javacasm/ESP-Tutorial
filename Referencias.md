# Referencias a mirar


## Trucos

### [Usar módulos ESP12 con NodeMCU](http://www.instructables.com/id/Foolproof-ESP8266-12E-Programming-and-Use/)

La idea es añadir al ESP12 pines "macho" de 2mm y al NodeMCU pines "hembra" de 2mm y así poder conectarlos

![ejemplo](https://cdn.instructables.com/FND/464N/IXLA7QDN/FND464NIXLA7QDN.LARGE.jpg)


Adaptación personal:
* Usar el NodeMCU que no funciona
* Pararar un adaptador 2mm a 2.54mm con una de las placas adaptadoras

### Deep Sleep para bajo consumo

Deep Sleep (GPIO 16) pin debe conectarse al pin Reset

![gpio 16 to reset](https://tzapu.com/wp-content/uploads/2015/12/ESP8266-battery-deep-sleep-mod-esp01.jpg)

[Ejemplo de código](https://github.com/tzapu/DeepSleepDHT22/blob/master/DeepSleepDHT22.ino)

      ESP.deepSleep(5 * 60 * 1000 * 1000);

![montaje en el NodeMCU](http://www.esploradores.com/wp-content/uploads/2017/01/Circuito-ESP8266-NodeMCU-DHT22_2.png)

[Proyecto similar](http://www.esploradores.com/practica-8-thinger-io-almacenamiento-y-monitorizacion-de-datos-segunda-parte/)

## Alimentación

[Alimentación con 18650](https://tzapu.com/minimalist-battery-powered-esp8266-wifi-temperature-logger/)

## Proyectos

[Datalogger](https://tzapu.com/minimalist-battery-powered-esp8266-wifi-temperature-logger/)
