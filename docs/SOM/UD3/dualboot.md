# Pasito a pasito para hacer una máquina con DualBoot

## Windows y Ubuntu
### Configuraciones iniciales
1. ISO: Windows_20-04.iso
2. Pasos intermedios para [el resto de máquinas](???)
3. Hardware > BIOS: OVMF (UEFI)
4. Agregar > Disco EFI
5. Desde "Opciones", ajustar el orden de arranque de manera que la iso de Windows esté primero
6. Encender

En este arranque, la idea es ir rápido a la pantalla de la máquina, preferiblemente desde SPICE, y pulsar cualquier tecla. De todas formas, se mostrará una terminal en la que, ingresando `exit`, entraremos a la BIOS, desde la cual puedes darle a "continue" y volver al principio. Aporreando el teclado llegaremos al instalador de Windows sin problema.

Aparte del proceso normal de [instalación para Windows](/docs/SOM/UD3/3.%20Primera%20instalaci%C3%B3n.md), en vez de ocupar todo el disco, haz una partición manualmente de manera que quede espacio sin asignar para Ubuntu. Una vez terminada la instalación, reiniciar para asegurarse de que todo ha salido bien.

Cosillas destacables de la instalación de Ubuntu: 
- Ten cuidado con las particiones de Windows y/o desconocidas, **no las toques**, por muy desconocidas que parezcan es evidente que son canalizadores de magia negra de Windows
- No hagas una partición EFI de Ubuntu, la de Windows hace todo el trabajo necesario