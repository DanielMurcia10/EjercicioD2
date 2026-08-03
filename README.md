# EjercicioD2

COMANDOS QUE SE USARON DURANTE LA PRACTICA:

cd .. Desktop/ -- para trabajar en el escritorio
mkdir Practica/ -- creamos la carpeta en donde se iba a trabajar 
ls -- para ver todos los archivos del escritorio y verficar si fue creada nuestra carpeta Practica
cd Practica -- accedemos a la carpeta 
mkdir practica01, practica02 y practica 03 dentro de nuestra carpeta practica 
cd practica 01 para trabajar y crear archivos de texto en esta carpeta 
nano Prueba.txt, nano Archivo.txt, nano Ensayo.txt -- creamos nuestros archivos de texto
cd .. para salirnos de la carpeta practica01
cd practica 02 para trabajar y crear archivos de texto en esta carpeta 
nano Prueba.cpp, nano Archivo.cpp, nano Ensayo.cpp -- creamos nuestros archivos de texto
cd .. para salirnos de la carpeta practica02
cd practica 03 para trabajar y crear archivos de texto en esta carpeta 
nano Prueba.py, nano Archivo.py, nano Ensayo.py -- creamos nuestros archivos de texto
cd .. para salirnos de la carpeta practica03
cd .. para regresar a Desktop y despues cd .. otra vez para salirnos de Desktop
ya que no estamos en ninguna carpeta, en la terminal instalamos la extension necesaria para generar nuestro arbol de carpetas 
"brew install tree" para instalar
una vez instalada, regresamos a Prueba cd Desktop/Practica
ya en la carpeta escribimos en la terminal tree > inventario.txt
y para observar como quedo nuestro arbol de carpetas, escribimos en la terminal cat inventario.txt
nos regresamos a Desktop y creamos la carpeta mkdir Respaldo/
despues ejecutamos la siguiente linea: cp -r Practica/ Respaldo/ para copiar tambien las subcarpetas
cd Respaldo/ y ls para verificar si esta todo
y por ultimo eliminamos la carpeta original usando rm -r Practica/



