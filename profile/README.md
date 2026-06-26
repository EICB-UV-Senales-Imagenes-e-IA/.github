# 🧠📡 SmartBioMed-EICB-UV  
### Área de **Señales, Imágenes e Inteligencia Artificial**  
**Escuela de Ingeniería Civil Biomédica — Universidad de Valparaíso**

Bienvenido(a)s al repositorio oficial del área de **Señales, Imágenes e Inteligencia Artificial (SIIA)** de la EICB-UV.  
Este espacio reúne proyectos académicos, repositorios estudiantiles, material docente y desarrollos asociados al trabajo del área en cursos y actividades de investigación.

### Descripción:

SmartBioMed es un marco conceptual que integra modelos matemáticos y computacionales con datos biomédicos multimodales —incluyendo señales fisiológicas, imágenes médicas y variables clínicas— para avanzar hacia una medicina más precisa, personalizada y basada en evidencia cuantitativa. Inspirado en la idea de los gemelos digitales, SmartBioMed propone la construcción de "hermanos digitales": representaciones computacionales flexibles, no necesariamente completas ni en tiempo real, que permiten estudiar mecanismos fisiológicos, simular escenarios clínicos y explorar respuestas individuales a distintas intervenciones.

Este enfoque establece un marco metodológico común para el área de Señales, Imágenes e Inteligencia Artificial, articulando procesamiento de señales, análisis de imágenes y modelamiento computacional. SmartBioMed integra estas líneas en una base formativa y de investigación que permite abordar problemas biomédicos mediante métodos cuantitativos y modelos basados en datos, manteniendo coherencia con las capacidades actuales del área y proyectando un desarrollo académico y tecnológico sólido.

## 🗂️ Estructura general de los repositorios

Cada repositorio debe incluir un `README.md` principal con el contenido mínimo listado a continuación. Si el proyecto se ejecuta en Colab/Kaggle, mencionarlo explícitamente e incluir una celda inicial con `!pip install paquete==version` en el notebook para las librerías no preinstaladas.

- [ ] Abstract con un resumen del proyecto que presente la motivación, la metodología, los principales resultados, las conclusiones y las limitaciones (máx. 300 palabras).
- [ ] Instrucciones de instalación y uso.
- [ ] Ejemplo mínimo de ejecución (entrada → ejecución → salida esperada), o referencia al notebook correspondiente en `notebooks/`.
- [ ] Gráficas y figuras con los resultados principales y breves descripciones (máx. 5 figuras)
- [ ] Indicación de las dependencias principales y de la versión de Python utilizada.
- [ ] Información sobre licencia y uso (si aplica).

> **💡 Nota**  
>  
> Cada estudiante debe crear el repositorio en su propia cuenta de GitHub y enviarme el link para que yo realice un *fork* hacia la organización SmartBioMed-EICB-UV. El repositorio puede permanecer **privado** si así se requiere (por ejemplo, mientras el trabajo no esté publicado o si contiene material sensible); en ese caso, agregarme como colaborador para poder hacer el *fork*.

### 🏷️ Convención de nombres de repositorio

Para mantener un listado ordenado en la organización, se sugiere nombrar los repositorios siguiendo el formato:

```
SIIA-<año><semestre>-<apellido>-<tema-corto>
```

Por ejemplo: `SIIA-2025-01-Madrid-PINN-PPG-ECG` o `SIIA-2025-02-Alarcon-Airways-ML`. Usar guiones en lugar de espacios y evitar tildes o caracteres especiales.

### 📋 Estructura del repositorio

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
├── data/             # Datos (ver sección "Gestión de datos")
├── notebooks/        # Notebooks con ejemplos funcionales y exploración
├── results/          # Resultados, figuras y outputs generados
├── src/              # Código fuente (módulos, funciones, clases)
├── test/             # Pruebas unitarias o de integración
├── requirements.txt  # (o environment.yml)
└── README.md
```

No es obligatoria, pero sí recomendada. Como mínimo, se espera `src/` (o equivalente) y `notebooks/`.

### 🚀 Cómo unirse al área

Si eres estudiante y quieres incorporar tu proyecto al área SIIA:

1. Crea el repositorio en tu cuenta personal de GitHub siguiendo la convención de nombres y la estructura mínima descritas arriba.
2. Asegúrate de que el `README.md` cumpla con el contenido mínimo (checklist).
3. Envíame el link del repositorio al correo de contacto. Si es privado, agrégame como colaborador.
4. Realizaré el *fork* hacia la organización SmartBioMed-EICB-UV y lo agregaré a la tabla de proyectos correspondiente.
5. Mantén tu repositorio actualizado: la organización refleja los cambios mediante sincronización periódica del *fork*.

### 📦 Gestión de datos

Los datos clínicos o sensibles **no deben subirse al repositorio**. La carpeta `data/` debe contener un `README.md` propio que documente el origen de los datos (institución, dataset público, link o DOI), su licencia y permisos de uso, e instrucciones de descarga (incluyendo la ruta esperada dentro de `data/` si la descarga es manual). Cuando aplique, indicar la versión o fecha de descarga del dataset. Si se trabaja con datos clínicos propios, documentar el procedimiento de anonimización aplicado (con script en `src/` si corresponde). Se recomienda incluir una muestra mínima sintética o anonimizada que permita ejecutar el notebook de ejemplo sin acceso al dataset completo.

### 🔁 Reproducibilidad

Para que el trabajo sea reproducible por otros estudiantes: fijar semillas aleatorias (`numpy`, `random`, `torch`, etc.) al inicio del notebook o script principal; evitar rutas absolutas, usando rutas relativas al repositorio; documentar el preprocesamiento, no solo el modelo final; indicar la versión de Python y, si aplica, de CUDA/GPU; y dejar las salidas (figuras, métricas) ya ejecutadas en el notebook de ejemplo, para que un lector pueda comparar sin re-ejecutar todo.



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

---

## 📬 Contacto del área

**Coordinación del Área SIIA — Escuela de Ingeniería Civil Biomédica - UV**  
Universidad de Valparaíso  
✉️ *david.ortiz@uv.cl*  
🌐 https://www.biomedica.uv.cl/

---
