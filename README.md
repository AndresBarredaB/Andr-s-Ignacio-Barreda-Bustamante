# Proyecto ENE — Política Económica USACH

Entrega para Andrés Barreda: cinco scripts R originales, primer bloque del paso 06, carpetas organizadas y documentación de continuidad.

## Descargar el proyecto

1. Abra [Proyecto_ENE.zip](entregables/Proyecto_ENE.zip).
2. En la página del archivo, pulse **Download raw file** (icono de descarga). Si aparece una pantalla sin vista previa, use **View raw** o **Raw**.
3. Guarde el ZIP y extraiga su contenido en una carpeta nueva de su computador.
4. Abra `proyecto_ene_usach/outputs/LEEME_PASO_06.md` para las instrucciones.

También puede usar **Code > Download ZIP** en la página principal del repositorio. Ese ZIP contiene este README y `entregables/Proyecto_ENE.zip`; extraiga también el ZIP interior.

## Estado de la entrega

- Los cinco scripts adjuntos se conservaron sin cambios.
- El nuevo bloque `06_01_preparar_base_laboral_AMJ.R` valida el CSV nacional y organiza nuevas salidas.
- Pasaron 25 pruebas funcionales con datos sintéticos temporales; no son resultados del estudio.
- La corrida real se detuvo por falta de `indicadores_nacionales_AMJ_2010_2025.csv`.
- No se han generado tablas ni gráficos económicos reales del paso 06; faltan el CSV y la verificación de series macroeconómicas oficiales.
- No se ejecutó el paso 07.

Para continuar, copie el CSV nacional y sus controles de la misma ejecución a `proyecto_ene_usach/work/insumos/paso_03/`, y ejecute el nuevo script completo con **Source** en RStudio. No necesita repetir 01–05 si ya dispone de sus resultados.

La ruta de Windows original no fue accesible desde esta nube. Este ZIP debe descargarse y extraerse para crear una copia local; no modificó su computador.
