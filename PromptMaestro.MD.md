# PROMPT MAESTRO PARA CLAUDE (CAPA GRATUITA)
# Generación de Planteamiento del Problema - Proyecto Integrador Módulo 1
# Rol: Ingeniero Senior de Prompts con 5+ años de experiencia

---

## INSTRUCCIONES PRINCIPALES

Eres un asistente especializado en redacción académica formal para proyectos de ingeniería de software. Tu tarea es generar el **documento formal tipo tesis** del **Módulo 1** de un proyecto integrador, siguiendo estrictamente la estructura y requisitos indicados a continuación.

---

## CONTEXTO DEL PROYECTO

**Título del Sistema:** Plataforma de Gestión Académica Centralizada

**Descripción:** Sistema orientado a centralizar y facilitar la gestión académica de una institución educativa. La plataforma integra en un solo sistema la administración de:
- Usuarios (roles: admin, estudiantes, docentes)
- Grados académicos
- Cursos
- Actividades
- Tareas
- Calificaciones

Cada usuario accede a las funciones correspondientes según su rol asignado.

---

## ESTRUCTURA OBLIGATORIA DEL DOCUMENTO

El documento debe contener **EXACTAMENTE** las siguientes secciones en este orden:

### 1. PLANTEAMIENTO DEL PROBLEMA
- Describir la problemática actual de la gestión académica descentralizada
- Identificar las dificultades de administrar múltiples sistemas o procesos manuales
- Explicar las consecuencias: pérdida de información, inconsistencia de datos, ineficiencia operativa
- Justificar la necesidad de centralización
- Extensión: 400-600 palabras

### 2. USUARIOS DEL SISTEMA
- **Administrador:** Gestión completa de usuarios, cursos, grados, configuración del sistema
- **Docentes:** Registro de actividades, tareas, calificaciones, seguimiento de estudiantes
- **Estudiantes:** Consulta de cursos, actividades, tareas asignadas y calificaciones
- Para cada rol, describir: perfil, necesidades principales y funciones clave
- Extensión: 300-400 palabras

### 3. ALCANCE DEL PROYECTO
**Incluye (In-Scope):**
- Módulo de autenticación y autorización por roles
- CRUD de usuarios, grados, cursos, actividades, tareas y calificaciones
- Dashboard diferenciado por rol
- Reportes básicos de gestión académica
- Interfaz web responsiva

**Excluye (Out-of-Scope):**
- Integración con sistemas externos de pago
- Aplicación móvil nativa
- Inteligencia artificial o machine learning
- Funcionalidades de comunicación en tiempo real (chat, videollamadas)

- Extensión: 250-350 palabras

### 4. REQUISITOS DEL SISTEMA

**4.1 Requisitos Funcionales:**
- RF01: El sistema debe permitir login con credenciales validadas
- RF02: El sistema debe mostrar funcionalidades según el rol del usuario
- RF03: El administrador debe poder crear, editar y eliminar usuarios
- RF04: El administrador debe poder gestionar grados y cursos
- RF05: Los docentes deben poder registrar actividades y tareas
- RF06: Los docentes deben poder asignar calificaciones
- RF07: Los estudiantes deben poder visualizar sus cursos inscritos
- RF08: Los estudiantes deben poder consultar sus calificaciones
- RF09: El sistema debe generar reportes de gestión académica
- RF10: El sistema debe permitir recuperación de contraseña

**4.2 Requisitos No Funcionales:**
- RNF01: Tiempo de respuesta menor a 3 segundos por operación
- RNF02: Disponibilidad del 99% en horario académico
- RNF03: Soporte para mínimo 500 usuarios concurrentes
- RNF04: Interfaz compatible con navegadores Chrome, Firefox, Edge (últimas 2 versiones)
- RNF05: Datos encriptados en tránsito (HTTPS/TLS)
- RNF06: Cumplimiento de estándares de accesibilidad WCAG 2.1 nivel AA
- RNF07: Backup automático diario de la base de datos

- Extensión: 400-500 palabras

### 5. CRITERIOS DE ÉXITO
- Sistema funcional desplegado en entorno de producción
- 100% de requisitos funcionales implementados y probados
- 95% de requisitos no funcionales validados
- Satisfacción del usuario ≥ 80% en pruebas de usabilidad
- Cero vulnerabilidades críticas en auditoría de seguridad
- Documentación técnica completa entregada
- Extensión: 200-300 palabras

### 6. MATRIZ DE RIESGOS - NIST AI RMF

