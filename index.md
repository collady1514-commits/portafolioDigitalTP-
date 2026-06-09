
<div align="center">
  <img src="https://github.com/user-attachments/assets/0ff8a6e2-146c-4c1c-b3de-28ddce8a544c" 
  " width="250" style="border-radius:50%;">
<center> 
<dive>

# **UNIVERSIDAD NACIONAL DE LOJA**
## FACULTAD DE LA ENERGÍA, LAS INDUSTRIAS Y LOS RECURSOS NATURALES NO RENOVABLES
## CARRERA DE COMPUTACIÓN
## ASIGNATURA
### Teoria de la programación
## UNIDAD
### Aprendizaje Autónomo Actividad Nro. 1
## TÍTULO
### Portafolio Digital de Aprendizaje
## DOCENTE
### Lisette Geoconda López Faicán 
## ESTUDIANTE
### Ladi Anahí Guamán Arteaga
## FECHA DE ENTREGA
### Lunes, 4 de mayo de 2026
---
</div>

<div align="center">

# 🎓 PORTAFOLIO DIGITAL DE APRENDIZAJE

| 🏠 Inicio | 📘 Unidad 1 | 📗 Unidad 2 | 📙 Unidad 3 | 📂 Evidencias | 📚 Bibliografía | 🤖 Uso de IA |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| <a href="#inicio">Ir</a> | <a href="#unidad-1">Abrir</a> | <a href="#unidad-2">Abrir</a> | <a href="#unidad-3">Abrir</a> | <a href="#evidencias">Abrir</a> | <a href="#bibliografia">Abrir</a> | <a href="#ia">Abrir</a> |

</div>

---

---

##  — Fundamentos de Algoritmos y Programación

---

### 🔹 ¿Qué es un Algoritmo?

Un algoritmo es una **secuencia de pasos lógicamente 
ordenados y finitos** que dan solución a un problema. 
En mi vida diaria lo uso sin darme cuenta, por ejemplo 
para prepararme en la mañana: primero me ducho, luego 
me visto, desayuno y salgo — siempre en ese orden lógico.

Un algoritmo se compone de **3 partes**:

| Parte | Pregunta clave | Ejemplo |
|-------|---------------|---------|
| 📥 Entrada | ¿Qué datos necesito? | Ingredientes |
| ⚙️ Proceso | ¿Cómo llego al resultado? | Receta |
| 📤 Salida | ¿Qué obtengo? | Empanadas listas |

**Características que debe tener:**
- **Preciso** → cada paso claro y sin ambigüedades
- **Definido** → siempre da el mismo resultado con los mismos datos
- **Finito** → debe terminar en algún momento

---

### 🔹 Pseudocódigo

El pseudocódigo son **instrucciones escritas en lenguaje 
semiformal** que me ayudan a diseñar un algoritmo antes 
de escribir código real. Lo usamos en **PSeInt** que es 
el programa que vimos en clase.

**Ejemplo — Calcular el promedio de 3 notas:**
<img width="300" height="327" alt="image" src="https://github.com/user-attachments/assets/c37b87cb-eaad-42d9-b11b-07eccd8df81d" />

---

### 🔹 Diagrama de Flujo

Es la **representación gráfica** del algoritmo usando 
símbolos estandarizados. Lo que más me costó aprender 
fue identificar cuándo usar cada figura:

| Símbolo | Figura | Significado |
|---------|--------|-------------|
| ⬭ | Óvalo | Inicio / Fin |
| ▭ | Rectángulo | Proceso o cálculo |
| ◇ | Rombo | Decisión (sí/no) |
| ▱ | Paralelogramo | Entrada o Salida de datos |
| → | Flecha | Dirección del flujo |


**Ejemplo**
<img width="200" height="300" alt="image" src="https://github.com/user-attachments/assets/36190812-8631-4e0f-bbe0-7a5e32fa5e2a" />



---

### 🔹 Prueba de Escritorio

Es una **verificación manual** del algoritmo. Simulo 
la ejecución paso a paso con valores concretos y voy 
registrando el estado de cada variable en una tabla.

**Ejemplo con el promedio de las 3 notas:**

| Instrucción | NOTA1 | NOTA2 | NOTA3 | NOTA_FINAL | Pantalla |
|-------------|-------|-------|-------|------------|----------|
| Definir variables | — | — | — | — | — |
| Leer NOTA1 | 8 | — | — | — | — |
| Leer NOTA2 | 8 | 7 | — | — | — |
| Leer NOTA3 | 8 | 7 | 9 | — | — |
| NOTA_FINAL ← (8×0.30)+(7×0.30)+(9×0.40) | 8 | 7 | 9 | 7.70 | — |
| Escribir resultado | 8 | 7 | 9 | 7.70 | "Su nota final es 7.70" |

