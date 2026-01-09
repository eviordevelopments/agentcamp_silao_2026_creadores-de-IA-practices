# 📚 ÍNDICE MAESTRO AGENTCAMP
## Guía de Todos los Archivos + Cómo Usarlos

---

## 📂 ARCHIVOS CREADOS (5 Total)

### 1️⃣ TALLER_AGENTCAMP_90MIN_RETO30DIAS.md
**Para:** Personas asistiendo al taller
**Contiene:**
- Visión general (taller 90 min + reto 30 días)
- Agenda del taller paso a paso
- Placeholders para personalizar con tu idea
- Instrucciones paso a paso para Antigravity
- Presupuesto estimado
- Checklist pre-reto

**CUÁNDO USAR:**
- Día 1: Revisar antes del taller
- Durante taller: Seguir agenda con placeholders
- Después taller: Comenzar reto 30 días

---

### 2️⃣ PROMPTS_MAESTROS_COPIAR_PEGAR.md
**Para:** Todos
**Contiene:** Los 3 PROMPTS MAESTROS completos, listos para copiar-pegar:
- PROMPT #1: Requirements Engineer Agent
- PROMPT #2: Product Owner Agent
- PROMPT #3: Agentic Software Engineer (Antigravity Base)

**CUÁNDO USAR:**
1. **Primero:** PROMPT #1 (Requirements Engineer)
   - Cópialo completo
   - Pégalo en Claude/Kiro/Antigravity
   - Reemplaza [PLACEHOLDERS] con tu contexto
   - Output: Specification (30-40 páginas)

2. **Segundo:** PROMPT #2 (Product Owner)
   - Cópialo completo
   - Reemplaza [PLACEHOLDERS]
   - Output: Roadmap + Unit economics + Market analysis

3. **Tercero:** PROMPT #3 (Software Engineer)
   - Cópialo completo
   - Pégalo en Antigravity System Instructions
   - Reemplaza [PLACEHOLDERS]
   - Sube tu spec como Knowledge Base
   - Output: MVP code + tests + docs (3-5 días)

---

### 3️⃣ PROMPTS_ANTIGRAVITY_ESPECIALIZADOS.md
**Para:** Usuarios avanzados de Antigravity
**Contiene:** 4 prompts especializados para roles específicos:
- PROMPT #1A: Frontend Agent (React/Vue/Angular)
- PROMPT #1B: Backend/DevOps Agent (APIs + Infrastructure)
- PROMPT #1C: SRE/DevOps Agent (Reliability, Monitoring)
- PROMPT #1D: QA/Testing Agent (Test strategy)

**CUÁNDO USAR:**
- DESPUÉS de ejecutar PROMPT #3
- Para profundizar especialización por rol
- Opcional: Solo si necesitas control granular

**CÓMO INTEGRAR CON ANTIGRAVITY:**
```
Opción A: Agentes separados (5 agentes)
- Agent 1: PROMPT #3 (maestro)
- Agent 2: PROMPT #1A (frontend)
- Agent 3: PROMPT #1B (backend)
- Agent 4: PROMPT #1C (devops)
- Agent 5: PROMPT #1D (qa)

Opción B: Un agent + rol switching (recomendado)
- Agent: PROMPT #3 (maestro)
- Tarea 1: Usa PROMPT #1A inline
- Tarea 2: Usa PROMPT #1B inline
- Tarea 3: Usa PROMPT #1D inline
- Tarea 4: Usa PROMPT #1C inline
```

---

### 4️⃣ ruta_agentcamp_2026.md (Original, MANTENER)
**Para:** Referencia completa de teoría
**Contiene:**
- Teoría fundamental (pensamiento de sistemas)
- Los 3 pilares del AgentCamp
- Arquitectura típica (CRM case study)
- Notas sobre ingeniería de sistemas

**CUÁNDO USAR:**
- Para entender fundamentos
- Como referencia durante el reto
- Para mentoring/enseñanza

---

### 5️⃣ Archivos de CÓDIGO (Notebooks)
**Para:** Desarrollo real
**Contiene:**
- Setup backend (FastAPI + SQLAlchemy)
- Setup frontend (Next.js + React)
- Tests (pytest + Jest)
- CI/CD (GitHub Actions)

**CUÁNDO USAR:**
- Durante generación Antigravity (como referencia)
- Copiar-pegar si necesitas templates

---

