# aspirantes-mir-ejercicio-1
1. Comando para abrir consola e imprirmir la ubicación actual: 
   PS C:\Users\pc> pwd
2. Comando para crear carpeta desde la consola:
   PS C:\Users\pc> mkdir ejercicios
3. Comando para cambiar la ubicación a la nueva carpeta:
   PS C:\Users\pc> cd ejercicios
   PS C:\Users\pc\ejercicios> cd /Users/pc/Desktop
4. Comando para abrir carpeta con VSCode:
   PS C:\Users\pc\ejercicios> code .
  
6. Comando para configurar nombre e email globalmente en git 
   pc@DESKTOP-PN9O9DN MINGW64 ~ (master)
    $ git config --global user.name Giselle
    $ git config --global user.email giselledc1394@gmail.com
7. Comando para crear el repositorio de git desde la liea de comandos desde la carpeta ejercicios: 
   pc@DESKTOP-PN9O9DN MINGW64 ~ (master)
   $ git init
   Reinitialized existing Git repository in C:/Users/pc/.git/

8. Comando para crear un primer commit: 
   pc@DESKTOP-PN9O9DN MINGW64 ~/ejercicios (master)
   $ git add .
   $ git commit -m 'Versiòn Inicial'
   [master (root-commit) a030e32] Versiòn Inicial
   1 file changed, 0 insertions(+), 0 deletions(-)
    create mode 100644 README.md
