# Python para Análisis de Datos · Comisión 86215

Material de apoyo del curso. Acá vas a encontrar los notebooks de cada clase, para abrirlos y practicar desde el navegador, **sin instalar nada**.

**Instructura:** Ailén Iglesias Barrera

Sábados de 10 a 13hs

## 📁 Contenido

| Archivo | Qué es |
|---|---|
| `clase1_alumnos.ipynb` | Notebook de la Clase 1: datos, variables y colecciones. Lo completamos en clase |
| `clase1_repaso.ipynb` | Repaso para hacer durante la semana, desde cero, con autoevaluación |

> Cada semana se suman nuevos notebooks.

## 🛠️ ¿Con qué herramientas trabajamos?

| Herramienta | Cuándo | Necesita instalación |
|---|---|---|
| **Google Colab** | Clase 1 y principal herramienta por ahora | No (solo una cuenta de Google) |
| **Jupyter online** (JupyterLite) | Alternativa si no tenés cuenta de Google | No |
| **Versión de escritorio** (Anaconda o editor de texto) | La vemos y profundizamos durante la semana | Sí |

---

## 1 · Google Colab (herramienta principal)

**Colab** es un entorno de notebooks de Google que funciona desde el navegador. Python ya viene instalado y el código se ejecuta en la nube.

### Abrir un notebook de este repositorio
Hacé clic en el botón de cada notebook:

| Notebook | Abrir |
|---|---|
| Clase 1 | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibarrera/Python_Analisis_de_Datos_86215/blob/main/clase1_alumnos.ipynb) |
| Repaso | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aibarrera/Python_Analisis_de_Datos_86215/blob/main/clase1_repaso.ipynb) |

### Cómo se usa
1. **Iniciá sesión** con tu cuenta de Google si te lo pide.
2. **Guardá tu propia copia** para no perder tus cambios: menú **Archivo → Guardar una copia en Drive**. *Los cambios que hagas en el notebook original no se guardan en GitHub.*
3. Un notebook tiene **celdas de texto** y **celdas de código**. Para ejecutar una celda de código: hacé clic en ella y presioná **`Shift + Enter`** (o el botón ▶ de la izquierda).
4. **Ejecutá las celdas en orden, de arriba hacia abajo.** Si saltás una, puede aparecer un error porque falta algo que se definía antes.
5. Para agregar celdas usá los botones **+ Código** y **+ Texto** de la barra superior.
6. Si algo se traba o querés empezar de cero: **Entorno de ejecución → Reiniciar sesión**. Para ejecutar todo de una vez: **Entorno de ejecución → Ejecutar todas**.
7. Para guardar una copia en tu computadora: **Archivo → Descargar → Descargar .ipynb**.

> 💡 Si en el notebook aparece un **error** en rojo, no pasa nada: leé la **última línea**, dice qué falló.

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
- Es más lento que Colab y algunas librerías pueden no estar disponibles o necesitar instalación.
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

## 🔗 Recursos vistos en clase
- [Encuesta de Sueldos 2026.01 · OpenQube](https://sueldos.openqube.io/encuesta-sueldos-2026.01/): datos reales que usamos como ejemplo.

## 📝 Sobre el material
Los datos de ejemplo son **ficticios**, salvo los números de la Encuesta de Sueldos, que se citan con su fuente.

---
### Sitio para aprender estadistica

- https://www.khanacademy.org/math/probability

### Sitio de los Analistas de Datos y Cientificos de Datos

- https://www.kaggle.com/

### Sitio de descarga de Anaconda

- https://www.anaconda.com/download/success


### Sitio de proyectos / librerias mas grande del mundo con Python

- https://pypi.org/

## 4 Etapas del Análisis de Datos

### Primer etapa de AD

- Recolección de Datos (Fuentes)
  1. Base de Datos
  2. Archivos txt, csv, xls, etc
  3. Webs
  4. APIs (Application Program Interface) - Interfaces 

### Segunda etapa de AD  

- Limpieza (quizas es el mas costoso en esfuerzo)
  1. Ordenamiento
  2. Depuración 
  3. Busqueda de datos confiables y consistentes

### Tercer etapa de AD

- Análisis 
  1. Herramientas (tecnica de Python)
  2. Estadistica 
  3. Metodologia de construcción de Dashboards

### Cuarta etapa de AD

- Presentación de la información
- Storytelling 
- **Conclusiones**

- SE TOMAN DECISIONES

"El AD no sirve si no se toman decisiones"
