# Mesa de Parejas · contenido nuevo

La app **Mesa de Parejas** descarga este archivo (`contenido.json`) como mucho una vez cada 6 horas
y añade su contenido al juego. No hace falta publicar una versión nueva de la app.

Cada lunes, una tarea automática añade aquí refranes, objetos y curiosidades nuevos.

## Formato

- `refranes`: por país (`es`, `mx`, `co`, `ar`, `cl`, `en`, `br`, `it`, `fr`, `de`, `nl`, `pl`).
  Cada refrán es `["principio", "final", "significado"]`.
- `objetos`: `["emoji", "categoría", "es", "en", "pt", "it", "fr", "de", "nl", "pl"]`.
  Categorías válidas: `fruta`, `animal`, `cocina`, `ropa`, `transporte`, `musica`.
- `curiosidades`: por idioma (`es`, `en`, `pt`, `it`, `fr`, `de`, `nl`, `pl`), una frase cada una.

La app descarta cualquier entrada mal formada, repetida o con los signos `<` o `>`.
Este repositorio es público: no guardes aquí nada privado.
