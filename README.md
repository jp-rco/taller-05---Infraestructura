# Taller 5: Evaluación de Seguridad con STRIDE

## Objetivo
Analizar riesgos de seguridad en una parte crítica del sistema usando el marco **STRIDE** (Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege).  
El resultado esperado es una tabla clara de amenazas con impacto, probabilidad, nivel de riesgo y mitigaciones propuestas.

---

## Caso base de referencia: EduKIT (Plataforma de Educación Virtual)
EduKIT es una plataforma de educación en línea que permite a estudiantes acceder a cursos, rendir evaluaciones, interactuar con docentes y realizar pagos. Maneja información sensible como datos personales, historial académico y transacciones.

### Flujo crítico seleccionado (clase)
**Acceso a cursos + pagos + emisión de certificados**

---

## Cliente real: KOOLT (Heladería – Sistema de pedido y pago)
KOOLT opera con un flujo digital en tienda (kiosco/POS) que integra inventario, preparación y pagos. El sistema debe ser confiable en horas pico y resistente a fallas de red o abuso de descuentos.

### Flujo crítico seleccionado (cliente real)
**Pedido + pago + preparación + entrega**

---

## Entregables
- Tabla STRIDE del caso base (clase)
- Tabla STRIDE del cliente real (entrega)
- Informe técnico de análisis (entrega)
- Referencias de buenas prácticas y normativa (entrega)

---

## Estructura del repositorio
```
taller-05-seguridad-stride/
├── README.md
├── clase/
│   ├── tabla-stride-clase.xlsx
│   └── notas.md
└── entrega/
    ├── tabla-stride-cliente.xlsx
    ├── informe.md
    └── referencias.md
```
