# Notas de lectura

Regla: las notas van en mis propias palabras. No se copian párrafos del documento.
Cada dato lleva su fuente (documento, versión y número de sección o página).

---

## 1. CubeSat Design Specification (CDS)
- Versión leída: Rev. 14.1 (CP-CDS-R14.1), febrero de 2022
- Fecha de lectura: 2026-10-10/2026-10-11

### Datos clave
#### Dimensiones y masa
- **Dimensiones externas 3U (X × Y × Z):** 100 × 100 × 340,5 mm CON STANDOFF (Apéndice B, pág. 31)
- **Dimensiones de los standoff:** (0,5-7,0) 0,1 min +/- Z (sección 2.2.1.2)
- **Tolerancia general de los dibujos:** ± 0,1 mm (Apéndice B, pág. 31, cuadro de rótulo)
- **Masa máxima típica 3U:** 6 kg (sección 2.2.10, Tabla 1)
- **¿Se puede superar esa masa?:** SI, PERO DEPENDE DEL DISPENSADOR (secciones 2.2.10.1 y 2.2.10.2)
- **Dispensador elegido:** P-POD CAL POLY (RAIL, 3U, ACCESS PORTS, PURGE, RF INSULATION, VIBRATION ATTENUATION, Z CONSTRAINT, -Z ADITIONAL VOLUME(TUNA CAN)) (Tabla 3)

#### Centro de gravedad
- **Límite en X:** ±2 cm DESDE EL CENTRO GEOMETRICO (sección 2.2.11, Tabla 2)
- **Límite en Y:** ±2 cm (sección 2.2.11, Tabla 2)
- **Límite en Z:** ±7 cm (sección 2.2.11, Tabla 2)
- **Cara entrante:** -Z (sección 2.2.2)

#### Rieles y protrusiones
- **Cumplir normas para propulsiones, materiales y explosivos:** AFSPCMAN 91-710 (sección 2.1.2/3/6)
- **Protrusión máxima sobre las caras amarillas:** 6,5 mm PERPENDICULAR A LA SUPERFICIE(sección 2.2.3)
- **Anchura mínima del riel:** 8,5 mm DESDE EL BORDE DEL RIEL A LA PRIMERA PROTUCION (sección 2.2.5)
- **Rugosidad de los rieles:** < 1,6 μm max (sección 2.2.6)
- **Radio mínimo de los bordes de los rieles:** 1 mm (sección 2.2.7)
- **Área de contacto en los extremos de los rieles:** 6,5 x 6,5 mm (sección 2.2.8)
- **Porcentaje mínimo de riel en contacto con el dispensador:** 75% (sección 2.2.9)
- **Mecanismo de separacion:** RESORTE DE SEPARACION 6,7 N max, CARRERA DE 2,5 mm min (SEPARACION DE OTROS CUBESATS) (sección 2.2.14.1)
- **Venteo durante el ascenso:** V/A < 50,8 m (sección 2.1.9)

#### Material de la estructura
- **Material recomendado:** ALEACION DE ALUMINIO 7075, 6061, 6082, 5005 O 5052 (sección 2.2.12)
- **Tratamiento obligatorio de superficies de contacto y por qué:** ANODIZADO DURO, PARA EVITAR SOLDADURA EN FRIO (sección 2.2.13)
- **Requisito de desgasificación (TML y CVCM):** 1 % Y 0,1 % (sección 2.1.7)

#### Eléctrico y seguridad
- **Estado de energía desde la entrega hasta el despliegue:** APAGADO (sección 2.3.1)
- **Interruptores de despliegue mínimos:** 1 (sección 2.3.2)
- **Reglas RTC:** AISLADO, FRECUENCIA < 320kHz, CORRIENTE < 10 mA (sección 2.3.3)
- **Pin RBF y cuánto puede sobresalir:** RETIRAR ANTES DE INTEGRACION  AL DISPENSADOR, SE PUEDE RETIRAR DESPUES SI TIENEN ACCESS PORTS, 6,5 mm SOBRE LA SUPERFICIE DEL RIEL, CORTAR ENERGIA (sección 2.3.5)
- **Proteccion de baterias:** SOLO EL CIRCUITO DE PROTECCION PUEDE ESTAR ENERGIZADO DESDE EL INICIO (sección 2.3.6)
- **Inhibidores contra transmisión RF accidental:** 3 (sección 2.3.7)
- **Inhibidores contra despliegues accidentales:** 3 (sección 2.3.8)
- **Campo magnetico de imanes:** 0,5 + CAMPO MAGNETICO TIERRA (GAUSS) (sección 2.1.8)

