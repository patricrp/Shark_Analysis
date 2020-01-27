# Shark_Analysis

En este análisis se analiza la hipótesis de que el mayor número de ataques a surfistas se producen en la costa oeste de USA, donde nació el surf. 

Procedimiento

1. Tras la creación del DataFrame, analizo las columnas interesantes para el estudio. 
2. Reescribo los nombres de las columnas, ya que algunas contienen espacios.
3. Creo un nuevo DataFrame con las columnas que me interesan.
4. Reviso los registros duplicados en la columna Case Number, elimino los duplicados y para aquellos que son diferentes, añado una 'z' al final del Case Number.
5. Filtro el DataFrame por la actividad 'Surfing'.
6. Cuento cuántos ataques ha habido por países.
7. Filtro en USA los ataques en la zona de la costa oeste, en función de las Áreas que pertenecen a la costa oeste.
8. Comparo con el número de ataques en otras zonas, donde destaca Florida, desmontando la hipótesis de que el mayor número de ataques a surfistas se produce en la costa oeste de USA.

Hay un extra para intentar buscar aquellas actividades que pueden estar relacionadas con Surf, a través de Injury, si en este campo se indica que la tabla ha sido dañada.
