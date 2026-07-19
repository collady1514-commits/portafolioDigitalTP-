</div>


---
<a id="unidad-3"></a>

 [REGRESAR](inicio.md)

<div align="center">

<h1>📗 UNIDAD 3</h1>

# <h2>  Modularidad y Arreglos</h2>

</div>

<hr>

</tr>

### 🛠️ Modularidad en Programación

<div style="text-align: justify;">
La programación modular es una técnica de diseño de algoritmos que consiste en dividir un problema grande y complejo en subprogramas más pequeños y manejables, bajo el principio de <b>"divide y vencerás"</b>. Estos subprogramas, conocidos como módulos, procesos, funciones o rutinas, permiten reducir la complejidad del programa original.
</div>

### 🔹 Función
<div style="text-align: justify;">
Es un conjunto de sentencias que realiza una tarea específica con un propósito único e identificable. Las funciones no pueden ejecutarse solas; deben estar integradas en un programa principal (como el <code>main</code>) y pueden llamar a otras funciones entre sí.
</div>

<br>

<div align="center">
  <img src="https://github.com/user-attachments/assets/c7ec00a0-6ccd-456b-9e13-276b03e7a1bb" alt="Estructura de Funciones" width="450" style="max-width: 100%; height: auto;" />
</div>

<br>

#### 📌 Partes de una Función
<div style="text-align: justify;">
Consta de una <b>cabecera</b> (donde se define el tipo de dato de retorno, el nombre y la lista de parámetros) and un <b>cuerpo</b> (sentencias entre llaves y el valor de retorno).
</div>

<br>

<div align="center">
  <img src="https://github.com/user-attachments/assets/9d242bf6-bf1e-4408-b4bc-0da148e793fd" alt="Sintaxis de una Función" width="180" style="max-width: 100%; height: auto;" />
</div>

---

### 🔁 Paso de Parámetros

Al trabajar con funciones, la forma en que pasamos los datos (parámetros) cambia por completo el comportamiento del programa:

#### 📂 Paso por valor
<div style="text-align: justify;">
Se envía una <b>copia</b> del dato a la función. Cualquier modificación dentro de la función se queda de manera local; la variable original fuera de la función no cambia.
</div>

#### 🔗 Paso por referencia
<div style="text-align: justify;">
Se envía la <b>dirección de memoria</b> de la variable original. Si la función modifica el parámetro, el cambio afecta directamente y en tiempo real a la variable original.
</div>