#### Operaciones
- **Reglamento de radio:** LICENCIAS NACIONALES, ITU O AMATEUR CON IARU (sección 2.4.1/2)
- **Cumplir normas de basura espacial:** NPR 8715.6 (sección 2.4.3)
- **Energía máxima de reentrada de un componente:** < 15 J (sección 2.4.3.1)
- **Analisis mitigacion de basura espacial:** POGRAMA DAS DE LA NASA O ESA (sección 2.4.3.3/4)
- **Espera mínima antes de desplegar antenas o paneles:** 30 minutos (sección 2.4.4)
- **Espera mínima antes de transmitir:** 45 minutos (sección 2.4.5)
- **Licencia de teledeteccion:** NORMAS USA NOAA (sección 2.4.6)
- **Prueba de ajuste:** FIT-CHECK (sección 2.4.7)

#### Pruebas
- **Normas de pruebas:** GEVS (GSFC-STD-7000A) O SMC-S-016 (sección 3)
- **Pruebas típicas y quién define los niveles:** VIBRACION ALEATORIA (LAUNCH PROVIDER), HORNEADO DE VACIO TERMICO (LAUNCH PROVIDER), PRUEBA DE CHOQUE (LAUNCH PROVIDER), INSPECCION VISUAL (LAUNCH PROVIDER) (sección 3.1/2/3/4)
- **Diferencia entre calificación y protovuelo:** DOS SATELITES, UNO DE PRUEBAS DURAS Y UNO DE PRUEBAS LEVES QUE SERA EL QUE VOLARA., UN SATELITE DE PRUEBAS INTERMEDIAS QUE SERA EL MISMO QUE VOLARA (sección 3.5.1/2)
- **Pruebas aceptacion:** PRUEBAS TODO SISTEMA INTEGRADO (sección 3.5.3)

#### Volumen extra opcional
- **"Tuna Can" del 3U, diámetro y altura máximos:** D 64 max, 50/50 CENTRADO, 36 mm max DEL STANDOFF (sección 2.2.1.3 y pág. 32)
- **¿Está garantizado?:** SE PUEDE PERO PREFERIBLEMENTE NO (sección 2.2.1.3)

## 2. NASA CubeSat 101
- Título: CubeSat 101: Basic Concepts and Processes for First-Time CubeSat Developers
- Editor: NASA CubeSat Launch Initiative (CSLI); redactado por Cal Poly
- Versión leída: revisión de octubre de 2017 (NP-2017-10-2470-HQ)
- Fecha de lectura: 2026-10-11
- Páginas: se cita el número impreso al pie, no el del visor PDF
- Contexto: documento de 2017 y centrado en EE. UU. (CSLI, FCC, NOAA). Si contradice
  al CDS Rev. 14.1, manda el CDS; por encima de ambos, el ICD de la misión.

### Cap. 1 — Introducción
- **Qué distingue a un CubeSat de un "small satellite" genérico:** ___ (1.1, p. 4)
- **Por qué la estandarización reduce costos (dos mecanismos):** ___ (1.1, p. 4)
- **¿El CDS es el requisito oficial de lanzamiento? ¿Cuál lo es?:** ___ (1.1, p. 4; 4.1 y 4.3, p. 40)
- **Tres funciones del dispensador:** ___ (1.2, p. 4)
- **Quién elige normalmente el dispensador:** ___ (1.2, p. 5)
- **Funcionamiento básico del P-POD y capacidad:** ___ (1.2.1, p. 5)
- **Condiciones para que un lanzador pueda llevar CubeSats:** ___ (1.3, p. 8)
- **Implicación para mi proyecto:** ___

### Cap. 2 — Proceso de desarrollo
- **Duración típica de diseño a entrega, y antelación de entrega antes del lanzamiento:** ___ (intro cap. 2, p. 9)
- **2.1 Concepto — consejo sobre flexibilidad de la órbita y por qué importa:** ___ (p. 11)
  - Implicación para D-002 (SSO ~550 km): ___
- **2.2 Financiación — qué cubre CSLI, qué no, y reserva de presupuesto recomendada:** ___ (pp. 11–14)
  - Categorías de costo a incluir en el paso 10.4: ___ (Fig. 9, p. 12; p. 13)
