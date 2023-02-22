## Definición
Los drivers son un componente de software que se encarga de comunicar periféricos con el sistema operativo, de manera que 

## Crear MV en ProxMox
1. Click a `Create VM`
2. Elegir tu pool, poner una ID que concuerde con tu rango y un nombre
3. Elegir la ISO y cambiar el tipo de sistema si fuera necesario
4. Sistema
    - Tarjeta gráfica: SPICE
    - Qemu Agent: $\checkmark$
5. Disco Duro
    - Caché: Write back
    - Descartar: $\checkmark$
6. CPU
    - Tipo: host
7. Red
    - puente: vmbr199

