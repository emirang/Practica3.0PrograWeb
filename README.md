# Proyectos en JavaScript - Prácticas de Programación Web

Este repositorio contiene una colección de aplicaciones web interactivas desarrolladas en **HTML5** y **JavaScript (Vanilla)**. Los proyectos cubren desde manipulación de cadenas y criptografía básica hasta algoritmos de permutación y lógica de juegos interactivos con control de interfaz de usuario.

---

## 📋 Tabla de Contenidos

- [Proyectos Incluidos](#-proyectos-incluidos)
  - [1. Cifrado de Datos (Actividad 3.1)](#1-cifrado-de-datos-actividad-31)
  - [2. Juego de Craps con Apuestas (Actividad 3.3)](#2-juego-de-craps-con-apuestas-actividad-33)
  - [3. Generador de Cadenas de 3 Letras (Actividad 3.4)](#3-generador-de-cadenas-de-3-letras-actividad-34)
- [🚀 Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [💻 Cómo Ejecutar los Proyectos](#-cómo-ejecutar-los-proyectos)

---

## 🛠️ Proyectos Incluidos

### 1. Cifrado de Datos (`3.1.html`)
Aplicación orientada a la seguridad básica de la información que toma una cadena de **4 dígitos** enviada por el usuario y la cifra aplicando operaciones aritméticas y permuta de posiciones.

*   **Mapeo del algoritmo:**
    1. Reemplaza cada dígito por el resultado de: $(\text{dígito} + 7) \pmod{10}$.
    2. Intercambia el primer dígito con el tercero.
    3. Intercambia el segundo dígito con el cuarto.
*   **Características:** Validaciones contra valores no numéricos y longitud de entrada diferente de 4 dígitos.

---

### 2. Juego de Craps con Apuestas (`3.3.html`)
Simulación interactiva del popular juego de dados de casino **Craps**, que incluye un sistema completo de gestión de saldo y apuestas.

*   **Reglas del juego:**
    *   **Primer lanzamiento:**
        *   Suma de 7 u 11: **Gana** la apuesta.
        *   Suma de 2, 3 o 12: **Pierde** (Craps).
        *   Otra suma (4, 5, 6, 8, 9, 10): Se establece el **Punto**.
    *   **Lanzamientos posteriores (buscando el Punto):**
        *   Si vuelve a salir el **Punto**, el jugador **gana**.
        *   Si sale un **7**, el jugador **pierde**.
*   **Características:**
    *   Fondo y tipografía personalizada (*Impact* y celeste *SkyBlue*).
    *   Control de presupuesto inicial ($1000) y validación de apuestas.
    *   Mensajes y comentarios dinámicos e interactivos en pantalla según el estado del juego.

---

### 3. Generador de Cadenas de 3 Letras (`3.4.html`)
Generador algorítmico de permutaciones que toma una palabra de exactamente **5 letras** ingresada por el usuario y calcula todas las posibles combinaciones únicas de **3 letras** derivadas de ella.

*   **Características:**
    *   Uso de bucles anidados para el cálculo combinatorio evitando la repetición de índices.
    *   Filtrado automático de duplicados.
    *   Salida formateada dentro de una caja de texto multilínea (`<textarea>`) indicando el total de combinaciones generadas.

---

## 🚀 Tecnologías Utilizadas

- **HTML5:** Estructura e interfaz semántica.
- **CSS3:** Estilos personalizados, diseño adaptado y sombras.
- **JavaScript (ES5/ES6):** Manipulación del DOM, algoritmos matemáticos, manejo de eventos y control de flujo.

---

## 💻 Cómo Ejecutar los Proyectos

1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   ```
2. **Abre cualquiera de los archivos en tu navegador:**
   - No se requiere ningún servidor web ni instalación de paquetes (npm/node).
   - Simplemente haz doble clic en el archivo `.html` deseado (`3.1.html`, `3.3.html` o `3.4.html`) o arrástralo a tu navegador de preferencia.