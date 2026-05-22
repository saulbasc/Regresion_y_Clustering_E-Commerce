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
├── docs/                   # Documentación LaTeX y PDF
│   ├── *.tex              # Archivos fuente LaTeX
│   └── documento.pdf      # PDF final (se sube a Git)
├── README.md              # Este archivo
├── requirements.txt       # Dependencias Python
└── .gitignore            # Archivos excluidos de Git
```