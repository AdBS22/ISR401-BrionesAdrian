# ISR401-BrionesAdrian

Repositorio personal de Ingeniería de Requerimientos (ISR-401), UTEQ, SPA 2026-2027.

Cada actividad está en su propia carpeta y se compila de forma independiente. Compilador y herramientas comunes a todas las actividades:

- Compilador: pdflatex, MiKTeX-pdfTeX 4.23 (MiKTeX 25.12).
- Bibliografía: Biber, versión 2.21.

## FORM-TL-01: Taller de tipos de requisitos

Actividad formativa de Ingeniería de Requerimientos (ISR-401), UTEQ.

### Archivo principal

`FORM-TL-01/main.tex`

### Orden de comandos

Desde la carpeta `FORM-TL-01`:

```
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

El resultado es `FORM-TL-01/main.pdf`.

### Dependencias

Paquetes de LaTeX: inputenc, fontenc, babel (opción spanish), geometry, array, booktabs, longtable, csquotes y biblatex (backend biber, estilo ieee).

Archivo de bibliografía: `FORM-TL-01/references.bib`.

## TA-IND-01: IEEE 29148 y tipos de requisitos de un sistema conocido

Actividad sumativa individual de Ingeniería de Requerimientos (ISR-401), UTEQ. El sistema analizado es el Explorador de archivos de Windows 10.

### Archivo principal

`TA-IND-01/main.tex`

### Orden de comandos

Desde la carpeta `TA-IND-01`:

```
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

El resultado es `TA-IND-01/main.pdf`.

### Dependencias

Paquetes de LaTeX: inputenc, fontenc, babel (opciones spanish y es-tabla), geometry, array, booktabs, longtable, graphicx, amsmath, csquotes, titlesec y biblatex (backend biber, estilo ieee).

Archivo de bibliografía: `TA-IND-01/referencias.bib`.

Las capturas del sistema están en `TA-IND-01/figuras/`.
