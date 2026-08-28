# 12. Preguntas de reflexión

Responder individualmente al finalizar.

### 1. ¿Cuál es la diferencia entre `git add` y `git commit`?
la diferencia radica en que el git add añade el o los archivos a un estado intermedio llamado staged y el commit lo que hace es pasar del staging area al repositorio local
---

### 2. ¿Cuál es la diferencia entre `git push` y `git pull`?
la diferencia es que git pull lo que hace es traer todas las actualizaciones del repositorio remoto y unirlas con el repositorio local (fetch+merge) en cambio el push lo que hace es subir los cambios del repositorio local al repositorio remoto
---

### 3. ¿Cuál es la diferencia entre un repositorio local y uno remoto?
en la logica ambos cumplen la funcion de ser un historial de cambio y la diferencia radica en que uno se maneja de manera local y el otro en la nube
---

### 4. ¿Qué problema resuelve una rama?
el principal error que solucionan es que una nueva implementacion vaya a romper todo el proyecto y se utilizan mayoritariamente para hacer pruebas a base de la rama central o principal (main/master), ademas permite que varias personas se encarguen de distintas tareas en paralelo 

---

### 5. ¿Qué diferencia existe entre `git merge` y `git rebase`?
la diferencia radica en que el merge une las dos ramas pero mantiene la rama en cambio el rebase une las dos ramas y no genera ningun commit provocando un flujo mas limpio y ordenado 
---

### 6. ¿Por qué ocurre un conflicto? 

--- Los conflictos se originan al intentar sincronizar los cambios realizados sobre una misma parte de un archivo. Al existir dos historias diferentes, se debe resolver cuál será la versión definitiva para resolver el conflicto.

### 7. ¿Quién debe decidir cómo resolver un conflicto?

--- Se debe resolver en equipo, ya sea de las partes implicadas o con ayuda o apreciación de un tercero. Nunca se debe ser de manera individual para evitar confusiones entre los desarrolladores.

### 8. ¿Qué problema resuelve un Pull Request?

--- Resuelve los problemas que pueden generar los cambios que son subidos directamente al código principal sin supervisión. Esto evita que se introduzcan errores o que los nuevos cambios rompan la aplicación.

### 9. ¿Por qué es recomendable revisar un Pull Request antes de integrarlo?

--- Esto ayuda a detectar errores antes de que ocurran, asegura que los objetivos que se quieran sean cumplidos, evita la introducción de vulnerabilidades y mantiene la consistencia del código.

### 10. ¿Qué ventaja tiene trabajar en una rama en lugar de modificar directamente `main`?

--- El main, al ser el código que está en funcionamiento y en constante uso, puede verse afectado a la hora de implementar nuevos cambios por errores. Esto puede causar que la aplicación falle, afectando a sus usuarios. Por eso, es mejor hacer las modificaciones en un ambiente seguro que no afecte el funcionamiento correcto de la aplicación
