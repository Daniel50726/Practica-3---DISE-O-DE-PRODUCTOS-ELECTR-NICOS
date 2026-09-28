# Repositorio de soporte - CubeSat UD34

Este directorio organiza los archivos que se deben subir al repositorio de GitHub solicitado en la guia del laboratorio.

## Que pide la guia

Ademas del informe tecnico en PDF, deben entregarse archivos de soporte:

- Hoja de calculo editable con matrices, comparaciones y presupuestos.
- Diagramas de arquitectura en formato editable y exportados como imagen o PDF.
- Calculos adicionales usados para justificar decisiones.
- Lista de fuentes tecnicas consultadas, con enlaces y referencias precisas.
- Hojas de datos de los componentes usados como soporte tecnico.

## Estructura propuesta

- `informe/`: PDF final del informe y, si se desea, una copia exportada del documento.
- `latex/`: fuente LaTeX de Overleaf, archivos `.tex`, bibliografia e imagenes usadas.
- `soportes/`: Excel editable con matrices, presupuestos e interfaces.
- `diagramas/exportados/`: diagramas finales en PNG o PDF.
- `diagramas/editables/`: archivos editables de diagramas o enlaces documentados a Canva.
- `calculos/`: calculos adicionales, hojas auxiliares o notas de dimensionamiento.
- `fuentes/`: lista organizada de fuentes, links y decisiones que soportan.
- `datasheets/`: hojas de datos descargadas, separadas por subsistema.

## Archivos que ya estan incluidos

- `soportes/matrices_lab3_punto9_actualizado.xlsx`
- `diagramas/exportados/diagrama_funcional_cubesat_ud34.png`
- `diagramas/editables/diagrama_funcional_cubesat_ud34.svg`
- `fuentes/componentes_candidatos.md`

## Pendientes principales

- Exportar el informe final desde Overleaf como PDF y guardarlo en `informe/`.
- Descargar desde Overleaf el proyecto fuente o copiar el `.tex` final a `latex/`.
- Exportar desde Canva el diagrama definitivo del punto 9 en PNG o PDF.
- Guardar el enlace editable de Canva en `diagramas/editables/README.md` o en `fuentes/componentes_candidatos.md`.
- Descargar los datasheets de los componentes candidatos y guardarlos en las carpetas correspondientes.
- Revisar que el Excel final sea el actualizado, especialmente si el archivo original estaba abierto y se genero una copia.

## Nombre sugerido del repositorio

`cubesat-ud34-arquitectura-electronica`

Puede ser privado si el docente no exige que sea publico.

## Enlace para poner en el informe

Cuando el repositorio exista, agregar en la seccion de referencias o anexos:

`Repositorio de soporte: https://github.com/USUARIO/cubesat-ud34-arquitectura-electronica`
