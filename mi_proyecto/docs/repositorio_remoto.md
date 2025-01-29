# Creación y Sincronización de un Repositorio Remoto en GitHub

## 1. Crear un Repositorio en GitHub
1. Inicia sesión en [GitHub](https://github.com/).
2. Haz clic en el botón **New repository**.
3. Especifica un nombre para el repositorio y elige su visibilidad (público o privado).
4. No inicialices con un README, ya que lo configuraremos desde la terminal.
5. Haz clic en **Create repository**.

## 2. Vincular el Repositorio Remoto con el Repositorio Local
Si ya tienes un repositorio local, sigue estos pasos para conectarlo con GitHub:

1. **Abre la terminal y navega al repositorio local:**
   ```sh
   cd /ruta/al/repositorio
   ```
2. **Añade el repositorio remoto:**
   ```sh
   git remote add origin https://github.com/usuario/nombre-repositorio.git
   ```
   Reemplaza `usuario` y `nombre-repositorio` con tu nombre de usuario y el nombre de tu repositorio en GitHub.

3. **Verifica que el remoto se agregó correctamente:**
   ```sh
   git remote -v
   ```

## 3. Subir el Código al Repositorio Remoto
Si el repositorio local ya tiene archivos y commits, puedes subirlos a GitHub con:

1. **Asegurar que la rama principal se llama `main` o `master`**
   ```sh
   git branch -M main
   ```
2. **Subir los cambios al repositorio remoto:**
   ```sh
   git push -u origin main
   ```

## 4. Clonar un Repositorio Remoto
Si deseas descargar un repositorio existente en GitHub a tu computadora, usa:
```sh
git clone https://github.com/usuario/nombre-repositorio.git
```
Esto crea una copia local del repositorio para que puedas trabajar en él.

Siguiendo estos pasos, puedes administrar y sincronizar tus proyectos entre un repositorio local y GitHub de manera eficiente.
