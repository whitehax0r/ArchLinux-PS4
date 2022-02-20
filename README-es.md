

Primer Projecto de Github, orgullosamene creado por un latino 🤠

# ArchLinux-PS4

Esta es una version compilada y actualizada del sistema operativeo Arch Linux con algunos retoques personales en la interfaz grafica de usuario para que se vea mejor and alguno emuladores integrados.

![neofetch](https://github.com/whitehax0r/ArchLinux-PS4/blob/4c8010140ee8e5f8d68b1d623464d555706d2f8d/neofetch.png)

![lscpi](https://github.com/whitehax0r/ArchLinux-PS4/blob/883347d1f54bdcb4b2fc1828fcb714c84158b72d/lspci.png)

![glxinfo](https://github.com/whitehax0r/ArchLinux-PS4/blob/883347d1f54bdcb4b2fc1828fcb714c84158b72d/glxinfo.png)

![desktop2](https://github.com/whitehax0r/ArchLinux-PS4/blob/883347d1f54bdcb4b2fc1828fcb714c84158b72d/Desktop2.png)

# Caracteristicas en este sistema operativo.

- Descargas paralelas habilitado.
- Repositorio de PS4 hablitiado.
- LightDM con autologin habilitado.
- Neofetch - Muestra informacion general sobre el sistema.
- Ultimos Driver de PS4 directamente del repositorio oficial.
- XFCE - Entorno grafico.
- Steam - Programa para descargar juegos de PC.
- Soporte para el formate ExFat.
- Bluez - Para poder emparejar tu control de PS4.
- Blueberry - Interfaz grafica de usuario compatible con GTK y XFCE.
- Duckstation - Mejor emulador de Playstation 1.
- Dolphin emulator - Nintengo Wii y emulador de GameCube.
- Nano - Editor de texto.
- Chromium - Buscador web de codigo abierto.
- Powerlevel10k - Terminal ZSH.
- PCSX2 - Emulador de Playstation 2 con soporte Vulkan.
- Yabaouze - Emulador de Sega Dreamcast.
- Hacknerdfonts - Fuente de letras para el sistema operativo y iconos especiales.
- RetroArch - Emulador multiplataforma.
- Minecraft Java - Porque es divertido. :pick:
- LSD - Comando LS mejorado basicamente.
- BAT - Comando CAT mejorado basicamente.
- VLC - Reproductor de video.
- Spotify - Reproductor de musica.
- Yay - Otro gestor de programas con el repositorio AUR escritor en Go. 
- Zip - Comprimir archivos a formato Zip.
- Unzip - Descomprimir archivos de formato Zip.
- P7zip - Version de linea de comandos de 7zip para Linux.
- Htop - Ver procesos y rendimiento del sistema.

# Requerimientos obligatorios
Un cerebro xD y mucha paciencia.

# El hardware de mi Playstation 4

- PS4 Slim
- Sistema operativo 9.00
- Model0 CUH-2115B.
- SouthBridge Baikal.

## Si tienes el mismo modelo de Playstation 4 que yo puede usar y descargar los archivos que estan adjuntados abajo:

- [bootargs.txt](https://github.com/whitehax0r/ArchLinux-PS4/blob/4add3a72d25dcfabff433283606b9ce30762d4d9/bootargs.txt) MD5 >__C84AD779CE76762C04CBF80E420E324D__
- [initramfs.cpio.gz](https://github.com/whitehax0r/ArchLinux-PS4/blob/4add3a72d25dcfabff433283606b9ce30762d4d9/initramfs.cpio.gz) MD5 >__951549B1DEB59DAE3ADA8038461BADD2__
- [bzImage](https://github.com/whitehax0r/ArchLinux-PS4/blob/4add3a72d25dcfabff433283606b9ce30762d4d9/bzImage) MD5 >__B8BDDA64FDED673D1FD8017C2A4B4122__
- [arch.tar.xz](https://mega.nz/file/6ro0mZqb#uzVI3PjhxZ7m5hk4EC2AxCIg5B8h87mqEuvUEzo20Oo) MD5 >__7A997C14B2FAD0C839107A07C69FC312__

# Preparando tu sisteam de PS4.

- Asegurate que tienes primero tu sisteam operativo con sistema operativo 9.00.
- Ve a Ajustes>Sonido y pantalla>Ajustes de salida de video>
- Resolucion cambialo a >__1080p__
- Opcion RGB cambialo a >__Completo__
- HDR cambialo a  >__Desactivado__
- Salida de color profundo cambialo a >__Desactivado__
- Ve a Ajustes>Sistema>
- Desmarca la cajita "Activar enlace del dispositivo HDMI"
- Desmarca la cajita "Activar HDCP"

# Preparando tu dispositivo de interfaz 3.0 para ArchLinux-PS4

:warning: Altamente recomendable que uses un disco duro o USB >=16GB :warning:

- Formatea el USB/Discoduro 3.0 a formato Fat32. Puedes utilizar este [software.](http://ridgecrop.co.uk/index.htm?guiformat.html)
- Copia y pega el fichero bzImage, initramfs.cpio.gz, bootargs.txt y arch.tar.xz a la raiz de tu USB/Discoduro 3.0.
- :warning: Si estas usando el initramfs.cpio.gz de mi Github, este es creado por Nazky, el nombre de este Sistema operativo deberia ser arch.tar.xz :warning:
- :warning: __Si estas usando el initramfs.cpio.gz del psxita team, deberias de renombrar este fichero de arch.tar.xz a psxitarch.tar.xz__ :warning:
- El total de 4 ficheros deberian de estar en la razi de tu USB/Discoduro 3.0 bzImage, initramfs.cpio.gz, bootargs.txt y arch.tar.xz o psxitarch.tar.xz.
- Abre el navegador web del PS4 y primero has el Jailbreak a tu PS4 con el Host de [Al-Azif.](https://cthugha.exploit.menu/#PS4%20(9.00))
- Despues conecta tu USB/Discoduro 3.0 con todos los archivos necesarios dentro en la raiz, asegurate de conectar tu USB/Discoduro en el puerto USB que esta mas cercano a la lectora de discos del PS4.
- Selecciona y arranca el payload 1GB Linux usando el host de tu confianza pero te recomiendo que uses [este](https://sleirsgoevy.github.io/900-host/) de [Sleirsgoevy](https://github.com/sleirsgoevy) porque este detecta el fichero bootargs.txt para evitar el problema de pantalla negrra. __He intentando varios host y ninguno detecta el fichero bootargs.txt.__

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
- Cuando estes en el rescueshell escribe los siguientes comandos:
>__exec install-psxitarch.sh__
- :warning: Si estas usando el initramfs.cpio.gz de Nazky escrbie los siguietens comandos: :warning:
>__exec install-arch.sh__
- Cuando la instalacion termine ArchLinux-PS4 se va iniciar automanticamente, en caso de que no inicie, escribe los siguientes comandos:
>__exec start-psxitarch.sh__
-  :warning: __Si estas usando el initramfs.cpio.gz de Nazky escribe los siguientes comandos:__ :warning:
>__exec start-arch.sh__

- ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

# Cosas por incluir.

- RPCS3 emulator - Emuladr de PS3. (Puedes probar el AppImage que esta en la [website.](https://rpcs3.net/download)) oficial.
- ProtonDB programa para jugar juegos de PC en Linux.
- Nada mas, tu dime :) 

# Problemas conocidos

No se porque pero cada vez que inicias el sistema operativo, tienes que configurar el hora y la fecha, solo escribe los siguientes comando como 'root': 

>__# timedatectl set-time "yyyy-MM-dd hh:mm:ss"__

Por ejemplo:

>__# timedatectl set-time "2022-02-19 13:13:54"__

Cada vez que inicies en Linux tendras que desemparejar y emparejar nueva mente tu contro de PS4.

# Algunas preguntas frecuentes

## Cual es la contrasena del usuario sony y root?
Lo puedes encontrar en el escritorio, ahi encontratar un fichero con el nombre de 'Important.txt'.

## Tengo pantalla negra
Asegurate primero que tu monitor o TV soporta la resolucion de video de 1080p, si aun asi sigues teniendo el mismo problema asegurate de seguir bien los pasos o puedes intentar con otro TV o monitor.

## Quiero desintalar este sistema operativo de mi USB/Discoduro 3.0
Solo formatea nuevamente tu USB/Discoduro al sistema de archivos de tu preferencia.

## Como actualizo ArchLinux-PS4?
Solo escribe el siguiente comando en la terminal:
>__sudo pacman -Syyu__
- y escribe "Yes" si ves paquetes con actualizaciones.

## Puedo usar mi control de PS4 como un mouse o raton?
Si!, si puedes usar el touchpad de tu control de ps4 como mouse.

## Tengo dificultades para conectar mi control de PS4, que hago?
Voy a subir un video despues en dos dias aproximadamente para explicarte mejor.

## No estoy seguro del Hardware de mi PS4?
Puedes buscar [aqui](https://www.psdevwiki.com/ps4/Southbridge#Southbridge_revisions) o [aqui.](https://www.psdevwiki.com/ps4/)

## Donde puedo encontrar estos PS4 kernels y initramfs.cpio.gz de otras consolas PS4?
Puedes descargar estos fichero del repositorio de [Hakkuraifu.](https://github.com/Hakkuraifu/PS4Linux-Documentation)

# Redes Sociales

- Me puedes seguir en [Twitter](https://twitter.com/razr2312)
- Me puedes seguir en [YouTube](https://www.youtube.com/user/allank2312/videos)

![esta es una imagen](https://github.com/whitehax0r/ArchLinux-PS4/blob/353059a5bbb0a7f161ade53a56e374a6398d7c6a/Flag.png)

## Creditos

Muchas gracias:
- @theflow0
- @notzecoxao
- @fail0verflow 
- @_AlAzif
- @Znullptr
- @SpecterDev
- @sleirsgoevy
- @ps4_hacking
- @frwololo
- @ChendoChap
- @Ps3ita_Team
- @NazkyYT
- @GBAtemp