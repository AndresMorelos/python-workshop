---
theme: seriph
background: https://images.unsplash.com/photo-1555066931-4365d14bab8c?w=1920&q=80
title: Python para Negocios
info: |
  Clase introductoria de Python para estudiantes de Administración de Empresas.
  Aprende variables, listas, diccionarios, condicionales, ciclos y funciones.
class: text-center
highlighter: shiki
drawings:
  persist: false
transition: slide-left
mdc: true
---

# Python para Negocios 🐍

### Programación aplicada a Administración de Empresas

<div class="pt-12">
  <span class="px-4 py-2 rounded-full bg-blue-600 text-white text-sm font-semibold tracking-wide">
    Introducción a Python · Administración de Empresas
  </span>
</div>

---
layout: default
---

# ¿Qué es Python?

Python es un **lenguaje de programación** que le permite a las computadoras seguir instrucciones que tú escribes, en un lenguaje casi igual al inglés.

<div class="grid grid-cols-2 gap-8 mt-8">

<div>

## Sin Python 😰
- Cálculos manuales y propensos a error
- Hojas de Excel con fórmulas complejas
- Copiar y pegar datos entre archivos
- Reportes que tardan horas en preparar

</div>

<div>

## Con Python ✅
- Cálculos automáticos en segundos
- Análisis de miles de registros
- Reportes generados con un clic
- Decisiones basadas en datos reales

</div>

</div>

<div class="mt-8 p-4 bg-blue-50 dark:bg-blue-900/30 rounded-lg border border-blue-200 dark:border-blue-700">
  <strong>Python</strong> es el lenguaje más usado en el mundo para análisis de datos, finanzas, automatización y negocios. Lo usan empresas como Google, Netflix y bancos internacionales.
</div>

---
layout: default
---

# ¿Para qué lo usamos en los negocios?

<div class="grid grid-cols-3 gap-5 mt-8">

<div class="p-5 rounded-xl border-2 border-blue-300 bg-blue-50 dark:bg-blue-900/30">
  <div class="text-3xl mb-3">📊</div>
  <div class="font-bold text-blue-700 dark:text-blue-300 mb-2">Análisis de Ventas</div>
  <div class="text-sm text-gray-600 dark:text-gray-300">Calcular totales, promedios, máximos y mínimos de cualquier período automáticamente.</div>
</div>

<div class="p-5 rounded-xl border-2 border-green-300 bg-green-50 dark:bg-green-900/30">
  <div class="text-3xl mb-3">👥</div>
  <div class="font-bold text-green-700 dark:text-green-300 mb-2">Gestión de Personal</div>
  <div class="text-sm text-gray-600 dark:text-gray-300">Nóminas, bonos, clasificación de empleados y cálculo de impuestos de forma automática.</div>
</div>

<div class="p-5 rounded-xl border-2 border-purple-300 bg-purple-50 dark:bg-purple-900/30">
  <div class="text-3xl mb-3">💰</div>
  <div class="font-bold text-purple-700 dark:text-purple-300 mb-2">Finanzas</div>
  <div class="text-sm text-gray-600 dark:text-gray-300">Cálculo de IVA, márgenes, descuentos, presupuestos y proyecciones financieras.</div>
</div>

<div class="p-5 rounded-xl border-2 border-orange-300 bg-orange-50 dark:bg-orange-900/30">
  <div class="text-3xl mb-3">📦</div>
  <div class="font-bold text-orange-700 dark:text-orange-300 mb-2">Inventario</div>
  <div class="text-sm text-gray-600 dark:text-gray-300">Rastrear stock, alertas de reorden y valoración de inventario en tiempo real.</div>
</div>

<div class="p-5 rounded-xl border-2 border-red-300 bg-red-50 dark:bg-red-900/30">
  <div class="text-3xl mb-3">📈</div>
  <div class="font-bold text-red-700 dark:text-red-300 mb-2">Reportes</div>
  <div class="text-sm text-gray-600 dark:text-gray-300">Generar reportes de ventas, desempeño y KPIs automáticamente cada semana.</div>
</div>

<div class="p-5 rounded-xl border-2 border-teal-300 bg-teal-50 dark:bg-teal-900/30">
  <div class="text-3xl mb-3">🤖</div>
  <div class="font-bold text-teal-700 dark:text-teal-300 mb-2">Automatización</div>
  <div class="text-sm text-gray-600 dark:text-gray-300">Tareas repetitivas que hoy toman horas, automatizadas en segundos.</div>