- **2.3 Revisión de mérito vs. revisión de factibilidad (qué evalúa cada una, quién revisa):** ___ (pp. 14–15)
  - Cómo aplico esa idea en mis cierres de fase: ___
- **2.4 Diseño — consejos "Free Advice" (en mis palabras) y la decisión de mi diseño que afecta cada uno:** (p. 16)
  | Consejo | Qué decisión de mi CubeSat afecta |
  |---|---|
  | ___ | ___ |
- **2.8 Licencias — cuántas licencias distintas, cuándo pedirlas, qué pasa si no están a tiempo:** ___ (pp. 20–21)
- **2.10 Estación terrena — componentes mínimos, por qué hacerla pronto, cómo practicar:** ___ (pp. 22–23)
- **2.16 Operaciones — TLE, vectores de estado, cómo se identifica el satélite tras el lanzamiento:** ___ (pp. 29–30)
  - Relación con mis herramientas (sgp4, skyfield, GMAT): ___

### Cap. 5 — Licencias
- **Qué dice el documento sobre organizaciones no estadounidenses:** ___ (intro cap. 5, p. 43)
- **5.1 Los cuatro tipos de licencia de radio y cuál correspondería a un proyecto no comercial:** ___ (p. 44)
- **5.1 Coordinación con la IARU — cuándo es necesaria, cuándo pedirla y por qué tarda:** ___ (pp. 45–46, 49)
- **5.1 Restricciones técnicas de diseño impuestas por la regulación:** ___ (pp. 47–48)
- **5.1 Plazo mínimo de tramitación citado:** ___ (p. 49)
- **5.2 Quién necesita licencia de teledetección, plazo aproximado y qué es el NEI waiver:** ___ (pp. 51–52)
- **5.2 Obligaciones después del lanzamiento:** ___ (p. 52)
- **Equivalente en Colombia:** NO está en este documento; se investiga en el paso 10.2.

### Cap. 6 — Documentación de certificación (hojeado)
- **Antelación del primer entregable respecto a la entrega del satélite:** ___ (p. 53)

| # | Entregable | Sección | Qué demuestra (en mis palabras) | Paso de mi plan que lo produce |
|---|---|---|---|---|
| 1 | ODAR (desechos orbitales) | 6.1 | ___ | 2.4 y 10.3 |
| 2 | Transmitter survey | 6.2 | ___ | 7.1–7.2 |
| 3 | Lista de materiales (TML/CVCM) | 6.3 | ___ | 8.3 |
| 4 | Propiedades de masa (masa, CG, inercias) | 6.4 | ___ | 3.4 (preliminar) y 8.4 |
| 5 | Informe de baterías | 6.5 | ___ | 6.3 y 6.5 |
| 6 | Verificación dimensional | 6.6 | ___ | 8.2 y 10.1 |
| 7 | Informe eléctrico (inhibidores, RBF, interruptores) | 6.7 | ___ | 6.5 y 7.6 |
| 8 | Análisis de venteo | 6.8 | ___ | (no está en el plan: ver dudas) |
| 9 | Pruebas: DITL, vibración/choque, TVAC bakeout | 6.9 | ___ | 7.8 y 10.1 |
| 10 | Carta de cumplimiento | 6.10 | ___ | 9.4 |
| 11 | Paquete de seguridad (MSPSP) | 6.11 | ___ | 10.1 |

### Contraste con el CDS Rev. 14.1
| Tema | CubeSat 101 (2017) | CDS Rev. 14.1 (2022) | Valor que uso |
|---|---|---|---|
| Masa máxima 3U | ___ (Apéndice C.6, p. 82) | 6 kg (2.2.10, Tabla 1) | ___ |
| Masa de 1U | ___ (1.1, p. 4) | ___ | ___ |
| Largo 3U y tolerancia | ___ (Apéndice C.6, p. 82) | 340,5 mm (Apéndice B) | ___ |
| Lista de verificación de aceptación | ___ (6.6, p. 58) | CIFP | ___ |
| Pin RBF: cuándo se retira | ___ (6.7, p. 58) | ___ (2.3.5) | ___ |
| Esperas tras la expulsión | ___ (Apéndice C, pp. 70 y 78) | 30 / 45 min (2.4.4 / 2.4.5) | ___ |
| Pirotecnia | ___ (2.4, p. 16) | ___ | ___ |

## 3. NASA State-of-the-Art of Small Spacecraft Technology
(pendiente)

## 4. NASA Systems Engineering Handbook
(pendiente)

## 5. SMAD
(pendiente)