## 🎯 FLUJO RECOMENDADO DE 30 DÍAS

### SEMANA 1: ESPECIFICACIÓN (Días 1-3)

```
DÍA 1-2: Preparación
├─ Revisar: TALLER_AGENTCAMP_90MIN_RETO30DIAS.md
├─ Revisar: PROMPTS_MAESTROS_COPIAR_PEGAR.md (PROMPT #1)
├─ Llenar placeholders con tu idea
└─ Output: Contexto listo

DÍA 3: PROMPT #1 - Requirements Engineer
├─ Abrir: PROMPTS_MAESTROS_COPIAR_PEGAR.md
├─ Copiar: PROMPT #1 completo
├─ Destino: Claude/Kiro/Antigravity
├─ Reemplazar [PLACEHOLDERS] con tu contexto
├─ Ejecutar: Agent genera specification v1.0
└─ Output: spec-requirements.md (30-40 págs)

VERIFICACIÓN:
☐ Spec tiene 30-40 páginas
☐ User stories tienen AC testeable (7 elementos)
☐ Ambigüedad: 0%
☐ Tu equipo lo aprueba
```

### SEMANA 2: PRODUCT (Días 4-7)

```
DÍA 4-7: PROMPT #2 - Product Owner
├─ Abrir: PROMPTS_MAESTROS_COPIAR_PEGAR.md
├─ Copiar: PROMPT #2 completo
├─ Destino: Claude/Kiro/Antigravity
├─ Input: Tu spec de Semana 1
├─ Reemplazar [PLACEHOLDERS]
├─ Ejecutar: Agent genera roadmap + business model
└─ Output: product-roadmap.md (20-30 págs)

VERIFICACIÓN:
☐ TAM/SAM/SOM calculados
☐ 3 personas (ICPs) descritas
☐ Roadmap tiene milestones claros
☐ Unit economics validadas
☐ Go-to-market strategy escrita
```

### SEMANAS 3-4: CÓDIGO AUTÓNOMO (Días 8-26)

```
DÍA 8-9: Setup Antigravity
├─ Abrir: TALLER_AGENTCAMP_90MIN_RETO30DIAS.md
├─ Sección: "PASO 2: Crear Proyecto"
├─ Crear workspace + project en antigravity.ai
├─ Conectar GitHub repo
└─ Output: Antigravity workspace listo

DÍA 9-10: Preparar Generación
├─ Subir a "Knowledge Base":
│  ├─ spec-requirements.md
│  ├─ architecture.md (si tienes)
│  └─ product-roadmap.md
├─ Esperar indexación (2-3 min)
└─ Output: Knowledge base indexada

DÍA 10: Activar Antigravity
├─ Copiar: PROMPTS_MAESTROS_COPIAR_PEGAR.md → PROMPT #3
├─ Pegar en: Antigravity → Settings → System Instructions
├─ Reemplazar: TODOS los [PLACEHOLDERS]
├─ Configurar:
│  ├─ Autonomy Level: 2 (Autonomous)
│  ├─ Auto-commits: ON
│  ├─ Auto-deploy: OFF (primero staging)
│  └─ Notification: Email diaria
├─ Click: "Start Generation"
└─ Output: Generation iniciada ✓

DÍA 11-26: MONITOREO (10 minutos/día)
├─ Cada mañana:
│  ├─ Revisar Antigravity dashboard
│  ├─ Coverage > 85%? ✓
│  ├─ Tests passing? ✓
│  ├─ No critical issues? ✓
│  └─ Si todo OK: Continuar
├─ Si problema:
│  ├─ Click "Pause"
│  ├─ Revisar logs
│  ├─ Apoyar a agent si atascado
│  └─ Click "Resume"
└─ Output: MVP se genera automáticamente

HITOS ESPERADOS:
- Día 12-14: Database + backend schema ✓
- Día 15-18: API endpoints ✓
- Día 19-22: Frontend components ✓
- Día 23-25: Testing + optimization ✓
- Día 26: Deploy a staging ✓
```

### SEMANA 5: VALIDACIÓN (Días 27-30)

