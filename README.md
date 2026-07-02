Simulador Interactivo de Autómatas (DFA/NFA) ⚙️

Una potente herramienta web interactiva construida en un solo archivo HTML para el diseño, simulación y análisis de Autómatas Finitos Deterministas (DFA) y No Deterministas (NFA). Ideal para estudiantes de ciencias de la computación, teoría de compiladores y lenguajes formales.

✨ Características Principales

Diseño Visual Intuitivo: Interfaz drag-and-drop sobre un lienzo infinito con soporte para Zoom y Paneo (Rueda del ratón / Clic central o Espacio + Clic).

Simulación Avanzada: Evalúa cadenas paso a paso o de forma completa. Soporta transiciones vacías (ε) y visualiza los estados activos en tiempo real.

Determinización Automática: Convierte cualquier NFA en su DFA equivalente utilizando el algoritmo de Construcción de Subconjuntos con un solo clic.

Reorganización Automática (Auto-Layout): Algoritmo de fuerza dirigida (Force-directed graph) para desenredar grafos complejos automáticamente.

Bitácora Detallada: Historial de cadenas evaluadas (Aprobadas/Rechazadas) con un modal de desglose paso a paso (estado y carácter) al hacer doble clic.

Gestión de Archivos: Guarda y carga tus autómatas en formato .json.

Exportación a PNG: Genera imágenes de alta calidad de tu grafo y de la Tabla de Transiciones (capturando la tabla completa sin importar el scroll).

Carga Rápida por Texto: Dibuja autómatas instantáneamente usando una sintaxis rápida (Ej: iq0-a.b-fq1).

Undo / Redo: Soporte completo de atajos de teclado (Ctrl+Z / Ctrl+Y) para proteger tu flujo de trabajo.

Modo Oscuro (Dark Mode): Interfaz adaptativa que protege tu vista durante largas sesiones de estudio.

🛠️ Tecnologías Utilizadas

HTML5 & Canvas API: Para el renderizado del grafo interactivo.

Vanilla JavaScript: Lógica de simulación, física de nodos y algoritmos de autómatas (Sin frameworks pesados).

Tailwind CSS (CDN): Para una interfaz moderna, limpia y responsive.

html2canvas: Para la exportación de tablas a imágenes PNG.

🚀 Cómo usarlo

El proyecto no requiere de instalaciones complejas ni servidores locales. ¡Es 100% Client-Side!

Descarga o clona este repositorio.

Abre el archivo automata-simulator.html directamente en tu navegador favorito (Chrome, Firefox, Edge, Safari).

¡Empieza a crear y simular!

💡 Atajos de teclado útiles

Ctrl + Z: Deshacer

Ctrl + Y: Rehacer

Rueda del ratón: Zoom In / Zoom Out

Espacio + Arrastrar o Clic Central: Moverse por el lienzo (Panning)

Clic Derecho sobre el texto de una transición: Editar el símbolo de transición (si lo dejas vacío, se elimina).

Hecho para facilitar el aprendizaje de Compiladores e Intérpretes.
