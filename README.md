<h1 align="center">Minecraft semi hardcore</h1>

## Como funciona?
En Minecrat existe un apartado llamado **scoreboard** el cual te permite guardar informacion, aqui lo que hacemos es guardar un valor(dependiendo del sistema que elijamos, luego a travez del plugin **conditional events** y **placeholder api** podremos hacer que cuando mueras se reste un 1 del valor de la scoreboard

## Pasos a seguir (no importa que opcion elijan van a ser los mismos pasos)

- En minecraft poner el siguiente comando: **/scoreboard objectives add vidas dummy**
- Luego en el conditional events deben crear un evento, no se preocupen mucho por eso, les dejare el archivo listo con el evento
- Lo unico que deben hacer el poner el evento en la carpeta **plugins\conditionalevents\events**
- Luego en el minecraft ponen **/ce reload**



## Opcion 1
En esta opcion se utilizara un sistema de tipo clasico, mueres y se te descuenta 1 vida, si llegas a 0 pierdes
## Opcion2
En esta opcion se utilizara la barra de vida como sistema de vidas, si mueres se te resta un corazon y si llegas a 0 pierdes
