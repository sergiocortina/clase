# GUÍA PARA CARGAR EL EXAMEN EN MOODLE

**Actividad:** Cuestionario (Examen) — Unidad 2 — Marco Jurídico de los Negocios
**Archivo de preguntas:** `Material Alumnos/Unidad 2/examen_unidad2.xml` (46 reactivos, 1 punto c/u)

---

## 1. Importar las preguntas al BANCO DE PREGUNTAS (primero esto)

**Paso 1.** Entra a tu curso → menú **"Más"** (o ⋮ arriba) → **"Banco de preguntas"**.

**Paso 2.** Pestaña **"Categorías"** → **"Añadir categoría"**:
- Nombre: `Unidad 2`
- Categoría padre: la del curso
- Clic en **"Añadir categoría"**.

**Paso 3.** Pestaña **"Importar"**:
- Formato: **"Formato XML de Moodle"**.
- Categoría de importación: selecciona la categoría **Unidad 2** que acabas de crear (para que no se mezclen con otras unidades).
- Arrastra el archivo `examen_unidad2.xml` en el cuadro de carga.
- Clic en **"Importar"**.

**Paso 4.** En la pantalla de resultados debe decir **"Importando 46 de 46 preguntas"** → clic en **"Continuar"**.

**Paso 5.** Verificación: en la pestaña **"Preguntas"**, filtra por la categoría **Unidad 2** — deben aparecer las 46 (nombres `U2-01` a `U2-24` y `U2-P01` a `U2-P22`).

> ⚠️ Si te aparecen avisos de "pregunta duplicada", es porque ya se había importado antes (prueba previa). Puedes borrar las duplicadas o dejarlas y usar solo una copia al armar el examen.

---

## 2. Crear la actividad CUESTIONARIO

**Paso 1.** Entra al curso → botón **"Activar edición"**.

**Paso 2.** En el tema correspondiente, clic en **"+ Agregar una actividad o recurso"** → elige **"Cuestionario"** → **"Agregar"**.

**Paso 3. Sección General:**
- **Nombre:** `Examen Unidad 2 — Marco Jurídico de los Negocios`
- **Descripción:** pega el texto del punto 4 de esta guía.
- Marca ✅ **"Mostrar la descripción en la página del curso"**.

**Paso 4. Temporización:**
- **Apertura:** viernes 2 de octubre de 2026, hora de la clase (ajústala).
- **Cierre:** mismo día, al término de la clase (o +1 hora de holgura).
- **Límite de tiempo:** ✅ activado — **60 minutos** (ajustable; 46 reactivos ≈ 1.3 min c/u).

**Paso 5. Calificación:**
- **Intentos permitidos:** `1`.
- **Método de calificación:** Primer intento.

**Paso 6. Diseño (opciones de diseño):**
- **Nuevo orden de preguntas:** ✅ Barajado.
- **Nuevo orden de respuestas:** ✅ Barajado (las opciones ya vienen marcadas para barajarse también en el XML).
- **Navegación de páginas:** como prefieras (recomendado: todas en una sola página para examen rápido).

**Paso 7. Comportamiento de las preguntas:**
- **Comportamiento:** "Diferido" (no retroalimentación durante el examen).

**Paso 8. Revisión de opciones (¡importante!):**
- **Durante el intento:** desmarca TODO (que no vean si acertaron mientras contestan).
- **Inmediatamente después del intento:** marca solo "Puntuación" si quieres que vean su nota al terminar.
- **Más tarde, cuando se cierre el cuestionario:** aquí sí puedes marcar todo (respuestas correctas y comentarios) para revisión posterior.

**Paso 9.** Clic en **"Guardar cambios y regresar al curso"**.

---

## 3. Añadir las 46 preguntas al cuestionario

**Paso 1.** Abre la actividad → clic en **"Editar cuestionario"** (o "Preguntas").

**Paso 2.** Clic en **"Añadir"** → **"+ a las preguntas del banco"**.

**Paso 3.** En la ventana:
- Categoría: **Unidad 2** (marca ✅ "incluir también las preguntas de las subcategorías" si aplica).
- Clic en **"Todo"** para seleccionar las 46 (o marcar la casilla general).
- Clic en **"Añadir preguntas seleccionadas al cuestionario"**.

**Paso 4.** Verifica:
- Deben verse las 46 preguntas en el cuestionario.
- **Puntuación total: 46.00** → en el campo **"Calificación máxima"** cámbiala a **`100`** y guarda (Moodle escala automáticamente: 46/46 = 100).

**Paso 5.** Prueba con **"Vista previa"**: contesta 2–3 preguntas y verifica que el orden esté barajado y que NO se muestren las respuestas correctas durante el intento.

---

## 4. Texto para la DESCRIPCIÓN del cuestionario

> Copia y pega en el editor de la descripción:

---

**EXAMEN UNIDAD 2 — MARCO JURÍDICO DE LOS NEGOCIOS**

Examen de opción múltiple sobre la Unidad 2: personas, bienes, derechos reales, obligaciones, extinción de las obligaciones, contratos y garantías, con casos prácticos basados en el portafolio de evidencias.

**Instrucciones:**

1. El examen contiene **46 reactivos**, cada uno vale **1 punto** y solo hay **una opción correcta**.
2. Tienes **60 minutos** desde que inicias el intento.
3. Las preguntas y las opciones aparecen **barajadas**; contesta con calma y lee todas las opciones antes de elegir.
4. Solo tienes **un intento**. Al terminar, revisa que no queden preguntas sin responder y presiona **"Enviar todo y terminar"**.

**Valor:** 100 puntos. **Modalidad:** individual.

⚠️ La consulta de libros, apuntes o páginas durante el examen anula el intento.

---

## 5. Texto para el aviso en el FORO DE NOVEDADES

> Copia y pega en el foro cuando publiques la actividad:

---

📢 **Recuerden: Examen de la Unidad 2 el viernes**

Estimados alumnos: este **viernes 2 de octubre** aplicaremos el examen de la Unidad 2 (personas, obligaciones y contratos) en el enlace **"Examen Unidad 2"** del curso. Son 46 preguntas de opción múltiple, con un límite de **60 minutos** y **un solo intento**.

No lo abran antes de la hora del examen: el intento inicia el cronómetro en cuanto entra la primera pregunta. Cualquier problema técnico, avísenme de inmediato por mensajería de Moodle (no después de cerrado el intento).

---

## 6. El día del examen

1. Abre el cuestionario como alumno de prueba o usa **"Vista previa"** antes de la clase.
2. Si un alumno pierde conexión, su intento se guarda automáticamente: en **"Calificar" → "Intentos"** puedes verlo y, si hace falta, usar **"Reabrir envío"** para darle minutos extra.
3. Al terminar: **Calificar → Descargar** las calificaciones o exporta el libro: **Calificaciones → Exportar → Libro de calificaciones**.

---

## 7. Recordatorio de archivos

| Archivo | Uso |
|---|---|
| `Material Alumnos/Unidad 2/examen_unidad2.xml` | ✅ El que se importa en el Banco de preguntas (punto 1) |
| Cuestiones del portafolio (E1–E8) | Ya están integradas como U2-P01 a U2-P22 — no se sube nada más |

---

> *Guía creada el 29 de septiembre de 2026 — examen: viernes 2 de octubre de 2026.*
