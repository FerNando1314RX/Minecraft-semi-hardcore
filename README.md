<h1 align="center">Minecraft semi hardcore</h1>
(por si no entendieron no se preocupen, pronto hare un tutorial en youtube explicando todo esto, una vez este listo no veran esto, veran un "Video" en azul con un hipervinculo)

## Como funciona?
En Minecrat existe un apartado llamado **scoreboard** el cual te permite guardar informacion, aqui lo que hacemos es guardar un valor(dependiendo del sistema que elijamos, luego a travez del plugin **conditional events** y **placeholder api** podremos hacer que cuando mueras se reste un 1 del valor de la scoreboard

## Pasos a seguir (no importa que opcion elijan van a ser los mismos pasos)

- Instalar los siguientes plugins: [ConditionalEvents](https://modrinth.com/plugin/conditionalevents/versions) y [PlaceHolderApi](https://www.spigotmc.org/resources/placeholderapi.6245/)
- En minecraft poner el siguiente comando: **/scoreboard objectives add vidas dummy**
- Luego ponenen: **/papi ecloud download player, /papi ecloud download playertime, /papi ecloud download scoreboardobjectives y por ultimo /papi reload**
- Luego en el conditional events deben crear un evento, no se preocupen mucho por eso, les dejare el archivo listo con el evento
- Lo unico que deben hacer el poner el evento en la carpeta **plugins\conditionalevents\events**
- Luego en el minecraft ponen **/ce reload**



## Opcion 1
En esta opcion se utilizara un sistema de tipo clasico, mueres y se te descuenta 1 vida, si llegas a 0 pierdes, si eliges esta opcion puedes elegir el numero de vidas que tendra el jugador al iniciar, el valor por defecto lo dejare en 5, lo puedes cambiar en la linea 8

**- 'console_command: scoreboard players set %player% vidas (cantidad de vidas a eleccion)'**

En la linea 14 y 21 se agregara el mensaje de muerte opcional, puedes poner lo que quieras cuando el jugador pierda una vida o directamente muera, pero para especificar al jugador debes poner %player%, ahora si ocupas una pagina como [birdflop](https://www.birdflop.com/resources/rgb/) no pongas ahi el %player%, debes ponerlo despues, ademas en esa pagina debes poner el formato de color en **"&x&r&r&g&g&b&b"** de todos modos en el archivo dejare un ejemplo.

** **
## Opcion2
En esta opcion se utilizara la barra de vida como sistema de vidas, si mueres se te resta un corazon y si llegas a 0 pierdes

En la linea 14 y 19 se agregara el mensaje de muerte opcional, puedes poner lo que quieras cuando el jugador pierda una vida o directamente muera, pero para especificar al jugador debes poner %player%, ahora si ocupas una pagina como [birdflop](https://www.birdflop.com/resources/rgb/) no pongas ahi el %player%, debes ponerlo despues, ademas en esa pagina debes poner el formato de color en **"&x&r&r&g&g&b&b"** de todos modos en el archivo dejare un ejemplo.

** **
## Recuerda seguirme en mis redes
[<img alt="YouTube Channel Subscribers" src="https://img.shields.io/youtube/channel/subscribers/%20UCK-AgU6luMFlKxKbWLRM-SA">](https://www.youtube.com/@FerNando1314XR)
[<img alt="Twitch Status" src="https://img.shields.io/twitch/status/fernando1314xr">](https://www.twitch.tv/fernando1314xr)
[<img alt="Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/fernandoxr24/)
