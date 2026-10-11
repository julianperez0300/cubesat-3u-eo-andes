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
- **¿Se puede superar esa masa?:** NO (secciones 2.2.10.1 y 2.2.10.2)
- **Dispensador:** P-POD CAL POLY (RAIL, 3U, ACCESS PORTS, PURGE, RF INSULATION, VIBRATION ATTENUATION, Z CONSTRAINT, -Z ADITIONAL VOLUME(TUNA CAN)) (Tabla 3)

#### Centro de gravedad
- **Límite en X:** ±2 cm DESDE EL CENTRO GEOMETRICO (sección 2.2.11, Tabla 2)
- **Límite en Y:** ±2 cm (sección 2.2.11, Tabla 2)
- **Límite en Z:** ±7 cm (sección 2.2.11, Tabla 2)
- **Cara entrante:** -Z (sección 2.2.2)

#### Rieles y protrusiones
- **Cumplir normas para propulsiones, materiales y explosivos:** AFSPCMAN 91-710 (sección 2.1.2/3/6)
- **Protrusión máxima sobre las caras amarillas:** 6,5 mm PERPENDICULAR A LA SUPERFICIE(sección 2.2.3)
- **Anchura mínima del riel:** 8,5 mm DESDE EL BORDE DEL RIEL A LA PRIMERA PROTUCION (sección 2.2.5)
- **Rugosidad de los rieles:** 1,6 μm (sección 2.2.6)
- **Radio mínimo de los bordes de los rieles:** 1 mm (sección 2.2.7)
- **Área de contacto en los extremos de los rieles:** 6,5 x 6,5 mm (sección 2.2.8)
- **Porcentaje mínimo de riel en contacto con el dispensador:** 75% (sección 2.2.9)
- **Mecanismo de separacion:** RESORTE DE SEPARACION 6,5 N max, CARRERA DE 2,5 mm min (SEPARACION DE OTROS CUBESATS) (sección 2.2.14.1)
- **Venteo durante el ascenso:** V/A < 50,8 m (sección 2.1.9)

#### Material de la estructura
- **Material recomendado:** ALEACION DE ALUMINIO 7075, 6061, 6082, 5005 O 5052 (sección 2.2.12)
- **Tratamiento obligatorio de superficies de contacto y por qué:** ANODIZADO DURO, PARA EVITAR SOLDADURA EN FRIO (sección 2.2.13)
- **Requisito de desgasificación (TML y CVCM):** 1 % Y 0,1 % (sección 2.1.7)

#### Eléctrico y seguridad
- **Estado de energía desde la entrega hasta el despliegue:** APAGADO (sección 2.3.1)
- **Interruptores de despliegue mínimos:** 1 (sección 2.3.2)
- **Reglas RTC:** AISLADO, FRECUENCIA < 320kHz, CORRIENTE < 10 mA (sección 2.3.3)
- **Pin RBF y cuánto puede sobresalir:** RETIRAR ANTES DE INTEGRACION  AL DISPENSADOR, 6,5 mm SOBRE LA SUPERFICIE DEL RIEL, CORTAR ENERGIA (sección 2.3.5)
- **Proteccion de baterias:** SEGURIDAD DE BATERIA, PUEDE ESTAR ENCENDIDA DESDE EL INICIO (sección 2.3.6)
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

### Dudas y cosas por investigar

---

## 2. NASA CubeSat 101
(pendiente)

## 3. NASA State-of-the-Art of Small Spacecraft Technology
(pendiente)

## 4. NASA Systems Engineering Handbook
(pendiente)

## 5. SMAD
(pendiente)