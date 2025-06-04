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
# Comentario: esto no se ejecuta
x = 5               # Variable entera
nombre = "Ana"      # Cadena de texto
pi = 3.14159        # Número decimal (float)

print("Hola", nombre)  # Imprime: Hola Ana
```
>💡 Consejo: Usa nombres descriptivos para las variables y evita acentos, espacios o caracteres especiales.

## 📦 Tipos de datos comunes
Trayendo a memoria lo que explicamos en el inciso anterior, tenemos: 
| Tipo    | Ejemplo          | Descripción                    |
| ------- | ---------------- | ------------------------------ |
| `int`   | `x = 10`         | Número entero                  |
| `float` | `pi = 3.14`      | Número con decimales           |
| `str`   | `nombre = "Ana"` | Texto (cadena de caracteres)   |
| `bool`  | `activo = True`  | Valor lógico (verdadero/falso) |

```python
# Declaracion
x = 10
pi = 3.14
nombre = "Ana"
activo = True

# Verificando tipos
print(type(x))       # <class 'int'>
print(type(pi))      # <class 'float'>
print(type(nombre))  # <class 'str'>
print(type(activo))  # <class 'bool'>
```
>💡 Consejo: La función type() nos sirve para identificar el tipo de dato de alguna variable

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

```python
a = 10
b = 3
print(a + b)   # 13
print(a % b)   # 1 (resto de 10 dividido entre 3)
```

🔁 Operadores de Comparación
| Operador | Descripción       | Ejemplo  |
| -------- | ----------------- | -------- |
| `==`     | Igual a           | `x == 5` |
| `!=`     | Distinto de       | `x != 3` |
| `>`      | Mayor que         | `x > 4`  |
| `<`      | Menor que         | `x < 10` |
| `>=`     | Mayor o igual que | `x >= 5` |
| `<=`     | Menor o igual que | `x <= 7` |

```python
x = 5
print(x == 5)    # True
print(x < 3)     # False
```

⚙️ Operadores Lógicos
| Operador | Descripción                           | Ejemplo            |
| -------- | ------------------------------------- | ------------------ |
| `and`    | Verdadero si ambas condiciones lo son | `x > 0 and x < 10` |
| `or`     | Verdadero si al menos una lo es       | `x < 0 or x > 5`   |
| `not`    | Invierte el valor lógico              | `not x == 5`       |

```python
x = 7
print(x > 5 and x < 10)  # True
print(x < 3 or x > 6)    # True
print(not x == 7)        # False
```
