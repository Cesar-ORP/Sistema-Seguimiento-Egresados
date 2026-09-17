# README
**Integrantes:** David Rivera - Developer , Cesar Riascos - Developer ,  Cristian Tapiero- Scrum Master , Juan Delgado - Developer , David Alejandro Villamil - Product Owner 

## Problema analizado
La institución no cuenta con información actualizada, confiable y consentida sobre la trayectoria de sus egresados, porque la recolección es esporádica, está dispersa entre dependencias y no le ofrece al egresado un beneficio claro a cambio de sus datos. Esto afecta los procesos de calidad, las decisiones curriculares y la relación con el egresado.

## Contexto
- Una institución educativa desea conocer qué ocurre con sus egresados después de terminar sus estudios: empleo, emprendimiento, estudios posteriores, sector laboral y relación con la institución.
- Hoy la información está desactualizada y distribuida en varias fuentes (registro académico, oficina de egresados, encuestas de programas, hojas de cálculo, correos).
- Se plantea una plataforma de información y seguimiento de egresados. Antes de diseñarla, el squad debe entender quién necesita realmente la información, qué datos se justifican y qué restricciones legales, sociales y tecnológicas la condicionan.

## Restricciones del caso y cómo las abordamos
| Restricción | Cómo se abordó |
|---|---|
| No toda la información deseada debe solicitarse | Aplicamos el principio de minimización: cada dato debe tener una finalidad y un usuario concreto. Ver tabla de datos (sección 5.3). |
| La protección de datos es una dimensión del contexto | Se trata como factor Legal prioritario (Ley 1581 de 2012) y como stakeholder (Oficina Jurídica / Protección de Datos y SIC). |
| Intereses de la institución ≠ intereses del egresado | Se analiza la tensión explícitamente (sección 5.4) y se resuelve con un intercambio de valor: datos mínimos y consentidos a cambio de beneficios reales. |


## Evidencias
| Fase | Archivos |
|---|---|
| 1. Stakeholders | [stakeholders.md](01-stakeholders/stakeholders.md) · [matriz](01-stakeholders/matriz-poder-interes.png) · [decisiones](01-stakeholders/decisiones-stakeholders.md) |
| 2. PESTEL | [pestel.md](02-pestel/pestel.md) · [evidencias.md](02-pestel/evidencias.md) |
| 3. Pain points | [pain-points.md](03-pain-points/pain-points.md) |
| 4. Problem/Solution Fit | [problem-solution-fit.md](04-problem-solution-fit/problem-solution-fit.md) |
| 5. Lean Canvas | [lean-canvas.png](05-lean-canvas/lean-canvas.png) · [decisiones-canvas.md](05-lean-canvas/decisiones-canvas.md) |
| 6. Uso de IA | [prompts.md](06-ia/prompts.md) · [salidas-ia.md](06-ia/salidas-ia.md) · [decisiones-humanas.md](06-ia/decisiones-humanas.md) |
| 7. Defensa | [evidencia-defensa.md](07-defensa/evidencia-defensa.md) |


## Síntesis de la decisión final
El sistema de seguimiento de egresados no es un problema de software sino de confianza, calidad de datos y cumplimiento legal. La decisión del squad es priorizar una plataforma que pida solo lo necesario, con autorización explícita y a cambio de beneficios reales para el egresado. Así se equilibra el interés de la institución (información para calidad y currículo) con el interés del egresado (control de sus datos y retorno).

