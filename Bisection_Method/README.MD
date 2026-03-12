# 📌 Método de Bisección en Python

## 📖 Resumen

Este proyecto implementa el **Método de Bisección**, una técnica numérica clásica utilizada para hallar **raíces de ecuaciones no lineales** dentro de un intervalo dado.

El programa permite a los usuarios introducir una función matemática y un intervalo donde se espera la raíz. Mediante la división iterativa del intervalo a la mitad, el algoritmo aproxima la raíz hasta alcanzar la tolerancia especificada.

Esta implementación se desarrolló para apoyar a un colega de Ingeniería Civil en su curso de Métodos Numéricos.

El programa sirve como complemento computacional a los cálculos manuales que se suelen realizar al aplicar el Método de Bisección, lo que permite una verificación más rápida de los resultados, el seguimiento automatizado de las iteraciones y el análisis gráfico de la convergencia del método.

---

## 🧠 Acerca del Método de Bisección

El **Método de Bisección** es un algoritmo de búsqueda de raíces que funciona con el **Teorema del Valor Intermedio**.

Si una función continua f(x) cumple:

f(a) * f(b) < 0

entonces existe al menos una raíz en el intervalo [a,b].

El método divide repetidamente el intervalo por la mitad y selecciona el subintervalo donde se produce el cambio de signo, convergiendo gradualmente a la raíz.

---

## ⚙️ Características

Esta implementación admite una amplia variedad de expresiones matemáticas, incluyendo:

- Funciones polinómicas
- Funciones trigonométricas
- Funciones exponenciales
- Funciones logarítmicas
- Combinaciones complejas de las anteriores

El programa solicita al usuario:

1. La función **f(x)** escrita en sintaxis Python
2. El intervalo **[a, b]** donde se espera la raíz
3. La **tolerancia** para la aproximación de la raíz

---

## 🚀 Mejoras Implementadas

Además del algoritmo básico, se añadieron varias mejoras para que el programa sea **más robusto y fácil de usar**:

- ✅ **Validación de funciones** con mensajes de error claros si la expresión no es válida
- 📈 **Gráfico de la función** que muestra la raíz localizada
- ⚠️ **Manejo de casos especiales**, como raíces exactas ubicadas en los límites de intervalo
- 🧾 **Detallado Guía** sobre cómo escribir expresiones matemáticas correctamente en Python
- 📊 **Formato de salida mejorado**, incluyendo una tabla de iteraciones bien estructurada
- 💾 **Exportación automática a CSV** que almacena:
  - Información general sobre el problema
  - Una tabla de iteraciones completa
- 📉 **Gráfico de convergencia** que muestra el error aproximado frente a las iteraciones

Estas funciones permiten a los usuarios no solo calcular la raíz, sino también **analizar el comportamiento de convergencia del método**.

---

## 📊 Salidas

El programa genera las siguientes salidas:

### 1️⃣ Tabla de Iteración (Consola)
Muestra datos detallados de la iteración, incluyendo:

- Número de iteración
- Límites del intervalo
- Punto medio
- Evaluación de la función
- Error aproximado

### 2️⃣ Archivo CSV
Un archivo CSV que contiene:

- Información del problema
- Parámetros utilizados
- Tabla de iteración completa

### 3️⃣ Gráfico de Función
Un gráfico de la función f(x) en el intervalo seleccionado, incluyendo:

- La curva de la función
- La ubicación de la raíz resaltada

### 4️⃣ Gráfico de Convergencia
Un gráfico que muestra:

Error vs. Iteración

Esto ayuda a visualizar cómo el método converge a la raíz.

---

## 📂 Problemas de ejemplo

La implementación puede resolver problemas como:

- Ecuaciones polinómicas
- Ecuaciones trigonométricas
- Expresiones racionales
- Funciones trascendentales mixtas

Los ejemplos probados incluyen funciones que combinan:

- Logaritmos
- Exponenciales
- Funciones Trigonometricas
- Expresiones polinómicas

---

## 🛠️ Tecnologías utilizadas

- **Python**
- `matplotlib`
- `pandas`
- `csv`
- `numpy`

---

## 📈 Objetivo educativo

Este proyecto se desarrolló para reforzar conceptos de métodos numéricos, combinando:

- Teoría matemática

- Implementación algorítmica

- Visualización de la convergencia numérica

Demuestra cómo se pueden implementar algoritmos numéricos clásicos en Python para resolver ecuaciones no lineales de forma eficiente. 
