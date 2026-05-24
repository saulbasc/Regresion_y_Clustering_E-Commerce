# Regresión y Clustering E-Commerce

Análisis de regresión lineal y clustering para datos de e-commerce, realizado mediante Jupyter Notebooks y con su documentación en LaTeX.

## Setup rápido

### 1. Clonar el repositorio
```bash
git clone <repo-url>
cd Regresion_y_Clustering_E-Commerce
```

### 2. Crear entorno virtual
```bash
python -m venv .venv
```

### 3. Activar el entorno

**Windows (PowerShell):**
```powershell
.\.venv\Scripts\Activate.ps1
```

**Windows (CMD):**
```cmd
.venv\Scripts\activate.bat
```

**macOS/Linux:**
```bash
source .venv/bin/activate
```

### 4. Instalar dependencias
```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 5. Ejecutar en VS Code

1. Abre VS Code y carga este proyecto.
2. Abre cualquier archivo `.ipynb` de la carpeta `src/`.
3. **Selecciona el kernel:** Haz clic en `Select Kernel` (arriba a la derecha) y elige `.venv`.
  - Si no aparece automáticamente, selecciona **Python Environments** → busca el `.venv` de esta carpeta.
4. Ejecuta las celdas con `Ctrl+Enter` o Run All en la barra superior del notebook.

**Alternativa: Jupyter en navegador**
```bash
jupyter notebook
```

## Estructura del proyecto

```
.
├── src/                    # Notebooks de análisis
├── data/                   # CSV inicial a explorar
│   └── data.csv           # Dataset original
├── output/                 # Salidas de CSV modificados
├── docs/                   # Documentación LaTeX y PDF
│   └── documento.pdf      # PDF final
├── README.md              # Este archivo
├── requirements.txt       # Dependencias Python
└── .gitignore            # Archivos excluidos de Git
```

## Orden de ejecución recomendado

1. **`src/exploracion.ipynb`** - Exploración inicial del dataset
   - Análisis descriptivo de variables
   - Visualización de distribuciones
   - Identificación de patrones

2. **`src/limpieza.ipynb`** - Limpieza y tratamiento de datos
   - Detección y tratamiento de valores faltantes
   - Eliminación de duplicados
   - Detección y tratamiento de outliers
   - Validación de tipos de datos

3. **`src/tratamiento_clustering.ipynb`** - Preparación de datos para clustering
   - Normalización y escalado de variables
   - Selección de características
   - Generación de datos limpios para clustering

4. **`src/tratamiento_regresion.ipynb`** - Preparación de datos para regresión
   - Normalización y escalado de variables
   - Selección de características
   - Generación de datos limpios para regresión

5. **`src/modelos_clustering/`** - Modelos de clustering
   - K-Means
   - DBSCAN
   - Análisis de perfiles de clientes

6. **`src/modelos_regresion/`** - Modelos de regresión
   - Regresión Lineal
   - Random Forest
   - XGBoost