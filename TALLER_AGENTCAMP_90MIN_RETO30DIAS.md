# 🚀 TALLER AGENTCAMP: PROTOTIPADO MVP CON IA
## Taller de 90 Minutos + Reto de 30 Días

---

## 📊 VISIÓN EJECUTIVA

### ¿QUÉ ES AGENTCAMP?

Un **taller intensivo de 90 minutos** donde equipos de startups crean **MVPs production-ready** integrando:

- **Pensamiento de sistemas** (System Design)
- **Ingeniería de requisitos** (Requirements Engineering)
- **Product ownership** (Market-driven development)
- **Agentic software engineering** (IA autónoma)
- **DevOps & deployment** (CI/CD, cloud)

### ESTRUCTURA: TALLER 90 MIN + RETO 30 DÍAS

```
TALLER (90 minutos):
├─ Min 0-15: Intro + Pensamiento de sistemas
├─ Min 15-30: Requirements Engineer Agent DEMO
├─ Min 30-45: Product Owner Agent DEMO
├─ Min 45-75: Software Engineer Agent DEMO (Antigravity)
├─ Min 75-90: Q&A + Reto 30 días (instrucciones)
└─ OUTPUT: Placeholders personalizados para tu idea

RETO 30 DÍAS (Autónomo):
├─ Semana 1: Especificar tu MVP (usar prompts)
├─ Semana 2-3: Generar código con Antigravity
├─ Semana 4: Testing + deployment
└─ Día 30: Validar con 10 usuarios reales

RESULTADO ESPERADO:
✓ MVP funcional
✓ 80%+ test coverage
✓ < $500 presupuesto
✓ 10+ primeros usuarios
✓ Metric tracking setup
```

---

## 🎯 RESULTADOS

| Métrica | Tradicional | Con AgentCamp |
|---------|-----------|----------------|
| Tiempo MVP | 3-4 meses | 90 min idea → 30 días MVP |
| Team size | 5 developers | 1 dev + IA |
| Code quality | 50-60% coverage | 80-90% coverage |
| Bugs en QA | 40-60 | 5-10 |
| Cost | $50k+ | < $500 |

---

## 📝 AGENDA TALLER (90 MIN)

### MIN 0-15: INTRODUCCIÓN & SYSTEMS THINKING

**Concepto:** 
Sistemas = Interdependencias entre usuario, producto, mercado, negocio

**Placeholder para tu idea:**
```
CONTEXTO: [Describe el problema local que quieres resolver]

USUARIOS: [Quién sufre este problema?]

MERCADO: [Dónde? (localidad, región, país)]

RESTRICCIONES: 
├─ Budget: $[X] USD / $[Y] MXN
├─ Timeline: [X] días/semanas
├─ Team: [#] personas con skills [lista]
└─ Tech: [Stack preferences, si tienes]

MEDIDA DE ÉXITO:
├─ Métrica 1: [Baseline] → [Target]
├─ Métrica 2: [Baseline] → [Target]
└─ Métrica 3: [Baseline] → [Target]
```

---

### MIN 15-30: REQUIREMENTS ENGINEER AGENT (DEMO)

**Qué hace:** Transforma idea vaga → Especificación precisa (sin ambigüedad)

**CÓMO USARLO CON TU IDEA:**

1. Toma el placeholder anterior
2. Copia PROMPT #1 (Requirements Engineer)
3. Pega en Antigravity o Claude/Kiro
4. Reemplaza [placeholders] con tu contexto
5. Agent genera especificación completa

**OUTPUT esperado:**
- 30-40 página specification
- 15-20 user stories con AC testeable
- 0% ambigüedad
- Test scenarios (happy path + error paths)

---

### MIN 30-45: PRODUCT OWNER AGENT (DEMO)

**Qué hace:** Spec → Roadmap + modelo de negocio + go-to-market

**CÓMO USARLO:**

1. Usa especificación de paso anterior
2. Copia PROMPT #2 (Product Owner)
3. Pega en Antigravity o Azure Foundry
4. Agent genera:
   - TAM/SAM/SOM (mercado)
   - 3 personas (ICPs)
   - Roadmap Q1-Q2
   - Pricing strategy
   - Unit economics (CAC/CLV)
   - Go-to-market plan

