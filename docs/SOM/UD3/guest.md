## Cómo instalar las guest additions en Ubuntu
1. Dispositivos > Instalar CD de las guest additions
2. Entra al contenido del CD desde el explorador de archivos y cópialo todo
3. Vete al escritorio, carpeta nueva, llámala ad
4. Entra y pega todo
5. En el escritorio click derecho y abrir en terminal
6. `sudo chmod 777 ad/*`
7. cd ad
8. sudo ./VBoxLinuxAdditions.run
9. sudo apt install gcc -y

> El último paso del proceso es experimental, a veces funciona y a veces rompe el arranque. Si quieres puedes intercambiar el orden de los 2 últimos pasos