---

---

### 🔹 Lenguajes de Programación

Un lenguaje de programación es un **conjunto de símbolos 
y reglas de sintaxis** que permiten expresar programas 
(software). Las computadoras entienden el **lenguaje 
binario** (unos y ceros), pero nosotros usamos lenguajes 
de programación para comunicarnos con ellas.

**Clasificación de los lenguajes:**

| Tipo | Descripción | Ejemplos |
|------|-------------|---------|
| 🖥️ **Máquina** | Solo unos y ceros, lo entiende directamente el CPU | 0001 1100 0111... |
| ⚙️ **Bajo nivel** | Instrucciones mnemotécnicas (abreviaturas) | ADD, DIV, STR |
| 📝 **Alto nivel** | Más cercano al lenguaje humano, fácil de entender | C, Python, Java |
| 📋 **Algorítmico** | Formado por acciones de nuestro lenguaje natural | 9+11=20 |

---

### 🔹 Lenguajes Compilados vs Interpretados

Los lenguajes de alto nivel necesitan ser **traducidos** 
para que la computadora los entienda. Hay dos formas:

<table>
  <tr style="background-color:#0071e3; color:white;">
    <th>Característica</th>
    <th>⚙️ Compilado</th>
    <th>🔄 Interpretado</th>
  </tr>
  <tr>
    <td><b>¿Cómo funciona?</b></td>
    <td>Traduce TODO el código de una vez</td>
    <td>Traduce línea por línea</td>
  </tr>
  <tr style="background-color:#f0f7ff;">
    <td><b>Velocidad</b></td>
    <td>Más rápido al ejecutar</td>
    <td>Más lento</td>
  </tr>
  <tr>
    <td><b>Flexibilidad</b></td>
    <td>Menos flexible</td>
    <td>Más flexible</td>
  </tr>
  <tr style="background-color:#f0f7ff;">
    <td><b>Resultado</b></td>
    <td>Programa ejecutable (.exe)</td>
    <td>Se ejecuta con intérprete</td>
  </tr>
  <tr>
    <td><b>Ejemplos</b></td>
    <td>C, C++, Pascal, Cobol</td>
    <td>Python, PHP, JavaScript</td>
  </tr>
</table>

---

💡 **Diferencia importante:**
 - Un **algoritmo** es el método para resolver un problema
 - Un **programa** es la implementación del algoritmo 
   en un lenguaje de programación ejecutado en la computadora

En clase usamos **C** que es un lenguaje **compilado** 
—  escribimos el código, lo compilamos con GCC: ( gcc.\nombre_del_archivo.c -o nombre_del_archivo) y 
 obtenemos un archivo ejecutable que se lo ejecuta de la sigiente forma: .\nombre_delarchico.exe 

---

### 🔹 Programación por Bloques

Es un paradigma **visual** donde se construyen programas 
arrastrando y conectando bloques gráficos, sin necesidad 
de escribir código. Me ayudó a entender la lógica 
secuencial de una forma muy divertida.

**Herramienta usada en clase:** Code.org

**Actividades que realicé:**

| Actividad | ¿En qué consistía? |
|-----------|-------------------|
| 🧩 **Rompecabezas** | Ordenar bloques en el orden correcto para completar el desafío |
| 🏃 **Laberinto** | Dar instrucciones de movimiento para guiar un personaje hasta la meta |

> 💡 **Lo que aprendí:** Aunque no escribí ni una 
> línea de código, estaba aplicando exactamente 
> la misma lógica que usamos en PSeInt — pasos 
> ordenados, uno tras otro, en secuencia.

---

## 💻 Ejercicio con Estructura Secuencial

---

### 📌 Planteamiento del Problema

Un estacionamiento requiere determinar el cobro que debe aplicar a las personas que lo utilizan. Considere que el cobro es con base en las horas que utiliza y que las fracciones de hora se toman como completas. Realice el algoritmo que permita determinar el cobro.

**Dato adicional:** El cobro por hora es de **$0.50**

---

### 🔍 Análisis del Problema

| Elemento | Detalle |
|----------|---------|
| **Entradas** | costo, horas y pago final |
| **Proceso** | pago final = horas × costo |
| **Salida** | Su pago final es |


---


### 🔷 Diseño del Algoritmo

**Pseudocódigo en PSeInt:**


<img width="340" height="320" alt="image" src="https://github.com/user-attachments/assets/1a43890c-7f10-4907-9eec-b6ace3334aea" />

**Diagrama de flujo**

