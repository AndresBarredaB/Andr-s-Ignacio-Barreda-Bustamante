# Proyecto ENE — siete etapas en R

Entrega conjunta para Andrés Barreda, Política Económica USACH.

## Informe de avance en Word

**[Descargar el informe en Word](https://github.com/AndresBarredaB/Andr-s-Ignacio-Barreda-Bustamante/raw/refs/heads/main/entregables/Informe_de_avance_Empleo_Chile_2010_2025.docx)**

Documento editable de7páginas que revisa el avance y las sugerencias: alcanceAMJ2010–2025, orden demográfico/sectorial y macro/políticas, dimensión socioeconómica y límites causales. Es un informe de avance; no inventa resultados. Los enlacesCEP/UC continúan pendientes de lectura por bloqueo de red.

## Descargar todo junto

**[Descargar Proyecto_ENE_01_07.zip](https://github.com/AndresBarredaB/Andr-s-Ignacio-Barreda-Bustamante/raw/refs/heads/main/entregables/Proyecto_ENE_01_07.zip)**

Si la descarga no comienza, abra [el archivo en GitHub](entregables/Proyecto_ENE_01_07.zip) y pulse **Download raw file** (flecha hacia abajo). Inicie sesión en GitHub si se solicita. Extraiga el ZIP en una carpeta nueva.

## Qué incluye

1. `01_inventario_ene.R` — original intacto.
2. `02_diagnostico_y_union_ene.R` — original intacto.
3. `03_indicadores_laborales_nacionales.R` — original intacto.
4. `04_indicadores_laborales_sexo_edad.R` — original intacto.
5. `05_empleo_sectores_productivos.R` — original intacto.
6. `06_01_preparar_base_laboral_AMJ.R` — primer bloque de validación del CSV nacional.
7. `07_politicas_empleo_y_estrategia_econometrica.R` — registro documental y estrategia econométrica.

Incluye sus carpetas, entradas disponibles, informes de ejecución y LEEME. Abra `proyecto_ene_usach/CONTEXTO_PROYECTO.md` y los LEEME06/07 antes de ejecutar. RStudio: abrir el script completo y pulsar **Source**.

## Estado real

- Los cinco originales se conservaron byte a byte; no se repitieron01–05.
- El06 se detiene correctamente si falta `indicadores_nacionales_AMJ_2010_2025.csv`; no hay resultados económicos nuevos inventados.
- El07 se ejecuta como revisión documental/metodológica. Incluye políticas candidatas y estrategia; las consultas oficiales están bloqueadas por la red. Sus fechas, requisitos y evaluaciones siguen sin verificar. Los registros pendientes no son evidencia de efectos.
- No se estimaron regresiones ni efectos causales. Con16cortes, las primeras diferencias dejan15observaciones; sexo y edad no identifican beneficiarios.
- Para completar el análisis se necesitan CSV03/controles, series macro oficiales y documentos de políticas/evaluaciones. Las carpetas Windows originales no fueron accesibles desde la nube.

El archivo anterior `entregables/Proyecto_ENE.zip` se conserva como entrega previa. El paquete nuevo conjunto es `Proyecto_ENE_01_07.zip`.
