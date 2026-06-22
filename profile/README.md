# 🧠📡 SmartBioMed-EICB-UV  
### Área de **Señales, Imágenes e Inteligencia Artificial**  
**Escuela de Ingeniería Civil Biomédica — Universidad de Valparaíso**

Bienvenido(a)s al repositorio oficial del área de **Señales, Imágenes e Inteligencia Artificial (SIIA)** de la EICB-UV.  
Este espacio reúne proyectos académicos, repositorios estudiantiles, material docente y desarrollos asociados al trabajo del área en cursos y actividades de investigación.

### Descripción:

SmartBioMed es un marco conceptual que integra modelos matemáticos y computacionales con datos biomédicos multimodales —incluyendo señales fisiológicas, imágenes médicas y variables clínicas— para avanzar hacia una medicina más precisa, personalizada y basada en evidencia cuantitativa. Inspirado en la idea de los gemelos digitales, SmartBioMed propone la construcción de “hermanos digitales”: representaciones computacionales flexibles, no necesariamente completas ni en tiempo real, que permiten estudiar mecanismos fisiológicos, simular escenarios clínicos y explorar respuestas individuales a distintas intervenciones.

Este enfoque establece un marco metodológico común para el área de Señales, Imágenes e Inteligencia Artificial, articulando procesamiento de señales, análisis de imágenes y modelamiento computacional. SmartBioMed integra estas líneas en una base formativa y de investigación que permite abordar problemas biomédicos mediante métodos cuantitativos y modelos basados en datos, manteniendo coherencia con las capacidades actuales del área y proyectando un desarrollo académico y tecnológico sólido.

## 🗂️ Estructura general de los repositorios

Cada repositorio debe incluir un `README.md` principal que describa el proyecto, sus objetivos, instrucciones de instalación y uso, y un ejemplo mínimo de ejecución (entrada → ejecución → salida esperada) o una referencia al notebook correspondiente. El README debe indicar también la versión de Python utilizada y las dependencias principales; si el proyecto se ejecuta en Colab/Kaggle, mencionarlo explícitamente e incluir una celda inicial con `!pip install paquete==version` para las librerías no preinstaladas.

- [ ] Descripción del proyecto y objetivos.
- [ ] Instrucciones de instalación y uso.
- [ ] Ejemplo mínimo de ejecución (entrada → ejecución → salida esperada), o referencia al notebook correspondiente en `notebooks/`.
- [ ] Indicación de dependencias principales y versión de Python utilizada. Si el proyecto se ejecuta en Colab/Kaggle, mencionarlo explícitamente e incluir una celda inicial con `!pip install paquete==version` en el notebook para las librerías no preinstaladas.
- [ ] Información sobre licencia y uso (si aplica).

Además del README, el repositorio debe contener:

- Código organizado en carpetas (ver estructura sugerida).
- Archivo de dependencias con versiones (`requirements.txt`, `environment.yml` o equivalente). **Obligatorio.**
- Al menos un notebook con un ejemplo funcional reproducible en `notebooks/`.
- Carpeta `results/` con figuras, métricas o salidas relevantes.
- Archivo `LICENSE`, si aplica.

### 📁 Estructura sugerida de proyecto

Recomendada para proyectos de análisis de datos, señales, imágenes o aprendizaje automático:

```
mi-proyecto/
├── config/         # Archivos de configuración (parámetros, hiperparámetros, rutas, semillas)
├── data/           # Datos (ver sección "Gestión de datos")
├── notebooks/      # Notebooks con ejemplos funcionales y exploración
├── results/        # Resultados, figuras y outputs generados
├── src/            # Código fuente (módulos, funciones, clases)
├── test/           # Pruebas unitarias o de integración
├── requirements.txt  # (o environment.yml)
└── README.md
```

No es obligatoria, pero sí recomendada. Como mínimo se espera `src/` (o equivalente) y `notebooks/`.

### 📦 Gestión de datos

Los datos clínicos o sensibles **no deben subirse al repositorio**. La carpeta `data/` debe contener un `README.md` propio que documente el origen de los datos (institución, dataset público, link o DOI), su licencia y permisos de uso, e instrucciones de descarga (incluyendo la ruta esperada dentro de `data/` si la descarga es manual). Cuando aplique, indicar la versión o fecha de descarga del dataset. Si se trabaja con datos clínicos propios, documentar el procedimiento de anonimización aplicado (con script en `src/` si corresponde). Se recomienda incluir una muestra mínima sintética o anonimizada que permita ejecutar el notebook de ejemplo sin acceso al dataset completo.

### 🔁 Reproducibilidad

Para que el trabajo sea reproducible por otros estudiantes: fijar semillas aleatorias (`numpy`, `random`, `torch`, etc.) al inicio del notebook o script principal; evitar rutas absolutas, usando rutas relativas o definidas en `config/`; documentar el preprocesamiento, no solo el modelo final; indicar la versión de Python y, si aplica, de CUDA/GPU; y dejar las salidas (figuras, métricas) ya ejecutadas en el notebook de ejemplo, para que un lector pueda comparar sin re-ejecutar todo.


## Proyectos de Ingeniería Biomédica, SIIA:

### 2026-01
| Título (con presentador) | Profesor Guía| Repositorio |
|--------------------------|------|-----|