**OUTPUT esperado:**
- Market analysis document
- Lean Canvas completo
- Revenue model validado
- Primeros 100 customers strategy

---

### MIN 45-75: SOFTWARE ENGINEER AGENT (DEMO)

**Qué hace:** Especificación + Design → Código autónomo production-ready

**DEMO EN VIVO:**
- Ejecutamos PROMPT #3 en Antigravity
- Mostramos generación autónoma de código
- Live monitoring (coverage, latency, security)
- Output: MVP deployable

**TU TURNO (después del taller):**
1. Usa spec + roadmap de pasos anteriores
2. Copia PROMPT #3 (Software Engineer)
3. Copia PROMPTS ESPECIALIZADOS (Frontend, Backend, QA, DevOps)
4. Sube a Antigravity workspace
5. Configura autonomy level (recomendado: Level 2)
6. Agent genera MVP completo en 3-5 días

---

### MIN 75-90: Q&A + RETO 30 DÍAS

**Instrucciones del Reto 30 Días:**

```
DÍA 1-3: ESPECIFICACIÓN
├─ Toma tu idea
├─ Usa Requirements Engineer Agent PROMPT #1
├─ Genera specification v1.0
└─ Aprueba spec con tu equipo

DÍA 4-7: ROADMAP + MERCADO
├─ Usa Product Owner Agent PROMPT #2
├─ Genera roadmap + unit economics
├─ Valida TAM/SAM/SOM
└─ Define first 100 customers strategy

DÍA 8-26: CÓDIGO AUTÓNOMO (Antigravity)
├─ Sube spec + roadmap a Antigravity
├─ Usa PROMPT #3 (Software Engineer)
├─ Configura autonomy level 2-3
├─ Agent genera MVP 24/7
├─ Tú haces PR reviews cada mañana
└─ Deploy a staging cuando esté listo

DÍA 27-30: VALIDACIÓN + USUARIOS
├─ Recluta 10 usuarios early
├─ Demos 1-on-1
├─ Recolecta feedback
├─ Setup metrics tracking
└─ Documento: "First 30 Days Learnings"

SUCCESS CRITERIA:
✓ MVP funcional (core features)
✓ 80%+ test coverage
✓ < $500 total cost
✓ 10+ usuarios probando
✓ Métricas baseline establecidas
✓ Roadmap validado
✓ Documento de aprendizajes
```

---

## 📚 SISTEMA DE PROMPTS

### ARQUITECTURA: 3 AGENTES PRINCIPALES

```
IDEA VAGA
   ↓
AGENTE 1: Requirements Engineer
   ├─ Input: Idea + constraints
   ├─ Output: Spec v1.0 (30-40 págs)
   ├─ Tiempo: 2-4 horas
   └─ Autonomía: Level 0 (human review)
   ↓
AGENTE 2: Product Owner
   ├─ Input: Spec + market context
   ├─ Output: Roadmap + business model
   ├─ Tiempo: 1-2 horas
   └─ Autonomía: Level 0-1 (human review)
   ↓
AGENTE 3: Software Engineer (Antigravity)
   ├─ Input: Spec + design + tasks
   ├─ Output: MVP code + tests + docs
   ├─ Tiempo: 3-5 días
   └─ Autonomía: Level 2-3 (autonomous)
   ↓
MVP PRODUCTION-READY ✓
```

### DÓNDE COPIAR CADA PROMPT

**Sección 1: PROMPTS MAESTROS**
- [Archivo: PROMPTS_MAESTROS_AGENTCAMP.md]
- PROMPT #1: Requirements Engineer Agent
- PROMPT #2: Product Owner Agent
- PROMPT #3: Software Engineer Agent (Antigravity Base)

**Sección 2: PROMPTS ESPECIALIZADOS (Antigravity)**
- [Archivo: PROMPTS_ANTIGRAVITY_ESPECIALIZADOS.md]
- PROMPT #1A: Frontend Agent
- PROMPT #1B: Backend/DevOps Agent
- PROMPT #1C: SRE/DevOps (Infrastructure)
- PROMPT #1D: QA/Testing Agent

**Sección 3: PROMPTS DE WORKFLOW**
- [Archivo: PROMPTS_WORKFLOW_AGENTCAMP.md]
- Epic Decomposition (PM)
- User Story → Tasks (Scrum Master)
- Atomic Commits & PR Template
- Hallucination Prevention Checklist

