# ADR-002 (revisada) — Orden de carga de catálogos por marca

Fecha original: 2026-09-28
Fecha de revisión: 2026-10-01
Estado: Aceptada

## Contexto
El proyecto trabaja con múltiples marcas reales. El orden de carga
sigue el uso actual del taller donde se trabaja hoy, no el uso
histórico.

Marcas confirmadas (7):
1. Conalum
2. Alugama (Forza)
3. Indalum
4. Profilo
5. Extrucciones Metálicas
6. Cuprum (Smart Frame)
7. Ayuso (Grupo Ayuso)

Perfilleto: eliminada del inventario (no se usa actualmente).

## Decisión
El orden de carga sigue el uso actual del taller:

1. Conalum — la más usada actualmente, la más económica.
2. Alugama (Forza) — muy solicitada actualmente.
3. Indalum — histórica, pero sigue usándose.
4. Profilo — línea 10000.
5. Extrucciones Metálicas — línea nacional.
6. Cuprum (Smart Frame) — RPT, alta gama.
7. Ayuso (Grupo Ayuso) — Magnum 400, alta gama.

Excepción: Forza ya está en progreso de verificación contra PDF.
Se termina Forza primero para no dejar trabajo a medias. Después
se sigue el orden de uso actual.

## Razón
El sistema debe servir primero para lo que más se usa. Pero no
se abandona trabajo ya iniciado.

## Consecuencias
- Forza: se termina de verificar (trabajo en curso).
- Conalum: siguiente en la fila (por uso actual).
- Alugama: después de Conalum.
- Los demás: en orden de uso.
- Carpetas de catálogo: se crean para las 7 marcas confirmadas.

## Revisión
Se revisa cuando Forza esté cerrada al 100%.
