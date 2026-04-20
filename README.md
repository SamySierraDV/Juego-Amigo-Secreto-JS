**Juego de Amigos Secretos 🎡**

¡Bienvenido al Juego de Amigos Secretos! Una aplicación web interactiva y divertida para sortear amigos secretos mediante una ruleta animada. Ideal para fiestas, eventos o juegos grupales. Agrega nombres, gira la ruleta y descubre el secreto al azar. ¡Mínimo 2 amigos requeridos!


✨ Características Principales
Agregar amigos: Ingresa nombres fácilmente (sin duplicados ni vacíos).

Ruleta animada: Giro realista con colores dinámicos y easing suave.

Eliminación rápida: Click en lista para remover amigos.

Nuevo Juego: Reinicia todo en un clic.

Responsive: Funciona en desktop y mobile.

Sin dependencias: Puro vanilla JS, HTML y CSS.

🛠️ Tecnologías Utilizadas
| Frontend          | Herramientas                             |
| ----------------- | ---------------------------------------- |
| HTML5             | Estructura semántica                     |
| CSS3              | Estilos responsive y animaciones         |
| JavaScript (ES6+) | Lógica de ruleta, Canvas 2D, eventos DOM |

🚀 Cómo Usar
Clona o descarga el repositorio:

[git clone https://github.com/SamySierraDV/Juego-Amigo-Secreto-JS.git)
cd Juego-Amigos-Secreto-JS
Abre index.html en cualquier navegador (no necesita servidor).

Juega:

Escribe nombres en el input y presiona Enter o botón Agregar.

Presiona Sortear para girar (¡al menos 2 amigos!).

Usa Nuevo Juego para reiniciar.

Demo en vivo: Abrir en GitHub Pages (configura Pages para hosting gratis).

📱 Capturas
Interfaz inicial:

Ruleta en acción:

🔍 Cómo Funciona (Lógica Clave)
Ruleta Canvas: Dibuja sectores coloreados dinámicamente con getColor() (RGB sinusoidal).

Animación: rotateWheel() con easeOut para giro realista (4-7 segundos).

Selección: Calcula índice ganador por ángulo final (stopRotateWheel()).

Validaciones: Previene sorteos inválidos (0-1 amigos).

Código principal en script.js (ver snippet arriba para funciones como agregarAmigo(), spin()).

🤝 Contribuir
¡Aportes bienvenidos!

Forkea el repo.

Crea branch feature/nueva-funcion.

Commit con mensajes claros.

Pull Request.

Ideas: Soporte multilenguaje, sonido en giro, exportar resultados, PWA.

📄 Licencia
MIT License - Usa, modifica y comparte libremente. © 2026 Samy Suárez.

👨‍💻 Autor
Samy Suárez
Desarrollador Java Full Stack | Bogotá, Colombia
