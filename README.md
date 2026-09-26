# Debugging a Donation Form

Proyecto de refactorización y depuración de un formulario de donación en **HTML5**[cite: 10]. El objetivo principal de este ejercicio fue corregir errores de sintaxis en etiquetas de entrada, mejorar la estructura semántica y aplicar buenas prácticas de accesibilidad web (asociación correcta de etiquetas `<label>` con `id` de controles)[cite: 10].

---

## 🛠️ Correcciones y Mejoras Aplicadas

- **Sintaxis de Inputs:** Se eliminaron las etiquetas de cierre erróneas en elementos vacíos (por ejemplo, `</input>`).
- **Etiquetas y Accesibilidad:** Se implementaron etiquetas `<label>` vinculadas mediante la propiedad `for` a los `id` correspondientes de cada campo.
- **Tipos de Entrada Adecuados:** Uso del tipo `email` para direcciones de correo y `number` para montos, optimizando la validación nativa en navegador.
- **Validación Requerida:** Inclusión del atributo `required` en los campos obligatorios.

---

## 📂 Estructura del Proyecto

```text
Debugging-a-donation-form/
│
└── index.html    # Código HTML corregido y refactorizado
