1)¿Qué hacen los siguientes comandos?
### 1. `pwd`
Muestra el directorio actual en el que te encuentras.

### 2. `ls`
Lista los archivos y carpetas del directorio actual.

### 3. `cd [directorio]`
Cambia al directorio especificado.

### 4. `mkdir [nombre]`
Crea un nuevo directorio con el nombre especificado.

### 5. `touch [nombre_de_archivo]`
Crea un archivo vacío o actualiza su fecha de modificación si ya existe.

---

2)¿Puedes explicar qué sucede en el siguiente escenario si ingresas estos comandos y argumentos en la línea de comandos? (Los argumentos son instrucciones adicionales dadas a un comando).
cd projects
mkdir new-project
touch new-project/newfile.md
cd ..
ls projects/new-project

1. `cd projects`  
   - Entra en la carpeta `projects`.

2. `mkdir new-project`  
   - Crea una carpeta llamada `new-project` dentro de `projects`.

3. `touch new-project/newfile.md`  
   - Crea un archivo vacío llamado `newfile.md` dentro de `new-project`.

4. `cd ..`  
   - Regresa al directorio padre (uno nivel arriba).

5. `ls projects/new-project`  
   - Lista los archivos dentro de `projects/new-project`, mostrando `newfile.md`.

---

3)¿Qué comando usarías en la terminal para listar todos los archivos, incluidos los archivos ocultos, en un directorio de Linux o macOS? Explica qué significan los parámetros utilizados en el comando.

### Comando:
```sh
ls -la