</div>

</div>

---
layout: center
class: text-center
---

# Los 6 Conceptos Clave

<div class="grid grid-cols-3 gap-5 mt-8 max-w-2xl mx-auto">

<div class="p-5 rounded-xl border-2 border-blue-400 bg-blue-50 dark:bg-blue-900/30">
  <div class="text-3xl mb-2">📦</div>
  <div class="font-bold text-blue-600">Variables</div>
  <div class="text-xs mt-1 text-gray-500">Guardar información</div>
</div>

<div class="p-5 rounded-xl border-2 border-green-400 bg-green-50 dark:bg-green-900/30">
  <div class="text-3xl mb-2">📋</div>
  <div class="font-bold text-green-600">Listas</div>
  <div class="text-xs mt-1 text-gray-500">Colecciones de datos</div>
</div>

<div class="p-5 rounded-xl border-2 border-yellow-400 bg-yellow-50 dark:bg-yellow-900/30">
  <div class="text-3xl mb-2">🗂️</div>
  <div class="font-bold text-yellow-700">Diccionarios</div>
  <div class="text-xs mt-1 text-gray-500">Registros con nombre</div>
</div>

<div class="p-5 rounded-xl border-2 border-red-400 bg-red-50 dark:bg-red-900/30">
  <div class="text-3xl mb-2">🔀</div>
  <div class="font-bold text-red-600">Condicionales</div>
  <div class="text-xs mt-1 text-gray-500">Tomar decisiones</div>
</div>

<div class="p-5 rounded-xl border-2 border-cyan-400 bg-cyan-50 dark:bg-cyan-900/30">
  <div class="text-3xl mb-2">🔄</div>
  <div class="font-bold text-cyan-600">Ciclos</div>
  <div class="text-xs mt-1 text-gray-500">Repetir acciones</div>
</div>

<div class="p-5 rounded-xl border-2 border-pink-400 bg-pink-50 dark:bg-pink-900/30">
  <div class="text-3xl mb-2">⚙️</div>
  <div class="font-bold text-pink-600">Funciones</div>
  <div class="text-xs mt-1 text-gray-500">Código reutilizable</div>
</div>

</div>

---
layout: default
---

# 📦 Variables — Guardar Información

Una **variable** es como una caja con etiqueta: le das un nombre y guardas un valor dentro.
Python detecta el tipo de dato automáticamente.

<div class="grid grid-cols-2 gap-6 mt-4">

<div>

```python
# Texto (str) — entre comillas
nombre_empresa = "Tech Store"
gerente        = "Ana García"

# Número entero (int)
empleados      = 42
año_fundacion  = 2018

# Número decimal (float)
ventas_mes     = 85000.50
tasa_iva       = 0.16

# Verdadero / Falso (bool)
activo         = True
en_quiebra     = False

print("Empresa:", nombre_empresa)
print("Empleados:", empleados)
```

</div>

<div>

### Los 4 tipos básicos

| Tipo | ¿Qué guarda? | Ejemplo |
|------|-------------|---------|
| `int` | Números enteros | `42`, `2018` |
| `float` | Números decimales | `0.16`, `85000.5` |
| `str` | Texto | `"Ana García"` |
| `bool` | Verdadero/Falso | `True`, `False` |

<div class="mt-4 p-3 bg-blue-50 dark:bg-blue-900/30 rounded border border-blue-200 dark:border-blue-700 text-sm">
  💡 Los nombres de variables no pueden tener espacios. Usa guión bajo: <code>ventas_mes</code>
</div>

</div>

</div>

---
layout: default
---

# 📦 Variables — Como Calculadora de Negocios

```python
# Datos de un producto
precio_venta   = 1200
costo_unitario = 750
unidades       = 45

# Python hace los cálculos automáticamente
ganancia_unit  = precio_venta - costo_unitario       # 450
ganancia_total = ganancia_unit * unidades             # 20,250
margen         = (ganancia_unit / precio_venta) * 100 # 37.5%

print(f"Ganancia por unidad: ${ganancia_unit}")
print(f"Ganancia total:      ${ganancia_total:,}")
print(f"Margen de utilidad:  {margen:.1f}%")
```

