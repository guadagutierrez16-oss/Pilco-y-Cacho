# Pilco y Cacho en el Bañado La Estrella

Escena 3D de un solo archivo (`index.html`): Cacho, guía turístico, y Pilco, el carpincho,
conversan de pie en el Bañado La Estrella, Formosa, en un día soleado.

## Para que las voces suenen igual en todos los dispositivos

La página reproduce los audios de la carpeta `audio/` si existen. Si faltan, usa la voz
del navegador (que cambia según el dispositivo).

Los 8 audios ya están generados con la voz de tus agentes (Eric, ElevenLabs) en este flujo:
https://elevenlabs.io/app/flows/az35fpU8kpqMRVhNsATl

1. Abrí el flujo, descargá cada audio en mp3 y renombralo con el número de la tabla.
2. Guardalos en la carpeta `audio/` junto a `index.html`.
3. Subí todo a GitHub y activá GitHub Pages (Settings → Pages → rama `main`, carpeta `/root`).

| Archivo | Quién | Dice |
| --- | --- | --- |
| 01.mp3 | Cacho | ¡Mirá quién anda por acá! Pilco, qué día lindo nos tocó en el Bañado La Estrella. |
| 02.mp3 | Pilco | ¡Hola, Cacho! Con este solcito, el agua está tibia y el pasto bien fresquito. Un día perfecto para un carpincho. |
| 03.mp3 | Cacho | Fijate esos palos secos que salen del agua. Los visitantes siempre me preguntan por ellos, y vos que vivís acá lo sabés mejor que yo. |
| 04.mp3 | Pilco | Son troncos de palmeras que quedaron parados en el agua del bañado. Muchas aves los usan de posadero para descansar y mirar el agua. |
| 05.mp3 | Cacho | Eso mismo les cuento yo: ir despacito, mirar de lejos y no dejar basura. |
| 06.mp3 | Pilco | ¡Eso es! Los carpinchos vivimos en grupo cerca del agua y nos gusta la tranquilidad. Cuidar el bañado es cuidar nuestra casa. |
| 07.mp3 | Cacho | Mirá vos, qué bien lo explicás. ¿Seguimos el recorrido antes de que se haga tarde? |
| 08.mp3 | Pilco | Dale, Cacho. Y si alguien quiere saber más, nos pregunta a los dos. |

La boca de cada personaje se mueve según el volumen real del audio.

## Notas
- Probala desde la dirección de GitHub Pages. Abierta como archivo local (`file://`) el navegador bloquea la lectura de los audios.
- Tipografías: se cargan de Google Fonts; sin internet se usa una de sistema.
- Los agentes Pilco y Cacho de ElevenLabs usan la misma voz (Eric). Si querés que suenen distinto, cambiá la voz de uno y regeneramos sus líneas.
