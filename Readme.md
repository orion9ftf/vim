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