```
DÍA 27: Demo Preparación
├─ Revisar MVP en staging
├─ Encontrar 10 usuarios early (amigos/colegas)
├─ Crear script de demo (5 min)
└─ Output: Demo listo

DÍA 28-29: User Testing
├─ Demo 1-on-1 con 10 usuarios
├─ Recolectar feedback:
│  ├─ Qué les gustó
│  ├─ Qué mejorarían
│  ├─ Pagarían por esto?
│  └─ Cuánto?
├─ Document feedback en Notion/Google Sheets
└─ Output: 10 customer feedback interviews

DÍA 30: Aprendizajes
├─ Documentar:
│  ├─ Qué funcionó
│  ├─ Qué no funcionó
│  ├─ Siguientes pasos
│  ├─ Roadmap Q2 actualizado
│  └─ Métricas baseline
├─ Crear: "30-Day Learnings" doc (2-3 págs)
└─ Output: Documento de aprendizajes

CHECKLIST FINAL DÍA 30:
☐ MVP funcional
☐ 80%+ test coverage
☐ < $500 total cost
☐ 10+ usuarios probando
☐ Feedback documentado
☐ Métricas baseline establecidas
☐ Roadmap Q2 escrito
☐ Documento de aprendizajes
```

---

## 🛠️ REFERENCIA RÁPIDA: DÓNDE ESTÁ CADA COSA

| Necesito... | Ir a... | Qué hacer |
|------------|---------|-----------|
| Entender qué es AgentCamp | TALLER_AGENTCAMP_90MIN_RETO30DIAS.md | Leer "Visión Ejecutiva" |
| Ejecutar PROMPT #1 | PROMPTS_MAESTROS_COPIAR_PEGAR.md | Copiar PROMPT #1 completo |
| Ejecutar PROMPT #2 | PROMPTS_MAESTROS_COPIAR_PEGAR.md | Copiar PROMPT #2 completo |
| Ejecutar PROMPT #3 | PROMPTS_MAESTROS_COPIAR_PEGAR.md | Copiar PROMPT #3 completo |
| Especificar componentes frontend | PROMPTS_ANTIGRAVITY_ESPECIALIZADOS.md | Copiar PROMPT #1A |
| Especificar APIs backend | PROMPTS_ANTIGRAVITY_ESPECIALIZADOS.md | Copiar PROMPT #1B |
| Setup testing | PROMPTS_ANTIGRAVITY_ESPECIALIZADOS.md | Copiar PROMPT #1D |
| Setup DevOps/infra | PROMPTS_ANTIGRAVITY_ESPECIALIZADOS.md | Copiar PROMPT #1C |
| Ejemplos de código | ruta_agentcamp_2026.md + notebooks | Ver sección "Notebooks de Código" |
| Instrucciones Antigravity | TALLER_AGENTCAMP_90MIN_RETO30DIAS.md | Sección "CÓMO USAR EN ANTIGRAVITY" |
| Teoría de sistemas | ruta_agentcamp_2026.md | Sección "Teoría Fundamental" |
| Entender pipeline completo | ruta_agentcamp_2026.md | Leer secciones 1-5 |

---

## 🎓 TRAINING PATH RECOMENDADO

### Para PRINCIPIANTES (Nunca has usado IA para coding)

```
Paso 1: Leer
└─ TALLER_AGENTCAMP_90MIN_RETO30DIAS.md (15 min)

Paso 2: Ver ejemplos
└─ ruta_agentcamp_2026.md (30 min)

Paso 3: Asistir taller
└─ Taller en vivo (90 min)

Paso 4: Ejecutar paso a paso
├─ PROMPT #1 (Requirements) con AYUDA
├─ PROMPT #2 (Product Owner) con AYUDA
├─ PROMPT #3 (Software Engineer) CON MONITOREO DIARIO
└─ Duration: 30 días

Resultado: MVP + aprendizaje
```

### Para INTERMEDIOS (Has usado ChatGPT/Claude para coding)

```
Paso 1: Revisar diferencias
└─ PROMPTS_MAESTROS_COPIAR_PEGAR.md (15 min)

Paso 2: Ejecutar PROMPT #3 directamente
├─ Crear workspace Antigravity
├─ Pegar PROMPT #3
├─ Setup spec
└─ Start generation (autonomy level 2)

Duration: 5-7 días para MVP

Resultado: MVP sin supervisión
```

### Para AVANZADOS (CTOs, Architects, DevOps engineers)

