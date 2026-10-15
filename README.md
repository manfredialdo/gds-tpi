# gds-tpi
Gestión de Desarrollos de Software – Trabajo Práctico Integrador - UTN tupad 2026


# 🎓 Sistema de Gestión de Certificados Académicos (SGCA)
> **Trabajo Práctico Integrador (TPI)**  
> Enfoque: **Docs as Code** | Gestión de Proyectos de Software con Asistencia
## 👥 Perfiles y Roles del Equipo

1. **Alumno A** — Negocio, Gobierno y Cierre del Proyecto
2. **Alumno B** — Ingeniería de Requerimientos y Documentación Técnica
3. **Alumno C** — Gestión de Tiempos, Costos, Riesgos y Control

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







## 📋 Distribución por Alumno

### 👔 Alumno A: Negocio, Gobierno y Cierre
**Enfoque:** Definición estratégica del proyecto, alineación de partes interesadas y proceso de cierre/calidad final.

* **Punto 1: Alcance del Proyecto** (`content/01-alcance.md`)
  * Objetivo General y Objetivos Específicos SMART.
  * Inclusiones/Exclusiones y Entregables.
  * Estrategia de gestión para mitigar el *Scope Creep*.
* **Punto 2: Stakeholders y Alineación** (`content/02-stakeholders.md`)
  * Identificación y clasificación de los 8 Stakeholders clave.
  * Matriz de Interés vs. Influencia y estrategias de gestión.
  * Acciones concretas de alineación.
* **Punto 10: Cierre del Proyecto** (`content/10-cierre.md`)
  * Definition of Done (DoD) del módulo.
  * Protocolo de UAT y Sign-off.
  * Informe Final y Lecciones Aprendidas (con resúmenes apoyados en IA).
* **Entregables adicionales:**
  * Presentación general e Índice principal en `README.md`.

---

### 💻 Alumno B: Ingeniería de Requerimientos y Documentación
**Enfoque:** Especificación de requisitos, elicitación con IA y artefactos de arquitectura/modelado técnico.

* **Punto 3: Ingeniería de Requerimientos** (`content/03-requerimientos.md`)
  * Técnicas de elicitación justificadas.
  * Clasificación RF (3) y RNF (2) con priorización MoSCoW.
  * Historias de Usuario (criterios INVEST y formato BDD / Given-When-Then).
  * Caso de Uso Formal: *Solicitar certificado analítico*.
* **Punto 4: Uso de IA en Requerimientos** (`content/04-ia-requerimientos.md`)
  * Registro de Prompts reutilizables para refinamiento y detección de ambigüedades.
  * Comparativa de Salidas generadas vs. Corrección/Validación humana.
* **Punto 9: Documentación y Artefactos Técnicos** (`docs/` y `assets/`)
  * Diagrama de Secuencia del Proceso en fuente Mermaid (`assets/diagrama-proceso.mmd`).
  * Arquitectura del proceso (`docs/proceso-solicitud.md`).
  * Guía Rápida para el Alumno de máximo 1 página (`docs/quick-start-alumno.md`).

---

### 📊 Alumno C: Planificación, Estimación, Riesgos y Control
**Enfoque:** Métricas cuantitativas, planificación temporal, presupuestación económica y monitoreo de ejecución.

* **Punto 5: Riesgos, Supuestos y Restricciones** (`content/05-riesgos-supuestos.md`)
  * Matriz de Riesgos (Probabilidad, Impacto y Mitigación).
  * Supuestos clave y Restricciones técnicas.
  * Ejemplo encadenado (*Supuesto no cumplido → Riesgo → Restricción*).
* **Punto 6: Estimación de Tiempos y Costos** (`content/06-estimacion.md`)
  * Cálculo PERT para tareas críticas.
  * Puntos de Función (PF) aplicados al módulo PDF.
  * Presupuesto económico detallado (Límite: USD 18.000).
  * Datos históricos para entrenamiento de IA.
* **Punto 7: Planificación y Cronograma** (`content/07-planificacion.md`)
  * Estructura de desglose de tareas (WBS) y dependencias.
  * Hitos y Entregables SMART.
  * Diagrama Gantt interactivo/código.
* **Punto 8: Seguimiento y Control** (`content/08-seguimiento-control.md`)
  * KPIs del proyecto (Velocity, Lead Time, Cycle Time, Defect Density).
  * Reporte de Avance Semanal (Semáforo de proyecto).
  * Alertas automáticas de Dashboard con IA.
  *
```text
/
├── README.md                          # Presentación del proyecto e índice principal
├── docs/                              # Documentación de arquitectura y guías
│   ├── proceso-solicitud.md           # Diagrama de flujo y arquitectura del proceso
│   └── quick-start-alumno.md          # Guía Rápida para el Alumno (Máx. 1 página)
├── content/                           # Desarrollo punto por punto del TPI
│   ├── 01-alcance.md                  # Punto 1: Alcance, Objetivos SMART y Scope Creep
│   ├── 02-stakeholders.md             # Punto 2: Matriz de Stakeholders y Alineación
│   ├── 03-requerimientos.md           # Punto 3: RF, RNF, MoSCoW, HU (INVEST/BDD) y Caso de Uso
│   ├── 04-ia-requerimientos.md        # Punto 4: Prompts de IA, Salidas y Validación Humana
│   ├── 05-riesgos-supuestos.md        # Punto 5: Matriz de Riesgos, Supuestos y Cadena de Impacto
│   ├── 06-estimacion.md               # Punto 6: Estimación PERT, Puntos de Función y Presupuesto
│   ├── 07-planificacion.md            # Punto 7: Cronograma, Hitos, Entregables y Diagrama Gantt
│   ├── 08-seguimiento-control.md      # Punto 8: KPIs, Reporte Semanal y Alertas de IA
│   └── 10-cierre.md                   # Punto 10: DoD, UAT, Informe Final y Lecciones Aprendidas
└── assets/                            # Recursos gráficos y código fuente Mermaid
    └── diagrama-proceso.mmd           # Archivo fuente Mermaid del proceso

    
    
    
    
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
