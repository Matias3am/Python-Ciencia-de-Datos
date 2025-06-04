# 🐍 Módulo 1.1: Fundamentos de Python

> **Objetivo**: Al finalizar este módulo, entenderás qué es Python, para qué se usa, sus características principales, y conocerás los tipos de datos más comunes, su uso y su peso en memoria. Este es el primer paso para convertirte en desarrollador/a con Python.

---

## 📘 ¿Qué es Python?

Python es un lenguaje de programación **interpretado**, **de alto nivel**, **multiparadigma** y **fácil de leer**.

Fue creado por **Guido van Rossum** y lanzado en 1991. Su principal ventaja es que permite escribir código claro y conciso.

### 🔎 ¿Dónde se usa Python?

| Área                 | Aplicaciones comunes                             |
|----------------------|--------------------------------------------------|
| Ciencia de Datos     | Análisis de datos, Machine Learning, visualización |
| Desarrollo Web       | Backend con frameworks como Django o Flask      |
| Automatización       | Scripts para tareas repetitivas                  |
| Videojuegos          | Motores simples, prototipado                     |
| Educación            | Ideal para aprender lógica de programación      |

---

## 🧠 ¿Por qué aprender Python?

✅ Sintaxis simple  
✅ Comunidad enorme  
✅ Multiplataforma  
✅ Librerías para TODO  
✅ Muy solicitado en el mercado laboral

---

## 🧮 ¿Qué es un programa en Python?

Un programa en Python es simplemente un archivo de texto con extensión `.py` que contiene **instrucciones** que el intérprete de Python ejecutará línea por línea.

```python
# Ejemplo de programa básico
print("¡Hola, mundo!")
```

## 🛠️ ¿Cómo escribir y ejecutar un programa en Python?
### ✍️ 1. Escribir el código
Puedes escribir código Python en cualquier editor de texto (como Notepad, VS Code, Sublime Text) o en entornos especializados como Jupyter Notebook o PyCharm.

* Abre tu editor favorito.
* Escribe tu código, por ejemplo:
  
```python
print("¡Hola, mundo!")
```

> Guarda el archivo con la extensión .py, por ejemplo: saludo.py.
  
### ▶️ 2. Ejecutar el código (compilar no es necesario)
Python es un lenguaje interpretado, lo que significa que no necesitas compilar el código antes de ejecutarlo. Solo necesitas tener Python instalado en tu sistema.

En la terminal o consola:
* Abre la terminal (CMD en Windows, Terminal en macOS/Linux).
* Navega hasta la carpeta donde guardaste el archivo.
* Ejecuta el archivo con el comando:
  
```python
python saludo.py
```

> Nota: En algunos sistemas puede ser python3 en lugar de python  o py a secas.

### 🧪 ¿Cómo saber si tienes Python instalado?
Escribe en la terminal:

```terminal
python --version
```

Si ves algo como Python 3.X.X, ¡ya estás listo para comenzar!

## 🧱 Tipos de Datos en Python

Python tiene varios tipos de datos básicos. Cada uno representa una forma diferente de almacenar y manipular información.
| Tipo    | Ejemplo          | Descripción                       | Tamaño Aproximado |
| ------- | ---------------- | --------------------------------- | ----------------- |
| `int`   | `42`             | Números enteros                   | Depende del valor |
| `float` | `3.14`           | Números decimales (coma flotante) | \~24 bytes        |
| `str`   | `"Hola"`         | Cadenas de texto                  | 49 + 1 byte/carac |
| `bool`  | `True` / `False` | Valores booleanos                 | \~24 bytes        |
| `list`  | `[1, 2, 3]`      | Lista de elementos ordenados      | Variable          |
| `dict`  | `{"a": 1}`       | Diccionario clave-valor           | Variable          |
| `None`  | `None`           | Representa ausencia de valor      | \~16 bytes        |




