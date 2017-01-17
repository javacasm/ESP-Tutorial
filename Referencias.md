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

### [Conexión con google docs](https://www.youtube.com/watch?v=5f7wCeD4gB4)

## Alimentación

[Alimentación con 18650](https://tzapu.com/minimalist-battery-powered-esp8266-wifi-temperature-logger/)

[Alimentación con 18650 lipo](http://www.esp8266.com/viewtopic.php?p=52974)

[Uso con 18650 recargable](http://www.instructables.com/id/ESP8266-Li-Ion-Battery-rechargeable-battery-power-/)

[¿el mismo?](http://www.esp8266-projects.com/2015/03/mailbag-arrival-new-battery-solution.html)

![18650 recargable](https://cdn.instructables.com/F7X/CECJ/I8BGIARY/F7XCECJI8BGIARY.MEDIUM.jpg?width=614)

## Proyectos

[Datalogger](https://tzapu.com/minimalist-battery-powered-esp8266-wifi-temperature-logger/)


## Referencias

[Pinout del ESP01](http://henrysbench.capnfatz.com/henrys-bench/arduino-projects-tips-and-more/esp8266-esp-01-pin-outs-and-schematics/)