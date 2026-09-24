# Ensayo de compresion de un hormigon

## 1. Propósito
Explicación clara del proyecto de ensayo de compresión de hormigón.

## 2. Entrada: Geometria y supuestos del ensayo
- **Diámetro de la probeta ($D$):** 150 mm
- **Altura de la probeta ($H$):** 300 mm
- **Área de la sección transversal ($A$):** $\pi \times (D/2)^2 = 17671.46 \text{ mm}^2$
- **Unidades:**
  - Carga (P): kN
  - Desplazamiento ($u$): mm
  - Esfuerzo ($\sigma$): MPa ($\text{N/mm}^2$)
## 3. Procedimiento 
Pasos secuenciales para procesar los datos, calcular esfuerzos ($\sigma = P / A$) y generar las curvas.

## 4. Salida
Resultados e imágenes que se obtienen.
Gráfico obtenido de los datos de excel e informe final sobre el ensayo.

## 5. Estructura del repositorio
```text
├── data/
│   ├── raw/                  # Datos originales sin modificar
│   │   └── ensayo_hormigon.xlsx
│   └── processed/            # Datos procesados y calculados
│       └── ensayo_hormigon_procesado.csv
├── results/
│   └── figures/              # Gráficos generados automáticamente
│       └── grafico_esfuerzo_desplazamiento.png
├── docs/                     # Informe final y documentación
│   └── informe_final.docx
└── README.md                 # Documentación principal del proyecto
