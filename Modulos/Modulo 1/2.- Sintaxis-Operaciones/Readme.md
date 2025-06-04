# 🐍 Módulo 1.2: Sintaxis y Operaciones en Python

> **Objetivo**: Al finalizar este módulo, conocerás la sintaxis básica de Python, sabrás cómo declarar variables, utilizar operadores aritméticos, lógicos y de comparación, y podrás escribir tus primeras expresiones y operaciones básicas en este lenguaje.

---

## ✍️ Sintaxis básica

Python se caracteriza por tener una sintaxis **simple y legible**, sin necesidad de llaves `{}` ni punto y coma `;`.

### 📌 Reglas clave:
- Los **bloques de código** se definen por **indentación** (espacios o tabulación).
- Las **instrucciones** se escriben en líneas separadas.
- No se necesita declarar el tipo de dato (tipado dinámico).

```python
# Esto es un comentario
x = 5       # Asignación de valor entero
nombre = "Ana"  # Cadena de texto
```

## 🔣 Operadores en Python
➕ Operadores Aritméticos
| Operador | Descripción     | Ejemplo         |
| -------- | --------------- | --------------- |
| `+`      | Suma            | `3 + 2` → `5`   |
| `-`      | Resta           | `5 - 1` → `4`   |
| `*`      | Multiplicación  | `4 * 2` → `8`   |
| `/`      | División        | `6 / 3` → `2.0` |
| `//`     | División entera | `7 // 2` → `3`  |
| `%`      | Módulo (resto)  | `7 % 3` → `1`   |
| `**`     | Potencia        | `2 ** 3` → `8`  |

🔁 Operadores de Comparación
| Operador | Descripción       | Ejemplo  |
| -------- | ----------------- | -------- |
| `==`     | Igual a           | `x == 5` |
| `!=`     | Distinto de       | `x != 3` |
| `>`      | Mayor que         | `x > 4`  |
| `<`      | Menor que         | `x < 10` |
| `>=`     | Mayor o igual que | `x >= 5` |
| `<=`     | Menor o igual que | `x <= 7` |

⚙️ Operadores Lógicos
| Operador | Descripción                           | Ejemplo            |
| -------- | ------------------------------------- | ------------------ |
| `and`    | Verdadero si ambas condiciones lo son | `x > 0 and x < 10` |
| `or`     | Verdadero si al menos una lo es       | `x < 0 or x > 5`   |
| `not`    | Invierte el valor lógico              | `not x == 5`       |
