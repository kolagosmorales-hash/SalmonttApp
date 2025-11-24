Semana 5: Organización modular y creación de una librería personalizada
Proyecto SalmonttApp 

Descripción del Proyecto 
SalmonttApp es una aplicacion desarrollada en Java que permite cargar, gestionar y consultar información de centros de cultivos de una empresa salmonera.
el objetivo de este proyecto es:
- organizacion modular del codigo 
- uso de colecciones (ArrayList)
- lectura de datos desde archivos externos (.txt)
- validación basica y filtro de busqueda 
- empaquetamiento y buenas practicas de programacion 
El sistema carga centros de cultivos desde un archivo de texto y permite consultarlos mediante filtros como localidad o estado operativos.

Paquetes y clases Implementadas 
1. Paquete model 
CentroCultivo: representa un centro cultivo con atributo getters, setters y metodo toString 
2. Paquete service 
Contiene la logica del sistema y manejo de datos 
CentroService: 
- Carga datos desde el archivo .txt
- Maneja la coleccion de centros 
- Implementa filtros, busqueda y validacion 
3. app
Contiene la clase principal 
Main: 
- Inicia el sistema
- Llama a los metodos de carga y consulta 
- Muestra resultado por consola 

Estructura del Poyecto 
src/
├──app/
    |__ Main.java
├── model/
    |__ CentroCultivo.java
├── service/
    |__ CentroService

data
|__ centro.txt 

Ejecucion del programa 

1. clonar el reprositorio: https://github.com/kolagosmorales-hash/SalmonttApp/blob/81a7ae49f51f75a13ebf0a7ddce6c36b7c2fd75f/SalmonttApp.zip
2. abrir el archivo 
3. verificar que el archivo data/centro.txt exista dentro del proyecto 
4. ejecutar la clase principal: src/app/Main.java
5. El sitema mostrara por consola 
 - lista de todos los centros
 - resultado de la busqueda por localidad 
 - centros filtrados por estado

Konny Lagos 
Asignatura: Desarrollo Orientado a Objeto 1
