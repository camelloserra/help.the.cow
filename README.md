# HELP THE COW 🐄🛸

Juego arcade pixelado estilo años 80. Un OVNI quiere abducir a la vaca y vos tenés que hacer click lo más rápido posible para que no se la lleve.

## Cómo se juega

- **Click**, **toque** o **ESPACIO**: cada uno baja un poquito a la vaca del rayo. Mantener apretado no cuenta.
- Aguantá **60 segundos** sin que la vaca llegue al OVNI.
- **¡RAYO TURBO!**: tres veces por partida el rayo se pone rosa y tira más fuerte. Las luces del OVNI titilan en rojo justo antes.
- **Vaquitas bonus**: dos veces por partida aparece una vaquita flotando en el rayo, más arriba que la vaca. Si te dejás subir un poco, la vaca la alcanza y la lleva en el lomo. Después hay que bajarla hasta el pasto: **+1500 puntos**. Mientras la llevás, cada click baja un poco menos. Si tardás mucho, el OVNI se la lleva.
- **Segundo OVNI**: en el segundo 44 llega otro OVNI y la abducción se acelera hasta el final.
- Ganar suma **+3000** de bonus. El récord queda guardado en el navegador.
- **M** activa o desactiva el sonido.

Rangos según los clicks por segundo: Granjero Novato → Peón Bravo → Gaucho Galáctico → Leyenda del Campo.

## Jugar en tu compu

Abrí `index.html` con cualquier navegador. No hace falta instalar nada: está todo en un solo archivo, y solo descarga la tipografía *Press Start 2P* de Google Fonts (sin internet usa otra tipografía).

## Publicarlo con GitHub Pages

1. Creá un repositorio nuevo en GitHub (por ejemplo `help-the-cow`).
2. Subí `index.html` y este `README.md` (**Add file → Upload files**).
3. Andá a **Settings → Pages**, elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guardá.
4. En uno o dos minutos el juego va a estar en `https://TU-USUARIO.github.io/help-the-cow/`.

## Tecnología

HTML + JavaScript puro, sin dependencias. Todo se dibuja a mano en un canvas de 192×144 píxeles escalado, y los sonidos chiptune se generan en el momento con la Web Audio API.
