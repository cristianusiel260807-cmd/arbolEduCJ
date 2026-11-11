# ArbolEduCJ

**ArbolEduCJ** es una aplicación web educativa interactiva y de código abierto diseñada para aprender, simular y evaluar conceptos de **Árboles Binarios de Búsqueda (BST)** en tiempo real.

Desarrollada con **JavaScript puro (ES6+)**, **Tailwind CSS** y **HTML5 Canvas**, cuenta con una arquitectura de cero dependencias externas de librerías de terceros para estructuras de datos.

---

## Características Principales

1. **Módulo 1: Simulador Visual Interactivo**
   - Inserción, búsqueda y eliminación dinámica de nodos.
   - Validación estricta de tipos: Modo numérico (solo enteros, sin decimales) y modo alfabético (solo letras A-Z).
   - Recorridos animados paso a paso (*In-Orden*, *Pre-Orden*, *Post-Orden*) con consola sincrónica.
   - Tabla de estadísticas en tiempo real (Altura, Cantidad de nodos, Hojas, Mínimo y Máximo).
   - Controles de navegación *Pan & Zoom* (arrastrar y hacer zoom con la rueda del ratón).

2. **Módulo 2: Teoría y Glosario Dinámico**
   - Visualización interactiva de conceptos fundamentales: Raíz, Padres e Hijos, Hojas, Ramas (Nodos internos), Subárboles, Niveles, Altura y Grado.

3. **Módulo 3: Quiz de Evaluación**
   - Evaluación práctica analizando árboles generados aleatoriamente en tiempo real.
   - Caja de texto interactiva para ingresar los recorridos ordenados separados por comas.

---

## Tecnologías Utilizadas
- **HTML5 & Canvas API** para renderizado gráfico con soporte de animación fluida (`requestAnimationFrame`).
- **Tailwind CSS** (via CDN) para un diseño moderno, responsivo y modo oscuro.
- **JavaScript (Vanilla ES6+)** con clases personalizadas (`BSTNode`, `BinarySearchTree`).

---

## Cómo Ejecutar Localmente

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/ArbolEduCJ.git
   ```
2. Entra a la carpeta del proyecto:
   ```bash
   cd ArbolEduCJ
   ```
3. Abre el archivo `index.html` en tu navegador web favorito (o utiliza una extensión como *Live Server* en Visual Studio Code).