<img width="340" height="322" alt="image" src="https://github.com/user-attachments/assets/02a2eac5-f484-447c-b957-5d48082fd950" />

---

### 💾 Codificación en Lenguaje C

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/6c60a2f1-1336-40e6-9e68-6d62c1f3c7c2" />

<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/cb170131-8bce-403a-b2ae-f6c36163f9e7" />


  
### 🧪 Validación — Prueba de Escritorio


| Horas | Costo/hora | pago_final = horas × costo | Resultado |
|-------|------------|---------------------------|-----------|
| 5 | $1.00 | 5 × 1.00 | $5.00 ✓ |

----
### 💭 Principales dificultades y reflexión crítica en la aplicación de los contenidos
---


###  Dificultades que encontré

**1. Tipos de datos: int vs float**
Al principio no entendía bien la diferencia entre 
`int` y `float`. Lo aprendí de la peor manera — 
mi programa no mostraba nada porque usé `%f` 
para leer un `int`. Ahora sé que:
- `int` → números enteros, se lee con `%d`
- `float` → números decimales, se lee con `%f`

**2. Las máscaras de formato**
Me costó recordar qué máscara usar para cada tipo 
de dato en el `printf` y `scanf`. Tengo que seguir 
practicando para que se me quede grabado 

**3. Pasar de PSeInt a C**
Esta fue mi mayor dificultad. En PSeInt todo está 
en español y es más flexible, pero en C:
- `Escribir` se convierte en `printf`
- `Leer` se convierte en `scanf`
- Hay que agregar `;` al final de cada línea
- Hay que poner `&` antes de las variables en `scanf`
- Los tipos de datos cambian de nombre:
  - `Entero` → `int`
  - `Real` → `float`
  - `Cadena` → `char`

---

### Reflexión crítica

Esta unidad me enseñó que programar requiere mucha 
**atención al detalle**. Un simple `%f` en lugar 
de `%d` puede hacer que el programa no funcione.

Lo más importante que aprendí fue el proceso:
1. Primero **analizar** el problema
2. Diseñar en **PSeInt** sin preocuparme por la sintaxis
3. Luego **traducir** a C con cuidado
4. Finalmente **validar** con la prueba de escritorio

Sé que aún me falta practicar las máscaras de 
formato y los tipos de datos, pero cada error 
que cometo me ayuda a aprender mejor. 

---

##  Declaración de Uso de IA Generativa

**Herramienta utilizada:** Claude (Anthropic) — claude.ai

Durante la elaboración de este portafolio utilicé 
inteligencia artificial como tutor de acompañamiento. 

La IA me ayudó en los siguientes aspectos:

- Me enseñó los códigos de **Markdown** para dar 
  formato a mi portafolio, como usar `#` para títulos, 
  `**texto**` para negrita, cómo hacer tablas y 
  cómo insertar imágenes con `<img src="">`.

- Me **guió en la estructura** del portafolio para 
  que cumpla con lo que pide la actividad.

- Me ayudó con la **redacción** de los contenidos 
  teóricos, aunque siempre con mis propias ideas 
  y lo que entendí en clase.

---

##  Bibliografía

[1] M. M. Arteaga Martínez, *Lógica de programación 
con Pseint. Enfoque práctico*, 1.ª ed. Fondo Editorial 
Remington, 2023. [En línea]. Disponible en: 
https://research.ebsco.com/linkprocessor/plink?id=0c1115b8-e552-38e4-bc75-bf84bbdd293f

[2] I. Tarsini y R. Anggraeni, "Explore flowchart and 
pseudocode concepts in algorithms and programming," 
*Indonesian Journal of Multidisciplinary Science*, 
vol. 3, núm. 5, 2024. Disponible en: 
https://doi.org/10.55324/ijoms.v3i5.807

[3] J. E. Guerra Salazar, M. V. Ramos Valencia y 
G. E. Vallejo Vallejo, *Programando en C desde la 
práctica problemas resueltos*. Puerto Madero 
Editorial, 2023. Disponible en: 
https://dialnet.unirioja.es/servlet/libro?codigo=933288

[4] A. A. Bhuiyan y M. Amiruzzaman, *Programming 
with Java*, 2.ª ed. PA-ADOPT, 2025. Disponible en: 
https://open.umn.edu/opentextbooks/textbooks/programming-with-java

[5] J. M. Toro Bonilla, *Fundamentos de programación: 
Python*, 2.ª ed. Editorial Universidad de Sevilla, 
2023. Disponible en: 
https://dialnet.unirioja.es/servlet/libro?codigo=871117

---

## Unidad 2
## Unidad 3
