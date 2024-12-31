# 4GEEKS_CLASS

"RECETA para Preparar Codespace"

1. Ir a Extenciones, e instalar python y jupyter

2. Creamos nuestro entorno virtual llamado "venv" y lo activamos. 
   Aegurandonos que quedo activado al ver que en la terminal la linea de comandos comienza con "(.venv)"
    ```Comandos:
        python -m vent .venv
        source .venv/bin/activate

3. Crear el archivo gitignore con
    ```Comandos:
        touch .gitignore

4. editamos el archivo gitignore, agregando estas dos lineas en el archivo
   ```Codigo:
        .venv
        .env

5. Hacemos commit en la rama main, solo del archivo gitignore
   ```Comandos:
        git add .gitignore
        git commit -m "Add gitignore"
        git push

6. Instalamos los paquetes que necesitaremos de python
   ```Comandos:
        python -m pip install ipykernel nbformat  pandas seaborn scikit-learn
