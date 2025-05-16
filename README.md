# movilidad_natales_EDA
Análisis exploratorio de la Encuesta Origen-Destino aplicada en Puerto Natales, con foco en los patrones de movilidad según género, edad (adultos mayores) y condición de discapacidad.


## Microinforme
La encuesta fue aplicada a 518 hogares y 1.000 personas en Puerto Natales, de las cuales 528 eran mujeres y 472 hombres. Del total, el 71,6% de los hombres realizaron al menos un viaje durante el día medido, en comparación con el 63,6% de las mujeres. Aunque los propósitos de viaje más comunes fueron similares entre géneros —trabajo, estudio, búsqueda o traslado de personas, e ir de compras—, se observa que un mayor porcentaje de hombres (37,5%) viajó por motivos laborales, mientras que solo el 17,6% de las mujeres lo hizo. En contraste, las mujeres realizaron más viajes cuyo propósito fue dejar o buscar a alguien (58,8%).
Este patrón también se refleja en la distribución de asientos en los viajes en automóvil. Las mujeres que viajan únicamente para dejar o buscar a alguien tienden a ocupar el asiento de pasajero, mientras que los hombres, que viajan como conductores, reportan el trabajo como su principal motivo, lo que sugiere que el traslado de otra persona no es el objetivo principal del viaje, sino parte de su trayecto.
Los viajes se concentran principalmente en personas entre los 30 y 64 años, donde el 71,9% de este grupo reportó haber viajado, mayormente por trabajo o para dejar/buscar a alguien. Los jóvenes entre 0 y 18 años se movilizan principalmente para asistir a clases, mientras que en el grupo de adultos mayores (65+), el 52,1% no realizó ningún viaje. Entre quienes sí se movilizaron (47,9%), los motivos principales fueron compras, trabajo, traslado de personas y salud.
En cuanto a los modos de transporte, existen cuatro formas principales de movilizarse en Natales: automóvil, a pie, taxi colectivo y radiotaxi. Aunque se esperaba una mayor variación en el uso de medios según la edad, los porcentajes son bastante similares entre grupos etarios, por lo que esta variable no parece ser un factor diferenciador significativo.
Si bien uno de los intereses principales era conocer detalles sobre la movilidad de las personas con capacidad reducida, se identificaron inconsistencias importantes en la información que dificultan una lectura precisa de estos casos. Se detectaron folios perdidos entre las tablas y no fue posible determinar el origen del problema. Dicho esto, se identificaron 59 hogares registrados con al menos un integrante con capacidad reducida. De estas personas, el 76,3% tiene una discapacidad física, el 22,0% una discapacidad sensorial y el 1,7% una discapacidad intelectual.

## Herramientas utilizadas:
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook

##  Limitaciones de los Datos
Durante el análisis de la Encuesta Origen-Destino aplicada en Puerto Natales, se identificaron algunas inconsistencias en los datos originales. Específicamente, al comparar las tablas de hogares, personas y viajes, se observó que había un número menor de registros de viajes en comparación con las personas que declararon haber realizado viajes.
Esta discrepancia puede deberse a errores en la recopilación, procesamiento o incluso en la conversión de datos desde el formato original en Access a CSV.
Debido a esto, se recomienda tener en cuenta estas limitaciones al interpretar los resultados del análisis.

## Datos
Los datos utilizados en este análisis provienen de la Encuesta Origen-Destino aplicada en Puerto Natales por el Ministerio de Transporte y Telecomunicaciones.  
Puedes acceder a ellos desde el siguiente enlace:  
📎 [https://biblioteca.mtt.gob.cl/documento/c9e15b67-38aa-4921-9e40-75c3a0e34b8a]
