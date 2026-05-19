# Especificación Formal y Verificación de Correctitud — Algoritmos sobre Ciudades

**Trabajo Práctico I — Algoritmos y Estructuras de Datos II (FCEyN, UBA) — 2024**  
**Autores:** Martín Iván Cuestas, Gabriel Nuñez Moreno, Julián Nakasone, Gerónimo Pacheco Parrondo

## Descripción

Especificación formal y demostración de correctitud de algoritmos sobre secuencias
de ciudades, utilizando lógica de primer orden, la técnica de Weakest Precondition
(WP) y el Teorema del Invariante de ciclo.

## Contenido

### Especificaciones formales
- `grandesCiudades`: filtrado de ciudades con más de 50.000 habitantes
- `sumaDeHabitantes`: combinación de dos secuencias de ciudades sumando poblaciones
- `hayCamino`: verificación de existencia de camino en un grafo representado 
   como matriz de distancias simétrica
- `cantidadCaminoNSaltos`: cómputo iterativo del producto matricial para contar 
   caminos de exactamente N saltos
- `caminoMinimo`: especificación del camino de menor distancia entre dos nodos

### Demostraciones de correctitud
Para el algoritmo `poblacionTotal` implementado en SmallLang, se demostró:
- **Correctitud parcial** via Teorema del Invariante (3 puntos: PC→I, {I∧B}S{I}, I∧¬B→QC)
- **Terminación** del ciclo via función variante (2 puntos)
- **Correctitud total** respecto a la especificación via tripla de Hoare

## Conceptos aplicados

Lógica de primer orden · Weakest Precondition (WP) · Invariante de ciclo ·
Triplas de Hoare · Función variante · Especificación por pre y postcondición

## Tecnologías

LaTeX · SmallLang (lenguaje de especificación académico)
