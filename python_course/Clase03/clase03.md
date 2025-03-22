# 🐍 Python Profesional
## Cheatsheet - Clase 03

# Cheatsheet - Día 3: Entrada de Datos y Concatenación

---

## 📂 Entrada de Datos con `input()`

En Python, la función `input()` permite al usuario ingresar datos desde la consola.

```python
nombre = input("¿Cuál es tu nombre?: ")
print("Hola,", nombre, "! Bienvenido a Python.")
```

---

## 👉 Concatenación con `,`

Podemos unir textos y variables de forma sencilla usando `,`, lo que mejora la legibilidad y permite la conversión automática de tipos de datos.

```python
nombre = "Carlos"
edad = 30
print("Mi nombre es", nombre, "y tengo", edad, "años.")
```

> 🔹 **Ventaja:** Con `,` no es necesario convertir tipos de datos manualmente, ya que `print()` lo hace automáticamente.

---

## 🏆 Ejercicio práctico

**Crea un programa que solicite al usuario su color favorito, número favorito, comida favorita y serie favorita de TV, y luego muestre los datos ingresados.**

```python
color = input("Ingresa tu color favorito: ")
numero = input("Ingresa tu número favorito: ")
comida = input("Ingresa tu comida favorita: ")
serie = input("Ingresa tu serie favorita: ")

print("Tus datos ingresados son:")
print("Color favorito:", color)
print("Número favorito:", numero)
print("Comida favorita:", comida)
print("Serie favorita:", serie)
```

---

🏅 **Listo para el siguiente día?** Mañana veremos **Operadores en Python**! 🚀