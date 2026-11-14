# Python para Análisis de Datos · Comisión 86215

Material de apoyo del curso. Acá vas a encontrar los notebooks de cada clase, para abrirlos y practicar desde el navegador, **sin instalar nada**.

**Instructora:** Ailén Iglesias Barrera

Sábados de 10 a 13hs

> 📘 **La teoría oficial está en las presentaciones del aula virtual.** Los notebooks las acompañan con práctica y no las reemplazan: en cada sección se indica qué presentación consultar.

---

## 📁 Contenido por clase

| Clase | Notebook | Tema | Presentación (aula virtual) | Abrir en Colab |
|---|---|---|---|---|
| 1 | `clase1_alumnos.ipynb` | Datos, variables y colecciones. Lo completamos en clase | Módulo 1 | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibarrera/Python_Analisis_de_Datos_86215/blob/main/clase1_alumnos.ipynb) |
| 1 | `clase1_repaso.ipynb` | Repaso para hacer durante la semana, con autoevaluación | Módulo 1 | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibarrera/Python_Analisis_de_Datos_86215/blob/main/clase1_repaso.ipynb) |
| 2 · Parte 1 | `clase2_parte1_repaso_modulo1_alumnos.ipynb` | Repaso del Módulo 1: variables, colecciones, control de flujo y listas por comprensión | Módulo 1 | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibarrera/Python_Analisis_de_Datos_86215/blob/main/clase2_parte1_repaso_modulo1_alumnos.ipynb) |
| 2 · Parte 2 | `clase2_parte2_funciones_alumnos.ipynb` | Módulo 2: funciones, argumentos, `map`/`filter`, `lambda`, `sorted` y módulos | Módulo 2 | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibarrera/Python_Analisis_de_Datos_86215/blob/main/clase2_parte2_funciones_alumnos.ipynb) |
| 3 · Parte 1 | `clase3_parte1_repaso_alumnos.ipynb` | Repaso exprés: listas por comprensión, `*args`/`**kwargs`, `map`/`filter`, `lambda`/`sorted`/`key` y módulos | Módulos 1 y 2 | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibarrera/Python_Analisis_de_Datos_86215/blob/main/clase3_parte1_repaso_alumnos.ipynb) |
| 3 · Parte 2 | `clase3_parte2_numpy_alumnos.ipynb` | Módulo 3 · NumPy: arrays, indexing, vectorización, broadcasting, filtros, agregaciones y álgebra lineal | Módulo 3 (ppt 1 a 4) | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibarrera/Python_Analisis_de_Datos_86215/blob/main/clase3_parte2_numpy_alumnos.ipynb) |

> Cada semana se suman nuevos notebooks.

---

## 🛠️ ¿Con qué herramientas trabajamos?

| Herramienta | Cuándo | Necesita instalación |
|---|---|---|
| **Google Colab** | Principal herramienta por ahora | No (solo una cuenta de Google) |
| **Jupyter online** (JupyterLite) | Alternativa si no tenés cuenta de Google | No |
| **Versión de escritorio** (Anaconda o editor de texto) | La vemos y profundizamos durante la semana | Sí |

> 💡 **NumPy ya viene instalado en Colab**: para la Clase 3 alcanza con ejecutar `import numpy as np`.

---

## 1 · Google Colab (herramienta principal)

**Colab** es un entorno de notebooks de Google que funciona desde el navegador. Python ya viene instalado y el código se ejecuta en la nube.

### Cómo se usa
1. Hacé clic en el botón **Abrir en Colab** de la tabla de arriba e **iniciá sesión** con tu cuenta de Google si te lo pide.
2. **Guardá tu propia copia** para no perder tus cambios: menú **Archivo → Guardar una copia en Drive**. *Los cambios que hagas en el notebook original no se guardan en GitHub.*
3. Un notebook tiene **celdas de texto** y **celdas de código**. Para ejecutar una celda de código: hacé clic en ella y presioná **`Shift + Enter`** (o el botón ▶ de la izquierda).
4. **Ejecutá las celdas en orden, de arriba hacia abajo.** Si saltás una, puede aparecer un error porque falta algo que se definía antes.
5. Para agregar celdas usá los botones **+ Código** y **+ Texto** de la barra superior.
6. Si algo se traba o querés empezar de cero: **Entorno de ejecución → Reiniciar sesión**. Para ejecutar todo de una vez: **Entorno de ejecución → Ejecutar todas**.
7. Para guardar una copia en tu computadora: **Archivo → Descargar → Descargar .ipynb**.

