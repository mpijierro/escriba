# Escriba

**Escriba** es una página web ligera (un solo archivo HTML) para **escribir prompts con orden**: plantilla → edición → resultado final listo para copiar.  
Pensado para uso diario en consola (Claude, ChatGPT, etc.) y para mantener una librería personal de plantillas.

---

## ✨ Características

- **3 columnas**
    - **Izquierda**: plantilla seleccionada (solo lectura)
    - **Centro**: editor para modificar el prompt
    - **Derecha**: resultado final listo para copiar
- **Selector de plantillas**
    - SuperClaude / consola-ready
    - Rápido (directo a implementar)
    - Solo análisis
    - Solo código
- **Normalización de salida (terminal-friendly)**
    - Unifica saltos de línea
    - Limpia espacios al final de línea
    - Colapsa exceso de líneas en blanco
    - Asegura salto final
- **“Mis plantillas” (localStorage)**
    - Guardar como…
    - Sobrescribir
    - Duplicar
    - Renombrar
    - Borrar
- **Export / Import**
    - Exporta tu librería a JSON
    - Importa (mezclar) o importar reemplazando todo

---

## 🚀 Uso rápido

1. Descarga/clona el repo.
2. Abre el archivo `prompter.html` (o el nombre que tenga el HTML principal) en tu navegador.
3. Elige una plantilla, edita en el panel central y copia el resultado con **📋 Copiar**.

> No requiere instalación, dependencias ni backend.

---

## 🧰 Consejos de uso

- Si vas a pegar en consola, deja **Normalizar salida** activado.
- Usa plantillas diferentes según la intención:
    - **SuperClaude**: tareas complejas / dominio con reglas
    - **Rápido**: tareas pequeñas / iteraciones rápidas
    - **Solo análisis**: diseño, decisiones, edge cases
    - **Solo código**: cuando ya está todo decidido

---

## 📦 Exportación / Importación

En **📦 Export/Import** puedes:
- copiar un JSON con tus plantillas
- restaurarlas en otro equipo
- compartir tu librería con alguien

---

## 🖼️

![Escriba](./escriba.png)
