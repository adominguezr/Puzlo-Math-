# Puzlo Math + 🧩

**Puzlo Math +** es una plataforma maker de impacto social dedicada a crear un repositorio abierto de **tableros y rompecabezas táctiles impresos en 3D**. Nuestro objetivo es facilitar el aprendizaje intuitivo de las matemáticas para niños y adultos, con especial enfoque en la inclusión de personas neurodivergentes (autismo, TDAH, discalculia, dislexia, etc.).

¡Queremos que la comunidad cree, adapte y comparta sus propios tableros, puzzles y fichas!

---

## 🎯 Objetivo de la Comunidad
Construir una biblioteca colaborativa de archivos CAD y STL clasificados por categoría pedagógica:
- **Tableros de conteo y operaciones:** Marcos tipo *Ten Frame*, tableros de sumas y restas.
- **Gráficas y plano cartesiano táctil:** Tableros con rejilla (grid), pivotes para coordenadas (X, Y) y barras encajables para construir diagramas de barras, líneas y funciones básicas de forma física.
- **Fracciones y geometría:** Puzzles de proporciones, círculos y bloques encajables.
- **Rompecabezas de lógica:** Puzzles de encaje y patrones visuales/táctiles.

---

## 🧱 Estado Actual del Proyecto
> ⚠️ **Estado:** Fase inicial de arquitectura y comunidad. El proyecto está listo para recibir **los primeros diseños comunitarios de tableros, puzzles y fichas**. No existen aún modelos probados ni validados físicamente.

### 🔍 Lo que debes verificar/probar antes de subir un modelo:
- [ ] **Tolerancias de encaje:** Probar las holguras (ej. 0.2 mm - 0.4 mm) entre fichas, barras y tableros en impresoras FDM estándar.
- [ ] **Ergonomía y textura:** Verificar que el tamaño de las piezas sea cómodo de manipular y que las texturas táctiles sean claras.
- [ ] **Seguridad física:** Asegurar que las piezas para uso infantil no presenten riesgo de asfixia (piezas > 3 cm).
- [ ] **Facilidad de impresión:** Diseñar modelos que no requieran soportes complejos de impresión.

---

## 📂 Estructura del Repositorio

```text
├── tableros/          # Modelos de tableros base (Ten Frames, plano cartesiano, tablas de encaje)
├── puzzles/           # Puzzles de fracciones, lógica y patrones táctiles
├── fichas/            # Fichas de números, símbolos (+, -, =), pines de coordenadas y bloques
├── plantillas-cad/    # Archivos base en FreeCAD/Tinkercad para crear nuevos modelos
└── docs/              # Guías de impresión, accesibilidad y retroalimentación pedagógica
