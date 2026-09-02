# Trader

Proyecto de trading sistemático/algorítmico en fase de investigación —
actualmente corre **100% en papel** (sin bróker real conectado, sin
capital real en riesgo).

## ¿Qué hace?

El sistema evalúa señales sobre un universo de símbolos (acciones e
índices) y opera automáticamente varias estrategias en paralelo, cada
una con su propia cuenta de papel independiente:

- Un libro principal de riesgo controlado.
- Variantes de corto, mediano y largo plazo.
- Estrategias experimentales en fase de prueba (sombra), que solo pasan
  a operar con seguimiento real después de acumular suficiente muestra
  y superar una validación estadística.

Un control de riesgo semanal (killswitch) revisa el desempeño de cada
libro y reduce o pausa automáticamente los que vienen perdiendo de
forma consistente.

## Resultados

El desempeño se publica automáticamente, una vez al día, en:

**https://jorgeahmed.github.io/trader/**

Ahí se puede ver la curva de resultados de cada libro, cuántas señales
están activas en el sistema, y el estado general de la operación —
actualizado todos los días después del cierre de mercado.

## Estado

Proyecto en investigación activa. Ninguna estrategia opera con capital
real todavía — la disciplina del proyecto es que nada se promueve a
real sin pasar primero una validación fuera de muestra.
