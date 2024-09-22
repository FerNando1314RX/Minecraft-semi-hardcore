<p align="center">(Tutorial en ingles y español, ingles abajo)\\(Tutorial in English and Spanish, English below)
  
** **

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


## Aclaraciones:
Lo que hice basicamente fue inspirarme del codigo de [iTSoS(el mejor tutorial que he visto para la opcion 1)](https://www.youtube.com/watch?v=GLKRz29umrc&t=300s) y de un short de [ajneb97(creador del plugin ConditionalEvents)](https://www.youtube.com/shorts/2wEmZw3W1SU)



** **
** **
** **
<h1 align="center"> </h1>
<h1 align="center">English</h1>

** **
** **
** **


<h1 align="center">Minecraft semi hardcore</h1>
(if you didn't understand, don't worry, I'll soon make a tutorial on YouTube explaining all this, once it's ready you won't see this, you'll see a "Video" in blue with a hyperlink)

## How does it work?
In Minecraft there is a section called **scoreboard** which allows you to save information, here what we do is save a value (depending on the system we choose, then through the plugin **conditional events** and **placeholder api** we can make it so that when you die a 1 is subtracted from the scoreboard value

## Steps to follow (it doesn't matter which option you choose, they will be the same steps)

- Install the following plugins: [ConditionalEvents](https://modrinth.com/plugin/conditionalevents/versions) and [PlaceHolderApi](https://www.spigotmc.org/resources/placeholderapi.6245/)
- In minecraft put the following command: **/scoreboard objectives add dummy lives**
- Then put: **/papi ecloud download player, /papi ecloud download playertime, /papi ecloud download scoreboardobjectives and finally /papi reload**
- Then in the conditional events must create an event, don't worry too much about that, I'll leave the file ready with the event
- The only thing you have to do is put the event in the **plugins\conditionalevents\events** folder
- Then in minecraft put **/ce reload**

## Option 1
In this option a classic type system will be used, you die and 1 life is deducted from you, if you reach 0 you lose, if you choose this option you can choose the number of lives that the player will have at the start, the default value I will leave at 5, you can change it in line 8

**- 'console_command: scoreboard players set %player% lives (number of lives of your choice)'**

In lines 14 and 21 the optional death message will be added, you can put whatever you want when the player loses a life or directly dies, but to specify the player you must put %player%, now if you occupy a page like [birdflop](https://www.birdflop.com/resources/rgb/) don't put the %player% there, you must put it afterwards, also on that page you must put the color format in **"&x&r&r&g&g&b&b"** anyway in the file I will leave an example.

** **
## Option2
In this option the life bar will be used as a life system, if you die you lose a heart and if you reach 0 you lose

In lines 14 and 19 the optional death message will be added, you can put whatever you want when the player loses a life or directly dies, but to specify the player you must put %player%, now if you use a page like [birdflop](https://www.birdflop.com/resources/rgb/) do not put the %player% there, you must put it after, also on that page you must put the color format in **"&x&r&r&g&g&b&b"** anyway in the file I will leave an example.

## **Remember to follow me on my networks**
[<img alt="YouTube Channel Subscribers" src="https://img.shields.io/youtube/channel/subscribers/%20UCK-AgU6luMFlKxKbWLRM-SA">](https://www.youtube.com/@FerNando1314XR)
[<img alt="Twitch Status" src="https://img.shields.io/twitch/status/fernando1314xr">](https://www.twitch.tv/fernando1314xr)
[<img alt="Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/fernandoxr24/)

## Clarifications:
What I basically did was get inspired by the code from [iTSoS(the best tutorial I've seen for option 1)](https://www.youtube.com/watch?v=GLKRz29umrc&t=300s) and a short from [ajneb97(creator of the ConditionalEvents plugin)](https://www.youtube.com/shorts/2wEmZw3W1SU)