<div class="mt-6 p-4 bg-gray-50 dark:bg-gray-800 rounded-lg border border-gray-200 dark:border-gray-700 font-mono text-sm">
  <div class="text-green-600 dark:text-green-400">Salida:</div>
  <div>Ganancia por unidad: $450</div>
  <div>Ganancia total:      $20,250</div>
  <div>Margen de utilidad:  37.5%</div>
</div>

<div class="grid grid-cols-4 gap-3 mt-4 text-center text-sm">
  <div class="p-2 bg-gray-100 dark:bg-gray-700 rounded"><code>+</code> Suma</div>
  <div class="p-2 bg-gray-100 dark:bg-gray-700 rounded"><code>-</code> Resta</div>
  <div class="p-2 bg-gray-100 dark:bg-gray-700 rounded"><code>*</code> Multiplicar</div>
  <div class="p-2 bg-gray-100 dark:bg-gray-700 rounded"><code>/</code> Dividir</div>
</div>

---
layout: default
---

# 📋 Listas — Colecciones de Datos

Una **lista** guarda varios valores en orden dentro de corchetes `[ ]`.
Cada elemento tiene un número de posición (**índice**) que empieza en **0**.

<div class="grid grid-cols-2 gap-6 mt-4">

<div>

```python
productos = ["Laptop", "Mouse", "Teclado", "Monitor"]
precios   = [15000, 450, 800, 3200]

# Acceder por posición (empieza en 0)
print(productos[0])    # "Laptop"
print(productos[-1])   # "Monitor" (último)

# Operaciones básicas
print(len(productos))  # 4 (cuántos hay)
productos.append("Webcam")  # agregar
print("Mouse" in productos) # True
```

</div>

<div>

### Visualización de una lista

```
productos = ["Laptop", "Mouse", "Teclado", "Monitor"]

┌──────────┬─────────┬─────────┬──────────┐
│ "Laptop" │ "Mouse" │"Teclado"│"Monitor" │
└──────────┴─────────┴─────────┴──────────┘
    [0]        [1]       [2]       [3]
                                   ↑
                              También [-1]
```

<div class="mt-4 p-3 bg-green-50 dark:bg-green-900/30 rounded border border-green-200 text-sm">
  💡 El primer elemento siempre es <code>[0]</code>, nunca <code>[1]</code>.
</div>

</div>

</div>

---
layout: default
---

# 🗂️ Diccionarios — Registros con Nombre

Un **diccionario** guarda pares de **clave: valor** entre llaves `{ }`.
Perfecto para representar un registro como una ficha de empleado o un producto.

<div class="grid grid-cols-2 gap-6 mt-4">

<div>

```python
empleado = {
    "nombre":       "Ana García",
    "departamento": "Ventas",
    "salario":      18500,
    "activo":       True
}

# Acceder por nombre de clave
print(empleado["nombre"])      # Ana García
print(empleado["salario"])     # 18500

# Modificar un valor
empleado["salario"] = 20000

# Agregar un campo nuevo
empleado["correo"] = "ana@empresa.com"
```

</div>

<div>

### Visualización de un diccionario

```
empleado = { ... }

 ┌─────────────────┬──────────────────┐
 │ 🔑 Clave        │ 📄 Valor         │
 ├─────────────────┼──────────────────┤
 │ "nombre"        │ "Ana García"     │
 │ "departamento"  │ "Ventas"         │
 │ "salario"       │ 18500            │
 │ "activo"        │ True             │
 └─────────────────┴──────────────────┘
```

<div class="mt-3 p-3 bg-yellow-50 dark:bg-yellow-900/30 rounded border border-yellow-200 text-sm">
  Lista → posición <code>[0]</code> &nbsp;|&nbsp; Diccionario → nombre <code>["clave"]</code>
</div>

</div>

</div>

---
layout: default
---

# 🔀 Condicionales — Tomar Decisiones

Con **`if` / `elif` / `else`** el programa elige qué hacer según una condición.
La **indentación** (4 espacios) es obligatoria — define qué código pertenece a cada rama.

```python
ventas_mes = 92000
meta       = 100000
porcentaje = (ventas_mes / meta) * 100

if porcentaje >= 100:
    resultado = "¡Meta superada! 🎉"
    bono      = "10%"
elif porcentaje >= 80:
    resultado = "Cerca de la meta 👍"
    bono      = "5%"
else:
    resultado = "Meta no alcanzada 😔"
    bono      = "0%"

print(f"Logro: {porcentaje:.1f}%  →  {resultado}  →  Bono: {bono}")
```

