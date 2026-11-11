# 100 DÍAS — CrossFit en casa (v3.1.1)

Aplicación web progresiva (PWA), minimalista en blanco y negro, para seguir un programa de CrossFit en casa de 100 días.

## Qué incluye

- Programa estructurado en cinco fases: adaptación (1–20), construcción de base (21–45), intensidad (46–70), pico de rendimiento (71–90) y consolidación/test (91–100).
- Primeros 20 días desarrollados individualmente, con calentamiento, fuerza/técnica, bloque metabólico y core/finalizador. El detalle también está en `PROGRAMA_100_DIAS.md`.
- Calendario completo de 100 días. Se programa un día de recuperación cada siete; los días 21–100 quedan preparados por fase para completar su programación en la siguiente entrega. Los días 95 y 100 aparecen reservados para los tests.
- Pantalla inicial a pantalla completa con el mensaje “EMPEZAMOS?”; se accede a la app deslizando hacia arriba.
- Navegación por páginas independientes: Inicio, Sesión, Calendario y Progreso.
- Registro sencillo: cada ejercicio indica claramente “N series de X repeticiones”; cada fila corresponde a una única serie.
- Historial de cargas y repeticiones.
- Temporizador de descanso ajustable.
- Estadísticas de sesiones completadas y avance por fase.
- Exportación y restauración de copias JSON.
- Guardado local en el navegador, sin cuenta ni servidor.
- PWA instalable y caché offline. No depende de CDN ni de conexión externa para mostrar estilos o lógica.

## Navegación

- **Inicio:** resumen del día y acceso a la sesión.
- **Sesión:** ejercicios, registro de series, temporizador y notas.
- **Calendario:** selección de día y fases.
- **Progreso:** estadísticas, historial y copias de seguridad.

## Publicar en GitHub Pages

1. Descomprime el ZIP.
2. Sube el contenido de la carpeta `TRAINING-main` a la raíz de un repositorio de GitHub (no es necesario subir la carpeta contenedora).
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, rama `main` y carpeta `/(root)`.
5. Guarda y abre la URL publicada por GitHub Pages.

## Instalar en móvil

- iPhone: abre la web en Safari → Compartir → Añadir a pantalla de inicio.
- Android: abre la web en Chrome → menú → Instalar aplicación / Añadir a pantalla de inicio.

## Datos y privacidad

Los datos se guardan en `localStorage` del navegador y dispositivo actual. No se sincronizan entre dispositivos. Exporta una copia periódicamente desde **Progreso → Copia de seguridad**. La restauración sustituye los datos actuales, previa confirmación.

La versión anterior (`fullbody-home-100-v1`) no se borra del almacenamiento del navegador. La nueva versión utiliza una clave independiente para no sobrescribir registros antiguos.

## Contenido del programa

Los primeros 20 días están completos. Las fases 2–5 están reflejadas en el calendario y en la estructura, pero sus sesiones día por día aún no se han desarrollado. Se mantiene esa distinción para no presentar sesiones futuras como si ya estuvieran definidas.
