# Descripción de los datos

Los datos reales utilizados en el Trabajo de Fin de Grado no se incluyen en este repositorio por motivos de confidencialidad, ya que proceden de explotaciones agrícolas reales y contienen información productiva y económica sensible.

El análisis se realizó a partir de varios archivos Excel internos con información agronómica, operativa, tecnológica y económica de distintas campañas agrícolas.

## Archivos utilizados en el análisis original

### Datos_cultivos.xlsx

Contiene información técnica y agronómica de las parcelas analizadas. Cada fila representa una observación parcela-campaña-cultivo.

Variables principales:

- Año
- Parcela
- Cultivo
- Superficie
- Rend_t_ha
- Humedad
- Productividad_ha_h
- Productividad_ha_12h
- Consumo_L_h
- Consumo_L_ha
- Fitosanitarios_ha
- Semilla_ha
- Semillas_min_ha
- Semillas_max_ha
- Abono_ha
- Abono_min_ha
- Abono_max_ha
- Pasadas_ha
- GPS
- RTK
- ISOBUS
- Siembra_variable
- Abono_variable
- Corte_tramos

### maiz_cerrodelacruz.xlsx

Contiene los datos específicos de la parcela Cerro de la Cruz Cati para el análisis comparativo inicial entre campañas.

Variables principales:

- Año
- Superficie
- Rend_t_ha
- Productividad_ha_h
- Consumo_L_ha
- Consumo_L_h
- Fitosanitarios_ha
- Semilla_ha
- Abono_ha
- Humedad
- GPS
- RTK
- ISOBUS
- Siembra_variable
- Abono_variable
- Corte_tramos

### Balance_economico.xlsx

Contiene la información económica utilizada para calcular costes, ingresos y beneficio por hectárea.

Variables principales:

- Año
- Parcela
- Cultivo
- Superficie
- Precio_tonelada_venta
- Descuento_humedad_por_t
- Ingreso_bruto_ha
- Precio_litro_gasoleoB
- Precio_litro_Fitosanitario
- Precio_Semillas_ha
- Precio_Abono_kg
- Gastos_fijos_por_ha
- Coste_total_por_ha
- Coste_total_por_tonelada
- Beneficio_por_ha
- Beneficio_total_parcela
- GPS
- RTK
- ISOBUS
- Siembra_variable
- Abono_variable
- Corte_tramos

### gastos_implantacion_tecnologica.xlsx

Contiene los costes estimados de implantación de las tecnologías analizadas.

Variables principales:

- Tecnología
- Coste_inversion
