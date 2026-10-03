# Taller Fasecolda — Aprendizaje Automático

Notebook para el taller **“Análisis Exploratorio del Mercado de Autos Usados en Colombia”**.

## Contenido

- Carga y perfilamiento inicial de Fasecolda.
- Análisis de valores faltantes y duplicados.
- Análisis univariado.
- Distribución del precio 2017.
- Marcas más frecuentes.
- Análisis bivariado:
  - cilindraje vs. precio;
  - precio promedio por marca;
  - peso promedio por marca.
- Pregunta de enriquecimiento de datos.
- Extensión opcional de aprendizaje supervisado (regresión).
- Extensión opcional de aprendizaje no supervisado (clustering).

## Ejecutarlo en Google Colab

1. Sube este proyecto a GitHub.
2. Abre `Taller_Fasecolda.ipynb`.
3. Selecciona **Open in Colab** o abre el enlace de Colab correspondiente al archivo de GitHub.
4. Si el repositorio contiene la carpeta `data/`, el notebook encontrará automáticamente `data/guia_fasecolda.csv`.

## Ejecución local

```bash
pip install -r requirements.txt
jupyter notebook Taller_Fasecolda.ipynb
```

## Estructura

```text
taller_fasecolda/
├── Taller_Fasecolda.ipynb
├── README.md
├── requirements.txt
└── data/
    ├── guia_fasecolda.csv
    └── guia_fasecolda.sqlite
```

## Nota sobre el precio

Para los análisis monetarios se utilizan únicamente registros con `Precio_2017 > 0`, porque los ceros dominan la columna y no representan observaciones útiles de precio.


