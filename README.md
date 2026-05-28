# Fundamentos de ciencia de datos en R

Materiales para el curso de ciencia de datos en R.

## Dataset

Trabajamos con el dataset *A comprehensive dataset of the Spanish research output and its associated social media and altmetric mentions (2016-2020)*, que recoge publicaciones de instituciones españolas junto a sus menciones en redes sociales y otras fuentes altmétricas.

## Estructura del repositorio

```
curso_R/
├── README.md
├── notebook.Rmd        # notebook principal del curso
├── style.css           # estilos para el HTML renderizado
├── data/
│   ├── publications.tsv
│   └── top_authors.tsv
├── results/            # ficheros exportados
└── images/             # recursos gráficos
```

## Requisitos

Necesitas R (>= 4.0) y RStudio. Los paquetes que se usan a lo largo del notebook son los siguientes.

```r
install.packages(c('data.table', 'dplyr', 'tidyr',
                   'ggplot2', 'viridis', 'corrplot',
                   'broom', 'knitr'))
```

## Cómo ejecutar

1. Clona o descarga el repositorio.
2. Abre `notebook.Rmd` en RStudio.
3. Asegúrate de que el directorio de trabajo es la raíz del repositorio.
4. Pulsa *Knit* para renderizar el HTML o ejecuta los chunks de uno en uno.
