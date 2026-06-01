# ♟️ MiguelAngel: Orquestador GTM & Apalancamiento B2B

MiguelAngel no es un simple asistente de IA; es un **Motor de Apalancamiento de Marketing** y un **Arquitecto Go-To-Market**. Diseñado bajo una arquitectura de micro-agentes, su propósito es multiplicar la capacidad operativa de la agencia asumiendo el trabajo pesado de investigación técnica, auditoría y estructuración de contenidos.

Este ecosistema está optimizado para intervenir en sectores técnicos y tradicionales (como ingeniería, industria o gestión inmobiliaria), aplicando principios *Lean Startup* (Build-Measure-Learn) para validar hipótesis de mercado y enfocándose implacablemente en los puntos de dolor reales de los clientes, dejando de lado la jerga de marketing o los simples detalles normativos.

---

## 🚀 Capacidades Core

- **Orquestación de Micro-Agentes:** Actúa como un *Dispatcher* central. Recibe un *input* mínimo, evalúa la intención comercial y enruta la tarea al sub-agente especialista adecuado (`Auditor-SEO-agent` o `competitors-redactor-agent`).
- **Enrutamiento Inteligente de Modelos (Model Handoff):** Maximiza el ROI ejecutando tareas mecánicas de fuerza bruta y *scraping* con modelos de alta velocidad (Gemini 2.5 Flash), reservando el poder de razonamiento avanzado (Gemini 2.5 Pro) exclusivamente para la estrategia, el diagnóstico estructural y el *copywriting* persuasivo.
- **Guardrails de Veracidad ("Cero Alucinaciones"):** Bloqueo estricto contra la invención de datos. Los perfiles de clientes y diagnósticos se basan 100% en la realidad operativa extraída de la web, prohibiendo alucinaciones sobre IA o herramientas tecnológicas si la industria no lo justifica.

---

## 📥 Inputs: Disparadores Mínimos

El sistema está diseñado para iniciar cadenas de automatización complejas con el mínimo esfuerzo humano:
* **Auditoría y UX:** Una URL objetivo (Ej. web de un cliente potencial).
* **Inteligencia de Mercado:** Un listado de URLs de la competencia para ingeniería inversa.

---

## 📤 Outputs: Entregables de Negocio

MiguelAngel y sus sub-agentes traducen el código técnico a lenguaje de negocios, entregando:
* **Diagnósticos Traducidos:** Identificación de errores de código y UX explicados directamente como impacto financiero o pérdida de conversiones.
* **Ingeniería de Buyer Personas:** Perfiles ultradetallados divididos lógicamente entre el *Rol Operativo* (KPIs, tablero B2B) y el *Perfil Humano* (sesgos, motivadores).
* **Fábrica de Contenido Estructural:** Diseño de arquitecturas web (*Sitemaps* y *Wireframes*), redacción de artículos SEO y variaciones de copy *data-driven* listas para programar en LinkedIn y Meta.

---

## 🛡️ Seguridad y Entorno

Este proyecto opera bajo estrictas reglas de seguridad en su despliegue sobre el servidor local (OpenClaw):
* **Aislamiento de Ejecución:** La comunicación y ejecución de herramientas residen exclusivamente dentro de `/workspace/`.
* **Protección de Credenciales:** Todos los *tokens* (Google Gemini, Telegram, OpenClaw Gateway) y bases de datos locales están blindados e ignorados del control de versiones mediante reglas estrictas en el archivo `.gitignore`. **Nunca subir archivos `.json` de configuración a este repositorio.**
