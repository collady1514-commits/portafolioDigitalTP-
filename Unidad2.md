[REGRESAR](inicio.md)

<a id="unidad-2"></a>

<div align="center">

<h1>📗 UNIDAD 2</h1>

<h2>Estructuras Condicionales y Repetitivas</h2>

</div>

<hr>



</tr>

<h3>📌 Estructuras Condicionales</h3>

<ul>
           
**Condicional simple (if)**

Estructura que ejecuta un bloque de código de solo una condición especifica se evalúa como verdadera.

<h4 align="center">Diagrama de flujo</h4>
<p align="center">
  <img width="327" height="381" alt="Diagrama de flujo condicional simple" src="https://github.com/user-attachments/assets/718a7cb8-f311-4d65-9535-e1d06e8c4f7d" />
</p>

<h4 align="center">Pseudocodico</h4>
<p align="center">
<img width="146" height="61" alt="image" src="https://github.com/user-attachments/assets/ca279b02-07f2-46ae-aff3-c7f595b9ff09" />

       
**Condicional doble (if-else)**

Permite elegir entre dos alternativas: ejecuta un bloque si la condición es verdadera y otro bloque si es falsa.

<h4 align="center">Diagrama de flujo</h4>
<p align="center">
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/b42416cb-b0fb-4c06-8b38-b1f5550bf275" />

<h4 align="center">Pseudocodico</h4>
<p align="center">
<img width="140" height="124" alt="image" src="https://github.com/user-attachments/assets/290ab008-0c29-47e6-a12f-b8325ab43d01" />


**Condicional múltiple (if-else if)**

Es aquela que permite escoger entre dos o más opciones

 <h4 align="center">Diagrama de flujo</h4>
<p align="center">
<img width="278" height="191" alt="image" src="https://github.com/user-attachments/assets/b7af3fa8-b757-4583-aa1c-7fe4347b1999" />

<h4 align="center">Pseudocodico</h4>
<p align="center">
<img width="193" height="152" alt="image" src="https://github.com/user-attachments/assets/dafc8e63-042a-4460-92fd-b3f92a0d520e" />



**Condicional múltiple (switch case)**

Estructura de selección múltiple que compara una variable con diferentes valores constantes(casos), facilito la lectura en múltiples opciones.

<h4 align="center">Diagrama de flujo</h4>
<p align="center">
<img width="264" height="241" alt="image" src="https://github.com/user-attachments/assets/a160c953-1f95-49c7-b67e-de7fe33f739c" />

<h4 align="center">Pseudocodico</h4>
<p align="center">
<img width="209" height="308" alt="image" src="https://github.com/user-attachments/assets/e06de8f8-9af5-4fb4-a197-e4328af65473" />


<h3>📌 Estructuras Repetitivas</h3>


**Para (For)**

**Mientras (While)**

**Repetir Hasta Que (Do While)**
</ul>

<h3>📌 Ejercicio Integrador</h3>
<ul>
**Planteamiento del problema**
El encargado de una tienda de tecnología necesita revisar el inventario de un lote de 3 productos diferentes (por ejemplo: Laptops, Mouse y Teclados) para saber cuáles necesitan una compra urgente.

El programa debe utilizar un ciclo for para solicitar la cantidad disponible de cada uno de los 3 productos. Si un producto tiene menos de 5 unidades en existencia, la estructura condicional debe mostrar un mensaje de alerta indicando: "¡ALERTA: Reordenar producto!". Si tiene 5 o más unidades, indicará: "Stock seguro".
<li>Análisis del problema</li>
### 2. Análisis del Problema

| Componente | Descripción | Variables / Datos |
| :--- | :--- | :--- |
| **Entradas** | Cantidad de unidades de cada producto (se repite para cada artículo del lote). | `unidades` (Entero) |
| **Procesos** | 1. Controlar un ciclo `for` de 3 iteraciones (para los 3 productos).<br>2. En cada vuelta, leer la cantidad de existencias.<br>3. Evaluar mediante un `if-else` si el stock es menor al mínimo permitido (5 unidades). | Ciclo: `i` (desde 1 hasta 3)<br>Condición: `unidades < 5` |
| **Salidas** | Mensaje de estado en pantalla según el resultado de la evaluación. | `[¡ALERTA!]` o `[OK]` |
<li>Diseño del algoritmo</li>
<li>Diagrama de flujo</li>
<img width="16384" height="8676" alt="image" src="https://github.com/user-attachments/assets/1ffc857d-80da-46b5-9569-9f7b8973b6b5" />

<li>Codificación en C</li>
#include <stdio.h>

int main() {
    // Declaracion de variables
    int i;
    int unidades;

    printf("=== REVISION AUTOMATICA DE INVENTARIO ===\n\n");

    // Ciclo FOR: Se repite exactamente 3 veces (para 3 productos)
    for (i = 1; i <= 3; i++) {
        printf("Ingrese las unidades disponibles del producto %d: ", i);
        scanf("%d", &unidades);

        // Estructura condicional doble (If-Else)
        if (unidades < 5) {
            printf("  -> [¡ALERTA!]: Unidades bajas. ¡Reordenar producto ya!\n\n");
        } else {
            printf("  -> [OK]: Stock seguro. Cantidad suficiente.\n\n");
        }
    }

    printf("-----------------------------------------\n");
    printf("Proceso finalizado. Inventario revisado.\n");
    printf("-----------------------------------------\n");

    return 0;
}
<li>Prueba de escritorio</li>
## Prueba de Escritorio

| Iteración (i) | Unidades ingresadas | ¿unidades < 5? | Salida |
|--------------|-------------------|---------------|---------|
| 1 | 3 | Sí | ALERTA: Unidades bajas. ¡Reordenar producto ya! |
| 2 | 8 | No | OK: Stock seguro. Cantidad suficiente. |
| 3 | 2 | Sí | ALERTA: Unidades bajas. ¡Reordenar producto ya! |
</ul>

<li>Dificultades encontradas</li>
<li>Aprendizajes obtenidos</li>
</ul>

<hr>

<div align="right">
🔝 <a href="#inicio">Volver al inicio</a>
</div>

<hr>
