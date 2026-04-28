# Actividad: Propuesta Documentada de Práctica Temática (ARM64 Assembly, C, Python o Bash)

## 1) Título

Diseña un título claro, específico y temático para tu práctica. Debe reflejar **qué problema resuelve** y **con qué lenguaje principal trabajarás**.

### Ejemplos de referencia (3–5)
1. **Automatización básica de respaldos locales con Bash para laboratorio escolar**
2. **Validador de archivos de configuración en C para entornos de práctica**
3. **Mini analizador de logs en Python para monitoreo local**
4. **Conversor de formatos numéricos en ARM64 Assembly (programa pequeño)**
5. **Organizador de evidencias académicas por carpetas usando Bash**

---

## 2) Descripción General

En esta actividad vas a **diseñar y documentar** la propuesta de un proyecto pequeño de práctica.  
El objetivo principal es que demuestres planeación técnica, estructura de repositorio y claridad de alcance **antes de programar**.

### Reglas clave
- Elige un lenguaje principal entre:
  - ARM64 Assembly
  - C
  - Python
  - Bash
- Si eliges **ARM64 Assembly**, úsalo solo para programas **muy pequeños** y con alcance acotado.
- Prioriza soluciones simples y ejecutables en entorno local.

### Restricciones del proyecto
Tu propuesta **debe cumplir** lo siguiente:
- Proyecto pequeño (compatible con apoyo limitado de IA como Codex).
- Sin frameworks pesados.
- Sin APIs pagadas.
- Sin bases de datos.
- Sin servicios en la nube.
- Sin contenedores.
- Sin dependencias complejas.

### Enfoque de evaluación de esta etapa
Primero se evalúa la **documentación y justificación técnica**; la implementación es secundaria en esta actividad.

---

## 3) Entregables del Estudiante

### Obligatorios
- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

### Opcionales (si decides adelantar implementación)
- `src/`
- `scripts/`
- `tests/`

---

## 4) Descripción de cada archivo

A continuación se describe **qué debe contener** cada documento.

### `README.md`
Documento de entrada del repositorio.

Incluye como mínimo:
- Título del proyecto.
- Resumen en 5–8 líneas.
- Lenguaje principal elegido y por qué.
- Estado del proyecto (solo propuesta / propuesta + prototipo).
- Instrucciones básicas para revisar la documentación.
- Integrantes (si aplica) y datos del curso.

Preguntas guía:
- ¿Qué problema pequeño resuelve tu propuesta?
- ¿Por qué ese problema es adecuado para una práctica corta?
- ¿Qué se espera entregar al final del proyecto completo?

### `docs/propuesta.md`
Documento central de planeación técnica.

Incluye como mínimo:
- Problema a resolver.
- Objetivo general y 2–4 objetivos específicos.
- Alcance (qué sí incluye / qué no incluye).
- Justificación técnica del lenguaje elegido.
- Restricciones técnicas del proyecto.
- Lista inicial de funcionalidades mínimas (MVP).
- Riesgos y mitigaciones (por ejemplo: tiempo, dificultad, ambiente).
- Cronograma breve por etapas.

Preguntas guía:
- ¿Tu alcance es realista para 1–2 semanas de trabajo académico?
- ¿Qué funcionalidad mínima demostraría que el proyecto sí funciona?
- ¿Qué partes pueden quedarse fuera sin romper el objetivo principal?

### `docs/caso_de_uso.md`
Explica el contexto real o simulado donde se usaría el proyecto.

Incluye como mínimo:
- Usuario objetivo (perfil básico).
- Contexto de uso (dónde, cuándo, para qué).
- Flujo principal de uso paso a paso.
- Entradas esperadas.
- Salidas esperadas.
- Criterios de éxito del caso de uso.

Preguntas guía:
- ¿Quién usaría esta herramienta y con qué nivel técnico?
- ¿Qué datos recibe y qué resultado devuelve?
- ¿Cómo sabrás que el caso de uso quedó bien resuelto?

### `docs/estructura_repositorio.md`
Define la organización de carpetas y archivos del proyecto.

Incluye como mínimo:
- Árbol de directorios propuesto.
- Descripción breve de cada carpeta.
- Convenciones de nombres de archivos.
- Estrategia para separar código, scripts y pruebas.
- Posibles cambios futuros de estructura (si el proyecto crece).

Preguntas guía:
- ¿Tu estructura facilita revisar, ejecutar y evaluar el proyecto?
- ¿Dónde pondrías la lógica principal y dónde las evidencias?
- ¿Cómo evitarías mezclar documentación con código experimental?

### `docs/plan_de_pruebas.md`
Planeación de validación funcional del proyecto.

Incluye como mínimo:
- Estrategia de pruebas manuales (y automáticas si aplica).
- Casos de prueba mínimos (tabla sugerida: ID, entrada, procedimiento, salida esperada).
- Criterios de aceptación por funcionalidad.
- Escenarios de error y manejo esperado.
- Evidencias a recolectar (capturas, logs, salida en terminal).

Preguntas guía:
- ¿Qué pruebas demuestran que la funcionalidad mínima cumple?
- ¿Qué errores comunes debe soportar tu solución?
- ¿Qué evidencia mostrarás para validar cada prueba?

---

## 5) Estructura Recomendada del Repositorio

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> Nota: `src/`, `scripts/` y `tests/` pueden iniciar vacíos en esta etapa si tu entrega se concentra en la propuesta documentada.

---

## Criterios de Evaluación Sugeridos (rúbrica breve)

- **Claridad del problema y objetivo (25%)**: el problema está bien delimitado y el objetivo es medible.
- **Viabilidad técnica (25%)**: alcance realista, sin dependencias prohibidas y acorde al lenguaje elegido.
- **Calidad de documentación (30%)**: redacción clara, estructura completa y justificación suficiente.
- **Coherencia de estructura y pruebas (20%)**: organización del repositorio y plan de pruebas alineados al caso de uso.

---

## Recomendaciones finales para estudiantes

- Mantén el proyecto pequeño y enfocado.
- Prioriza una solución funcional mínima antes que muchas funciones incompletas.
- Escribe documentación pensando en que otra persona pueda entender y ejecutar tu idea sin explicación oral.
- Si usas ARM64 Assembly, reduce el alcance al máximo y documenta muy bien el flujo de entrada/salida.
