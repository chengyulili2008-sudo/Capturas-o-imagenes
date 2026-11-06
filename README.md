# Práctica de React, Git y Three.js

Proyecto desarrollado con React y Vite que incluye una escena 3D interactiva de fondo, integración de efectos con confetti y gestión de ramas en Git.

---

## 📸 Capturas de pantalla

### 1. Escena 3D de fondo
![Escena 3D](capturas/hola.png)

### 2. Efecto Confetti
![Confetti](capturas/confetti.png)

### 3. Vista General
![Vista General](capturas/general.png)


Pregunta 

**Si la carpeta `node_modules/` está excluida, ¿borrar una dependencia hace alguna acción sobre el repositorio? ¿Cuál?**

** Sí. Aunque la carpeta `node_modules/` no se incluye en el repositorio (gracias al archivo `.gitignore`), al ejecutar `npm uninstall <nombre>` se modifican los archivos **`package.json`** y **`package-lock.json`**. 

