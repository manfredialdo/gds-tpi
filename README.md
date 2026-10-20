# gds-tpi
Gestión de Desarrollos de Software – Trabajo Práctico Integrador - UTN tupad 2026

https://github.com/manfredialdo/gds-tpi


---

# 🎓 Sistema de Gestión de Certificados Académicos (SGCA)
> **Trabajo Práctico Integrador (TPI)**  
> Enfoque: **Docs as Code** | Gestión de Proyectos de Software

---

# 🎓 Sistema de Gestión de Certificados Académicos (SGCA)
## 📌 Contexto y Enunciado del Proyecto

La universidad requiere la implementación de un módulo web que permita a los alumnos solicitar y descargar certificados académicos (**alumno regular** y **analítico parcial**). 

### Funcionalidades Requeridas:
- **Validación administrativa:** Verificar automáticamente que el alumno no presente deudas pendientes.
- **Generación de documentos:** Emisión automática del certificado en formato PDF.
- **Notificaciones:** Envío de correos electrónicos automáticos al emitir el documento.
- **Auditoría y registro:** Registrar formalmente cada solicitud y su fecha exacta de emisión.
- **Integración:** Conexión en modo **solo lectura** con el sistema de alumnos existente.

### Restricciones Iniciales:
- ⏱️ **Plazo de ejecución:** 6 semanas (simulado).
- 👥 **Equipo de trabajo:** 2 Desarrolladores, 1 Tester (QA), 1 Diseñador UX.
- 💰 **Presupuesto base:** USD 18.000.
- 🛠️ **Stack tecnológico obligatorio:** 
  - **Backend:** Node.js
  - **Frontend:** React
  - **Base de Datos:** PostgreSQL
- 📜 **Regla de negocio del Analítico:** Escala numérica estricta 1–10 y exclusión automática de materias extracurriculares.




---
1. Alcance del proyecto
- Redactar objetivo general y 3 objetivos específicos SMART.
- Definir inclusiones y exclusiones.
- Mencionar 2 entregables externos y 2 internos.
- Explicar en 10 líneas por qué una buena gestión del alcance evita el scope creep.

2. Stakeholders
- Identificar al menos 8 stakeholders (internos y externos).
- Completar una tabla con rol, tipo, interés, influencia y estrategia de gestión.
- Mencionar 3 acciones para mantener alineados a los interesados.

3. Ingeniería de Requerimientos
- Describir técnicas de elicitación a utilizar y justificar.
- Clasificar y listar: 3 RF y 2 RNF.
- Priorizar los RF con método MoSCoW.
- Redactar 2 Historias de Usuario refinadas con INVEST y criterios de aceptación BDD.
- Redactar 1 Caso de Uso formal para “Solicitar certificado analítico” (actor, precondiciones, flujo principal y excepción).

4. Uso de IA en Requerimientos
- Incluir 2 prompts en el anexo: refinar, detectar ambigüedades y generar Caso de Uso/diagrama Mermaid o similar.
- Para cada prompt: instrucción exacta, salida de IA y corrección/validación humana.

5. Riesgos, supuestos y restricciones
- Identificar 2 riesgos con probabilidad, impacto y mitigación.
- Identificar 2 supuestos y 2 restricciones.
- Explicar con un ejemplo: supuesto no cumplido → riesgo → restricción agravante.

6. Estimación de tiempos y costos
- Aplicar PERT a una tarea crítica (fórmula y resultado).
- Aplicar Puntos de Función al módulo “Generar certificado PDF”.
- Realizar presupuesto simplificado: personal, infraestructura, contingencia 10 % y total.
- Mencionar qué datos históricos pediría para mejorar la estimación con IA.

7. Planificación
- Elaborar cronograma con al menos 6 tareas, dependencias y duración.
- Definir 4 hitos SMART y 4 entregables (2 internos y 2 externos).
- Representar en tabla o diagrama Gantt simple (puede ser con Mermaid o similar).

8. Seguimiento y control
- Definir 4 KPIs aplicables (Velocity, Lead Time, Cycle Time, Densidad de Defectos, etc.).
- Redactar 1 reporte de avance simulado semanal: semáforo, hitos, en curso, bloqueos y próximos pasos.
- Proponer 2 alertas automáticas de un dashboard inteligente con IA.

9. Documentación y artefactos
- Proponer estructura de carpetas bajo Docs as Code.
- Redactar un README.md breve (máximo 1 página).
- Incluir 1 diagrama Mermaid del proceso de solicitud.
- Redactar una Guía Rápida de máximo 1 página para el alumno.

