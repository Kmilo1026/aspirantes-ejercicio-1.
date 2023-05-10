1. Abrir la consola e imprimir la ubicación actual.
PS C:\Users\Cristian> pwd
2. Crear una carpeta llamada ejercicios desde la consola.
PS C:\Users\Cristian> mkdir ejercicios
3.Cambiar la ubicación a la nueva carpeta que crearon.
PS C:\Users\Cristian\desktop\node> move ejercicios c:\Users\Cristian\desktop\make_it_real\
4. Abrir la carpeta con VSCode.
PS C:\Users\Cristian\desktop\make _it_real\ejercicios> code .
5. En VSCode crear una carpeta ejercicio1.
PS C:\Users\Cristian\desktop\make _it_real\ejercicios> mkdir ejercicio1
6. Crear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1.
7. Configurar nombre e email globalmente en git.
git config --global user.name Cristian Oviedo
git config --global user.mail camilooviedo1026@gmail.com
8. Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios.
PS C:\Users\Cristian\desktop\make _it_real\ejercicios> git init
9.Crear un primer commit con el mensaje “Versión Inicial”.
PS C:\Users\Cristian\desktop\make _it_real\ejercicios> git commit -m "Versión Inicial"
Agregar al README.md los comandos que ejecutaron en cada paso.
Crear un nuevo commit con el mensaje “Agrega solución primer ejercicio”