```
Paso 1: Personalizar prompts
└─ PROMPTS_ANTIGRAVITY_ESPECIALIZADOS.md

Paso 2: Setup multi-agent configuration
├─ Agent 1: PROMPT #3 (maestro)
├─ Agent 2: PROMPT #1A (frontend)
├─ Agent 3: PROMPT #1B (backend)
├─ Agent 4: PROMPT #1D (qa)
└─ Agent 5: PROMPT #1C (devops)

Paso 3: Configure orchestration
└─ Custom task dependencies

Paso 4: Monitor + iterate
└─ Weekly improvements

Resultado: Production system con IA
```

---

## 🔗 INTEGRACIÓN: CÓMO CONECTAN LOS ARCHIVOS

```
IDEA VAGA
   ↓ (Usa: TALLER_AGENTCAMP_90MIN_RETO30DIAS.md)
[PROBLEMA IDENTIFICADO + PLACEHOLDER LLENOS]
   ↓ (Usa: PROMPTS_MAESTROS_COPIAR_PEGAR.md → PROMPT #1)
[ESPECIFICACIÓN COMPLETA]
   ↓ (Usa: PROMPTS_MAESTROS_COPIAR_PEGAR.md → PROMPT #2)
[ROADMAP + BUSINESS MODEL]
   ↓ (Usa: PROMPTS_MAESTROS_COPIAR_PEGAR.md → PROMPT #3)
[CÓDIGO AUTÓNOMO - ANTIGRAVITY]
   ↓ (OPCIONAL - Usa: PROMPTS_ANTIGRAVITY_ESPECIALIZADOS.md)
[MEJORAS ESPECIALIZADAS]
   ↓
MVP PRODUCTION-READY ✓
```

---

## 📞 SOPORTE Y RECURSOS

### Donde obtener ayuda

```
PROBLEMA: No entiendo cómo empezar
SOLUCIÓN: 
1. Lee: TALLER_AGENTCAMP_90MIN_RETO30DIAS.md
2. Sigue: "AGENDA TALLER (90 MIN)"
3. Llena: "Placeholder para tu idea"

PROBLEMA: No sé cómo usar Antigravity
SOLUCIÓN:
1. Lee: TALLER_AGENTCAMP_90MIN_RETO30DIAS.md
2. Sección: "CÓMO USAR EN ANTIGRAVITY"
3. Sigue: Paso 1-6 exactamente

PROBLEMA: Agent está atascado
SOLUCIÓN:
1. Abre: TALLER_AGENTCAMP_90MIN_RETO30DIAS.md
2. Sección: "MONITOREO ANTIGRAVITY"
3. Sigue: Pasos de troubleshooting

PROBLEMA: No tengo spec clara
SOLUCIÓN:
1. Ejecuta: PROMPT #1 (Requirements Engineer)
2. 3-5 iteraciones
3. Agent hará preguntas hasta clarificar
```

### Documentación externa

```
Antigravity docs: https://docs.antigravity.ai
Azure Foundry: https://docs.globalai.community/azure-client.html
Claude API: https://platform.openai.com/docs
GitHub: https://docs.github.com
```

---

## ✅ CHECKLIST ANTES DE EMPEZAR

```
SETUP:
☐ Descargar/guardar los 5 archivos
☐ Crear carpeta: /agentcamp
☐ Guardar archivos en la carpeta
☐ Crear Antigravity workspace
☐ Crear GitHub repo

PREPARACIÓN:
☐ Idea identificada (problema real)
☐ Target users definidos (3-5 personas)
☐ Restricciones claras (budget, timeline)
☐ Equipo formado (roles asignados)
☐ Métricas de éxito definidas (3-5 KPIs)

DOCUMENTACIÓN:
☐ Problema statement (1 pág)
☐ Market sizing (TAM/SAM/SOM)
☐ Competitors identificados (3)
☐ Wireframes básicos (si tienes)

LISTO PARA:
☐ Ejecutar PROMPT #1
☐ Generar specification
☐ Comenzar 30-day challenge
```

---

## 🚀 NEXT STEPS

1. **Ahora:** Descarga y guarda los 5 archivos
2. **Mañana:** Lee TALLER_AGENTCAMP_90MIN_RETO30DIAS.md
3. **Mañana tarde:** Llena los placeholders con tu idea
4. **Mañana noche:** Prepárate para ejecutar PROMPT #1
5. **Día 3:** Ejecuta PROMPT #1 (Requirements Engineer)

**Tu MVP te espera en 30 días.** ¡Comenzemos! 🎉

---

**Documento versión:** 2.0
**Última actualización:** [Omitida - Sin fechas]
**Formato:** Guía maestro + Índice de recursos

