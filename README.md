# Catálogo Taller

Sistema de catálogos interactivos para manufactura de ventanas y cancelería.

## Qué es

Herramienta de taller que convierte 40+ años de oficio en un sistema
que cotiza y fabrica con precisión. Empezando por Forza, con planes
de sumar Indalum y Conalum cuando Forza esté completa.

## Para qué sirve

- Cotizar un vano (ancho x alto) con material, herraje, vidrio y precio.
- Generar la orden de corte para el taller.
- Documentar las reglas del oficio (fichas KB).

## Estructura

- `docs/` — documentación por nivel (00-contexto a 07-implementacion)
- `catalogos/` — datos verificados por marca (forza, indalum, conalum)
- `fuentes/` — PDFs originales y transcripciones
- `fichas-kb/` — 15 fichas de conocimiento del oficio
- `decisiones/` — registro de decisiones tomadas (ADR)
- `codigo/` — motor de cálculo, interfaz, pruebas

## Estado actual

Ver `ESTADO.md`.

## Tipo de proyecto

Tipo A — personal de oficio. Sistematización del taller para uso
propio y legado. No es producto. No es negocio.

## Reglas de trabajo

1. Ningún dato se acepta como cerrado sin señalar su fuente exacta.
2. Se avanza por rebanada vertical: un caso completo antes de extenderse.
3. Nada se marca cerrado si el siguiente paso es validarlo.
4. Fuente única verificable: PDF, ficha KB, o declaración directa.
