# 🌳 Visualizador de Jerarquía Organizacional y Red de Comunicación con Árboles y Grafos

> **Proyecto Académico — Estructura de Datos y Algoritmos 2 (UAO)**  
> Plataforma interactiva de modelado algorítmico que combina un **Árbol N-ario jerárquico** para la estructura de mando con un **Grafo Dirigido/No Dirigido** para la red de comunicaciones interdepartamentales.

---

## 🎯 Estructuras de Datos y Algoritmos
* **Árbol Jerárquico Organizacional (`TreeNode.js`):**
  * Representación en árbol de la relación Supervisor-Subordinado.
  * Renderizado interactivo con **`react-d3-tree`** (colapso/expansión de ramas, cálculo dinámico de profundidad).
* **Grafo de Comunicación Empresarial (`Graph.js`):**
  * Matriz/Lista de adyacencia para mapear canales de comunicación entre colaboradores.
  * Visualización topológica basada en física de partículas con **`vis-network`** y **`vis-data`**.
* **Gestión Dinámica de Nodos:** Adición, edición, búsqueda y eliminación de empleados manteniendo la consistencia de las aristas.

---

## 🛠️ Stack Tecnológico
* **Frontend:** React 18, Vite, `react-d3-tree`, `vis-network`, `vis-data`
* **Estilos:** CSS3 Moderno con paleta semántica
* **Arquitectura:** Componentes desacoplados y estructuras de datos nativas en JS

---

## 🚀 Instalación y Ejecución Local
```bash
# 1. Navegar al subdirectorio del código
cd Proyecto3_Correccion

# 2. Instalar dependencias
npm install

# 3. Iniciar entorno interactivo
npm run dev
```

---
*Desarrollado para el curso de Estructura de Datos y Algoritmos 2 — Universidad Autónoma de Occidente.*
