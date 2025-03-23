# 🐍 Python Profesional  
## Cheatsheet - Clase 04  

# Cheatsheet - Día 4: Operadores Aritméticos y Conversión de Tipos  

---

## ➖️ Operadores Aritméticos en Python  

Los operadores aritméticos permiten realizar cálculos matemáticos en Python.  

| Operador | Descripción           | Ejemplo (`a = 10`, `b = 3`) | Resultado |
|----------|-----------------------|----------------------------|-----------|
| `+`      | Suma                  | `a + b`                    | `13`      |
| `-`      | Resta                 | `a - b`                    | `7`       |
| `*`      | Multiplicación         | `a * b`                    | `30`      |
| `/`      | División (decimal)     | `a / b`                    | `3.3333`  |
| `//`     | División entera        | `a // b`                   | `3`       |
| `%`      | Módulo (residuo)       | `a % b`                    | `1`       |
| `**`     | Exponenciación         | `a ** b`                   | `1000`    |

```python
a = 10
b = 3

print("Suma:", a + b)       # 13
print("Resta:", a - b)      # 7
print("Multiplicación:", a * b)  # 30
print("División:", a / b)   # 3.3333
print("División entera:", a // b) # 3
print("Módulo:", a % b)     # 1
print("Exponenciación:", a ** b) # 1000
```

---

## 🔄 Conversión de Tipos con `int()`  

La función `int()` convierte un string numérico en un número entero.  

```python
num_str = "10"
num_int = int(num_str)

print(num_int, type(num_int))  # Output: 10 <class 'int'>
```

> ⚠ **Nota:** `int()` solo funciona con números enteros en formato string. Si intentas convertir un texto, Python mostrará un error.  

---

## 🏷️ Verificar Tipo de Dato con `type()`  

La función `type()` muestra el tipo de una variable o valor.  

```python
print(type(10))      # <class 'int'>
print(type(10.5))    # <class 'float'>
print(type("Hola"))  # <class 'str'>
```

---

## 🏆 Ejercicio Práctico  

**Crea un programa que pida dos números al usuario y realice las cuatro operaciones básicas (suma, resta, multiplicación y división).**  

```python
num1 = int(input("Ingresa el primer número: "))
num2 = int(input("Ingresa el segundo número: "))

print("Suma:", num1 + num2)
print("Resta:", num1 - num2)
print("Multiplicación:", num1 * num2)
print("División:", num1 / num2)
```

---

🏅 **Listo para el siguiente día?** Mañana veremos **Operadores Relacionales o de Comparacion en Python**! 🚀

