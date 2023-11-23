# Cinco Noches Con Freduardo (CNCF)

## ¿De Qué Trata?

Básicamente una parodia de Five Nights At Freddy's en Minecraft hecho en 5 días por las risas

![Lo que me "inspiró" a hacerlo](https://github.com/CPlayxs/Eventos/assets/100153287/de0223b6-bf6c-4fdd-ad83-7eb576b30a81)

**Cabe aclarar**, el mapa es simple, como está hecho en 5 días, no me dió tiempo a hacerlo más completo.

# Guía

Primero, añadir a los jugadores al equipo de jugador con el comando `/team join jugador <nombre>`

Arriba del inicio, hay un cofre, en el cual hay 3 libros (Periodico "El Minuto", Utility y Extra), usando el libro de Extra, y presionando el texto "Casa" se teletransportarán los jugadores a la casa, donde en la habitación de la derecha se pondrá el libro de 'Periodico "El Minuto"', en el cual los jugadores irán a la última página y harán click en "Inscribirme" (Leer el apartado de servidor) ahí serán teletransportados a la avenida, donde entrarán a la pizzería. Dentro estará una caja de netherite la cual será el cuarto de seguridad, hay cinco carteles que funcionan como botones, abrir puertas, cerrar puertas e iluminar al animatrónico.
Para el animatrónico, hay que transformarse en zombie, usando el mod de "Identity" el cual no tendrá textura, por lo tanto, será invisible, ahora en el libro de "Utility", están los nombres de los tres animatrónicos, se pueden presionar y serán calabazas con el modelo de cada uno, se debería pegar con una espada de hierro para no matar a los jugadores de un solo golpe, pero se puede cambiar.
Antes de empezar, se ejecuta el comando `/team join animatronico @s` y `/playsound minecraft:music_disc.chirp block @a 100.05 -59.00 43.51` ese comando hará sonar la música de Freddy, cuando acabe, el animatrónico tendrá que salir, como son 5 noches, la idea es matar a uno cada noche a excepción de la 5, al final de cada noche se teletransportan los jugadores otra vez a la casa y se repite el proceso.
En la quinta noche, se ejecuta el comando `/setblock 100 -60 80 shulker_box{Items:[{Slot:3b,id:"minecraft:cooked_beef",Count:16b},{Slot:4b,id:"minecraft:iron_helmet",Count:1b},{Slot:5b,id:"minecraft:cooked_beef",Count:16b},{Slot:12b,id:"minecraft:iron_chestplate",Count:1b},{Slot:13b,id:"minecraft:iron_sword",Count:1b},{Slot:14b,id:"minecraft:iron_leggings",Count:1b},{Slot:21b,id:"minecraft:cooked_beef",Count:16b},{Slot:22b,id:"minecraft:iron_boots",Count:1b},{Slot:23b,id:"minecraft:cooked_beef",Count:16b}]}`, con este comando, se pondrá una caja shulker en la entrada, el jugador que queda, debe entrar y matar a los tres animatronicos (el que esté de animatronico se cambia de cabeza cada vez que muera), después de que haya matado a todos, con el hacha de madera, gracias a World Edit, se selecciona toda la pizzería y se ejecutan los comandos `//pos1 115,-52,-76`, `//pos2 69,-61,-4` y `//replace polished_blackstone_button tnt`, luego se enciende la tnt.

Eso es todo, en lo que pueda trataré de subir un video explicando todo para que se entienda mejor y mejorar el mapa.

# Servidor
Cosas necesarias que deben estar en el servidor:

Debe ser Fabric/Forge con por lo menos el mod de Identity con sus dependencias.
También se necesita configurar un mod de permisos para que los jugadores puedan ejecutar el comando de `/tp` y `/tellraw`.

# Mods
Como actualmente no puedo subir el cliente por varios motivos, voy a dejar la lista de mods necesitados y usados en el cliente de CNCF temporalmente
(La versión que se usó es Fabric 1.19.2)

[Architectury](https://modrinth.com/mod/architectury-api)

[Auto Config](https://www.curseforge.com/minecraft/mc-mods/auto-config-updated-api)

[Cloth Config](https://modrinth.com/mod/cloth-config)

[Custom Splash Screen](https://modrinth.com/mod/custom-splash-screen)

[Dynamic FPS](https://modrinth.com/mod/dynamic-fps)

[Enhanced Block Entities](https://modrinth.com/mod/ebe)

[Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin)

[FancyMenu](https://modrinth.com/mod/fancymenu)

[FerriteCore](https://modrinth.com/mod/ferrite-core)

[Identity](https://www.curseforge.com/minecraft/mc-mods/identity)

[ImmediatelyFast](https://modrinth.com/mod/immediatelyfast)

[Indium](https://modrinth.com/mod/indium)

[Konkrete](https://modrinth.com/mod/konkrete)

[LambDynamicLights](https://modrinth.com/mod/lambdynamiclights)

[LazyDFU](https://modrinth.com/mod/lazydfu)

[Lithium](https://modrinth.com/mod/lithium)

[Memory Leak Fix](https://modrinth.com/mod/memoryleakfix)

[ModernFix](https://modrinth.com/mod/modernfix)

[OpenMCSkins](https://modrinth.com/mod/openmcskins)

[Reese's Sodium Options](https://modrinth.com/mod/reeses-sodium-options)

[Sodium](https://modrinth.com/mod/sodium)

[Sodium Extra](https://modrinth.com/mod/sodium-extra)

[Starlight](https://modrinth.com/mod/starlight)

[WorldEdit](https://www.curseforge.com/minecraft/mc-mods/worldedit)

[YetAnotherConfigLib](https://modrinth.com/mod/yacl)

[Zoomify](https://modrinth.com/mod/zoomify)

![Cliente](https://github.com/CPlayxs/Eventos/assets/100153287/1b4ae8f9-e7aa-4427-b138-3cabdf5c56f4)
