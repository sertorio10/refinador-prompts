# Refinador de Prompts

Herramienta gratuita para mejorar prompts de IA. Funciona en cualquier browser, sin instalación ni servidor.

🔗 **Demo online**: [sertorio10.github.io/refinador-prompts](https://sertorio10.github.io/refinador-prompts)

---

## ¿Qué hace?

**Biblioteca** — Guardá, organizá y buscá tus mejores prompts. Exportá e importá como JSON para hacer backup o compartir con tu equipo.

**Refinador con IA** — Pegás un borrador en lenguaje natural, elegís el tipo de tarea, y obtenés un prompt optimizado con contexto, restricciones y formato de salida bien definidos.

---

## Cómo usar la herramienta web

1. Abrí [sertorio10.github.io/refinador-prompts](https://sertorio10.github.io/refinador-prompts)
2. Hacé clic en **⚙ Configurar API key**
3. Ingresá tu API key de Anthropic ([obtener una gratis](https://console.anthropic.com/keys))
4. Listo — la biblioteca funciona sin key, el refinador la necesita

> Tu API key se guarda únicamente en tu browser (localStorage). Nunca se envía a ningún servidor externo.

---

## Usar los prompts en cualquier herramienta de IA

No necesitás la app. En `/prompts/refinador-sistema.md` encontrás los prompts de sistema listos para copiar y pegar en:

- **Claude** (claude.ai) — como System Prompt de un Project
- **ChatGPT** — en Custom Instructions
- **Gemini, Grok, Copilot** — al inicio del mensaje
- **Cualquier API** — como `role: "system"`

---

## Instalar localmente

```bash
git clone https://github.com/sertorio10/refinador-prompts.git
cd refinador-prompts
# Abrí index.html en tu browser — no necesita servidor
open index.html
```

---

## Estructura del proyecto

```
refinador-prompts/
├── index.html              # App completa (biblioteca + refinador)
├── prompts/
│   └── refinador-sistema.md  # Prompts para usar en cualquier IA
└── README.md
```

---

## Activar GitHub Pages

1. Ir a **Settings → Pages** en este repositorio
2. Source: **Deploy from a branch**
3. Branch: **main**, carpeta: **/ (root)**
4. Guardar — en 1-2 minutos estará disponible en `sertorio10.github.io/refinador-prompts`

---

## Modelos disponibles

| Modelo | Velocidad | Costo | Recomendado para |
|--------|-----------|-------|-----------------|
| Claude Haiku 4.5 | ⚡ Rápido | $ Bajo | Uso diario, alto volumen |
| Claude Sonnet 4.6 | Medio | $$ Medio | Prompts complejos |

---

## Licencia

MIT — hacé lo que quieras con esto.
