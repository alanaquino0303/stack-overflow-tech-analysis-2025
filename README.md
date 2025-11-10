# Stack Overflow Tech Analysis 2025

Procesamiento de datos, visualizaciones y generación automatizada de un informe PDF con resultados clave sobre tecnologías, lenguajes y tendencias de la comunidad.

---

## Características principales
- Carga y procesamiento de los datos originales de la encuesta Stack Overflow 2025.
- Generación de visualizaciones y gráficos informativos.
- Creación automática de un informe en formato PDF.
- Código modular y reproducible en Python.
- Compatible con diferentes sistemas operativos (Linux, macOS y Windows).

---

## Estructura del proyecto
```
/ stack-overflow-tech-analysis-2025
├─ analisis_tech_2025.py                  # Script principal de análisis.
├─ Encuesta Tech Stack Overflow 2025.csv  # Datos crudos de la encuesta.
├─ Informe Stack Overflow 2025.pdf        # Informe PDF generado automáticamente.
└─ README.md                              # Documentación del proyecto.
```

---

## Requisitos
- Python 3.9 o superior (recomendado 3.10 o 3.11).
- Librerías necesarias:
  - pandas.
  - matplotlib.
  - reportlab.

### Instalación de dependencias
Ejecuta los siguientes comandos desde la terminal o consola:

#### Linux o macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install pandas matplotlib reportlab
```

#### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
pip install --upgrade pip
pip install pandas matplotlib reportlab
```

---

## Ejecución del script
Una vez instaladas las dependencias y con los archivos en el mismo directorio:

```bash
python analisis_tech_2025.py
```

El script generará:
- Gráficos de tendencias y análisis.
- El informe final en formato PDF (`Informe Stack Overflow 2025.pdf`).

---

## Autor

Alan Aquino.
