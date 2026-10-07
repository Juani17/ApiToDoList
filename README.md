# API ToDo — Variante académica

Variante de un ejercicio de tareas, sprints y backlog con Node.js, Express y Mongoose. Se conserva como referencia histórica; para el portfolio se prioriza [ProyectoToDoList](https://github.com/Juani17/ProyectoToDoList).

El código de ambas variantes difiere y no fue fusionado. Esta versión utiliza rutas `/api/tasks`, `/api/sprints` y `/api/backlog` y variables `MONGO_URI` y `PORT`.

Limitaciones de la implementación original: los scripts de inicio apuntan a `src/app.js`, aunque `app.js` está en la raíz; `models/Sprint.js` no exporta el modelo, y la asociación de tareas a sprints utiliza un nombre de campo diferente al esquema. Estas limitaciones requieren cambios de código y se mantienen documentadas.
