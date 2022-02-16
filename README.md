# Actividad_3_lab_metodos
Esta es la 3ra clase
Parte 1:
##clonamos un repositorio de git hub
 
$ git clone https://github.com/mariacamilamanosalva/Actividad_3_lab_metodos.git
 
$ ls

##nos metimos al repositrio

$ cd Actividad_3_lab_metodos/

 /Actividad_3_lab_metodos (main)
$ ls
README.md

##entramos y lo leimos

 /Actividad_3_lab_metodos (main)
$ less README.md

 /Actividad_3_lab_metodos (main)
$ nano README.md

##abrimos un notepad desde el terminal

 /Actividad_3_lab_metodos (main)
$ notepad

 /Actividad_3_lab_metodos (main)
$ g++ --version
bash: g++: command not found

##no encontramos g++ asi que lo tuvimos que descargar

Segunda parte:

// despues de descargar C++ comenzamos a trabajar allá
// sacamos la libreria para imprimir cosas
#include <iostream>
// el en main para usar con todos los C++ en cosas principales
int main()
//luego para llamar la libreria e imprimir algo
std::cout<<"Este es mi primer programa"<<std::endl; //similar a np.cos()
//compilacion el archivo
g++ primer_programa.cpp -o a.out
//ejecutar el archivo dinamico
./a.out
//ingrsar valores con 
cin>>s;
//tambien se puede definir variables char o sea caracteres
char carac="ejejejeje afd";
//para que no cambie la variable de un programa se le pone
const char carac= "ankjndoszbn";
// para importa un string se necesita libreria
#include <string>
std::string g="jajajajajaj";
//si nombro dos variables con la misma letra manda error porque ya esta declarada
//puedo hacer una variable igual a otra
d='a';
// el resultado fue 97 en tabla ascii
//numero binarios
int v= 0b11;
//numero hexadecimal
int w= 0xa;
