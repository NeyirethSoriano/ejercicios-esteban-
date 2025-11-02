📘 proyecto_A/README_A.md
# 🧮 Proyecto A – Entorno Virtual con Jupyter

## 📖 Descripción

Este proyecto demuestra el uso de un entorno virtual en Python con el paquete **Jupyter**.  
Incluye un script (`algoritmo_a.py`) y un notebook (`notebook_a.ipynb`) que ejecutan ejemplos básicos de algoritmos.

---

## 🐍 Versión de Python utilizada
**Python 3.11**

---

## ⚙️ Configuración del entorno virtual

### 1️⃣ Crear el entorno
```bash
python3 -m venv venv_1

2️⃣ Activar el entorno
source venv_1/bin/activate


📸 Captura sugerida: Activación del entorno venv_1.

📦 Instalación de paquetes

Instalar el paquete Jupyter:

pip install jupyter


📸 Captura sugerida: Instalación de jupyter.

🧾 Generar archivo requirements.txt
pip freeze > requirements.txt


📸 Captura sugerida: Contenido del archivo requirements.txt.

▶️ Ejecución
Script principal
cd src
python algoritmo_a.py


Salida esperada:

El factorial de 5 es 120

Notebook

Ejecutar en Jupyter:

jupyter notebook src/notebook_a.ipynb


📸 Captura sugerida: Ejecución del notebook o del script en terminal.

📁 Estructura del proyecto
proyecto_A/
│
├─ venv_1/            ← (no se sube al repositorio)
├─ src/
│   ├─ algoritmo_a.py
│   └─ notebook_a.ipynb
├─ requirements.txt
└─ README_A.md

✍️ Autor

Neyireth Soriano
📅 Noviembre de 2025


---

## 📗 **proyecto_B/README_B.md**

```markdown
# 📊 Proyecto B – Entorno Virtual con Pandas

## 📖 Descripción

Este proyecto utiliza el paquete **pandas** dentro de un entorno virtual de Python para crear y manipular estructuras de datos.  
Incluye dos scripts: uno para crear un DataFrame y otro para realizar operaciones con sus columnas.

---

## 🐍 Versión de Python utilizada
**Python 3.11**

---

## ⚙️ Configuración del entorno virtual

### 1️⃣ Crear el entorno
```bash
python3 -m venv venv_2

2️⃣ Activar el entorno
source venv_2/bin/activate


📸 Captura sugerida: Activación del entorno venv_2.

📦 Instalación de paquetes

Instalar el paquete pandas:

pip install pandas


📸 Captura sugerida: Instalación de pandas.

🧾 Generar archivo requirements.txt
pip freeze > requirements.txt


📸 Captura sugerida: Contenido del archivo requirements.txt.

▶️ Ejecución
Script 1 – algoritmo_b1.py
cd src
python algoritmo_b1.py


Salida esperada:

  Nombre  Edad
0    Ana    23
1   Luis    34
2  Pedro    29

Script 2 – algoritmo_b2.py
python algoritmo_b2.py


Salida esperada:

   A  B  C
0  1  4  5
1  2  5  7
2  3  6  9


📸 Captura sugerida: Ejecución de ambos scripts.

📁 Estructura del proyecto
proyecto_B/
│
├─ venv_2/            ← (no se sube al repositorio)
├─ src/
│   ├─ algoritmo_b1.py
│   └─ algoritmo_b2.py
├─ requirements.txt
└─ README_B.md
