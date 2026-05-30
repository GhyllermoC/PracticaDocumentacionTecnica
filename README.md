# ➕ Programa Básico de Suma en Python V1.0.0 BMV-JIRA

Este es un programa sencillo en Python que permite sumar dos números ingresados por el usuario desde la consola.

---

## 📌 Descripción

El programa realiza las siguientes acciones:

1. Solicita al usuario dos números.
2. Convierte los valores ingresados a tipo `float`.
3. Realiza la suma de ambos números.
4. Muestra el resultado en pantalla.

---

## 🧠 Código del Programa

```python
# Programa básico para sumar dos números

# Pedimos los números al usuario
numero1 = float(input("Ingresa el primer número: "))
numero2 = float(input("Ingresa el segundo número: "))

# Realizamos la suma
resultado = numero1 + numero2

# Mostramos el resultado
print("La suma es:", resultado)
