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

#### Ejemplo
<img width="629" height="315" alt="image" src="https://github.com/user-attachments/assets/3cbc1215-e067-44c4-858c-a06c4c99ad22" />


#### Resultado
<img width="413" height="91" alt="image" src="https://github.com/user-attachments/assets/ed2d1f93-c394-4723-80f8-2d6581fec55a" />



#### 🔗 Paso por referencia
<div style="text-align: justify;">
Se envía la <b>dirección de memoria</b> de la variable original. Si la función modifica el parámetro, el cambio afecta directamente y en tiempo real a la variable original.
</div>

#### Ejemplo
<img width="555" height="326" alt="image" src="https://github.com/user-attachments/assets/57915dce-ed15-4ce3-9ca4-13a076535610" />

#### Resultado
<img width="344" height="77" alt="image" src="https://github.com/user-attachments/assets/9a5f840f-2c09-4a2f-8076-5b1890376e3c" />

### 📦Arreglos 

<div style="text-align: justify;">
Un <b>arreglo</b> es una estructura de datos estática que almacena una colección de elementos del <b>mismo tipo</b> (homogéneos) bajo un solo nombre. Todos los elementos se guardan en posiciones de memoria contiguas. Al ser estáticos, su tamaño debe definirse al momento de compilar y no puede cambiar durante la ejecución del programa. El acceso a cada casilla se realiza de manera directa utilizando <b>índices</b> que inician siempre en la posición <code>0</code>.
</div>

---

#### 🔹Arreglos Unidimensionales (Vectores)

<div style="text-align: justify;">
Tienen una sola dimensión. Imagínalo como una fila ordenada de casilleros. Este programa interactivo solicita al usuario ingresar las calificaciones de un estudiante para guardarlas en un vector y luego calcular su promedio.
</div>

#### Ejemplo
<img width="404" height="385" alt="image" src="https://github.com/user-attachments/assets/d7570c38-6b65-4e36-94a6-02682d2684c8" />

#### Resultado
<img width="359" height="119" alt="image" src="https://github.com/user-attachments/assets/26742e30-2dc2-4a1b-a94a-aceded684315" />

---
#### 🔹 Arreglo Bidimensional (2D)
<div style="text-align: justify;">
Un arreglo <b>bidimensional</b> es una estructura de datos estática que organiza la información en dos dimensiones principales de forma simultánea: <b>filas (horizontales) y columnas (verticales)</b>. Matemáticamente se comporta como una matriz o una cuadrícula bidimensional. Para localizar, almacenar o modificar cualquier dato dentro de esta estructura, el programa requiere obligatoriamente de dos índices de control independientes, representados comúnmente con la sintaxis <code>[índice_fila][índice_columna]</code>.
</div>

#### Ejemplo
<img width="535" height="434" alt="image" src="https://github.com/user-attachments/assets/d1c56550-5ee9-4cc2-93b7-a9ed53c077e4" />

#### Resultado
<img width="335" height="173" alt="image" src="https://github.com/user-attachments/assets/c2762649-80c3-4a09-8462-7b759ced8fe1" />



#### 🔹 Arreglo Tridimensional / Multidimensional (3D)
<div style="text-align: justify;">
Un arreglo <b>tridimensional</b> es una estructura que añade una tercera capa de profundidad a la organización de los datos. Conceptualmente, se puede visualizar como un <b>hipercubo, un sólido geométrico o un bloque compuesto por múltiples matrices superpuestas</b>. Para gestionar la información en este espacio, el sistema requiere de tres coordenadas o índices de control independientes: el primero define la capa o plano de profundidad, el segundo especifica la fila y el tercero determina la columna, estructurándose bajo la sintaxis <code>[capa][fila][columna]</code>.
</div>

#### Ejemplo
<img width="684" height="389" alt="image" src="https://github.com/user-attachments/assets/30ff9aeb-5bd6-4879-98e4-ea8d69ff4366" />
<img width="684" height="82" alt="image" src="https://github.com/user-attachments/assets/0dc18a04-0763-431e-b0d7-30ea26ff51ed" />


#### Resultado
<img width="338" height="222" alt="image" src="https://github.com/user-attachments/assets/cb2030a4-2be7-4d74-bc6a-ec8c38231d01" />

----

### 🧠 3. Principales Dificultades

#### ⚠️ Dificultades Técnicas en la Aplicación
<div style="text-align: justify;">
Durante el desarrollo práctico de los contenidos de esta unidad, la principal dificultad se presentó específicamente en la <b>modularidad al momento de realizar la codificación</b>. Estructurar correctamente la lógica del programa para dividirlo en funciones independientes y coordinar de forma exacta el traspaso de información mediante parámetros (por valor y por referencia) representó el desafío técnico más complejo durante la escritura del código.
</div>

---



