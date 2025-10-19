# Entregable Nº2  
**Curso:** Estadística para el Análisis Político 2°  
**Clave:** POL304  
**Horario:** 0689  
**Integrante:** Carolina Lima Dupuy (20213002)

---

## Tema de investigación:

**El impacto de las estrategias geopolíticas chinas sobre la distribución global de sus transacciones económicas exteriores: un análisis estadístico entre países aliados y no aliados en el año 2024.**

---

## Contenido del repositorio:

China_data/
├── China_data.xlsx # Base original
├── China_data_limpia.xlsx # Base limpia (resultado de la limpieza en R)
├── ENTREGA_2_CAROLINA_LIMA_DUPUY_20213002.Rmd # Proceso de limpieza
└── README.md # Documentación del proyecto

---

## Proceso de limpieza:

La limpieza de datos se realizó en **R**, empleando las librerías:
- `tidyverse`
- `rio`
- `janitor`

### Pasos aplicados:
1. Estandarización de nombres de columnas (`clean_names`).
2. Eliminación de filas con valores vacíos (`drop_na`).
3. Conversión de variables categóricas a factores (`country`, `region`, `bri`).
4. Conversión de variables numéricas (`usadf`, `idi_2024`).
5. Exportación de la base limpia como `China_data_limpia.xlsx`.

---

## Diccionario de datos:

| **Variable** | **Medición** | **Valores** |
|---------------|--------------|--------------|
| **country** | País considerado en el análisis para el año 2024. | Categórica nominal (*Factor*). Nombre del país, p. ej.: *China, Perú, Alemania.* |
| **region** | Región geográfica o económica donde se ubica el país. | Categórica nominal (*Factor*). *Asia, Europa, América Latina, África, Medio Oriente, Oceanía.* |
| **ied_china** | Monto de la Inversión Extranjera Directa (IED) proveniente de China. | Cuantitativa continua (*Numérica*). Medida en millones de dólares estadounidenses (USD). |
| **bri** | Participación del país en la Iniciativa de la Franja y la Ruta (Belt and Road Initiative). | Categórica dicotómica (*Factor*). *1 = País aliado / 0 = No aliado.* |
| **usadf** | Nivel de financiamiento o ayuda económica proveniente de EE. UU. | Cuantitativa continua (*Numérica*). Medida en millones de dólares estadounidenses (USD). |
| **pbi** | Producto Bruto Interno del país (nivel de producción nacional). | Cuantitativa continua (*Numérica*). Medida en millones de dólares estadounidenses (USD). |
| **idi_2024** | Índice de Desarrollo de la Infraestructura Digital en 2024. | Cuantitativa continua (*Numérica*). Escala de 0 a 100. |

---

## Autora:

**Carolina Lima Dupuy**  
Pontificia Universidad Católica del Perú  
Fecha: *19 de octubre de 2025*

