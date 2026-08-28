# 12. Preguntas de reflexión

Responder individualmente al finalizar.

### 1. ¿Cuál es la diferencia entre `git add` y `git commit`?

--- 

### 2. ¿Cuál es la diferencia entre `git push` y `git pull`?

--- 

### 3. ¿Cuál es la diferencia entre un repositorio local y uno remoto?

---

### 4. ¿Qué problema resuelve una rama?

---

### 5. ¿Qué diferencia existe entre `git merge` y `git rebase`?

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