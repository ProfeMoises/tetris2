# 📱 Tetris Móvil / PC – Edición Responsive con Controles Táctiles

¡El clásico Tetris ahora completamente adaptado para móviles y tablets!  
Esta versión incluye **botones táctiles** para jugar sin teclado, detección automática de dispositivo, modo pausa y la misma jugabilidad adictiva de siempre.

![Tetris Responsive](https://via.placeholder.com/800x400?text=Tetris+en+PC+y+Móvil)

---

## 📜 Historia del Tetris

**Tetris** fue creado en 1984 por el ingeniero soviético **Alexey Pajitnov** mientras trabajaba en el Centro de Computación Dorodnitsyn de la Academia de Ciencias de la URSS en Moscú. Inspirado por su pasatiempo favorito, los pentominós, diseñó un juego electrónico donde las piezas (tetrominós) caen y deben encajarse perfectamente.

El nombre proviene del griego *"tetra"* (cuatro) y *"tennis"* (deporte favorito de Pajitnov). Rápidamente se extendió por toda la Unión Soviética y, tras sortear las barreras de la Guerra Fría, conquistó el mundo occidental. Nintendo lo incluyó con la Game Boy en 1989, catapultándolo a la fama global.

### Datos curiosos:
- Es uno de los videojuegos más vendidos de la historia (más de 500 millones de copias).
- Existen estudios sobre el "Síndrome de Tetris" (alucinaciones visuales tras jugar mucho tiempo).
- Fue el primer juego llevado al espacio (a bordo de la estación MIR en 1993).
- La música temática es una adaptación de la canción popular rusa **"Korobeiniki"**.
- Tetris es considerado un "rompecabezas eterno": no tiene final, solo récords.

---

## 🕹️ Cómo Jugar

**Objetivo:**  
Acomoda los bloques que caen (tetrominós) para formar líneas horizontales completas. Cada línea eliminada suma puntos. ¡El juego termina cuando los bloques se apilan hasta la parte superior!

### Controles según dispositivo

#### 💻 PC / Escritorio (con teclado)

| Tecla               | Acción                     |
|---------------------|----------------------------|
| ⬅️  **Flecha Izquierda** | Mover pieza a la izquierda |
| ➡️  **Flecha Derecha**    | Mover pieza a la derecha   |
| ⬆️  **Flecha Arriba**      | Rotar pieza 90° a la derecha |
| ⬇️  **Flecha Abajo**       | Acelerar caída hacia abajo  |
| **Barra espaciadora**   | Caída instantánea (Hard Drop) |
| **Tecla P**              | Pausar / Reanudar          |
| **Tecla R**              | Reiniciar partida          |

#### 📱 Móvil / Tablet (pantalla táctil)

La interfaz muestra automáticamente **6 botones táctiles** cuando detecta un dispositivo móvil o pantalla pequeña. También puedes forzar el modo móvil/PC con el botón **"📱 MODO MÓVIL"**.

| Botón táctil       | Acción                           |
|--------------------|----------------------------------|
| ⬅️                | Mover izquierda                  |
| ➡️                | Mover derecha                    |
| ⬇️                | Mover abajo (caída suave)        |
| 🔄                | Rotar pieza                      |
| 💥⬇️              | Caída instantánea (Hard Drop)    |
| ⏸️ PAUSA / ▶️ REANUDAR | Pausar o continuar la partida |

> 💡 **Consejo táctil:** Los botones tienen feedback visual al presionarlos (se hunden ligeramente). Puedes usar el botón **REINICIAR** en cualquier momento.

### Puntuación (clásica)

| Líneas eliminadas | Puntos |
|------------------|--------|
| 1 línea          | 100    |
| 2 líneas         | 300    |
| 3 líneas         | 500    |
| 4 líneas (Tetris)| 800    |

---

## 🧩 Piezas (Tetrominós)

Cada pieza tiene una forma y color característico:

| Pieza | Forma       | Color      |
|-------|-------------|------------|
| I     | 4 bloques rectos | Cian `#2ad4e3` |
| O     | Cuadrado    | Amarillo `#f7d44a` |
| T     | Forma de T  | Morado `#cc6aef` |
| S     | Zigzag inverso | Verde `#5fdc7a` |
| Z     | Zigzag      | Rojo `#e35f5f` |
| L     | L normal    | Naranja `#f0a25e` |
| J     | L invertida | Azul `#6b9bf5` |

---

## 🛠️ Características Técnicas de Esta Versión

- **Canvas HTML5** con escalado responsivo (el área de juego mantiene proporción 300x600 píxeles lógicos).
- **Detección automática de dispositivo táctil** (muestra/oculta botones según `ontouchstart` y tamaño de pantalla).
- **Botón manual** para alternar entre modo móvil y modo PC (útil para tablets o escritorios táctiles).
- **Sistema de pausa funcional** que congela la caída y evita movimientos.
- **Controles duales**: funcionan tanto teclado como botones táctiles simultáneamente.
- **Mecánicas clásicas**: rotación con *wall kick* simple (desplazamiento lateral si hay obstáculo), siguiente pieza, eliminación de líneas, game over y reinicio completo.
- **Sin dependencias externas**: todo el código está en un solo archivo HTML/CSS/JS.

---

## 🚀 Cómo Ejecutar el Juego

1. **Descarga** el archivo `tetris_responsive.html` (o copia el código completo).
2. **Abre el archivo** con cualquier navegador moderno (Chrome, Firefox, Edge, Safari).
3. En **PC** usa el teclado. En **móvil** los botones táctiles aparecerán automáticamente.
4. Si quieres forzar modo móvil en tu PC (para probar botones), presiona el botón **"📱 MODO MÓVIL"**.

> 📱 **Nota:** En dispositivos iOS, asegúrate de tener la última versión de Safari. Los botones táctiles responden al evento `click` optimizado para pantallas táctiles.

---

## 🧪 Posibles Mejoras Futuras

- Velocidad creciente por nivel (dificultad progresiva).
- Guardado de puntuación máxima (localStorage).
- Efectos de sonido y música (Web Audio API).
- Soporte para gestos táctiles (deslizar para rotar, etc.).
- Tabla de récords y modos de juego.

---

## 📄 Licencia

Este proyecto es de **código abierto** y puede ser usado, modificado y distribuido libremente con fines educativos o de entretenimiento. Basado en la mecánica original de Tetris® (marca registrada de The Tetris Company).

---

## 🙌 Agradecimientos

- A **Alexey Pajitnov** por crear una obra maestra atemporal.
- A la comunidad de desarrolladores que mantiene vivo el espíritu de los juegos clásicos en la web y dispositivos móviles.

---

**¡Diviértete y construye líneas donde sea que estés!** 🟦🟩🟧🟪  
*– Juega en el autobús, en la sala o en la oficina –*
