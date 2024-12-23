# L4D2_8Coop_Server_Custom
**Versión actual:** v1.0.0
### Introducción

Les paso los archivos y configuraciones necesarias para poder jugar con 8 jugadores en Left 4 Dead 2.

## Instalación

Requisitos previos

Descarga los archivos necesarios desde el repositorio.

Asegúrate de tener el juego Left 4 Dead 2 instalado.

Copia la carpeta 
```left4dead2/``` 
dentro de la carpeta del juego
```*\SteamLibrary\steamapps\common\Left 4 Dead 2\```

<sub>(referencia donde esta la carpera del juego)</sub>


## Configuración

Configuración del menú de administración

Vamos a configurar el menú de administración para tener acceso total al servidor.

Pasos a seguir:

* Dirígete a la página:
```
https://steamdb.info/calculator/
```


* Busca tu perfil de Steam e identifica tu Steam2 ID.

  Ejemplo:

  Steam2 ID ---> STEAM_1:0:XXXX123

* Encuentra el siguiente archivo en la ruta:
```
*\Left 4 Dead 2\left4dead2\addons\sourcemod\configs\admins_simple.ini
```

* Abre el archivo con un editor de texto y agrega tu Steam2 ID de la siguiente manera:

  "STEAM_1:0:XXXX123"        "99:z"

  <sub>El valor 99:z otorga control total al administrador.</sub>

### Addons necesarios desde el Workshop

Para habilitar un lobby de 8 jugadores necesitarás instalar el siguiente addon:

* 8 Slots Lobby Fixed

  Link:
```
https://steamcommunity.com/sharedfiles/filedetails/?id=2754956355
```

* Nota:

  Este addon es imprescindible para habilitar el lobby de 8 jugadores.

  <sub>Si el addon entra en conflicto con otra extensión, desactiva la extensión que genera el error.<sub>

