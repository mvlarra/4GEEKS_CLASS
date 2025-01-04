# README

La primer linea de un readme siempre es # Readme por convencion. 

En el archivo readme, se escribe utilizando markdown, que no habilita a usar texto, formulas, tablas, etc. Por eso termina en md.

El # significa titulo. El ## Subtiluto. Y asi en adelante.

## RECETA para Preparar Codespace

1. Ir a Extenciones, e instalar python y jupyter

2. Creamos nuestro entorno virtual llamado "venv" y lo activamos. 
   Aegurandonos que quedo activado al ver que en la terminal la linea de comandos comienza con "(.venv)"
```bash
        python -m vent .venv
        source .venv/bin/activate
```

3. Crear el archivo gitignore con agregando estas dos lineas en el archivo
```bash
        echo -e ".venv\n.env" > gitignore
```     

4. Instalamos los paquetes que necesitaremos de python
```bash
        python -m pip install ipykernel nbformat  pandas seaborn scikit-learn
```

5. Crear Carpetas de Trabajo
```bash
        mkdir notebooks src app docs
        mkdir -p data/{raw,baking,final}
```

6. Editar un archivo
```bash
        touch mitexto.txt
        manomitexto.txt
```

7. Agregamos todas las carpetas

```bash
        git add app data docs notebooks src      
```     
        
8. Hacemos commit en la rama main, solo del archivo gitignore        
        
        git add .gitignore
        git commit -m "Add gitignore"
        git push



x. con "ls" que viene a significar lista, listo todos los archivos y carpetas que hay en mi directorio. Las carpetas las pinta de verde.
x. con "ls -a" (a de all) tambien habilito a listar los archivos ocultos.
x. con "pwd" imprimo el directorio de trabajo actual, o sea, donde estoy parado. pwd = print working directory
x. con "cat" vemos el arvhivo readme en la terminal.
x. con "clear" borra lineas del terminal
x. con "touch name" para crear un archivo.
x. con "echo texto" imprimo texto en la terminal
x. con "echo ... > ..." agrega el texto de la izquierda en el archivod de la derecha
x. añadir mas texto: "echo ... >> ..." agrega el texto de la izquierda al file de la derecha. 
x. para agregar texto con salto de linea"echo -e "Linea1\nLinea2"
x. es util usar echo para generar el archivo gitignore echo -e ".venv\n.env" > gitignore
x. git branch para saber la rama donde estoy parado.
x. git checkout nos sirve para movernos de rama en rama. Con el -b creo esa rama y me muevo para alli

x. rm -rf nombre de la carpeta borra la carpeta
x. mkdir -p (make directory) p = parents  para crear carpeta y subdirectorios data/{raw,baking,final}

git status para ver que esta sin commit


HOY VAMOS A CREAR NUESTRO VADEMECUM, COMMITEARLO Y TRABAJARLO.

``` backtick se llama este simbolo que sirve para poner un bloque de codigo. 
le ponemos bash para indicar que el codigo que estamos escribiendo es bash.


