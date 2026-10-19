## Punto 1: Alcance del Proyecto (content/01-alcance.md)

### Objetivo General y Objetivos Específicos SMART.

### Inclusiones/Exclusiones y Entregables.

### Estrategia de gestión para mitigar el Scope Creep.



# 1. Alcance del Proyectogit add content/01-alcance.md

## Objetivo General
Implementar un módulo web integrado bajo la metodología *Docs as Code* para la solicitud y descarga automatizada de certificados académicos (alumno regular y analítico parcial) de la universidad, asegurando la validación automática de deudas, emisión de PDFs, notificaciones por correo y auditoría de solicitudes en un plazo de 6 semanas y un presupuesto máximo de USD 18.000, utilizando Node.js, React y PostgreSQL.

## Objetivos Específicos (SMART)
1. **Específico y Temporal:** Desarrollar y desplegar el flujo completo de validación de deudas y generación de certificados PDF en un plazo estricto de 6 semanas.
2. **Medible y Alcanzable:** Automatizar el 100% de la emisión de certificados válidos mediante integración en modo solo lectura con el sistema de alumnos existente, reduciendo a cero la intervención manual administrativa.
3. **Relevante:** Cumplicar con la regla de negocio del analítico (escala numérica estricta 1–10 y exclusión automática de materias extracurriculares) manteniendo el presupuesto base por debajo de los USD 18.000.

## Inclusiones y Exclusiones
* **Inclusiones:**
  * Módulo web de solicitud de certificados de alumno regular y analítico parcial.
  * Conexión en modo solo lectura con la base de datos o API del sistema de alumnos actual.
  * Validación automática de deudas pendientes antes de autorizar la emisión.
  * Generación automatizada de documentos en formato PDF con diseño institucional.
  * Envío automático de notificaciones por correo electrónico al emitir el documento.
  * Registro formal de auditoría con fecha y hora de cada solicitud y emisión.
* **Exclusiones:**
  * Modificación o escritura directa sobre el sistema de alumnos existente (es estrictamente solo lectura).
  * Emisión de analíticos totales o títulos universitarios definitivos (fuera del alcance de este módulo).
  * Pasarela de pagos integrada para cobro de aranceles de certificados (el servicio se asume gratuito o bonificado por la institución).

## Entregables
* **Entregables Externos (para el cliente / universidad):**
  1. Módulo web funcional de solicitud y descarga de certificados desplegado en entorno de producción.
  2. Documentación técnica y Guía Rápida de uso para el alumno en formato Markdown/PDF.
* **Entregables Internos (para el equipo y gestión):**
  1. Repositorio configurado bajo *Docs as Code* con la trazabilidad completa del proyecto.
  2. Informe final de gestión, inventario de deuda técnica y lecciones aprendidas procesadas por IA.

## Gestión del Alcance y Prevención del *Scope Creep*
Una gestión estricta del alcance es el pilar fundamental para evitar el *scope creep* (la adición descontrolada de requerimientos no planificados) que suele destruir los plazos y presupuestos de un proyecto de software. Al fijar formalmente las inclusiones y exclusiones en esta etapa, se establece una línea base contractual y técnica inquebrantable con los stakeholders. Cualquier solicitud de cambio posterior que quede fuera de este documento no se rechaza de inmediato, sino que se somete a un proceso formal de control de cambios, evaluando su impacto en tiempo, costos y recursos. Esto protege al equipo de desarrollo de sobrecargas imprevistas y garantiza que el proyecto se entregue dentro de las 6 semanas estipuladas y sin superar el presupuesto de USD 18.000.