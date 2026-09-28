# ADR-002 — Empezar por Forza

Fecha: 2026-09-28
Estado: Aceptada

## Contexto

Se trabaja con tres marcas reales: Forza, Indalum, Conalum.
No se puede cargar todo a la vez.

## Decisión

Empezar por Forza y cerrarla completa antes de abrir Indalum o Conalum.

## Razón

Forza es la que se ha verificado con más rigor contra PDF.
Es la que tiene motor de cálculo probado en al menos un caso completo.
Es la referencia para juzgar si las demás marcas se manejan igual.

## Consecuencias

- Forza se carga completa: series 3100, 4100, 5100, todas las tipologías.
- Se verifica contra PDF cada una.
- Hasta que Forza no esté cerrada, no se abre Indalum ni Conalum.
- La base multi-marca se confirma cuando Indalum (o Conalum) se cargue
  con el mismo rigor.

## Revisión

Se revisa cuando Forza esté completa y verificada al 100%.
