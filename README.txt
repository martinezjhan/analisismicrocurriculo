RECURSO INTERACTIVO — ANÁLISIS DE OPORTUNIDADES DEL MICROCURRÍCULO · V2

Esta versión conserva exactamente 10 diapositivas y la interactividad de la versión anterior, pero:
- hace más explícitos los RESULTADOS DEL ANÁLISIS;
- presenta por separado las FORTALEZAS identificadas y las OPORTUNIDADES DE MEJORA;
- distingue los hallazgos del material de las estrategias propuestas para exploración;
- sustituye las intervenciones audiovisuales por espacios de AUDIO del expositor;
- intenta reproducir automáticamente el audio de la diapositiva al entrar en ella.

CÓMO AGREGAR TUS AUDIOS
En index.html encontrarás varias etiquetas:
<audio class="slide-audio" data-slide-audio controls preload="auto" playsinline></audio>

Solo agrega el atributo src, por ejemplo:
<audio class="slide-audio" data-slide-audio controls preload="auto" playsinline src="audio/01-apertura.mp3"></audio>

Puedes guardar los MP3 en una carpeta audio junto a index.html. No necesitas modificar script.js.

IMPORTANTE SOBRE AUTOPLAY
El navegador puede bloquear la reproducción automática con sonido en la primera carga por sus políticas de autoplay. El recurso intenta reproducir el audio al entrar a cada diapositiva y vuelve a intentarlo después de la primera interacción del usuario. Una vez que el usuario ha interactuado, la navegación normalmente permite que los audios se reproduzcan automáticamente.

GUIONES
Cada espacio de audio contiene un <details> con un guion sugerido. El texto está basado en el material proporcionado para el análisis. Las estrategias de la diapositiva 9 se presentan explícitamente como propuestas de exploración, no como resultados observados.

IDENTIDAD
Se conserva la línea visual académica de la versión anterior, con Open Sans y colores institucionales de referencia. El círculo UNAB del encabezado continúa siendo un marcador editable; para distribución institucional debe sustituirse por el recurso oficial autorizado.

ARCHIVOS
- index.html
- styles.css
- script.js
- microcurriculo_plan.png
- microcurriculo_panel.png
- README.txt