<div class="mt-4 p-4 bg-gray-50 dark:bg-gray-800 rounded-lg border border-gray-200 dark:border-gray-700 font-mono text-sm">
  <span class="text-green-600 dark:text-green-400">Salida:</span>  Logro: 92.0%  →  Cerca de la meta 👍  →  Bono: 5%
</div>

---
layout: default
---

# 🔀 Condicionales — Diagrama de Flujo

```
                  ventas >= meta?
                       │
          ┌────────────┼────────────┐
         SÍ          NO (pero ≥80%) NO (< 80%)
          │               │               │
   "¡Meta superada!"  "Cerca de       "Meta no
    Bono: 10%          la meta"       alcanzada"
                       Bono: 5%       Bono: 0%
```

<div class="grid grid-cols-3 gap-4 mt-6">

<div class="p-4 bg-green-50 dark:bg-green-900/30 rounded-lg border-2 border-green-400 text-center">
  <div class="text-2xl mb-1">✅</div>
  <div class="font-bold text-green-700 dark:text-green-300 text-sm">if porcentaje >= 100</div>
  <div class="text-xs mt-1 text-gray-500">Primera condición</div>
</div>

<div class="p-4 bg-yellow-50 dark:bg-yellow-900/30 rounded-lg border-2 border-yellow-400 text-center">
  <div class="text-2xl mb-1">🤔</div>
  <div class="font-bold text-yellow-700 dark:text-yellow-300 text-sm">elif porcentaje >= 80</div>
  <div class="text-xs mt-1 text-gray-500">Si la primera no se cumplió</div>
</div>

<div class="p-4 bg-red-50 dark:bg-red-900/30 rounded-lg border-2 border-red-400 text-center">
  <div class="text-2xl mb-1">❌</div>
  <div class="font-bold text-red-700 dark:text-red-300 text-sm">else</div>
  <div class="text-xs mt-1 text-gray-500">Si ninguna se cumplió</div>
</div>

</div>

<div class="mt-5">

| Operador | Significado | Ejemplo |
|----------|-------------|---------|
| `==` | Igual a | `estado == "activo"` |
| `!=` | Diferente de | `stock != 0` |
| `>` / `<` | Mayor / Menor | `ventas > meta` |
| `>=` / `<=` | Mayor o igual / Menor o igual | `porcentaje >= 80` |

</div>

---
layout: default
---

# 🔄 Ciclos (for) — Automatizar Tareas Repetitivas

El ciclo **`for`** recorre cada elemento de una lista y ejecuta el mismo código para cada uno.
En lugar de escribir 100 líneas, escribes 3.

<div class="grid grid-cols-2 gap-6 mt-4">

<div>

```python
# Sin ciclo — tedioso y propenso a error
print("Laptop:   $15,000")
print("Mouse:    $450")
print("Teclado:  $800")
# ... y así para cada producto
```

<div class="mt-2 p-2 bg-red-50 dark:bg-red-900/30 rounded border border-red-200 text-sm text-center">
  ❌ Repetitivo, difícil de mantener
</div>

</div>

<div>

```python
# Con ciclo — elegante y escalable
productos = ["Laptop", "Mouse", "Teclado"]
precios   = [15000,    450,     800]

for i in range(len(productos)):
    print(f"{productos[i]}: ${precios[i]:,}")
```

<div class="mt-2 p-2 bg-green-50 dark:bg-green-900/30 rounded border border-green-200 text-sm text-center">
  ✅ Funciona para 3 o 3,000 productos
</div>

</div>

</div>

<div class="mt-4">

```python
# Ciclo con acumulador — calcular total de ventas
ventas = [3200, 4800, 2900, 5100, 4400, 3700, 6200]
total  = 0

for venta in ventas:
    total += venta          # total = total + venta

print(f"Total semanal: ${total:,}")   # Total semanal: $30,300
print(f"Promedio diario: ${total / len(ventas):,.0f}")
```

</div>

---
layout: default
---

# 🔄 Ciclos — Paso a Paso

¿Cómo funciona `for venta in ventas`?

```
ventas = [3200, 4800, 2900, 5100, 4400]

Iteración 1:  venta = 3200  →  total = 0 + 3200 = 3200
Iteración 2:  venta = 4800  →  total = 3200 + 4800 = 8000
Iteración 3:  venta = 2900  →  total = 8000 + 2900 = 10900
Iteración 4:  venta = 5100  →  total = 10900 + 5100 = 16000
Iteración 5:  venta = 4400  →  total = 16000 + 4400 = 20400
                                                        ↑
                                                   Resultado final
```

