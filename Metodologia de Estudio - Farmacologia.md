# Metodología de Estudio — Farmacología

> Revisión de evidencia sobre cómo estudiar farmacología para retener mecanismo, nombres, farmacocinética/farmacodinamia (PK/PD), reacciones adversas medicamentosas (RAM) e indicaciones/contraindicaciones, sin que el volumen (12 temas × ~20 fármacos) se vuelva memorización pura. Aplicable a cualquier grupo farmacológico que trabajes con `farmaco-memoria` o `farmaco-cuadro`.

---

## Sistema propuesto (resumen ejecutivo)

```
1. Elegir el fármaco PROTOTIPO de cada grupo → razonar su mecanismo completo (sesión activa)
2. Del mecanismo del prototipo, derivar en cadena: efecto PD → indicación → RAM esperable → contraindicación
3. El resto del grupo = solo diferencias respecto al prototipo (no mecanismo desde cero)
4. Nombres: aprender la RAÍZ del grupo (INN/WHO), no cada nombre suelto
5. RAM: clasificar cada una como "extensión del mecanismo" (tiene por qué) o "idiosincrática" (no lo tiene, va directo a repaso espaciado)
6. Fijar con interleaving (mezclar grupos confundibles) + repetición espaciada (Anki) del residuo arbitrario
7. Priorizar tiempo en los conceptos umbral: mecanismo de acción, relación potencia/eficacia, farmacocinética — son los que trancan todo lo demás
```

---

## 1. Estrategia general de estudio de farmacología

