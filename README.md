# 📊 Análisis de Perfil de Intensidad en Imagen Radiográfica

Este repositorio contiene un notebook escrito en **Perl** con el kernel **IPerl**, donde se explora el análisis de imágenes clínicas (radiografías) mediante la extracción de un **perfil de intensidad horizontal** usando `PDL` y `PDL::OpenCV`, junto con visualizaciones interactivas con `Chart::Plotly`.

---

## 🧪 Objetivo

Analizar imágenes médicas digitales, particularmente radiografías, extrayendo perfiles de intensidad que permiten:

- Identificar bordes o transiciones de densidad.
- Estudiar estructuras internas con fines didácticos o clínicos.
- Desarrollar herramientas cuantitativas simples para el análisis de imágenes.

---

## 🧰 Tecnologías utilizadas

- **Perl**
- [PDL (Perl Data Language)](https://pdl.perl.org/)
- [PDL::OpenCV](https://metacpan.org/pod/PDL::OpenCV)
- [Chart::Plotly](https://metacpan.org/pod/Chart::Plotly)
- Kernel **IPerl** en Jupyter Notebooks

---

## 📂 Archivos

- `perfil_Intensidad_Xchest_pdl_opencv.ipynb` — Notebook principal con el análisis.
- `Chest_Xray_PA_3-8-2010.png` — Imagen utilizada para el análisis (puede reemplazarse).
- `README.md` — Este archivo.

---

## 💡 ¿Cómo ejecutar este notebook?

Este notebook está hecho en Perl usando el kernel IPerl.  
Puedes ejecutarlo localmente con los siguientes pasos:

1. Instala Perl y `cpanm` (si aún no lo tienes):
   ```bash
   curl -L https://cpanmin.us | perl - App::cpanminus

2. Instala los módulos necesarios
   cpanm Devel::IPerl PDL PDL::OpenCV Chart::Plotly MIME::Base64

3. Abre el notebook en Visual Studio Code
	•	Instala la extensión Jupyter en VSCode.
	•	Asegúrate de tener el kernel IPerl instalado.
	•	Abre el archivo .ipynb y selecciona el kernel Perl.

También puedes usar jupyter notebook desde terminal si prefieres Jupyter clásico.
