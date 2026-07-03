

# Synaptech AI — Landing Page

Curso de Inteligencia Artificial. Landing page desarrollada con HTML, CSS y JavaScript vanilla.

## 🌐 Despliegue

[https://nicolezutaprada-netizen.github.io/landingppage/](https://nicolezutaprada-netizen.github.io/landingppage/)

**Repositorio:** [https://github.com/nicolezutaprada-netizen/landingppage](https://github.com/nicolezutaprada-netizen/landingppage)

---

## 🎨 Tokens CSS (Variables en `:root`)

### Color naranja

| Token | Valor | Dónde se usa |
|---|---|---|
| `--naranja` | `#ff6b2b` | Textos, bordes e íconos de acento principal |
| `--naranja-03` | `rgba(255, 107, 43, 0.03)` | Fondo de módulos abiertos en temario |
| `--naranja-10` | `rgba(255, 107, 43, 0.1)` | Fondo de badges, tags y tarjetas de módulo |
| `--naranja-15` | `rgba(255, 107, 43, 0.15)` | Fondo de íconos de contacto y summary abierto |
| `--naranja-20` | `rgba(255, 107, 43, 0.2)` | Borde de números de módulo en temario |
| `--naranja-30` | `rgba(255, 107, 43, 0.3)` | Borde de badges y tags |
| `--naranja-35` | `rgba(255, 107, 43, 0.35)` | Borde hover en FAQ y temario |
| `--naranja-40` | `rgba(255, 107, 43, 0.4)` | Borde del hero badge |
| `--naranja-50` | `rgba(255, 107, 43, 0.5)` | Borde hover de cards de características |

### Blancos semitransparentes

| Token | Valor | Dónde se usa |
|---|---|---|
| `--blanco-03` | `rgba(255, 255, 255, 0.03)` | Fondo de cards, form y detalles FAQ |
| `--blanco-05` | `rgba(255, 255, 255, 0.05)` | Hover del botón enviar del formulario |
| `--blanco-06` | `rgba(255, 255, 255, 0.06)` | Fondo de inputs del formulario |
| `--blanco-08` | `rgba(255, 255, 255, 0.08)` | Borde de cards, inputs y form |
| `--blanco-10` | `rgba(255, 255, 255, 0.1)` | Borde de stat-float en hero |
| `--blanco-20` | `rgba(255, 255, 255, 0.2)` | Borde del botón ghost del hero |
| `--blanco-30` | `rgba(255, 255, 255, 0.3)` | Borde del botón enviar |
| `--blanco-40` | `rgba(255, 255, 255, 0.4)` | Color de texto de stats y meta en temario |
| `--blanco-50` | `rgba(255, 255, 255, 0.5)` | Color del ícono + en temario |
| `--blanco-55` | `rgba(255, 255, 255, 0.55)` | Párrafos secundarios y descripciones |
| `--blanco-60` | `rgba(255, 255, 255, 0.6)` | Texto de respuestas FAQ y lecciones |
| `--blanco-70` | `rgba(255, 255, 255, 0.7)` | Labels del formulario |

### Colores base

| Token | Valor | Dónde se usa |
|---|---|---|
| `--bgcolor` | `#0a0a0a` | Fondo general del body |
| `--textcolor` | `#f0f0f0` | Color de texto principal |

---

## ✅ Validaciones del formulario

| Campo | Atributo | Error nativo del navegador |
|---|---|---|
| Nombre | `required` | "Por favor completa este campo" |
| Nombre | `minlength="3"` | "Usa al menos 3 caracteres" |
| Nombre | `maxlength="50"` | Impide escribir más de 50 caracteres |
| Nombre | `pattern="[A-Za-záéíóúÁÉÍÓÚñÑ\s]+"` | "Por favor usa el formato solicitado" — solo letras y espacios |
| Email | `required` | "Por favor completa este campo" |
| Email | `type="email"` | "Incluye un signo @ en la dirección" |
| Teléfono | `required` | "Por favor completa este campo" |
| Teléfono | `pattern="[0-9]{9}"` | "Por favor usa el formato solicitado" — exactamente 9 dígitos |
| Teléfono | `minlength="9"` | "Usa al menos 9 caracteres" |
| Teléfono | `maxlength="9"` | Impide escribir más de 9 caracteres |
| Motivo | `required` | "Por favor selecciona un elemento de la lista" |
| Mensaje | `required` | "Por favor completa este campo" |
| Mensaje | `minlength="10"` | "Usa al menos 10 caracteres" |
| Términos | `required` (checkbox) | "Por favor marca esta casilla si quieres continuar" |

---

## 📁 Estructura del proyecto

```
landingppage/
├── index.html
├── precios.html
├── temario.html
├── faq.html
├── css/
│   └── style.css
├── img/
│   ├── facebook.png
│   ├── instagram.png
│   ├── tiktok.png
│   └── wsp.png
└── README.md
```

---

## 🌿 Flujo Git utilizado

- `main` — rama principal, siempre estable
- `feature/form-validado` — rama donde se desarrolló la validación del formulario, mergeada a main via Pull Request #1

## Demo
🔗 [Ver en GitHub Pages](https://nicolezutaprada-netizen.github.io/landingpage-minera/)