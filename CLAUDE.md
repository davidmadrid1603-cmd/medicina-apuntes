# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

---

## Contexto del proyecto

Este directorio es el espacio de estudio clínico de **David**, estudiante de 4° año de medicina. Contiene notas estructuradas de Medicina Interna: planes de trabajo diagnósticos, revisiones clínicas y tablas comparativas por patología.

David ya domina semiología, fisiopatología e historia clínica. Su objetivo actual es aprender **razonamiento diagnóstico aplicado**: qué exámenes pedir, en qué orden y por qué, con la lógica fisiopatológica detrás de cada decisión.

**Idioma:** Siempre responder en español. Comunicación directa y pedagógica.

---

## Skills instalados — cuándo usar cada uno

Antes de responder cualquier solicitud médica, invocar el skill correspondiente:

| Situación | Skill a invocar |
|-----------|----------------|
| "Plan de trabajo de X", "qué pido en X", "cómo diagnostico X", "laboratorios para X", "gold standard de X" | `plan-de-trabajo` |
| "Revísame X", "explícame X", "fisiopatología de X", "semiología de X", "clínica de X", "cómo se presenta X" | `revision-clinica` |
| "Imágenes de X", "hallazgos en TC/RMN/eco de X", "signos radiológicos de X" | `imagen-medica` |
| Libro de texto o resumen bibliográfico | `book-summary` |

**Regla:** Si hay >1% de probabilidad de que un skill aplique, debe invocarse. No racionalizar por qué no aplicaría.

---

## Estándar de calidad del contenido

Los archivos `Plan de trabajo Accidente Cerebrovascular.md` y `Revision Accidente Cerebrovascular (ACV).md` son los modelos de referencia para la calidad esperada. Todo output médico debe cumplir:

### Planes de trabajo
- **Lista rápida de exámenes** al inicio (bloque de código), subcategorías por urgencia y subtipo de enfermedad: urgentes, complementarios, marcadores específicos, imagenología urgente/complementaria, especiales
- **Gold standard** explicado con sensibilidad/especificidad cuando estén disponibles en guías
- **Algoritmo diagnóstico** en árbol de decisión visual con ramas positivo/negativo; al final del árbol, bloque "¿Qué resultado NO se esperaría?" con 1-2 singularidades clínicas que deben hacer replantear el diagnóstico
- **Plan detallado por sistema**: párrafo completo por examen (mecanismo, qué detecta, hallazgo esperado); para los 2-3 exámenes más importantes incluir S/E cuando estén en guías
- **Tabla de valores normales vs. hallazgo esperado** por subtipo, con leyenda de abreviaturas — la columna "Hallazgo en [Patología]" siempre lleva el número exacto con unidades según valores estandarizados actuales; nunca solo "elevado" o "disminuido" sin cifra
- **Escalas clínicas** cuando la enfermedad las usa de forma estándar (NIHSS, DAS28, CURB-65, etc.)
- **Errores diagnósticos frecuentes**: 3-4 escenarios clínicos concretos con la singularidad que se ignoró y el diagnóstico que se perdió — no sesgos abstractos
- Alertas de urgencia destacadas con `>`
- Fuentes con nombre de guía, año y enlace

### Revisiones clínicas
- **Caso prototipo** al inicio: 3-4 líneas de escena clínica concreta (quién, qué, cuándo, cómo) — activa el illness script antes de cualquier definición abstracta
- **Descripción breve** (enabling conditions): quién tiene esta enfermedad y por qué importa
- **Representación del problema**: one-liner con semantic qualifiers (perfil, curso temporal, distribución, patrón, síndrome) — la frase que el clínico dice en el pasillo
- **Fisiopatología** (fault): 4 oraciones que narren el mecanismo completo, cada una construyendo sobre la anterior
- **Manifestaciones clínicas** (consequences): con ⭐ para hallazgos sello, organizadas por sistema, cada una con su "por qué"
- **Tabla de subtipos** si aplica: distinguir explícitamente características clave vs. discriminadores de cada subtipo
- **Semiología**: técnica exacta, resultado positivo, por qué ocurre ese hallazgo
- **¿Qué no encaja?**: 2-3 singularidades diagnósticas — hallazgos que si están presentes hacen menos probable este diagnóstico y hacia dónde apuntan
- **Tabla "¿Cómo identifico esta enfermedad?"**: paciente típico, síntoma cardinal, signo sello, laboratorio clave, imagen, asociación clásica, **ausencia característica**
- **Regla nemotécnica** si aplica
- **Para consolidar**: 1-2 enfermedades con presentación similar para estudiar en paralelo (interleaving), con el discriminador clave explicado
- Fuentes

### Tablas comparativas
- Filas: distinguir **características clave** (presentes consistentemente) de **discriminadores** (lo que diferencia una entidad de sus mimics)
- No listar lo que todas las entidades comparten
- Siempre incluir leyenda de abreviaturas debajo

---

## Formato de documentos

- Markdown estándar compatible con Typora
- Márgenes Typora: 10mm superior/inferior, 8mm laterales (no sugerir cambios)
- Bloques de código para algoritmos diagnósticos o esquemas de decisión
- Usar `---` como separador de secciones principales
- Fuentes al final del documento con autores, revista y año

---

## Lo que conecta cada examen con la enfermedad

David aprende mejor cuando cada examen tiene una justificación mecanística completa. Ejemplo del estándar esperado:

> **Glucometría / Glicemia urgente:** Es el primer examen que se realiza antes incluso del traslado al tomógrafo. La hipoglicemia grave (<50 mg/dL) puede producir un déficit neurológico focal idéntico clínicamente a un ACV isquémico ("pseudostroke hipoglicémico"), y se resuelve completamente con glucosa intravenosa. Confundirlo con un ACV real y dar trombolíticos sería catastrófico.

No: *"Pedir glucometría"*
Sí: párrafo con mecanismo fisiopatológico, consecuencia clínica, valor de corte relevante e implicación terapéutica

---

## Nivel de detalle y audiencia

- Audiencia: estudiante que ya conoce la base teórica, aprendiendo aplicación clínica
- No explicar conceptos básicos de anatomía o bioquímica elemental
- Sí explicar el **por qué** detrás de las decisiones diagnósticas
- Conectar siempre el hallazgo clínico con el mecanismo de enfermedad subyacente
- Incluir criterios diagnósticos oficiales cuando existan (ACR/EULAR, AHA, etc.)

---

## Sesiones de casos clínicos

La metodología completa de casos clínicos (tutor, feedback, estándares de plan, seguimiento de capítulos) vive en `casos-clinicos/CLAUDE.md`. Trabajar esas sesiones desde ese directorio para que Claude Code cargue ambos archivos.