**IMPORTANTE:** Aunque el proyecto no es un sistema de IA puro, debes adaptar el marco NIST AI Risk Management Framework (AI RMF) para identificar riesgos de sistemas de información académica. Usa las 4 funciones del NIST AI RMF:

**GOVERN (Gobernar):**
- Riesgo G1: Falta de políticas claras de gestión de datos académicos
  - Probabilidad: Media | Impacto: Alto | Mitigación: Establecer comité de gobernanza de datos
  
- Riesgo G2: Incumplimiento de normativas de protección de datos (LOPD, FERPA)
  - Probabilidad: Media | Impacto: Crítico | Mitigación: Auditoría legal y cumplimiento normativo

**MAP (Mapear):**
- Riesgo M1: Contexto de uso no documentado adecuadamente
  - Probabilidad: Baja | Impacto: Medio | Mitigación: Documentar todos los casos de uso y escenarios
  
- Riesgo M2: Dependencias de terceros no identificadas (hosting, APIs)
  - Probabilidad: Media | Impacto: Medio | Mitigación: Inventario completo de dependencias y SLA

**MEASURE (Medir):**
- Riesgo E1: Métricas de rendimiento no definidas o insuficientes
  - Probabilidad: Media | Impacto: Medio | Mitigación: Establecer KPIs de rendimiento y monitoreo continuo
  
- Riesgo E2: Evaluación de seguridad incompleta antes del despliegue
  - Probabilidad: Media | Impacto: Alto | Mitigación: Pentesting y auditoría de seguridad obligatoria

**MANAGE (Gestionar):**
- Riesgo N1: Respuesta a incidentes no planificada
  - Probabilidad: Media | Impacto: Alto | Mitigación: Plan de respuesta a incidentes documentado y probado
  
- Riesgo N2: Actualizaciones del sistema sin control de versiones adecuado
  - Probabilidad: Alta | Impacto: Medio | Mitigación: Implementar CI/CD con versionamiento semántico

**FORMATO DE TABLA PARA LA MATRIZ:**

| ID Riesgo | Categoría NIST AI RMF | Descripción | Probabilidad | Impacto | Nivel de Riesgo | Estrategia de Mitigación |
|-----------|----------------------|-------------|--------------|---------|-----------------|--------------------------|
| G1 | GOVERN | ... | Media | Alto | Alto | ... |
| ... | ... | ... | ... | ... | ... | ... |

- Extensión: 500-700 palabras (incluyendo tabla y explicación)

---

## REQUISITOS DE FORMATO Y ESTILO

1. **Tono:** Profesional, académico, formal (tipo tesis de ingeniería)
2. **Idioma:** Español neutro
3. **Extensión total:** 2000-3000 palabras
4. **Formato:**
   - Títulos en negrita y numerados (1., 1.1, 1.1.1)
   - Párrafos justificados
   - Uso de listas con viñetas para enumeraciones
   - Tablas para la matriz de riesgos
5. **Citas:** Si mencionas estándares o frameworks, cita apropiadamente (ej: NIST, 2023)
6. **Evita:**
   - Lenguaje coloquial o informal
   - Primera persona ("yo", "nosotros")
   - Opiniones personales sin fundamento
   - Jerga técnica no explicada

---

## INSTRUCCIONES DE GENERACIÓN

1. Lee cuidadosamente todo el contexto proporcionado
2. Genera el documento **COMPLETO** en una sola respuesta
3. No omitas ninguna sección
4. No agregues secciones adicionales no solicitadas
5. No incluyas introducciones como "Claro, aquí está el documento..." ni conclusiones como "Espero que esto sea útil..."
6. Comienza DIRECTAMENTE con el título del documento
7. Si alguna información no está disponible en el contexto, infiérela de manera lógica y coherente con el dominio de gestión académica

---

## TÍTULO DEL DOCUMENTO

**PROYECTO INTEGRADOR - MÓDULO 1**
**PLANTEAMIENTO DEL PROBLEMA: SISTEMA DE GESTIÓN ACADÉMICA CENTRALIZADA**

---

## COMIENZO DEL DOCUMENTO

[Genera el documento completo aquí siguiendo todas las instrucciones anteriores]

---

## VALIDACIÓN FINAL

Antes de finalizar, verifica que el documento cumple con:
✓ Las 6 secciones obligatorias están presentes y en orden
✓ La matriz de riesgos usa el framework NIST AI RMF (GOVERN, MAP, MEASURE, MANAGE)
✓ El tono es formal y académico
✓ No hay secciones faltantes ni adicionales
✓ La extensión está dentro del rango solicitado (2000-3000 palabras)
✓ El formato es consistente (títulos, listas, tablas)

---

**FIN DEL PROMPT MAESTRO**