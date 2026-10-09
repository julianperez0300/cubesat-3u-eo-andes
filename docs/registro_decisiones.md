# Registro de decisiones y supuestos

Convención: D-xxx para decisiones, S-xxx para supuestos.
Cada supuesto debe indicar en qué fase se valida.

---

## D-001 | Fecha: 2026-10-09
- **Decisión:** Formato 3U
- **Alternativas consideradas:** 1U, 2U, 6U
- **Justificación:** Espacio suficiente para una óptica de ~1,5U y estándar
  con amplia oferta de componentes comerciales (COTS).
- **Impacto:** Masa máxima ~4 kg y volumen limitado para la óptica.
- **Estado:** Abierta (se revisa si la carga útil no cabe)

## D-002 | Fecha: 2026-10-09
- **Decisión:** Órbita heliosíncrona (SSO) a ~550 km
- **Alternativas consideradas:** Órbitas de otras altitudes o inclinaciones
- **Justificación:** Iluminación solar consistente en cada pasada y
  decaimiento orbital compatible con la regla de los 25 años.
- **Impacto:** Define eclipses, revisita, tasa de arrastre y pasadas sobre estación.
- **Estado:** Abierta (se valida en Fase 2)

## D-003 | Fecha: 2026-10-09
- **Decisión:** Carga útil RGB + NIR
- **Alternativas consideradas:** Solo RGB, multiespectral con más bandas
- **Justificación:** Con NIR se calcula NDVI, útil para vegetación y deforestación.
- **Impacto:** Afecta la arquitectura de la cámara (dos cámaras, filtros en
  franjas o filtro intercambiable).
- **Estado:** Abierta (arquitectura se define en Fase 3)

## D-004 | Fecha: 2026-10-10
- **Decisión:** Software de CAD: KOMPAS-3D, con exportación a STEP
- **Alternativas consideradas:** SolidWorks (costo de licencia), FreeCAD, Fusion 360, Onshape
- **Justificación:** El autor ya domina KOMPAS-3D, lo que evita una curva de aprendizaje
  larga. STEP (ISO 10303) permite que cualquier CAD abra el diseño.
- **Impacto:** Fase 8. La carpeta `cad/` incluirá STEP y PDF de planos además del formato nativo.
- **Pendiente:** Prueba de ida y vuelta KOMPAS → STEP → FreeCAD con un cubo de 100 mm.
- **Estado:** Cerrada (se reabre solo si la prueba de STEP falla)

---

## S-001 | Supuesto
- **Supuesto:** Altitud SSO de ~550 km
- **A validar en:** Fase 2 (análisis de misión)