<div class="mt-6 grid grid-cols-2 gap-6">

<div class="p-4 bg-blue-50 dark:bg-blue-900/30 rounded-lg border border-blue-200">
  <div class="font-bold mb-2">Forma simple</div>

```python
# Solo necesitas el valor
for producto in productos:
    print("✔", producto)
```

</div>

<div class="p-4 bg-purple-50 dark:bg-purple-900/30 rounded-lg border border-purple-200">
  <div class="font-bold mb-2">Con índice</div>

```python
# Necesitas posición Y valor
for i in range(len(productos)):
    print(i, productos[i])
```

</div>

</div>

---
layout: default
---

# ⚙️ Funciones — Código Reutilizable

Una **función** es un bloque de código con nombre propio que puedes usar muchas veces.
Se define con `def`, recibe **parámetros** y devuelve un resultado con `return`.

```python
def calcular_precio_final(precio_base, descuento=0):
    precio_desc = precio_base * (1 - descuento)   # aplicar descuento
    iva         = precio_desc * 0.16               # calcular IVA 16%
    total       = precio_desc + iva
    return round(total, 2)

# Llamar la función con distintos productos
laptop  = calcular_precio_final(12000, descuento=0.10)
mouse   = calcular_precio_final(400)
teclado = calcular_precio_final(700, descuento=0.05)

print(f"Laptop  (10% desc. + IVA): ${laptop:,}")    # $12,528.0
print(f"Mouse   (sin desc. + IVA): ${mouse:,}")      # $464.0
print(f"Teclado ( 5% desc. + IVA): ${teclado:,}")   # $773.64
```

<div class="mt-4 p-3 bg-pink-50 dark:bg-pink-900/30 rounded border border-pink-200 text-sm">
  💡 <strong>Ventaja clave:</strong> Si el IVA cambia de 16% a 18%, solo cambias una línea en la función — no en cada producto.
</div>

---
layout: default
---

# ⚙️ Funciones — Anatomía

<div class="grid grid-cols-2 gap-8 mt-4">

<div>

```python
#      ① nombre de la función
#              ② parámetros (entrada)
#              ③ valor por defecto
def calcular_precio_final(precio_base, descuento=0):
    #
    # ④ cuerpo (indentado 4 espacios)
    precio_desc = precio_base * (1 - descuento)
    iva         = precio_desc * 0.16
    total       = precio_desc + iva
    #
    return round(total, 2)  # ⑤ resultado (salida)

# ⑥ llamar la función
resultado = calcular_precio_final(12000, 0.10)
```

</div>

<div>

### Las 6 partes

| # | Parte | Descripción |
|---|-------|-------------|
| ① | Nombre | Verbo descriptivo, snake_case |
| ② | Parámetros | Datos que recibe |
| ③ | Valor por defecto | Si no se pasa, usa este |
| ④ | Cuerpo | El código a ejecutar |
| ⑤ | `return` | El resultado que devuelve |
| ⑥ | Llamada | Cómo se usa la función |

<div class="mt-3 p-3 bg-pink-50 dark:bg-pink-900/30 rounded border border-pink-200 text-sm">
  Una función se define <strong>una vez</strong> y se llama <strong>las veces que quieras</strong>.
</div>

</div>

</div>

---
layout: default
---

# Resumen — Los 6 Conceptos

| Concepto | ¿Qué es? | Ejemplo de negocio |
|----------|----------|-------------------|
| **📦 Variables** | Caja que guarda un valor | `ventas_mes = 85000` |
| **📋 Listas** | Varios valores en orden | `["Laptop", "Mouse", "Teclado"]` |
| **🗂️ Diccionarios** | Registro clave → valor | `{"nombre": "Ana", "salario": 18500}` |
| **🔀 Condicionales** | Tomar decisiones (if/elif/else) | Clasificar cliente según compras |
| **🔄 Ciclos** | Repetir para cada elemento | Calcular total de ventas diarias |
| **⚙️ Funciones** | Código reutilizable con nombre | `calcular_precio_final(precio, desc)` |

<div class="mt-8 grid grid-cols-3 gap-4 text-sm">

<div class="p-3 bg-blue-50 dark:bg-blue-900/30 rounded border border-blue-200">
  <strong>Variables + Operadores</strong><br>
  El motor de los cálculos
