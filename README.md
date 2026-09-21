# Proyecto Kiva por Eddy

Análisis de préstamos Kiva con Excel, Power Query y Power Pivot.

## Objetivo
Analizar la financiación por país, sector y modalidad de pago, y su evolución mensual mediante un dashboard interactivo.

## Archivos
- Proyecto_Kiva.xlsx: modelo de datos, medidas, tablas dinámicas y dashboard.
- kiva_loans_42304_rows.csv: datos originales del ejercicio.

## Herramientas utilizadas
- Power Query: limpieza y transformación de datos.
- Power Pivot: relaciones y medidas DAX.
- Excel: gráficos dinámicos y filtros por país y año.

Los importes se calculan contando cada préstamo una sola vez, para evitar duplicaciones al separar los datos de los prestatarios.

## Cómo utilizar el proyecto
1. En GitHub, pulsa Code → Download ZIP.
2. Extrae el ZIP.
3. Abre Proyecto_Kiva.xlsx con Excel de escritorio para Windows compatible con Power Pivot.
4. En la hoja Dashboard, utiliza los filtros de país y año.

El dashboard se utiliza en Excel; GitHub permite descargar los archivos, pero no ejecutar sus filtros.

## Cómo actualizar los datos
La conexión al CSV contiene una ruta local que debes ajustar en tu ordenador:

1. En Excel, entra en Datos → Obtener datos → Configuración de origen de datos.
2. Selecciona el origen CSV y pulsa Cambiar origen.
3. Busca el archivo kiva_loans_42304_rows.csv en la carpeta que extrajiste.
4. Acepta y pulsa Datos → Actualizar todo.

Cambiar los filtros utiliza los datos ya guardados en el modelo. Para incorporar cambios del CSV, debes actualizar.

## Resultados generales sin filtros
- Préstamos únicos: 42.308.
- Total financiado: 35.721.825,00 USD.
- Plazo promedio por préstamo: 14,12 meses.

Aunque el nombre del CSV indica 42304, el archivo utilizado contiene 42.308 préstamos.

## Alcance
Los datos abarcan desde enero de 2014 hasta julio de 2017. El año 2017 está incompleto, por lo que su total no debe compararse directamente con años completos.

Proyecto educativo basado en el CSV facilitado en el curso. No representa toda la actividad de Kiva.
