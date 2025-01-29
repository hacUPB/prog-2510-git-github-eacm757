# Creación de un Repositorio Local con Git

Git es un sistema de control de versiones distribuido que permite gestionar cambios en el código fuente de un proyecto. A continuación, se describen los pasos para crear un repositorio local con Git.

## 1. Inicializar un Repositorio Local
Para crear un nuevo repositorio en un directorio local, utiliza el siguiente comando:
```sh
mkdir mi_proyecto  # Crear un nuevo directorio
cd mi_proyecto     # Acceder al directorio
git init           # Inicializar el repositorio Git
```
Esto creará un nuevo repositorio Git en la carpeta actual.

## 2. Agregar Archivos al Repositorio
Después de crear o modificar archivos, es necesario agregarlos al área de preparación (staging area) con el siguiente comando:
```sh
git add archivo.txt  # Agregar un archivo específico
git add .           # Agregar todos los archivos del directorio
```

## 3. Confirmar los Cambios (Commit)
Para guardar los cambios en el historial del repositorio, usa:
```sh
git commit -m "Mensaje descriptivo del cambio"
```

## 4. Ver el Estado del Repositorio
Para conocer el estado actual del repositorio, usa:
```sh
git status
```

## 5. Ver el Historial de Cambios
Para listar los commits realizados, usa:
```sh
git log
```

Siguiendo estos pasos, puedes gestionar tu código de manera eficiente con Git en un repositorio local.


