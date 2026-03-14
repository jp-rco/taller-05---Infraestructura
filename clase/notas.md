# Notas – Trabajo en Clase (STRIDE)

## Caso base: EduKIT
**Flujo crítico trabajado:** acceso a cursos + pagos + certificados.

### Enfoque de análisis
- Se listaron componentes involucrados (autenticación, API, BD, gateway, pagos, certificados, logs).
- Se aplicó STRIDE por componente, buscando amenazas concretas y realistas.
- Se asignó Impacto y Probabilidad en escala 1–5, y se calculó el Riesgo como Impacto × Probabilidad.

### Criterios usados para priorizar
- Riesgo alto: 16–25 (requiere acción prioritaria)
- Riesgo medio: 9–15 (plan de mitigación)
- Riesgo bajo: 1–8 (monitoreo y control básico)

### Hallazgos rápidos (clase)
- Riesgo alto en autenticación (suplantación por credenciales filtradas).
- Riesgo alto en disponibilidad (picos de tráfico / DoS en gateway).
- Riesgos relevantes por alteración de notas/certificados si no hay controles server-side y auditoría.

### Próximos pasos definidos
- Ajustar mitigaciones con prácticas recomendadas (MFA, WAF, logs inmutables, RBAC).
- Replicar el ejercicio al cliente real, cambiando el dominio y componentes críticos.
