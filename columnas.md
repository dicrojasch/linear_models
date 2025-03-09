# Columnas del modelo de distribución

Este archivo describe brevemente cada columna utilizada en el modelo de distribución de viajes. A continuación se listan las variables y su significado:

- **max_nivel_edu**: Indica el nivel educativo máximo alcanzado por los integrantes del hogar.
- **app_antes_vj**: Señala si se utilizó alguna aplicación (p. ej., para planificar) antes de iniciar el viaje.
- **otro_vj**: Indica si existe un encadenamiento adicional de viaje (viajes previos o posteriores inmediatos).
- **orden_vj**: Orden secuencial del viaje dentro del día (1 = primer viaje, 2 = segundo viaje, etc.).
- **estra_hg**: Estrato socioeconómico del hogar (categoría socioeconómica asignada en la encuesta).
- **etapas**: Número de etapas que componen el viaje (subtramos con cambio de modo o interrupción).
- **zat_hg**: Zona de análisis de transporte asociada al hogar (ID o código de la ZAT).
- **utam_ori**: Código de la zona de origen (UTAM) donde inicia el viaje.
- **utam_des**: Código de la zona de destino (UTAM) donde finaliza el viaje.
- **total_trips**: Cantidad total de viajes observados en la celda (por combinación de zonas y otras variables).
- **weights**: Factor de expansión muestral que permite extrapolar los datos de la muestra a la población total.
- **mean_duracion**: Duración promedio del viaje (en minutos) calculada para la celda correspondiente.
- **mean_edad_prom**: Edad promedio de los viajeros dentro de la celda.
- **mean_mujeres**: Proporción de mujeres viajeras dentro de la celda.
- **mean_modo_a_pie**: Proporción de viajes realizados a pie (ya sea más o menos de 15 minutos).
- **mean_modo_priv**: Proporción de viajes en modo privado (auto particular o motocicleta).
- **mean_modo_bici**: Proporción de viajes realizados en bicicleta.
- **mean_modo_pub**: Proporción de viajes realizados en transporte público.
- **mean_modo_tax**: Proporción de viajes en taxi (taxi ocupado).
- **mean_modo_otro**: Proporción de viajes en otros modos (especial, informal, etc.).
- **mean_otro_viaje**: Proporción de viajeros que no realizaron viajes adicionales (o cuyo encadenamiento fue distinto).
- **mean_freq_todos_dias**: Proporción de individuos que viajan prácticamente todos los días.
- **mean_freq_varios_dias**: Proporción de individuos que viajan varias veces a la semana.
- **mean_freq_otro**: Proporción de individuos con una frecuencia de viaje distinta (ni diario ni varias veces a la semana).
- **mean_madre_cab_familia**: Proporción de hogares identificados con madre cabeza de familia.