**Sección 4: 5-DAY AUTONOMOUS PROMPT**
- [Archivo: PROMPTS_5DAY_AUTONOMOUS.md]
- Complete system prompt para Antigravity
- Auto-correction protocol
- Daily reporting template
- Success criteria checklist

---

## 🛠️ CÓMO USAR EN ANTIGRAVITY

### PASO 1: Crear Workspace

```
1. Ir a: https://antigravity.ai
2. Sign up / Login
3. Click "New Workspace"
4. Nombre: [Tu-Idea]-AgentCamp
5. Invitar: tu equipo
```

### PASO 2: Crear Proyecto

```
1. Click "New Project"
2. Nombre: [Tu-Idea]-MVP
3. Seleccionar lenguajes:
   - Backend: Python 3.11 / Node.js 20
   - Frontend: TypeScript + React
   - Database: PostgreSQL 15
4. Click "Create"
```

### PASO 3: Subir Especificación

```
1. Section "Knowledge Base"
2. Click "Upload Documents"
3. Archivos a subir:
   ├─ spec-requirements.md (tu spec generada)
   ├─ architecture.md (tu design)
   └─ [opcional] existing code examples
4. Wait for indexing (2-3 min)
```

### PASO 4: Configurar Agent

```
1. Section "Configuration"
2. System Prompt: 
   ├─ Copy PROMPT #3 (Software Engineer)
   ├─ Reemplaza [placeholders]
   └─ Paste en "Instructions"
3. Autonomy Level:
   ├─ Selecciona: LEVEL 2 (Autonomous)
   ├─ Enable auto-commits: ON
   └─ Enable auto-deploy: OFF (primero staging)
4. Save configuration
```

### PASO 5: Conectar Repositorio

```
1. Section "Repository"
2. Conectar GitHub:
   ├─ Click "Authorize Antigravity App"
   ├─ Selecciona tu repo
   └─ Branch: "develop" (for staging)
3. CI/CD:
   ├─ Deployment target: AWS/Vercel
   ├─ Environment: "staging" first
   └─ Save
```

### PASO 6: START GENERATION

```
1. Click "Start Generation"
2. Selecciona scope:
   ├─ Epic 1: [Tu feature principal]
   ├─ Priority: P1
   └─ Timeline: 5 days
3. Click "Launch Agent"
```

**ANTIGRAVITY COMIENZA AQUÍ AUTOMÁTICAMENTE:**

```
FASE 1 (Horas 0-6): Planning & Architecture
├─ Analiza tu spec
├─ Propone tech stack final
├─ Genera database schema
├─ Crea task breakdown
└─ OUTPUT: Architecture document (wait for approval if Level 1)

FASE 2 (Horas 6-24): Code Generation (Parallelizable)
├─ Genera backend API (FastAPI/Node.js)
├─ Genera frontend components (React)
├─ Genera database migrations
├─ Escribe unit tests (TDD)
└─ Todas las AC verificadas ✓

FASE 3 (Horas 24-36): Integration & Testing
├─ E2E tests (Cypress/Playwright)
├─ Load tests (k6)
├─ Performance benchmarking
├─ Security audit (Bandit/OWASP)
└─ Coverage report (target: 85%+)

FASE 4 (Horas 36-60): Polish & Deployment
├─ Code cleanup
├─ Documentation (API, README, guides)
├─ Deploy to staging
├─ Smoke tests
└─ MVP PRODUCTION-READY ✓
```

---

## 📊 MONITOREO ANTIGRAVITY

### Dashboard en Vivo

```
METRICS DURING GENERATION:
├─ Code Generated: X líneas
├─ Tests Written: Y tests
├─ Tests Passing: Z/Y (coverage %)
├─ Build Status: ✅ / ❌
├─ Current Task: [TASK-X] (progress %)
├─ Commits: # merged
├─ Performance: P99 latency = Xms
└─ Security: # vulnerabilities

CADA 6 HORAS, VERIFICA:
☐ Coverage > 85%? (Si no: Agent lo señala)
☐ Tests passing? (Si no: Agent debugea)
☐ No critical issues? (Si sí: Agent propone fix)
☐ Commits sensibles? (Si no: Pause + discute)
```