</div>

<div class="p-3 bg-green-50 dark:bg-green-900/30 rounded border border-green-200">
  <strong>Listas + Diccionarios</strong><br>
  Para organizar información
</div>

<div class="p-3 bg-purple-50 dark:bg-purple-900/30 rounded border border-purple-200">
  <strong>Ciclos + Funciones</strong><br>
  Para automatizar y reutilizar
</div>

</div>

---
layout: default
---

# Ejercicios Prácticos

Resuelve estos ejercicios en el **Python Trainer**. ¡Usa los ejemplos del menú izquierdo como guía!

<div class="grid grid-cols-2 gap-6">

<div>

### Nivel 1 — Variables 📦
1. Crea variables para una empresa: nombre, empleados, ventas del mes
2. Calcula la ganancia: `precio_venta = 800`, `costo = 500`, `unidades = 30`
3. Calcula el precio con IVA 16% de un producto de $1,200

### Nivel 2 — Listas y Diccionarios 📋🗂️
4. Crea una lista con 5 productos de tu empresa. Imprime el primero y el último.
5. Crea un diccionario con tu información: nombre, carrera, semestre, ciudad
6. Modifica el salario de este empleado: `{"nombre": "Luis", "salario": 15000}`

</div>

<div>

### Nivel 3 — Condicionales 🔀
7. Dado `descuento_anual = 65000`, clasifica al cliente:
   - ≥ 100,000 → VIP (15%)
   - ≥ 50,000 → Premium (10%)
   - ≥ 20,000 → Regular (5%)
   - Menos → Nuevo (0%)

### Nivel 4 — Ciclos y Funciones 🔄⚙️
8. Recorre esta lista e imprime cada producto con su precio:
   `precios = [3200, 4800, 2900, 5100, 4400]`
9. Crea una función `calcular_iva(precio)` que devuelva el precio con 16% de IVA
10. **Reto:** Crea una función `resumen_ventas(lista_ventas)` que devuelva total, promedio, máximo y mínimo

</div>

</div>

---
layout: center
class: text-center
---

# Cómo Usar el Python Trainer

<div class="grid grid-cols-3 gap-5 mt-8 max-w-3xl mx-auto text-left">

<div class="p-4 rounded-lg border border-gray-200 dark:border-gray-700">
  <div class="text-3xl mb-2">📋</div>
  <div class="font-bold mb-1">1. Panel izquierdo</div>
  <div class="text-sm text-gray-500">
    Selecciona un <strong>tema</strong> y carga ejemplos predefinidos con un clic.
  </div>
</div>

<div class="p-4 rounded-lg border border-gray-200 dark:border-gray-700">
  <div class="text-3xl mb-2">⌨️</div>
  <div class="font-bold mb-1">2. Editor central</div>
  <div class="text-sm text-gray-500">
    Escribe o modifica el código. Ejecuta con <kbd>Ctrl</kbd>+<kbd>Enter</kbd> o el botón <strong>▶ Ejecutar</strong>.
  </div>
</div>

<div class="p-4 rounded-lg border border-gray-200 dark:border-gray-700">
  <div class="text-3xl mb-2">💡</div>
  <div class="font-bold mb-1">3. Tabs de resultado</div>
  <div class="text-sm text-gray-500">
    <strong>Resultado</strong> — ve el output de tu código.<br>
    <strong>Concepto Visual</strong> — diagrama del tema.
  </div>
</div>

</div>

<div class="mt-8 p-4 bg-blue-50 dark:bg-blue-900/30 rounded-lg border border-blue-200 dark:border-blue-700 max-w-2xl mx-auto text-sm text-left">
  <strong>Consejos:</strong>
  <ul class="mt-2 space-y-1">
    <li>• La tecla <kbd>Tab</kbd> inserta 4 espacios (indentación)</li>
    <li>• Si hay un error, lee el mensaje — te dice en qué línea está</li>
    <li>• Modifica los ejemplos y experimenta — no puedes romper nada</li>
  </ul>
</div>

---
layout: end
---

# ¡A practicar! 🐍

Abre el **Python Trainer** y empieza con los ejercicios del Nivel 1.

<div class="mt-4 text-gray-400 text-sm">
  Recuerda: la única manera de aprender a programar es <strong>escribiendo código</strong>.
  Los errores son parte del proceso — cada error es una lección.
</div>
