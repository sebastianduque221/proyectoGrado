# DballTrainer
Resumen del Proyecto

1. Conversión de Videos MOV a MP4:
   - Convertimos todos los archivos .MOV en la carpeta Videos a archivos .MP4 utilizando moviepy.

2. Detección y Evaluación de Posturas:
   - Creamos funciones para evaluar diferentes aspectos de la postura de un jugador (posición, movimiento, contacto, seguimiento, estabilidad).
   - Integramos estas evaluaciones en el archivo main.py para procesar videos y generar un análisis de postura.

3. Generación de Archivos de Salida:
   - Guardamos los videos de salida y los archivos CSV de análisis de postura en una carpeta llamada salidas.
   - Aseguramos que los nombres de los archivos de salida sean únicos para evitar sobrescribir archivos existentes.

4. Pendiente:
   - Hacer que el video tambien se reciba de fuentes online como Youtube