### Qué Hacer Si Hay Bloqueadores

```
Si Agent se queda atascado > 2h:
1. Click "Pause Generation"
2. Review "Logs" section
3. Leer error específico
4. Click en error → Agent propone soluciones
5. Approve una solución
6. Click "Resume"
```

---

## 💰 PRESUPUESTO ESTIMADO

```
AGENTCAMP TOTAL COST (30 days):

Software:
├─ Antigravity: $0 (free trial)
├─ Azure Foundry: $0 (education code: 2J4KV9)
├─ GitHub: $0 (free)
└─ Subtotal: $0

Cloud Hosting (1 month):
├─ AWS RDS (PostgreSQL): $0 (free tier 12m)
├─ AWS Lambda (backend): $0-5
├─ Vercel (frontend): $0 (free)
└─ Subtotal: $0-5

Domain + Services:
├─ Domain: $5-10
├─ SendGrid (emails): $0 (free tier)
├─ Slack: $0 (free)
└─ Subtotal: $5-10

TOTAL: < $15 USD
LOCAL: < $300 MXN ✓

ROI: 
├─ Salario 1 dev (5 weeks): $30k+
├─ Costo AgentCamp: < $15
└─ Savings: 99.95% ✓
```

---

## ✅ CHECKLIST PRE-RETO

```
ANTES DE EMPEZAR TUS 30 DÍAS:

SETUP:
☐ Antigravity workspace creado
☐ GitHub repo creado
☐ Azure Foundry account (código 2J4KV9)
☐ Idea validada con 5+ usuarios
☐ Team aligned en vision

DOCUMENTACIÓN:
☐ Problema statement (1 pág)
☐ Target users identified (3 personas)
☐ MVP scope definido (core features)
☐ Success metrics (3-5 KPIs)
☐ Constraints (budget, timeline)

PRIMERO:
☐ Usar PROMPT #1 (Requirements Engineer)
☐ Generar spec v1.0
☐ Equipo aprueba spec
☐ Ir a PROMPT #2 (Product Owner)

LISTO PARA ANTIGRAVITY:
☐ Spec aprobada
☐ Roadmap definido
☐ Workspace configurado
☐ Knowledge base subida
☐ Agent configuration lista
☐ Repo conectado
☐ Click "START GENERATION"
```

---

## 🎓 APRENDIMIENTOS ESPERADOS

Después de los 30 días:

```
TÉCNICO:
✓ Entiendes cómo funcionan agentes de IA
✓ Puedes usar Antigravity para cualquier MVP
✓ Sabes escribir specs que AI entiende
✓ Tienes code base production-ready

PRODUCTO:
✓ TAM/SAM/SOM calculado realmente
✓ First 10 customers identificados
✓ Revenue model validado
✓ Roadmap Q1-Q2 escrito

NEGOCIO:
✓ CAC y CLV calculados
✓ Unit economics entendidos
✓ Go-to-market strategy escrita
✓ Pitch deck listo

MÉTRICAS:
✓ Baseline metrics establecidas
✓ Dashboard setup
✓ Weekly reporting set up
✓ Learning loop established
```

---

## 📞 SOPORTE

```
DURANTE EL TALLER:
├─ Slack: #agentcamp-support
├─ Live mentors: [TBD]
└─ Q&A: Final 15 minutos

DURANTE EL RETO 30 DÍAS:
├─ Antigravity docs: https://docs.antigravity.ai
├─ Azure Foundry: https://docs.globalai.community/azure-client.html
├─ Email: [support email]
├─ Slack community: [#agentcamp-30day]

BLOQUEADORES:
1. Document problem in detail
2. Share in Slack with context
3. Mentors respond within 24h
```

---

## 🏁 PRÓXIMOS PASOS

1. **Ahora:** Revisar este documento + los 4 archivos de prompts
2. **Antes de empezar:** Llenar placeholders con tu idea
3. **Día 1-3:** Ejecutar PROMPT #1 (Requirements)
4. **Día 4-7:** Ejecutar PROMPT #2 (Product Owner)
5. **Día 8-26:** Antigravity genera MVP
6. **Día 27-30:** Valida + usuarios + aprendizajes

**¡Bienvenido al reto AgentCamp!** 🚀

