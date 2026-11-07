# FORM-TL-01: Taller de tipos de requisitos

Actividad formativa de Ingeniería de Requerimientos (ISR-401), UTEQ.

## Compilador

pdflatex, MiKTeX-pdfTeX 4.23 (MiKTeX 25.12).

Biber para la bibliografía, versión 2.21.

## Archivo principal

`FORM-TL-01/main.tex`

## Orden de comandos

Desde la carpeta `FORM-TL-01`:

```
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

El resultado es `FORM-TL-01/main.pdf`.

## Dependencias

Paquetes de LaTeX: inputenc, fontenc, babel (opción spanish), geometry, array, booktabs, longtable, csquotes y biblatex (backend biber, estilo ieee).

Archivo de bibliografía: `FORM-TL-01/references.bib`.
