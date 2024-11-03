# Tarea para el módulo de Python avanzado  
  
## Descripción
  
Generar un Dataset (conjunto de datos) a partir de un algoritmo que genere nombres de servidores (hostnames) “random”.
Con este Dataset el alumno debe ser capaz de generar un DataFrame de
Pandas y debe generar una serie de gráficos con Matplotlib

#### Librerías necesarias. 
   Numpy, Pandas, Mathplotlib  
  
#### Crear una función para generar los hostnames en base a unas reglas  
- La función se ha de llamar set_hostnames y debe recibir un parámetro llamado number_of_hosts de tipo int que represente el número de hosts que queremos generar.
- El hostname debe estar compuesto por un total de 8 carácteres alfanuméricos, las letras siempre mayúsculas.
- El primer caracter debe indicar el sistema operativo, siendo L para Linux, S para Solaris, A para AIX y H para HP-UX.  
  La proporción aproximada de sistemas operativos debe ser:
  - Linux: 40%
  - Solaris: 30%
  - AIX: 20%
  - HP-UX: 10%
- El segundo caracter debe indicar el entorno, siendo D para Development, I para Integration, T para Testing, S para Staging y P para Production. La proporción aproximada de entornos debe ser:
  - Development: 10%
  - Integration: 10%
  - Testing: 25%
  - Staging: 25%
  - Production: 30%
- Los tres siguientes caracteres deben indicar el país, siendo NOR para Norway, FRA para France, ITA para Italy, ESP para Spain, DEU para Germany e IRL para Ireland. La proporción aproximada de países debe ser:
  - Norway: 6%
  - France: 9%
  - Italy: 16%
  - Spain: 16%
  - Germany: 23%
  - Ireland: 30%
- Por último 3 dígitos que indiquen el número de nodo que ya existe para un mismo sistema operativo, entorno y país. El valor debe ser incremental, comenzando en 001 y con un valor máximo de 999.  
  
## Github
  
Todo el desarrollo ha sido documentado en Github: https://github.com/jbarrerobuch/Tarea-Python-Basico