La farmacología es reconocida en la literatura de educación médica como una disciplina con **conceptos umbral** (*threshold concepts*): ideas que son difíciles de cruzar pero que, una vez comprendidas, transforman la forma en que se aprende todo lo demás en la materia. Los estudios identifican específicamente tres: **mecanismo de acción y interacción fármaco-receptor**, la **distinción potencia vs. eficacia**, y **farmacocinética**. Los estudiantes que no cruzan ese umbral quedan en una fase de "mimetismo" — memorizan superficialmente sin poder aplicar — mientras que cruzarlo produce un cambio irreversible en la comprensión ([Guilding et al., 2024, *Pharmacology Research & Perspectives*](https://bpspubs.onlinelibrary.wiley.com/doi/full/10.1002/prp2.70035); [estudio cualitativo de conceptos umbral en farmacología](https://hpe.researchcommons.org/journal/vol6/iss2/5/); [naturaleza cognitiva de los conceptos umbral, 2024](https://pubmed.ncbi.nlm.nih.gov/38899987/)).

**Implicación práctica:** no repartas tu tiempo de forma pareja entre los 12 temas. Invierte desproporcionadamente en dominar mecanismo de acción, potencia/eficacia y farmacocinética como *herramientas transferibles* al inicio — el resto del contenido se vuelve más barato de aprender una vez que esas herramientas están sólidas, porque dejan de ser 12 temas aislados y pasan a ser una sola lógica aplicada 12 veces.

Las técnicas con mayor evidencia agregada para el conjunto de la materia (no solo un fármaco puntual) son tres, y se combinan, no compiten entre sí:

- **Repetición espaciada con tarjetas de recuperación activa (Anki):** el estudio más directo en farmacología de pregrado (2024, *The Clinical Teacher*) implementó 501 tarjetas sobre 5 módulos con 104 estudiantes de primer año: menos estudiantes reportaron farmacología como "difícil" en los módulos cardiovascular y renal frente a la cohorte sin tarjetas, y el 75% las calificó como útiles ([Magro et al., 2024](https://pubmed.ncbi.nlm.nih.gov/39155059/)). Un estudio de 2025 en *Frontiers in Medicine* midió puntaje post-test de 16.24 (con tarjetas espaciadas) vs. 11.89 (método tradicional) sobre la misma base. El 87.8% de los estudiantes de medicina cree que Anki contribuye significativamente a su éxito en los módulos, y el uso de Anki correlaciona con percepción de éxito académico ([patrones de uso de Anki en primer año de medicina](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12662189/)). Esto ya lo tienes cubierto con `anki-marcado`.

- **Mapas conceptuales:** una revisión sistemática de 2025 confirma que mapas/mind maps mejoran específicamente la retención y comprensión en estudiantes preclínicos, superando a la enseñanza tradicional en transferencia de conocimiento y comprensión ([revisión sistemática, 2025](https://pubmed.ncbi.nlm.nih.gov/40553305/)). En farmacología puntual, el 74.5% de los estudiantes reportó que el mapeo conceptual facilitó adquisición de conocimiento profundo, y se ha usado específicamente para organizar mecanismo→efecto→indicación de un grupo farmacológico completo en una sola vista ([mapeo conceptual en farmacología, MedEdPORTAL](https://www.mededportal.org/doi/10.15766/mep_2374-8265.10281); [uso de mapas conceptuales en farmacología](https://pubmed.ncbi.nlm.nih.gov/21798134/)). Esto es una versión formalizada de los esquemas que ya haces en la tablet — vale la pena estructurarlos explícitamente como mapa conceptual (nodo central = mecanismo del prototipo, ramas = efecto/indicación/RAM/contraindicación) en vez de notas lineales.

- **Práctica intercalada (interleaving) entre grupos confundibles:** en estudios de aprendizaje de conceptos similares, la práctica intercalada produjo 72% de acierto vs. 38% con práctica bloqueada, y casi el doble de retención a largo plazo, porque obliga al cerebro a discriminar continuamente entre opciones en vez de reconocer un patrón repetido ([interleaving y discriminación de conceptos similares](https://www.researchgate.net/publication/271922077_Interleaving_Helps_Students_Distinguish_among_Similar_Concepts)). Aplicado a tu volumen: no estudies "todos los betabloqueantes" y luego "todos los IECA" en bloques aislados — una vez que ya viste ambos grupos, mezclá preguntas de ambos en el mismo repaso. Esto es exactamente lo que hace el paso 5 (opcional) de la sesión de `farmaco-memoria`; conviene dejar de tratarlo como opcional y hacerlo sistemático.

---

## 2. Cómo estudiar cada fármaco individual

Marco de trabajo en cadena, no en lista:

```
Mecanismo de acción (razonado, no memorizado)
        │
        ├─→ Efecto farmacodinámico esperado
        │        │
        │        ├─→ Indicación (¿qué patología se beneficia de ESE efecto?)
        │        └─→ RAM por extensión del mecanismo (¿dónde más actúa ese mismo efecto y no lo quiero?)
        │
        └─→ Farmacocinética (¿cómo llega, se metaboliza y se elimina?)
                 │
                 └─→ Contraindicación por PK (¿qué órgano de eliminación, si falla, lo vuelve tóxico?)
```

Para el **fármaco prototipo** de cada grupo, esta cadena se razona completa (sesión con `farmaco-memoria`, tú intentas primero cada eslabón). Para el **resto del grupo**, solo se anota la diferencia respecto al prototipo: esto es lo que reduce el trabajo de 20 mecanismos por tema a ~3-4 mecanismos razonados + diferencias puntuales, siguiendo el modelo de currículo por fármaco prototipo usado en educación médica para responder justamente al problema de saturación de contenido y sobrecarga cognitiva ([currículo por fármaco prototipo](https://faseb.onlinelibrary.wiley.com/doi/abs/10.1096/fasebj.2019.33.1_supplement.497.7); [carga cognitiva en educación farmacéutica](https://pubmed.ncbi.nlm.nih.gov/42526836/)).

---

## 3. Cómo memorizar los nombres — el hallazgo que cambia el problema

Aquí está el punto que probablemente no sabías y que reduce directamente tu "residuo arbitrario": **los nombres genéricos de los fármacos no son arbitrarios.** La OMS (WHO INN) y el consejo USAN asignan una **raíz** (*stem*) — una sílaba estandarizada de 2 a 5 letras, casi siempre al final del nombre — que identifica la clase farmacológica o el mecanismo de acción. Existen más de 400 raíces catalogadas oficialmente, organizadas por categoría farmacológica ([lista de raíces INN de la OMS, resumen en ACS J. Med. Chem.](https://pubs.acs.org/doi/10.1021/acs.jmedchem.1c00181); [guía de nomenclatura USAN, AMA](https://www.ama-assn.org/about/united-states-adopted-names/united-states-adopted-names-naming-guidelines); [nomenclatura de fármacos, PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC8154580/)). Dos fármacos que terminan en la misma raíz comparten clase, mecanismo y, casi siempre, perfil de RAM.

**Implicación práctica:** en vez de memorizar 20 nombres sueltos por tema, memorizas la raíz del grupo una sola vez, y cada nombre nuevo que veas ya "tiene sentido" apenas lo lees. Ejemplos de raíces de alto rendimiento para tus 12 temas (lista ilustrativa, no exhaustiva — cuando trabajes cada grupo con `farmaco-memoria`, identificamos la raíz exacta como parte del paso 1):

| Raíz | Clase | Ejemplo |
|---|---|---|
| -olol | Betabloqueante | Propranolol, atenolol |
| -pril | IECA | Enalapril, captopril |
| -sartán | ARA-II | Losartán, valsartán |
| -dipino | Bloqueante de canales de calcio | Amlodipino, nifedipino |
| -tatina | Estatina | Atorvastatina, simvastatina |
| -azepam / -azolam | Benzodiacepina | Diazepam, alprazolam |
| -prazol | Inhibidor de bomba de protones | Omeprazol, esomeprazol |
| -tidina | Antagonista H2 | Ranitidina, famotidina |
| -floxacino | Fluoroquinolona | Ciprofloxacino, levofloxacino |
| -ciclina | Tetraciclina | Doxiciclina, minociclina |
| -micina | Aminoglucósido/macrólido | Gentamicina, azitromicina |
| -cilina | Penicilina | Amoxicilina, ampicilina |
| -parina / -xabán / -gatrán | Anticoagulante | Enoxaparina, rivaroxabán, dabigatrán |
| -mab | Anticuerpo monoclonal | Infliximab, rituximab |
| -tinib | Inhibidor de tirosina-cinasa | Imatinib, erlotinib |
| -sona / -solona | Corticosteroide | Prednisona, metilprednisolona |
| -caína | Anestésico local | Lidocaína, bupivacaína |

**Excepción a marcar aparte:** los nombres que rompen el patrón (por historia comercial, no por mecanismo) son los que sí van directo a repaso espaciado como residuo verdaderamente arbitrario — pero son la minoría, no la mayoría como asumías.

---

## 4. Cómo relacionar y retener farmacocinética (PK) y farmacodinamia (PD)

La literatura de educación en farmacocinética señala el mismo problema que tú describís: la enseñanza tradicional expositiva de PK produce comprensión pobre, especialmente al aplicar los datos a un caso real, precisamente porque son conceptos abstractos con carga matemática ([revisión de estrategias de enseñanza de PK](https://www.researchgate.net/publication/357064510_The_Teaching_and_Learning_of_Pharmacokinetic_Subjects_to_Pharmacy_Students_Review_of_Teaching_Strategies)). Lo que consistentemente funciona mejor que la lectura pasiva:

- **Simulación interactiva con manipulación de parámetros:** ver cómo cambia la curva concentración-tiempo al mover manualmente vida media, volumen de distribución o clearance ayuda a internalizar qué significa cada parámetro en vez de memorizar la fórmula ([simulaciones interactivas de PK](https://www.ajpe.org/article/S0002-9459(23)03554-4/fulltext)).
- **Aprendizaje invertido (flipped):** revisar el material antes y usar el tiempo activo para aplicar los parámetros a casos de dosificación — mejora medible en retención frente a la clase expositiva tradicional en farmacología ([aula invertida y retención en farmacología, Semmelweis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11871698/)).

**Para conectar PK con PD sin que sean dos bloques separados:** cada parámetro de PK debería responderse en función de una pregunta de PD, no memorizarse aislado. La vida media no es un número suelto — determina la frecuencia de dosificación necesaria para mantener el efecto PD por encima del umbral terapéutico. El volumen de distribución no es un número suelto — te dice si el fármaco llega al compartimento donde está el receptor que buscás (p. ej., si necesita atravesar barrera hematoencefálica). Esa pregunta ("¿qué tiene que pasar en PK para que el efecto PD ocurra donde y cuándo lo necesito?") es la misma interrogación elaborativa que ya usás para mecanismo, aplicada a PK.

---

## 5. Cómo retener reacciones adversas (RAM) — clasificación mecanicista (Aronson)

Este es el marco que resuelve directamente tu queja de "busco cosas que no tienen sentido": la clasificación **DoTS** (Dose, Time, Susceptibility) de Aronson & Ferner separa explícitamente las RAM que **sí tienen mecanismo razonable** de las que **no lo tienen**, en vez de tratarlas todas igual ([Joining the DoTS, Aronson & Ferner, *BMJ* 2003](https://pubmed.ncbi.nlm.nih.gov/14630763/); [uso de DoTS en farmacovigilancia](https://link.springer.com/article/10.2165/00002018-200629070-00002)):

| Tipo (DoTS) | Cuándo ocurre | ¿Tiene "por qué"? | Ejemplo |
|---|---|---|---|
| **Tóxica** | Dosis supraterapéutica | Sí — es el mismo mecanismo, en exceso | Toxicidad digitálica → arritmia por exceso de inhibición de Na⁺/K⁺-ATPasa |
| **Colateral** (extensión del efecto) | Dosis terapéutica estándar | Sí — mismo mecanismo, tejido no deseado | Betabloqueante no selectivo → broncoespasmo (bloqueo β2 pulmonar, no solo β1 cardíaco) |
| **Hipersusceptibilidad** | Dosis subterapéutica, en paciente susceptible | No — es idiosincrática/genética/inmune | Anafilaxia por penicilina |

El complemento mecanístico **EIDOS** (Extrinsic species → Intrinsic species → Distribution → Outcome → Sequela) formaliza el mismo razonamiento que ya hacés al conectar mecanismo con efecto: qué molécula, sobre qué blanco, en qué tejido, produce qué alteración fisiológica, que se manifiesta como qué RAM clínica ([clasificación EIDOS](https://link.springer.com/article/10.2165/11318910-000000000-00000)).

**Implicación práctica:** antes de investigar el "por qué" de una RAM, primero clasificala. Si es **tóxica o colateral**, sí vale la pena razonarla — es una extensión directa del mecanismo que ya estudiaste, cero investigación adicional (el broncoespasmo del betabloqueante ya lo sabés si sabés que hay receptores β2 en bronquio). Si es **de hipersusceptibilidad**, dejá de buscarle un "por qué" fisiopatológico — no lo tiene, y ahí es donde el tiempo de investigación se pierde sin necesidad. Esa va directo a mnemotecnia + Anki.

---

## 6. Cómo retener indicaciones y contraindicaciones

**Indicaciones:** se derivan directo de la cadena del punto 2 — no es una lista a memorizar, es la pregunta "¿qué patología mejora con este efecto PD específico?", que ya podés responder solo con tu base de fisiopatología.

**Contraindicaciones:** tienen tres orígenes distintos, y conviene distinguirlos porque cada uno se razona diferente:

1. **Por mecanismo (PD):** el efecto farmacodinámico empeoraría una condición coexistente del paciente. Betabloqueante no selectivo contraindicado en asma — el mismo bloqueo β2 que es la RAM colateral (punto 5) es la razón de la contraindicación. Nota que esto conecta directo con la tabla DoTS: **toda RAM colateral es, en el paciente correcto, una contraindicación**. No son dos cosas separadas para memorizar.
2. **Por farmacocinética:** el órgano que elimina el fármaco está comprometido, y se acumula a niveles tóxicos. Esto se deriva directo del punto 4 (qué órgano depura el fármaco) cruzado con la patología del paciente.
3. **Por interacción:** mecanismo aditivo o sinérgico con otro fármaco o condición. IECA + diurético ahorrador de potasio → hiperkalemia (mismo eje renina-angiotensina-aldosterona, dos mecanismos convergiendo).

**Implicación práctica:** cuando memorices una contraindicación, preguntate primero a cuál de las tres categorías pertenece. Las categorías 1 y 3 ya las tenés resueltas si dominaste el mecanismo; solo la 2 requiere un dato adicional (vía de eliminación), que además es el mismo dato que necesitás para ajuste de dosis en insuficiencia renal/hepática — no es información nueva, es reutilización del mismo dato de PK.

---

## Cómo se integra todo (flujo por grupo farmacológico)

1. **Sesión activa** (`farmaco-memoria`) sobre el prototipo del grupo: cadena de mecanismo → PD → indicación → RAM (clasificada DoTS) → contraindicación (clasificada por origen). Vos intentás cada eslabón antes de que yo confirme.
2. **Raíz del nombre** del grupo, identificada en la misma sesión — reduce el resto de los nombres del grupo a reconocimiento de patrón, no memorización individual.
3. **Mapa conceptual** de esa cadena completa, una sola vista por grupo (podés hacerlo en la tablet, ahora como mapa conceptual explícito, no notas lineales).
4. **Diferencias del resto del grupo** respecto al prototipo — no mecanismo completo de nuevo.
5. **Residuo verdaderamente arbitrario** (RAM de hipersusceptibilidad, excepciones de nombre, dosis, vidas medias puntuales) → mnemotecnia propia + Anki (`anki-marcado`), repetición espaciada hoy/+2d/+1sem.
6. **Interleaving sistemático:** cada repaso espaciado mezcla el grupo actual con el grupo confundible más reciente (betabloqueantes con bloqueantes de canales de calcio, IECA con ARA-II, etc.), no como paso opcional sino como parte fija del calendario.

---

## Abreviaturas

- **PK:** farmacocinética
- **PD:** farmacodinamia
- **RAM:** reacción adversa medicamentosa
- **INN:** International Nonproprietary Name (denominación común internacional, OMS)
- **USAN:** United States Adopted Name
- **DoTS:** clasificación de RAM por Dosis, Tiempo (Time) y Susceptibilidad
- **EIDOS:** clasificación mecanística de RAM (Extrinsic species, Intrinsic species, Distribution, Outcome, Sequela)
- **IECA:** inhibidor de la enzima convertidora de angiotensina
- **ARA-II:** antagonista del receptor de angiotensina II

---

## Fuentes

- Guilding, C. et al. (2024). Threshold concepts and core concepts in pharmacology education: A commentary. *Pharmacology Research & Perspectives*. [Enlace](https://bpspubs.onlinelibrary.wiley.com/doi/full/10.1002/prp2.70035)
- Identifying and Exploring the Cognitive Nature of Threshold Concepts in Pharmacology (2024). *Teaching and Learning in Medicine*. [Enlace](https://pubmed.ncbi.nlm.nih.gov/38899987/)
- Threshold Concepts in the Discipline of Pharmacology — reflective essays. *Health Professions Education*. [Enlace](https://hpe.researchcommons.org/journal/vol6/iss2/5/)
- Magro, C. et al. (2024). Anki flashcards: Spaced repetition learning in the undergraduate medical pharmacology curriculum. *The Clinical Teacher*. [Enlace](https://pubmed.ncbi.nlm.nih.gov/39155059/)
- Utilization Patterns and Perceptions of Anki Among First-Year Medical Students. *PMC*. [Enlace](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC12662189/)
- Efficacy of mind maps and concept maps in enhancing academic performance among preclinical medical students: a systematic review (2025). [Enlace](https://pubmed.ncbi.nlm.nih.gov/40553305/)
- Concept Mapping for Enhanced Comprehension in Pharmacology. *MedEdPORTAL*. [Enlace](https://www.mededportal.org/doi/10.15766/mep_2374-8265.10281)
- Interleaving Helps Students Distinguish among Similar Concepts. [Enlace](https://www.researchgate.net/publication/271922077_Interleaving_Helps_Students_Distinguish_among_Similar_Concepts)
- The Teaching and Learning of Pharmacokinetic Subjects to Pharmacy Students: Review of Teaching Strategies. [Enlace](https://www.researchgate.net/publication/357064510_The_Teaching_and_Learning_of_Pharmacokinetic_Subjects_to_Pharmacy_Students_Review_of_Teaching_Strategies)
- A Blended Learning Approach to Teaching Basic Pharmacokinetics. *American Journal of Pharmaceutical Education*. [Enlace](https://www.ajpe.org/article/S0002-9459(23)03554-4/fulltext)
- Implementing the flipped classroom model to enhance knowledge retention in pharmacology (Semmelweis). [Enlace](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11871698/)
- Aronson, J.K. & Ferner, R.E. (2003). Joining the DoTS: new approach to classifying adverse drug reactions. *BMJ*. [Enlace](https://pubmed.ncbi.nlm.nih.gov/14630763/)
- Use of the DoTS Classification Scheme for Adverse Drug Reactions in Pharmacovigilance Planning. *Drug Safety*. [Enlace](https://link.springer.com/article/10.2165/00002018-200629070-00002)
- EIDOS — clasificación mecanística de RAM. *Drug Safety*. [Enlace](https://link.springer.com/article/10.2165/11318910-000000000-00000)
- What's in a Name? Drug Nomenclature and Medicinal Chemistry Trends using INN Publications. *J. Med. Chem.* [Enlace](https://pubs.acs.org/doi/10.1021/acs.jmedchem.1c00181)
- United States Adopted Names naming guidelines. *American Medical Association*. [Enlace](https://www.ama-assn.org/about/united-states-adopted-names/united-states-adopted-names-naming-guidelines)
- Patient Safety in Medication Nomenclature: Orthographic and Semantic Properties of INN. *PMC*. [Enlace](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4689353/)
- Currículo por fármaco prototipo — formulario común de medicación. *FASEB Journal*. [Enlace](https://faseb.onlinelibrary.wiley.com/doi/abs/10.1096/fasebj.2019.33.1_supplement.497.7)
- Applying Cognitive Load Theory to Best Practices in Pharmacy Education: A Narrative Review. [Enlace](https://pubmed.ncbi.nlm.nih.gov/42526836/)

*(Ver también la sesión previa de esta conversación para la evidencia de ciencia cognitiva general: interrogación elaborativa, efecto de producción, efecto de autoexplicación, codificación dual — Dunlosky et al. 2013, MacLeod & Bodner, Bisra et al. 2018.)*
