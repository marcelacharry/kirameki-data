# Kirameki data

Datos públicos que la app Kirameki descarga para actualizarse sin sacar versión nueva.

- `jp-images/official_jp_images.tsv`: foto oficial (pokemon-card.com) de cada carta japonesa que TCGdex no tiene. La app solo la usa cuando TCGdex no da foto.
- `jp-images/version.json`: versión y sha256 de la lista; la app lo consulta una vez al día.
- `state/`: lo que mostró pokemon-card.com la última vez, para que cada corrida solo lea fichas nuevas.

Se actualiza cada semana desde el repo de la app (workflow `jp-images.yml`). No editar a mano.
Las imágenes son © Pokémon / Nintendo / Creatures / GAME FREAK; aquí solo están sus direcciones.
