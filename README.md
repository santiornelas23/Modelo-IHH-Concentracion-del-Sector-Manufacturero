# Modelo IHH – Concentración del Sector Manufacturero en el Norte de México

Este repositorio contiene un archivo en Excel donde se calcula el **Índice Herfindahl–Hirschman (IHH)** para medir la concentración económica del sector manufacturero en los estados del norte de México. El documento incluye datos obtenidos del INEGI y una tabla final que muestra el nivel de **concentración** y **diversificación productiva** por estado.

---

## Contenido del archivo Excel

El documento incluye:

- Población ocupada por subsectores del sector manufacturero en:
  - Baja California  
  - Baja California Sur  
  - Chihuahua  
  - Coahuila  
  - Durango  
  - Nuevo León  
  - Sinaloa  
  - Sonora  
  - Tamaulipas  

- Cálculo del **IHH por estado**, usando la fórmula:

\[
IHH = \sum_(i=1)^(n) s_i^2
\]

donde \(s_i\) es la participación del subsector dentro del total estatal.

- Cálculo del índice de **diversificación**, medido como el inverso del IHH normalizado.

---

## Resultados Principales

La tabla final del Excel muestra:

| Estado | IHH (Concentración) | Diversificación |
|-------|----------------------|-----------------|
| Baja California | 2167.23 | 4.61 |
| Baja California Sur | 1380.12 | 7.24 |
| Chihuahua | 2682.19 | 3.72 |
| Coahuila | 2228.88 | 4.48 |
| Durango | 1552.27 | 6.44 |
| Nuevo León | 1479.45 | 6.75 |
| Sinaloa | 1153.99 | 8.66 |
| Sonora | 1436.53 | 6.96 |
| Tamaulipas | 2109.42 | 4.74 |

---

## Interpretación del Modelo IHH

- **Valores altos de IHH (2,000+)** indican **mayor concentración**, es decir, pocos subsectores manufacturero dominan la actividad del estado.  
  - Chihuahua (2682), Coahuila (2228) y Baja California (2167) presentan **mercados más concentrados**.

- **Valores bajos de IHH (~1100–1500)** indican **menor concentración** y mayor distribución entre subsectores.  
  - Sinaloa (1153), Nuevo León (1479) y Sonora (1436) muestran **mayor equilibrio sectorial**.

- La **diversificación** es el inverso lógico del IHH:
  - Valores mayores implican **economías más diversificadas**.  
    - Sinaloa (8.66) y Baja California Sur (7.24) son los estados **más diversificados**.
  - Valores menores implican **economías dependientes de pocos subsectores**.  
    - Chihuahua (3.72) y Tamaulipas (4.74) presentan **menor diversificación**.




