# Que he hecho para crear mi agente

Raul nos dio un ordenador el centro, el cual, encendí y pitaba indicando un error. Le comenté a OpenCode la secuencia de sonido que emitía el ordenador cada vez que lo encendía y me ayudó a resolverlo.

Tuve que abrirlo, soltar el cableado y limpiar las conexiones, además de soplar con aire a presión para quitar el polvo que había sobre el resto de componentes.

Desde mi portátil y con un USB, metí un Linux MINT al USB mediante el programa RUFUS. Para hacerlo, descargué la ISO de Linux y Rufus.ie.

Desde dentro de Rufus, seguí las instrucciones de Raul para poder instalar Linux dentro del USB.

Con el Linux y el PC del centro listos, encendí el PC y abrí la BIOS, luego, le cambié el arranque automático para que se iniciara con el USB y así poder tener acceso a Linux cada vez que lo encendiera.

Con el Linux operativo en el PC, me metí en la página web de OpenCode y se lo instalé en la terminal.

Con el OpenCode trabajando, le pedí que activara todos los requisitos y funciones necesarias para poder acceder a él mediante SSH desde mi portátil.

Desde mi portátil, le pedí a mi OpenCode que activara lo necesario para poder conectarme a otro equipo mediante SSH y le dije que me quería conectar al PC que se me asignó, indicándole el nombre de usuario, la dirección IP y la contraseña del equipo. Se conectó él solo y me dijo que estaba listo y operativo.

Desde mi portátil, me registro en OpenRouter y genero una API Key que posteriormente utilizaré para crear el bot. También, desde el BotFather de Telegram, creo mi propio bot y le asigno el nombre de BotniciusJR_bot, al cual, le pido también la Key para poder crear el agente posteriormente.

Conectado al PC de clase por SSH y con las dos Key listas, le pedí a OpenCode que instalara OpenClaw y que creara el bot de Telegram usando un modelo gratis y pidiéndole que cada pocas horas se refresque el servicio en caso de que se quede colgado o se caiga la conexión.

Finalmente, desde mi aplicación de Telegram, interactué con el Agente comprobando que OpenCode había usado un modelo gratuito (al principio no, lo tuve que cambiar luego pidiéndole que usara el modelo que Raul nos pidió) y luego le pedí la previsión del tiempo y un saludo para el profesor.