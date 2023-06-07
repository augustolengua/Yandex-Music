## Data:



- *сalls* — número de llamadas,
- *minutes* — duración total de la llamada en minutos,
- *messages* — número de mensajes de texto,
- *mb_used* — Tráfico de Internet utilizado en MB,
- *is_ultra* — plan para el mes actual (Ultra - 1, Smart - 0).

## Goal:

Necesitamos desarrollar un modelo que pueda analizar el comportamiento de los clientes e identificar patrones para recomendar uno de los nuevos planes de Megaline: Smart o Ultra. 

Se escogerá el modelo con la mayor exactitud posible. En este proyecto, el umbral de exactitud es 0.75.

## Libraries used:

pandas

sklearn.model_selection

sklearn.metrics

random

seaborn

matplotlib.pyplot

sklearn.tree

sklearn.ensemble

sklearn.linear_model