> 💡 Si en el notebook aparece un **error** en rojo, no pasa nada: leé la **última línea**, dice qué falló. En algunas celdas el error es **a propósito** (están marcadas con ⚠️) para que veas cómo se lee.

---

## 2 · Jupyter online (alternativa sin cuenta)

👉 **<https://jupyter.org/try-jupyter/lab/>**

Es **JupyterLite**: una versión de Jupyter que corre **dentro de tu navegador**, sin cuenta y sin instalar nada.

### Cómo se usa
1. Abrí el enlace y esperá a que cargue (la primera vez puede tardar un poco).
2. Descargá el notebook desde este repositorio: abrí el archivo `.ipynb` en GitHub y hacé clic en el botón **Download raw file** (ícono de descarga, arriba a la derecha del archivo).
3. En el panel de archivos de la izquierda, usá el botón **Upload** (flecha hacia arriba) y elegí el notebook descargado.
4. Hacé doble clic para abrirlo. Si te pide un *kernel*, elegí **Python**.
5. Ejecutá cada celda con **`Shift + Enter`**, de arriba hacia abajo.

### Para tener en cuenta
- Tu trabajo **se guarda en el navegador**, no en la nube. Para conservarlo, **descargá el notebook** (clic derecho sobre el archivo → **Download**).
- Es más lento que Colab y algunas librerías pueden no estar disponibles o necesitar instalación. **Para NumPy te recomendamos Colab.**
- Si cambiás de navegador o borrás los datos del sitio, el trabajo puede perderse.

---

## 3 · Versión de escritorio (la vemos durante la semana)

Durante la semana vamos a ver y a profundizar en cómo trabajar **en tu computadora**:
- **Anaconda** (instala Python y Jupyter): <https://www.anaconda.com/download>
- **Un editor de texto**, por ejemplo **Visual Studio Code** con la extensión *Jupyter*: <https://code.visualstudio.com/>
- Documentación de Jupyter: <https://jupyter.org/install>

*No hace falta instalar nada antes de esa instancia.*

---

## ⌨️ Atajos útiles

| Atajo | Qué hace |
|---|---|
| `Shift + Enter` | ejecuta la celda y pasa a la siguiente |
| `Ctrl + Enter` | ejecuta la celda y se queda en ella |
| `Ctrl + M` luego `B` (Colab) | agrega una celda de código debajo |

---

## 📝 Sobre el material

Los datos de ejemplo son **ficticios** (la cadena de tiendas **ModaSur**, que usamos desde la Clase 2), salvo los números de la Encuesta de Sueldos, que se citan con su fuente.

Si un notebook necesita crear un archivo (por ejemplo, la Clase 2 · Parte 2 genera `modulo_modasur.py` con `%%writefile`), **no hace falta descargarlo**: el propio notebook lo genera al ejecutarse.

---

## 🔗 Recursos

**Vistos en clase**
- [Encuesta de Sueldos 2026.01 · OpenQube](https://sueldos.openqube.io/encuesta-sueldos-2026.01/): datos reales que usamos como ejemplo.

**Para profundizar en NumPy (Clase 3)**
- [NumPy · What is NumPy?](https://numpy.org/devdocs/user/whatisnumpy.html): documentación oficial (en inglés).
- [NumPy · absolute beginners](https://numpy.org/doc/stable/user/absolute_beginners): guía oficial para empezar.
- VanderPlas, J. (2022). *Python Data Science Handbook*, 2.ª ed., O'Reilly. Cap. 8, «Computation on Arrays: Broadcasting»: <https://www.oreilly.com/library/view/python-data-science/9781098121211/ch08.html>

**Sitios útiles**
- Estadística: <https://www.khanacademy.org/math/probability>
- Comunidad de analistas y científicos de datos: <https://www.kaggle.com/>
- Descarga de Anaconda: <https://www.anaconda.com/download/success>
- Proyectos y librerías de Python (el repositorio más grande): <https://pypi.org/>

---

## 🔄 Las 4 etapas del Análisis de Datos

**1. Recolección de datos (fuentes)**
1. Bases de datos
2. Archivos txt, csv, xls, etc.
3. Webs
4. APIs (*Application Program Interface*)

**2. Limpieza** (quizás la más costosa en esfuerzo)
1. Ordenamiento
2. Depuración
3. Búsqueda de datos confiables y consistentes

**3. Análisis**
1. Herramientas (técnicas de Python)
2. Estadística
3. Metodología de construcción de dashboards

**4. Presentación de la información**
- Storytelling
- **Conclusiones**
- **Se toman decisiones**

> *"El AD no sirve si no se toman decisiones."*
