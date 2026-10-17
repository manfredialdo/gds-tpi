Punto 2: Stakeholders y Alineación (content/02-stakeholders.md)
Identificación y clasificación de los 8 Stakeholders clave.
Matriz de Interés vs. Influencia y estrategias de gestión.
Acciones concretas de alineación.



# 2. Stakeholders y Alineación

## Identificación y Clasificación de los 8 Stakeholders Clave
Para garantizar el éxito del Sistema de Gestión de Certificados Académicos (SGCA), se han identificado y categorizado 8 partes interesadas fundamentales (internas y externas al equipo de desarrollo):

1. **Alumnos / Estudiantes:** Usuarios finales que solicitan y descargan los certificados. (Externo / Operativo)
2. **Personal Administrativo de Gestión Académica:** Funcionarios que validan manualmente casos excepcionales o atienden consultas por certificados denegados. (Interno / Operativo)
3. **Secretaría Académica / Dirección:** Patrocinadores ejecutivos que aprueban el presupuesto y supervisan el cumplimiento institucional. (Interno / Estratégico)
4. **Equipo de Desarrollo (Desarrolladores Node.js y React):** Responsables de construir el código y desplegar la solución técnica. (Interno / Técnico)
5. **Especialista en QA (Tester):** Responsable de validar la calidad, la regla de negocio del analítico y las pruebas funcionales. (Interno / Técnico)
6. **Diseñador UX/UI:** Responsable de la experiencia de usuario en la interfaz web de solicitud. (Interno / Técnico)
7. **Departamento de Infraestructura / TI de la Universidad:** Propietarios de los servidores, bases de datos y sistemas de alumnos existentes (con quienes se conecta en modo solo lectura). (Interno / Soporte Técnico)
8. **Auditoría Interna / Compliance:** Organismo encargado de verificar que el sistema cumpla con la normativa de emisión de documentos oficiales y trazabilidad de auditoría. (Interno / Gobernanza)

---

## Matriz de Interés vs. Influencia y Estrategias de Gestión

| Stakeholder | Tipo | Nivel de Interés | Nivel de Influencia | Estrategia de Gestión / Enfoque |
| :--- | :--- | :--- | :--- | :--- |
| **1. Alumnos** | Externo | Alto | Bajo | **Mantener Informados:** Proveer una interfaz intuitiva, guías rápidas claras y notificaciones automáticas transparentes. |
| **2. Personal Administrativo** | Interno | Alto | Medio | **Mantener Satisfechos:** Involucrarlos en las pruebas de aceptación para asegurar que la automatización reduzca su carga operativa real. |
| **3. Secretaría Académica** | Interno | Alto | Alto | **Gestionar de Cerca (Partners Clave):** Informar semanalmente sobre el avance, consumo del presupuesto y cumplimiento de los hitos del cronograma. |
| **4. Equipo de Desarrollo** | Interno | Alto | Alto | **Gestionar de Cerca:** Proveer requerimientos claros, historias de usuario estables y evitar cambios de alcance de última hora. |
| **5. Tester (QA)** | Interno | Alto | Medio | **Gestionar de Cerca:** Suministrar criterios de aceptación claros (BDD) y asegurar tiempos lógicos para pruebas de calidad. |
| **6. Diseñador UX/UI** | Interno | Medio | Medio | **Mantener Informados:** Alinear los flujos de pantallas con las restricciones técnicas del backend en Node.js y React. |
| **7. Infraestructura / TI** | Interno | Alto | Alto | **Gestionar de Cerca:** Acordar tempranamente los accesos de solo lectura a la base de datos existente y esquemas de seguridad. |
| **8. Auditoría / Compliance** | Interno | Medio | Alto | **Mantener Satisfechos:** Validar los requerimientos de registro de auditoría y formato legal de los PDFs emitidos. |

---

## Acciones Concretas de Alineación
Para mantener a los interesados alineados y evitar sorpresas durante las 6 semanas de ejecución del proyecto, se implementarán las siguientes 3 acciones:

1. **Reuniones de Demostración Semanal (Sprint Reviews):** Al finalizar cada iteración, se presentará un avance funcional del módulo de certificados a la Secretaría Académica y al personal administrativo para recibir retroalimentación temprana.
2. **Canal de Comunicación y Reportes Automatizados (Slack/Teams):** Publicación semanal de un informe de avance con un semáforo de estado claro, métricas de rendimiento y alertas tempranas para los tomadores de decisiones.
3. **Comité de Control de Cambios (Change Control Board):** Instancia formal donde Secretaría Académica y TI evalúan cualquier solicitud extraordinaria para proteger el proyecto contra el *scope creep* sin descuidar las prioridades institucionales.