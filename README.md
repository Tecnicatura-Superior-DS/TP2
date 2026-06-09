# TP2 — Comparativa de Agentes de IA

## Datos del estudiante

| Campo | Detalle |
|---|---|
| Nombre | Navarro Javier |
| Carrera | Tecnicatura Superior en Desarrollo de Software a Distancia |
| Materia | Desarrollo Front-End |
| Trabajo | TP N° 2 — Prompt Engineering y Agentes de IA |

---

## Deploy unificado

🔗 **[Ver proyecto en Vercel](https://TU-URL.vercel.app)**

---

## Estructura del proyecto

```
TP2/
├── index.html       ← Portada con los 3 accesos
├── prompt.txt       ← Texto plano del prompt utilizado
├── README.md
├── agent1/
│   └── index.html   ← Landing generada por Codex CLI
└── agent2/
    └── index.html   ← Landing generada por OpenCode
```

---

## Prompt utilizado

```
## CONTEXT

You are an expert front-end developer specialized in building complete,
production-ready websites. Your task is to autonomously generate a
single-file responsive landing page using only HTML, CSS, and vanilla
JavaScript — no frameworks, no external dependencies, no build steps required.

[... prompt completo en prompt.txt ...]
```

> El prompt completo está disponible en [`prompt.txt`](./prompt.txt)

---

## Agentes utilizados

| # | Agente | Modelo | Tipo |
|---|---|---|---|
| 1 | Codex CLI | codex-1 (OpenAI) | CLI autónomo |
| 2 | OpenCode | big-pickle (OpenAI) | CLI autónomo |

---

## Capturas de pantalla

### Agent 1 — Codex CLI
![Agent 1 screenshot](./screenshots/agent1.png)

### Agent 2 — OpenCode
![Agent 2 screenshot](./screenshots/agent2.png)

---

## Observaciones

Ambos agentes recibieron exactamente el mismo prompt sin modificaciones
manuales al código generado, según las restricciones del trabajo práctico.