# Blackjack - Curso de JavaScript

Un proyecto del curso de JavaScript: un juego simple y elegante de Blackjack hecho con HTML, CSS y JavaScript. Fue creado para practicar lógica de juego, manipulación del DOM y uso de herramientas modernas como Node.js, Vite y pnpm. Se utilizaron las librerías underscore y Bootstrap para utilidades y estilos.

## Vista rápida
- Juego de cartas estilo Blackjack (21)
- Interfaz responsive con Bootstrap
- Lógica modular en JavaScript
- Workflow con Vite + pnpm

## Tecnologías
- Node.js
- pnpm (gestor de paquetes)
- Vite (dev server / build)
- JavaScript (ES Modules)
- HTML5 y CSS3
- Bootstrap (estilos)
- Underscore (utilidades)

## Instalación (rápida)
1. Clona el repositorio
    ```
    git clone <tu-repo-url>
    cd blackjack-vite
    ```
2. Instala dependencias con pnpm
    ```
    pnpm install
    ```
3. Levanta el entorno de desarrollo
    ```
    pnpm run dev
    ```
4. Construir para producción
    ```
    pnpm run build
    pnpm run preview
    ```

(Asegúrate de tener Node.js y pnpm instalados globalmente.)

## Cómo jugar
- Al cargar la página, haz clic en "Nuevo Juego" para repartir cartas.
- Usa los botones "Pedir" y "Plantarse" para jugar contra la banca (computadora).
- El objetivo es acercarte lo más posible a 21 sin pasarte.
- La banca juega automáticamente siguiendo reglas simples.

## Estructura recomendada
- /index.html
- /src
  - /js
     - app.js
     - juego.js
     - ui.js
  - /css
     - styles.css
- /public
- package.json
- README.md

## Buenas prácticas incluidas
- Separación de la lógica de juego y la presentación
- Uso de módulos ES para mantener el código limpio
- Dependencias mínimas: underscore para utilidades y Bootstrap para diseño

## Contribuir
- Crea un fork, una rama con tu feature/fix y abre un pull request.
- Escribe commits claros y añade una breve descripción del cambio.

## Licencia
Este proyecto puede licenciarse como MIT (o la que prefieras). Agrega un archivo LICENSE si quieres publicarlo.

---

Si quieres, te puedo generar un README más detallado con capturas, comandos personalizados de pnpm o plantillas para issues y PRs.