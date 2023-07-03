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