### 2025-02
| Título (con presentador) | Profesor Guía| Repositorio |
|--------------------------|------|-----|
| **_F. Alarcón_** - SMARTBIOMED: SEGMENTACIÓN DE VÍAS AÉREAS BASADA EN MACHINE LEARNING | **D. Ortiz** | [Repo](https://github.com/EICB-UV-Senales-Imagenes-e-IA/SMARTBIOMED-SEGMENTACI-N-DE-V-AS-A-REAS-BASADA-EN-MACHINE-LEARNING)

### 2025-01
| Título (con presentador) | Profesor Guía| Repositorio |
|--------------------------|------|-----|
| **_A. Muñoz_** — Sistema Semi-automático para la Segmentación y Medición de Espinas Dendríticas | **A. Veloz** | [Repo](https://github.com/EICB-UV-Senales-Imagenes-e-IA/Analisis-Espinas-Dendr-ticas)
| **_C. Osorio_** — MaternIA: Calculadora Inteligente de la Ganancia de Peso en el Embarazo | **R. Salas** | [Repo](https://github.com/EICB-UV-Senales-Imagenes-e-IA/Calculadora-GPG) |
| **_F. Estay_** — Red W-NET de doble tarea no supervisada para la detección y segmentación de hemorragias intracraneales en TC sin contraste | **R. Salas** | [Repo](https://github.com/EICB-UV-Senales-Imagenes-e-IA/WNet-Attention-ICH)|
| **_A. Argandoña_** — SEGMENTACIÓN DE VÍAS AÉREAS PULMONARES BASADO EN MACHINE LEARNING | **D. Ortiz** | [Repo](https://github.com/EICB-UV-Senales-Imagenes-e-IA/Airways-PIB)|
| **_B. Madrid_** — Estimación no invasiva de presión arterial utilizando Fotopletismografía, Electrocardiograma y Redes Neuronales Informadas por la física| **D. Ortiz** | [Repo](https://github.com/EICB-UV-Senales-Imagenes-e-IA/PINN-estimacion-no-invasiva-presion-arterial-con-PPG-ECG)|
| **_J. Mendoza_** —  Extractor Jerárquico de Características de Embeddings Multidimensionales Usando GMM y k-NN para la Clasificación de Tumores Cerebrales| **A. Veloz** | [Repo](https://github.com/EICB-UV-Senales-Imagenes-e-IA/Hierarchical-Enrichment-using-kNN-and-GMM) |
| **_C. Rodríguez_** — Detección y segmentación automática de lesiones isquémicas en imágenes de tomografía computarizada sin contraste de pacientes con accidente cerebrovascular en base a modelos de Deep Learning | **D. Ortiz** | - |
| **_A. Sanllehi_** — Modelo predictivo de fallas en monitores multiparamétricos basado en machine learning para apoyar la gestión del mantenimiento | **R. Salas** | - |
| **_E. Astargo_** — Sistema Explicable basado en Attention U-Net 3D y Modelos Neuro-Difusos para la Segmentación de Tumores Cerebrales en Imágenes de Resonancia Magnética  | **R. Salas** | - |


## Posters, abstracts de conferencias, u otras publicaciones recientes 📝:

| Título (con presentador) | Conferencia/Journal | DOI |
|--------------------------|------|-----|
| **_C. Osorio_** — Predicción de la ganancia de peso gestacional mediante un modelo lineal mixto multinivel: desarrollo de la aplicación MaternIA (2025) | LACSC 2025, Valparaíso, Chile | In press |
| **_F. Estay_** — Unsupervised Dual-Task W-Net for Intracranial Hemorrhage Detection and Segmentation in Non-Contrast CT (2025) | ICPRS 2025 | <a href="https://doi.org/10.1109/ICPRS66293.2025.11302854"><img src="https://img.shields.io/badge/10.1109%2FICPRS66293.2025.11302854-black" align="right"/></a> |
| **_G. Guerra_** — Visual Explainability of Attention U-Net for Brain Tumor Segmentation in Multicontrast Magnetic Resonance Images (2025) | SIPAIM 2025, Pasto, Colombia | <a href="https://doi.org/10.1109/SIPAIM67325.2025.11283424"><img src="https://img.shields.io/badge/10.1109%2FSIPAIM67325.2025.11283424-black" align="right"/></a> |
| **_C. Rodríguez_** — Performance comparison of supervised and unsupervised deep learning models for ischemic lesion detection in stroke non-contrast CT images (2025) | SIPAIM 2025, Pasto, Colombia | <a href="https://doi.org/10.1109/SIPAIM67325.2025.11283380"><img src="https://img.shields.io/badge/10.1109%2FSIPAIM67325.2025.11283380-black" align="right"/></a> |
| **_A. A. Sanllehi_** — Modelo predictivo de fallas en monitores multiparamétricos basado en machine learning para apoyar la gestión del mantenimiento | SINVIE 2025, Arica, Chile | In press |



---

## 🤝 Quiénes participan

Este espacio está destinado a estudiantes de pregrado y posgrado, ayudantes, investigadores y docentes del área de **Señales, Imágenes e Inteligencia Artificial** de la EICB.

---

## 📬 Contacto del área

**Coordinación del Área SIIA — Escuela de Ingeniería Civil Biomédica - UV**  
Universidad de Valparaíso  
✉️ *david.ortiz@uv.cl*  
🌐 https://www.biomedica.uv.cl/

---
