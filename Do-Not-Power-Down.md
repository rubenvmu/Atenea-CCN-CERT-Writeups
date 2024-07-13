Necesitamos tu ayuda para localizar a un conocido ciberdelincuente. La única información que tenemos del sujeto es el gif adjunto que compartió recientemente en un foro underground.

Objetivo: identifica la ciudad donde se encuentra el atacante. Ej: Oslo

1:
![Imagen de exploit](https://i.ibb.co/r6DvJP6/exploit-in202010231-thread3154-4da22237407a17c32af03bacd2123887.gif)


2: 
Nos preguntamos si podemos conocer el fabricante de la MAC, conocer algo sobre el dispositivo.

Vemos el siguiente comando:
Airodump-ng -c $1 f0:ab:54:50:1d:27 -w dump  wlan0mon
¿Se puede conocer a quien pertenece la mac?

3: 
Vemos que esa MAC está registrada:
https://maclookup.app/search/result?mac=f0:ab:54:50:1d:27

OUI: F0:AB:54
Range: F0:AB:54:00:00:00 - F0:AB:54:FF:FF:FF
Block Size: 16777215 (16.77 M)
Universally administered addresses (UAA) : the address is uniquely assigned by its manufacturer.
Type of transmission: Unicast
Wireshark:
MitsumiElect
Mitsumi Electric Co.,Ltd.

2-11-2
Tsurumaki
Tama-shi Tokyo 206-8567
JP.

4: 
Probamos si la ciudad es Tama, pero no lo es. Toca seguir buscando pruebas.

