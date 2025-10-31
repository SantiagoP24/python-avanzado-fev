# 🧠 Módulo 1 — Expresiones Regulares en Python

Las **expresiones regulares** (regex) son una herramienta fundamental para **buscar, validar, extraer y transformar texto**.
En este módulo aprenderás a dominar el módulo estándar `re` de Python y a aplicarlo a casos reales de validación, limpieza y análisis de datos.

---

## 🎯 Objetivos de aprendizaje

Al finalizar el módulo, el alumno será capaz de:

* Comprender la sintaxis básica y avanzada de las expresiones regulares.
* Utilizar las funciones principales del módulo `re` (`findall`, `match`, `search`, `split`, `sub`).
* Aplicar metacaracteres, cuantificadores y grupos de captura.
* Validar formatos comunes (emails, fechas, DNI, teléfonos, etc.).
* Realizar reemplazos inteligentes y limpieza de texto.
* Integrar expresiones regulares en flujos de análisis, ETL y preprocesado de datos.

---

## 📘 Estructura de notebooks

|    Nº   | Notebook                                  | Contenido principal                                                               |       |
| :-----: | :---------------------------------------- | :-------------------------------------------------------------------------------- | ----- |
| **1.1** | `11_re_intro.ipynb`                       | Introducción al módulo `re` y conceptos fundamentales de regex.                   |       |
| **1.2** | `12_re_metacaracteres.ipynb`              | Metacaracteres básicos: `. ^ $ * + ? { } [ ]                                      | ( )`. |
| **1.3** | `13_re_cuantificadores_y_grupos.ipynb`    | Cuantificadores, agrupaciones y grupos no capturantes.                            |       |
| **1.4** | `14_re_funciones_findall_match_sub.ipynb` | Funciones de búsqueda y reemplazo (`findall`, `match`, `search`, `split`, `sub`). |       |
| **1.5** | `15_re_validaciones_formatos.ipynb`       | Validaciones de formatos reales (emails, DNI, fechas, teléfonos, URLs).           |       |
| **1.6** | `16_re_reemplazos_y_limpieza.ipynb`       | Limpieza y normalización de texto con reemplazos avanzados.                       |       |
| **1.7** | `17_re_reto_global.ipynb`                 | Reto final: procesamiento y anonimización de logs reales.                         |       |

---

## 🧩 Metodología didáctica

Cada notebook combina:

1. **Bloques teóricos** en celdas Markdown con explicaciones y ejemplos.
2. **Celdas de práctica inmediata**, que el alumno puede ejecutar y modificar.
3. **Mini ejercicios guiados**, con comentarios y pistas.
4. **Reto final integrador**, aplicando todos los conceptos del módulo.

💡 Se recomienda ejecutar los notebooks en orden dentro de VS Code Codespaces o Jupyter Lab.

---

## 🔧 Requisitos técnicos

* Python ≥ 3.10
* Librerías estándar (`re`)
* Editor compatible con Jupyter Notebooks (VS Code, JupyterLab o Google Colab)

Para abrir el entorno en Codespaces:

```bash
cd notebooks/modulo1_regex
code .
```

---

## 🧠 Evaluación sugerida

| Tipo de actividad      | Descripción                                 | Peso |
| :--------------------- | :------------------------------------------ | :--: |
| Cuestionario rápido    | 10 preguntas tipo test sobre sintaxis regex | 20 % |
| Ejercicios intermedios | Validaciones y búsquedas con `findall`      | 30 % |
| Reto 1.7               | Procesamiento y limpieza de logs            | 50 % |

---

## 📚 Recursos y referencias

* [Documentación oficial de Python – módulo `re`](https://docs.python.org/3/library/re.html)
* [Regular Expressions 101 (visualizador online)](https://regex101.com)
* [Real Python – Regular Expressions](https://realpython.com/regex-python/)