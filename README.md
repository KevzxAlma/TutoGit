# Guía de uso de Git y GitHub

# Pasos iniciales con Git

# 1. Crear carpeta para el proyecto
# Crea una nueva carpeta para tu proyecto.

# 2. Inicializar Git en la carpeta
git init

# 3. Realizar cambios y preparar archivos para el commit
# Después de hacer modificaciones en tus archivos, agrega todos los archivos modificados.
git add .

# O si solo deseas agregar un archivo específico:
git add <nombre_del_archivo>

# 4. Hacer un commit con mensaje descriptivo
git commit -m "mensaje de commit"

# 5. Establecer la rama principal como `main`
git branch -M main

# 6. Conectar tu repositorio local con el repositorio remoto en GitHub
git remote add origin https://github.com/KevzxAlma/asd.git

# 7. Subir tus cambios a GitHub
git push -u origin main

# Después de realizar estos pasos iniciales, solo necesitarás usar `git commit` y `git push` para subir cambios.

# Trabajar con ramas

# 1. Crear una nueva rama
# Para crear una nueva rama:
git branch <nombre_de_la_rama>

# 2. Cambiar a la nueva rama
# Para cambiar a una rama ya creada:
git checkout <nombre_de_la_rama>

# 3. Crear y cambiar a una nueva rama en un solo paso
git checkout -b <nombre_de_la_rama>

# 4. Ver las ramas disponibles
git branch

# 5. Eliminar una rama
# Para eliminar una rama localmente:
git branch -d <nombre_de_la_rama>

# 6. Enlazar una rama a un repositorio remoto
# Si has creado una nueva rama y necesitas enlazarla a tu repositorio remoto, utiliza:
git push -u origin <nombre_de_la_rama>

# Colaboración con Pull Requests

# Pull Requests (PR): Es una forma de colaborar en proyectos de otros o de enviar cambios a tu propio proyecto.
# Un PR permite que otros revisen y aprueben tus cambios antes de que se integren a la rama principal.

# Clonar un repositorio y obtener los últimos cambios

# 1. Clonar un repositorio existente
git clone <URL_del_repositorio>

# 2. Obtener los últimos cambios de un repositorio remoto
git pull

# Resumen de Comandos Básicos

# Iniciar un repositorio
git init

# Agregar archivos
git add . o git add <archivo>

# Realizar un commit
git commit -m "mensaje"

# Ver ramas
git branch

# Cambiar de rama
git checkout <rama>

# Crear y cambiar a nueva rama
git checkout -b <rama>

# Eliminar una rama
git branch -d <rama>

# Subir cambios
git push -u origin <rama>

# Clonar un repositorio
git clone <URL>

# Obtener cambios del repositorio remoto
git pull

# ¡Feliz codificación!
