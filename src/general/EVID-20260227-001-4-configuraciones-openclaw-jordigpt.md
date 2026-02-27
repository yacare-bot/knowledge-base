# 4 Configuraciones para usar OpenClaw - by JordiGPT

**Evidencia ID**: EVID-20260227-001
**Fuente**: [Google Doc](https://docs.google.com/document/d/1TS7Ris4-v-pV9WwZnHzKOpoRoXUixuts6-KljftcCxM)
**Score**: 6/10 (⭐⭐ MEDIUM) | **Faceta**: General Tech
**Autor**: JordiGPT

---

## 1. Heartbeat con modelo barato
Usar Gemini 2.0 Flash-Lite para heartbeats (48x/día). Tarea liviana = modelo barato.

## 2. Auditoría de archivos del sistema
AGENTS.md, TOOLS.md, USER.md, MEMORY.md, HEARTBEAT.md, SOUL.md se cargan en cada mensaje.
Objetivo: recortar 40-60% de tokens. Identificar qué mover a skills, qué está repetido/verbose.

## 3. Memoria on demand
No cargar memoria automáticamente al inicio de sesión. Traer solo lo necesario cuando se necesita.

## 4. Cambio de modelo a Kimi K2.5
Via ▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄
██░▄▄▄░██░▄▄░██░▄▄▄██░▀██░██░▄▄▀██░████░▄▄▀██░███░██
██░███░██░▀▀░██░▄▄▄██░█░█░██░█████░████░▀▀░██░█░█░██
██░▀▀▀░██░█████░▀▀▀██░██▄░██░▀▀▄██░▀▀░█░██░██▄▀▄▀▄██
▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀
                  🦞 OPENCLAW 🦞                    
 
┌  OpenClaw onboarding
│
◇  Security ─────────────────────────────────────────────────────────────╮
│                                                                        │
│  Security warning — please read.                                       │
│                                                                        │
│  OpenClaw is a hobby project and still in beta. Expect sharp edges.    │
│  This bot can read files and run actions if tools are enabled.         │
│  A bad prompt can trick it into doing unsafe things.                   │
│                                                                        │
│  If you’re not comfortable with basic security and access control,     │
│  don’t run OpenClaw.                                                   │
│  Ask someone experienced to help before enabling tools or exposing it  │
│  to the internet.                                                      │
│                                                                        │
│  Recommended baseline:                                                 │
│  - Pairing/allowlists + mention gating.                                │
│  - Sandbox + least-privilege tools.                                    │
│  - Keep secrets out of the agent’s reachable filesystem.               │
│  - Use the strongest available model for any bot with tools or         │
│    untrusted inboxes.                                                  │
│                                                                        │
│  Run regularly:                                                        │
│  openclaw security audit --deep                                        │
│  openclaw security audit --fix                                         │
│                                                                        │
│  Must read: https://docs.openclaw.ai/gateway/security                  │
│                                                                        │
├────────────────────────────────────────────────────────────────────────╯
[?25l│
◆  I understand this is powerful and inherently risky. Continue?
│  ○ Yes / ● No
└ (no editar archivos manualmente).
API key desde platform.moonshot.ai o openrouter.ai.

---
*EVID-20260227-001 | yacaré.bot*
