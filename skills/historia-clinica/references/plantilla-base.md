# Plantilla base — Historia clínica (todo negado/normal)

Este es el documento de partida. Todo está negado o en su valor normal por defecto, igual que la app cuando los campos quedan vacíos. **Edita dentro de esta plantilla** los positivos que aporte el usuario y rellena los `[campos]` con los datos del paciente. Los datos objetivos que falten (filiatorios, signos vitales) se dejan con `___`.

---

```markdown
# HISTORIA CLÍNICA

## 1. DATOS FILIATORIOS
Nombres y Apellidos: [nombre]    C.I: [ci]
Edad: [edad] años    F. de Nacimiento: [fechaNacimiento]    Lugar de Nacimiento: [lugarNacimiento]    Nacionalidad: [nacionalidad]
Sexo: [Hombre/Mujer]    Género: [Masculino/Femenino]    Edo. Civil: [estadoCivil]    Raza: [raza]
Religión: [religion]    E-mail: [email]    Teléfono hab: [telefonoHab o "No posee"]    Celular: [celular]
Dirección: [direccion]
Contacto de Emergencia: [contacto] / Parentesco: [parentesco] / [teléfono] / Dirección: [dirección]
Lugar donde ha Residido: [lugarResidido]
Profesión u Ocupación: [profesion]    N. Académico: [nivelAcademico]    Hemisferio Dominante: [hemisferio]

## 2. MOTIVO DE CONSULTA
Refiere "[motivo de consulta]"

## 3. ENFERMEDAD ACTUAL
[Párrafo narrativo. Ver convenciones en SKILL.md — empezar con "Paciente [masculino/femenino] de [edad] años de edad, natural de [lugar]..." y desarrollar con ALICIA-DPH.]

## 4. ANTECEDENTES PERSONALES
### 4.1 ANTECEDENTES MÉDICOS
#### 4.1.1 ENFERMEDADES DE LA INFANCIA
Niega Varicela, Sarampión, Fiebre Reumática, Parotiditis, Tos Ferina.

#### 4.1.2 ENFERMEDADES DEL ADULTO
Niega HTA, Diabetes Mellitus, Enfermedad Arterioesclerótica Cardiovascular, Hipertiroidismo, Hipotiroidismo, Artritis Reumatoide, Anemia, Asma.

#### 4.1.3 ENFERMEDADES DE TRANSMISIÓN SEXUAL
Niega Sífilis, Blenorragia, Clamidias, Chancroide, Herpes Genital, Hepatitis B y C, VPH, Gonorrea, VIH.

#### 4.1.4 TRANSFUSIONES SANGUÍNEAS
Niega transfusiones.

### 4.2 ANTECEDENTES EPIDEMIOLÓGICOS
Niega Chagas, Paludismo, Tuberculosis, Parasitosis Intestinal, Bilharziosis, Dengue, Amibiasis, Otras enfermedades infecciosas.

### 4.3 ANTECEDENTES INMUNOALÉRGICOS
#### Alergias
Niega alergias.

### 4.5 ANTECEDENTES QUIRÚRGICOS Y TRAUMÁTICOS
Ingresos Hospitalarios No Quirúrgicos: Niega.
Procedimientos Quirúrgicos: Niega.
Traumáticos: Niega.

### 4.6 MEDICACIÓN
Niega medicación actual.

## 5. ANTECEDENTES FAMILIARES
Madre: Niega patología.
Padre: Niega patología.
Hermanos: Niega patología.
Hijos: Niega patología.
Abuela Materna: Niega patología.
Abuelo Materno: Niega patología.
Abuela Paterna: Niega patología.
Abuelo Paterno: Niega patología.

## 6. HÁBITOS PSICOBIOLÓGICOS
### 6.1 Alimenticios
[Solo si hay datos: "[N] comidas al día. Cantidad: [x]. Tipo: [x]."]
### 6.2 Cafeínicos
Niega hábito.
### 6.3 Tabáquicos
Niega hábito.
### 6.4 Alcohólicos
Niega hábito.
### 6.5 Drogas
Niega hábito.
### 6.6 Actividad Física
Niega hábito.
### 6.7 Sueño
[Solo si hay datos.]
### 6.8 Sexuales
Niega vida sexual activa.
### 6.9 Ocupacionales
Sin antecedentes ocupacionales de relevancia.
### 6.10 Situación Personal
[Solo si hay datos.]

## 7. INTERROGATORIO FUNCIONAL
### 7.1 GENERAL
Niega fiebre, pérdida de peso, debilidad o fatiga, sudoración nocturna, intolerancia al frío o calor, tendencia al sangrado.
### 7.2 PIEL Y ANEXOS CUTÁNEOS
Niega erupciones y urticaria, prurito, cambios de pigmentación, ictericia, cianosis, tumoraciones y lunares, cambios en lunares, cambios en textura, crecimiento anómalo, edema.
### 7.3 CABEZA
Niega cefalea, mareos o vértigos, síncope, lipotimia.
### 7.4 OJOS
Niega defectos de agudeza visual, uso de lentes, escotomas, cambios en la visión, diplopía, epífora, escotomas centellantes, fotofobia, secreción.
### 7.5 OÍDOS
Niega trastornos de agudeza auditiva, acusia, hipoacusia, dispositivos de ayuda, tinitus, secreción, mareos, tendencia a caída.
### 7.6 NARIZ
Niega anosmia, hiposmia, cacosmia/parosmia, epistaxis, rinorrea, sinusitis, obstrucciones nasales, descargas postnasales.
### 7.7 BOCA
Niega caries, edéntula y prótesis dentaria, gingivorragia, dolor/ardor en lengua, disgeusia, disfonía, afonía, odinofagia, disfagia, halitosis, ulceración.
### 7.8 CUELLO
Niega dolor a la movilización, aumento de volumen, bocio, latidos, inflamación, adenomegalias.
### 7.9 TÓRAX Y PULMONES
Niega dolores respiratorios, tos, esputo, hemoptisis, hemoptoica, disnea, platipnea.
### 7.10 CARDIOVASCULAR
Niega dolor torácico, palpitaciones, claudicación intermitente, aumento de volumen en MI, frialdad en MI, dilataciones venosas, ulceraciones.
### 7.11 GASTROINTESTINAL
Niega alteración en características de heces, diarrea, constipación, disentería, melena, rectorragia, hematoquecia, alteración del apetito, intolerancia alimentaria, acidez, pirosis, dolor epigástrico, flatulencia, meteorismo, náuseas y vómitos, hematemesis, dolor rectal, hemorroides, secreciones rectales.
### 7.12 GENITOURINARIO
Niega poliuria, oliguria, anuria, nicturia, nocturia, polaquiuria, hematuria, coluria, tenesmo vesical, disuria, retención urinaria, incontinencia, enuresis.
### 7.13 GINECOLÓGICO
[Solo en Mujer.] Niega amenorrea, oligomenorrea, polimenorrea, hipermenorrea, menometrorragia, metrorragia, dismenorrea, dispareunia.
### 7.14 MUSCULOESQUELÉTICO
Niega paresia, mialgia, rigidez muscular, atrofia, calambres, artralgia, artritis, rigidez articular, anquilosis, artrosis, deformidad articular.
### 7.15 NEUROLÓGICO
Niega síncope, convulsiones, parálisis, anomalías sensoriales, pérdida de memoria, nerviosismo, inestabilidad de la marcha, desorientación, cambios de carácter, desórdenes psiquiátricos, alteraciones del lenguaje.

## 8. EXAMEN FÍSICO
### 8.1 SIGNOS VITALES
Temperatura: [temp]°C ([región])    PA: [PA] mmHg    FR: [FR] rpm
Pulso: [pulso] lpm    Peso: [peso] Kg    Talla: [talla] cm    IMC: [IMC] kg/m²
[PAM: [PAM] mmHg]

### 8.2 ASPECTO GENERAL
Paciente consciente, orientado(a) en tiempo, espacio y persona, colaborador(a), tranquilo(a). Habitus exterior normolíneo. Normonutrido(a). Sin signos de dificultad respiratoria aparente.

### 8.3 PIEL Y ANEXOS CUTÁNEOS
Piel morena, turgor y elasticidad conservada, normotérmica al tacto. Sin lesiones aparentes. Uñas sin alteraciones. Pelo normoimplantado.

### 8.4 CABEZA
Cabello normoimplantado, resistente a la tracción. Normocéfalo, no doloroso a la palpación, no se palpan tumoraciones ni reblandecimiento, sin soplos. Puntos de Valleix no dolorosos a la digitopresión.

### 8.5 OJOS
Cejas normoimplantadas y simétricas. Pestañas normoimplantadas y simétricas. Párpados simétricos. Apertura ocular conservada. Conjuntivas rosadas sin alteraciones. Esclerótica blanquecina. Iris de color marrón. Pupilas redondeadas, con margen regular y simétricas. Reflejo fotomotor directo presente; reflejo consensual presente.
Fundoscopia: reflejo rojo-naranja presente. Disco óptico redondeado, bordes netos, relación arteriovenosa 2:1, cruces arteriovenosos normales.

### 8.6 OÍDOS
Pabellón auricular normoimplantado, simétricos y sin alteraciones aparentes. Resistente a la tracción mecánica y compresión del trago no doloroso. Percusión de Apófisis Mastoides no dolorosa. Otoscopia: CAE permeable con escaso cerumen en ambos oídos. Membrana Timpánica normal, translúcida de color gris perlado, triángulo luminoso de Politzer visible en cuadrante antero-inferior, sin presencia de abultamiento ni secreciones.

### 8.7 NARIZ
Pirámide nasal normoimplantada, simétrica, sin dolor. Tabique nasal central. Fosas nasales permeables, con mucosas simétricas, rosadas.

### 8.8 BOCA Y GARGANTA
Labios simétricos, mucosa rosada. Encías, cara interna de las mejillas, paladar duro y úvula rosados, húmedos y sin lesiones. Amígdalas palatinas eutróficas. Dientes en buenas condiciones generales, sin edéntula. Lengua central y móvil, de aspecto normal, sin lesiones aparentes.

### 8.9 CUELLO
Simétrico y central. Movimientos activos y pasivos conservados y no dolorosos. Tráquea central, móvil con craqueo laríngeo y ruidos respiratorios audibles sin soplos. Ganglios de las cadenas occipitales, retroauriculares, preauriculares, submandibulares, submentonianos, laterocervicales y supraclaviculares no palpables. Tiroides no palpable ni visible, sin tumoraciones, sin bocio ni soplos. Latidos carotídeos presentes.

### 8.10 TÓRAX
Tórax normolíneo, simétrico, con respiración torácica y regular. Normoexpansible, Vibraciones Vocales conservadas en ambos hemitórax. Sonoridad a la percusión en ambos hemitórax. Ruidos respiratorios presentes en ambos hemitórax sin sonidos agregados.

### 8.11 CARDIOVASCULAR
Pulso arterial: frecuencia normal, ritmo regular, amplitud y forma conservadas. Ápex no visible, ni palpable. Latido epigástrico ausente. Auscultación RsCs rítmicos, R1 y R2 audibles. No se auscultan desdoblamientos ni presencia de R3 ni R4. No se auscultan agregados diastólicos ni sistólicos.

### 8.12 ABDOMEN
Abdomen plano, no se observa red venosa colateral, RSHs presentes, abdomen deprimible no doloroso a la palpación superficial ni profunda. Punto cístico, Mc Burney, zona pancreatoduodenal no dolorosa. A la percusión timpanismo.
Hígado no palpable. Riñones no palpables ni dolorosos, puño percusión negativa, puntos ureterales superior y medio no palpables ni dolorosos.
Bazo no palpable ni percutible.
Estómago chapoteo gástrico de Chomel negativo, no se palpan tumoraciones. Ciego y Colon no palpables ni dolorosos.

### 8.13 NEUROLÓGICO
Paciente vigil, colaborador(a), ubicado(a) en tiempo, espacio y persona. Escala de Glasgow 15/15 puntos (respuesta ocular 4/4, respuesta verbal 5/5 y motora 6/6). Con lenguaje fluido, coherente, repetición, denominación, articulación y prosodia adecuados. Praxia y gnosia indemnes. Memoria conservada.
SENSIBILIDAD: sensibilidad superficial y profunda conservada. Grafiestesia, barestesia, barognosia, batiestesia, palestesia y estereognosia conservada.
PARES CRANEALES:
I) Nervio Olfatorio: percepción de olores presentes y conservados.
II) Nervio Óptico: agudeza visual conservada. Visión de colores sin alteración. Campimetría por confrontación normal en ambos ojos.
III, IV, VI) Nervio Oculomotor, Troclear y Abducens: movimientos oculares presentes y conservados. Pupilas redondeadas con bordes regulares, isocóricas y reactivas. Reflejo fotomotor directo y consensual presentes.
V) Nervio Trigémino: sensibilidad en la porción anterior del cráneo y rostro conservada. Fuerza muscular del masetero y temporal conservada.
VII) Nervio Facial: fuerza muscular de los músculos de expresión facial conservada. Sensibilidad de los 2/3 anteriores de la lengua conservada.
VIII) Nervio Vestibulococlear: prueba de Weber no lateralizada. Rinne positiva bilateral. Romberg negativo.
IX, X) Nervio Glosofaríngeo y Vago: sensibilidad presente y conservada de la faringe, amígdalas, paladar blando y 1/3 posterior de la lengua. Úvula central. Reflejo nauseoso presente.
XI) Nervio Accesorio: movimientos pasivos y activos del cuello presentes y conservados.
XII) Nervio Hipogloso: lengua central, movimientos pasivos y activos presentes y conservados.
FUERZA MUSCULAR, TONO Y TROFISMO: trofismo y tono normal, fuerza muscular conservada en miembros superiores e inferiores, distal y proximal.
REFLEJOS OSTEOTENDINOSOS: reflejos osteotendinosos presentes en miembros superiores e inferiores.
Bicipital C5-C6 derecho e izquierdo II/IV
Tricipital C6-C7-C8 derecho e izquierdo II/IV
Estilo Radial C5-C6 derecho e izquierdo II/IV
Patelar L5 derecho e izquierdo II/IV
Aquiliano S1-S2 derecho e izquierdo II/IV
REFLEJOS MUSCULOCUTÁNEOS: presentes y conservados simétricamente.
Cutáneo Abdominal: presente bilateral.
Cutáneo Plantar: flexión plantar bilateral, sin signos de Babinsky.
PRUEBAS CEREBELOSAS:
Dedo-índice: negativo bilateral.
Dedo-nariz: negativo bilateral.
Talón-rodilla: negativo bilateral.
Movimientos rápidamente alternados: positivos bilateral.
Prueba de Romberg: negativa.

### 8.14 ARTICULAR
a) COLUMNA CERVICAL: No se evidencian tumefacciones, masas ni puntos dolorosos. Movimientos de flexo-extensión, rotación y lateralidad conservados y no dolorosos.

b) COLUMNA DORSAL: No se evidencian tumefacciones, masas ni puntos dolorosos. Movilidad conservada.

c) COLUMNA LUMBOSACRA: No se evidencian tumefacciones, masas ni puntos dolorosos. Movimientos de flexión, extensión, rotación y lateralidad conservados. Prueba de Schober normal. Pruebas neurológicas sin alteraciones.

d) ART SACROILÍACA: No se evidencian tumefacciones, masas ni puntos dolorosos. Movilidad conservada no dolorosa.

e) HOMBRO: No se evidencian tumefacciones, masas ni puntos dolorosos. Movimientos de flexo-extensión, abducción-aducción y rotación longitudinal conservados tanto activo como pasivo simétricamente. Maniobra de Jobe, Patte, Gerber y Neer negativas.

f) CODO: No se evidencian tumefacciones, masas ni puntos dolorosos. Movimientos activos y pasivos de flexo-extensión y prono-supinación conservados, no dolorosos.

g) MUÑECA: No se evidencian tumefacciones, masas ni puntos dolorosos. Movimientos de flexo-extensión, prono-supinación, abducción, aducción presentes no dolorosos.

h) ART METACARPOFALÁNGICA: No se evidencian tumefacciones, masas ni puntos dolorosos. Movimientos presentes y conservados.

i) RODILLA: No se evidencian tumefacciones, masas ni puntos dolorosos. Movimientos de flexión, extensión, rotación conservados. Prueba de McMurray y de compresión y distracción de Apley negativos. Prueba del bostezo negativa.

j) TOBILLO Y PIE: No se evidencian tumefacciones, masas ni puntos dolorosos. Movimientos conservados no dolorosos.

## DIAGNÓSTICO SINDRÓMÁTICO
[diagnóstico sindromático]

## DIAGNÓSTICO DE PATOLOGÍA
[diagnóstico de patología]

---

## PERTINENTES POSITIVOS

**[Nombre del paciente]**

**Motivo de consulta:** "[motivo]"

**Enfermedad actual:** [párrafo de enfermedad actual]

[Secciones con positivos — ver SKILL.md. Si no hay positivos, solo aparecen el nombre, el motivo y la enfermedad actual.]
```

---

## Notas de uso de esta plantilla

- Las subsecciones **4.4 Ginecobstétricos** (menarquia, menstruación, FUR, embarazos, partos, abortos) solo se incluyen si el paciente es mujer y hay datos; insértala entre 4.3 y 4.5.
- En el examen físico, los marcadores de género "(a)", "(o)" se ajustan al sexo del paciente cuando se conoce (ej.: para Hombre → "orientado, colaborador, tranquilo").
- Convierte saltos de línea simples en dobles dentro de los párrafos largos del examen físico si vas a renderizar el Markdown en un visor.
