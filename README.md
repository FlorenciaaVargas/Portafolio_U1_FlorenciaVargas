# Portafolio_U1_FlorenciaVargas

# Ensayo de compresion de un hormigon

## 1. Geometria y supuestos del ensayo
- **Diametro (D):** 150 mm
- **Altura (h):** 300 mm
- **Area (A):** pi*((D/2)^2) = 17.671,5 mm^2
- **Unidades:**
  - Carga (P): kN
  - Desplazamiento ($u$): mm
  - Esfuerzo ($\sigma$): MPa ($\text{N/mm}^2$)

## 2. Estructura del repositorio
```text
├── data/
│   ├── raw/                  # Datos originales sin modificar
│   │   └── ensayo_hormigon.xlsx
│   └── processed/            # Datos procesados y calculados
│       └── ensayo_hormigon_procesado.csv
├── src/                      # Código ejecutable de procesamiento
│   └── procesar_ensayo.py
├── results/
│   └── figures/              # Gráficos generados automáticamente
│       └── grafico_esfuerzo_desplazamiento.png
├── docs/                     # Informe final y documentación
│   └── informe_final.docx
└── README.md                 # Documentación principal del proyecto
