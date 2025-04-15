# Laboratorio CTF Dockerizado con retos de Hacking Ético y OSINT                                                                                                                             

Este repositorio contiene una máquina virtual Kali Linux en formato **.ova** preparada para desplegar un laboratorio CTF (Capture The Flag). Todo lo necesario ya está instalado y configurado dentro de la máquina. El usuario únicamente debe importar la máquina en VirtualBox, iniciar sesión y lanzar un script de despliegue que montará automáticamente un entorno de prácticas de Hacking Ético y OSINT.

## Descripción

El objetivo de este proyecto es proporcionar un entorno práctico seguro, realista y controlado donde los participantes puedan poner en práctica sus habilidades de Hacking Ético y OSINT (Open Source Intelligence).

Dentro de la máquina virtual, el usuario encontrará:

- **Todos los contenedores Docker**, que simulan una red empresarial.
- **Scripts de despliegue**, que se encargan de levantar y configurar automáticamente el laboratorio, generando flags únicas basadas en el DNI del participante.
- **Retos** de diferentes temáticas y niveles, que permitirán trabajar técnicas reales de ciberseguridad como reconocimiento, fuerza bruta, fuzzing, estenografía y escalada de privilegios, entre otros.

## Herramientas disponibles 

La máquina virtual cuenta con un conjunto de herramientas preinstaladas y configuradas, pensadas para facilitar el análisis y explotación de los retos:

- Nmap
- Hydra
- Dirb / Dirbuster
- BurpSuite + FoxyProxy
- John The Ripper
- Wireshark
- Maltego
- Steghide / Binwalk / Exiftool
- Netcat
- Python
- Docker


## Descarga de la máquina virtual

Puedes descargar la máquina virtual desde el siguiente enlace:

https://mega.nz/file/XPgghIyL#lAjm9F3-vCpP7e_CAVX-0MRHLtfETlBwMJP8o_VtcRE


## Intrucciones de uso

### Importar la máquina en VirtualBox

    1. Abrir VirtualBox
    2. Archivo → Importar servicio virtualizado
    3. Seleccionar el archivo `maquina.ova`
    4. Siguiente → Siguiente → Importar

### Desplegar el laboratorio dentro de la máquina virtual

    Iniciar sesión con las siguientes credenciales:
    
    - Usuario: intruder
    - Contraseña: intruder

    Ejecutar el siguiente comando para desplegar el laboratorio:
    sudo /home/kali/Desktop/Escenario/start_containers.sh <Tu-DNI> start
    Esto iniciará todos los contenedores y dejará listo el entorno de prácticas.

    Ejecutar el siguiente comando para parar el laboratorio:
    sudo /home/kali/Desktop/Escenario/start_containers.sh <Tu-DNI> stop

   
## Autor

- Carlos Ramírez Adarve


   


