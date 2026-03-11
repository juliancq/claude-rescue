# Claude Sessions Viewer

Aplicación web (HTML/JS/CSS) para explorar y gestionar sesiones guardadas de Claude Code.

## Uso
Abrir `claude-sessions.html` en Chrome o Edge y seleccionar la carpeta `.claude/projects`.

## Funcionalidades
- Lista todas las sesiones con proyecto, alias, session ID, primer mensaje, cantidad de mensajes, fecha y edad
- Filtro por directorio y búsqueda por texto
- Ordenamiento por cualquier columna
- Click en una fila muestra el detalle de la conversación
- Alias editables por sesión, persistidos en `session-aliases.json`
- Botón para copiar el comando `cd "..." ; claude --resume <session-id>`