10. Cierre del proyecto
- Definir Definition of Done (DoD) del módulo.
- Explicar cómo se realizaría el UAT y la firma de conformidad (Sign-off).
- Elaborar Informe Final breve: resumen ejecutivo, desvíos, deuda técnica y liberación de recursos.
- Redactar las lecciones aprendidas con resúmenes generativos IA.



## 👥 Perfiles y Roles del Equipo
### 👤 ALUMNO A: Análisis Funcional & Modelado de Procesos
- **Punto 1:** Alcance (en progreso)
- **Punto 2:** Stakeholders (en progreso)
- **Punto 3:** Ingeniería de Requerimientos (Elicitación, 3 RF, 2 RNF, MoSCoW, 2 HU BDD/INVEST y 1 Caso de Uso formal).
- **Punto 4:** Uso de IA en Requerimientos (2 Prompts con instrucción, salida y validación humana).
- **Parte del Punto 9:** Diagramación del Proceso (Diagrama de flujo Mermaid y su código fuente `.mmd`).

---

### 👤 ALUMNO B: Métodos Cuantitativos, Riesgos & Cronograma
- **Punto 5:** Riesgos, Supuestos y Restricciones (Matriz de riesgos, supuestos, restricciones y cadena de impacto).
- **Punto 6:** Estimación de Tiempos y Costos (PERT, Puntos de Función, Presupuesto con 10% contingencia y datos históricos para IA).
- **Punto 7:** Planificación (Cronograma de 6 tareas, 4 Hitos SMART, 4 Entregables y Diagrama Gantt).

---

### 👤 ALUMNO C: Métricas, Infraestructura "Docs as Code" & Cierre
- **Punto 8:** Seguimiento y Control (4 KPIs, Reporte semanal simulado y 2 Alertas IA).
- **Parte del Punto 9:** Estructura y Artefactos de Documentación (Diseño de la estructura Docs as Code, redacción del `README.md` y la `quick-start-alumno.md`).
- **Punto 10:** Cierre del Proyecto (Definition of Done, UAT + Sign-off, Informe Final y Lecciones Aprendidas con IA).

```text
/
├── README.md                           # Alumno C (Estructura & Presentación Docs as Code)
├── apuntes/                            # Apuntes de cátedra por unidad
│   └── gds0000001.pdf
├── docs/                               # Documentación de arquitectura y guías
│   ├── proceso-solicitud.md            # Alumno A (Diagrama de flujo del proceso)
│   └── quick-start-alumno.md           # Alumno C (Guía Rápida para el Alumno - Máx. 1 pág.)
├── content/                            # Desarrollo punto por punto del TPI
│   ├── 01-alcance.md                   # Alumno A (Completado)
│   ├── 02-stakeholders.md               # Alumno A (Completado)
│   ├── 03-requerimientos.md            # Alumno A (RF, RNF, MoSCoW, HU BDD/INVEST, Caso de Uso)
│   ├── 04-ia-requerimientos.md         # Alumno A (Prompts de IA, Salidas y Validación)
│   ├── 05-riesgos-supuestos.md         # Alumno B (Matriz de Riesgos, Supuestos y Cadena de Impacto)
│   ├── 06-estimacion.md                # Alumno B (Estimación PERT, Puntos de Función y Presupuesto)
│   ├── 07-planificacion.md             # Alumno B (Cronograma, Hitos, Entregables y Diagrama Gantt)
│   ├── 08-seguimiento-control.md       # Alumno C (KPIs, Reporte Semanal y Alertas de IA)
│   ├── 09-documentacion-artefactos.md  # Alumno A, C 
│   └── 10-cierre.md                    # Alumno C, A (DoD, UAT, Informe Final y Lecciones Aprendidas)
└── assets/                             # Recursos gráficos y código fuente Mermaid
    └── diagrama-proceso.mmd            # Alumno A (Archivo fuente Mermaid del proceso)    
    
    
    /
    ├── README.md                          # Alumno A
    ├── docs/                              
    │   ├── proceso-solicitud.md           # Alumno B
    │   └── quick-start-alumno.md          # Alumno B
    ├── content/                           
    │   ├── 01-alcance.md                  # Alumno A
    │   ├── 02-stakeholders.md             # Alumno A
    │   ├── 03-requerimientos.md           # Alumno B
    │   ├── 04-ia-requerimientos.md        # Alumno B
    │   ├── 05-riesgos-supuestos.md        # Alumno C
    │   ├── 06-estimacion.md               # Alumno C
    │   ├── 07-planificacion.md            # Alumno C
    │   ├── 08-seguimiento-control.md      # Alumno C
    │   └── 10-cierre.md                   # Alumno A
    └── assets/                            
        └── diagrama-proceso.mmd           # Alumno B
