# Docente digital · Profesorado de Agronomía (General San Martín, Chaco)

Página con un humano digital (agente de voz de ElevenLabs) que explica cómo es la carrera y responde preguntas, en primera persona y con voseo. Público: estudiantes de nivel terciario.

## Archivos
- `index.html`: la página (un solo archivo) con el widget del agente.
- `docente.jpg`: imagen de referencia del personaje.

## Publicar en GitHub Pages
1. Creá un repositorio nuevo en GitHub y subí `index.html` y `docente.jpg` a la raíz.
2. En **Settings → Pages**, elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. Esperá un minuto: la página queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Agente de ElevenLabs
- Agent ID: `agent_6101m5dhyt1eedb8m34jat3qam83` (ya cargado en `index.html`).
- Para que funcione en público, en ElevenLabs → Agente → **Security**, desactivá la autenticación y agregá tu dominio `TU-USUARIO.github.io` en la lista de dominios permitidos.
- Idioma: español. Voz: la predeterminada de ElevenLabs; podés cambiarla en la pestaña **Voice** del agente.

## Base de conocimiento: qué está documentado y qué es atribuido
| Dato | Estado |
|---|---|
| Res. 1978/2021 (régimen de correlatividades), Res. 276/2017 (diseño curricular), Res. 6299/2017 (plan de estudios) | Documentado |
| Duración de 4 años, modalidad presencial, nivel terciario, ubicación en General San Martín | Atribuido (lo informó el equipo del proyecto) |
| Prácticas de 1.º a 4.º año (organizaciones, EFA, pre-residencia, residencia) | Atribuido |
| Ingreso, fechas, costos, horarios, contacto, nombres de docentes, listado de materias | No disponible: el agente deriva a la institución |

El agente dice «según me contaron» cuando usa un dato atribuido y no inventa lo que no está en la base.
