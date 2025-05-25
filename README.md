# Programación Lineal Dinámica

![Programación Lineal](https://img.shields.io/badge/Tool-Programaci%C3%B3n%20Lineal-blue)

Herramienta web interactiva para resolver **problemas de programación lineal** en 2 variables de forma gráfica, generar tablas de vértices y exportar los resultados en PDF.

---

## 📌 Tabla de Contenidos

* [Instalación](#instalación)
* [Uso](#uso)

  * [1. Función Objetivo](#1-función-objetivo)
  * [2. Restricciones](#2-restricciones)
  * [3. Resolver](#3-resolver)
  * [4. Exportar a PDF](#4-exportar-a-pdf)
* [Ejemplo de Prueba](#ejemplo-de-prueba)
* [Requisitos](#requisitos)
* [Personalización](#personalización)

---

## 🛠︎ Instalación

1. Clona o descarga este repositorio.
2. Abre el archivo `index.html` en tu navegador favorito (Chrome, Firefox, Edge).
3. ¡Listo! No requiere servidor ni instalación adicional.

---

## Uso

### 1️⃣ Función Objetivo

* Ingresa los **coeficientes** en los campos `c₁` y `c₂`.
* Selecciona si deseas **Maximizar** o **Minimizar** la función:

  > U = c₁·x₀ + c₂·x₁

### 2️⃣ Restricciones

* Añade condiciones de la forma:

  > a₁·x₀ + a₂·x₁  (≤, =, ≥)  b

* Usa **+ Agregar restricción** para incluir más filas.

* Elimina una fila con el botón **–** a la derecha.

### 3️⃣ Resolver

* Haz clic en **Resolver**.
* Se mostrarán:

  * Un **gráfico** con la región factible y el punto óptimo.
  * Una **tabla** con los vértices factibles (`x₀, x₁, U`).
  * Un mensaje con la **solución óptima**.

### 4️⃣ Exportar a PDF

* Haz clic en **Exportar a PDF**.
* Se descargará `PL_resultado.pdf` que incluye:

  1. Resumen de la función objetivo y restricciones.
  2. Imagen del gráfico.
  3. Tabla de vértices y solución óptima.

---

## 🔍 Ejemplo de Prueba

1. **Función Objetivo**: 3·x₀ + 1·x₁ (Maximizar)
2. **Restricciones**:

   * 2·x₀ + 1·x₁ ≤ 8
   * 2·x₀ + 3·x₁ ≤ 12

Resultado esperado: punto óptimo en alguno de los vértices y PDF descargable.

---

## 📋 Requisitos

* Navegador moderno con JavaScript habilitado.
* Conexión a internet para cargar las librerías (`Plotly`, `jsPDF`, `html2canvas`).

---

## ✨ Personalización

* Ajusta el parámetro `step` en el código para variar la precisión del dominio.
* Modifica estilos en la sección `<style>` o enlaza un archivo CSS externo.

---

> Desarrollado por tu nombre.
