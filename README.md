# test

Repositorio del mod de Sonny 2.

- `TRASPASO.md`: resumen para retomar el trabajo (lo último hecho, cómo compilar y probar, pendientes).
- `estado-mod-sonny.md`: estado del proyecto.
- `i26/`: rework del lobo (propuesta v4 «Mokoshotar: sangre y escarcha»), con su `LEEME.md` y `fuente/` (código propio del mod: capa `rw_*.as`, `build.py`, pruebas y guiones de Ruffle).
- `i27/`: el árbol del lobo con la forma del árbol de clase (conexiones como requisitos), con su `LEEME.md` y `fuente/`.
- `i28/`: el árbol del lobo ordenado por nivel, el tooltip y los avisos del árbol de clase, el +10 % de Ancestral Wolf restaurado y el panel de Aspectos con la forma del menú de personaje, con su `LEEME.md` y `fuente/`.
- `i29/`: el escudo del juego en los escudos del lobo, los estados que se acumulan con cantidad y turnos, y la regla «cada habilidad sube por Wounds o por Scent», con su `LEEME.md` y `fuente/`.
- `i30/`: el menú de habilidades a lo ancho del 16:9 (2K), con el árbol y la barra más grandes, y el panel de Aspectos con las mismas medidas, con su `LEEME.md` y `fuente/`.

- `i31/`: fondos HD de zona (Labyrinth e Il Sanctus en HD, Zona 1 y Hew al original, arreglo del bug de Hew), con `LEEME.md`, `documentacion/` (`ZONAS_HD.md`) y `fuente/`.
- `i32/`: combate HD en Oberursel (fondo a pantalla completa, solo las barras arriba, panel de abajo al 62 %).
- `i33/`: la imagen HD del combate sigue la cámara.
- `i34/`: combate HD en dos capas (cielo quieto, suelo con la cámara) y el diálogo en su cuadro.
- `i35/`: los 10 fondos de combate en HD (los 99 combates) y el zoom al 50 % en HD. **Versión vigente.** La guía está en `i35/documentacion/COMBATE_HD.md`.
- `instalador/`: `INSTALAR.bat` y `RESTAURAR.bat` (copian `SONNY2.swf` a la carpeta del juego de Steam con respaldo).

Cada versión desde I31 trae su `fuente/build.py`, que necesita la base y las herramientas de `DECOMPILACION_PASO5.zip` (ver `TRASPASO.md`).

El SWF del juego, las imágenes, las capturas y la descompilación (`DECOMPILACION_PASO5.zip`) no se suben mientras la repo sea pública.
