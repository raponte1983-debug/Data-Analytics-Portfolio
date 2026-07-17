# 📄 Entregable DAPP-DOC-000

| Campo         | Valor                                    |
| ------------- | ---------------------------------------- |
| **Proyecto**  | Data Analytics Portfolio Platform (DAPP) |
| **Código**    | DAPP-DOC-000                             |
| **Nombre**    | Estándar de Documentación del Proyecto   |
| **Ubicación** | `docs/00_Project/Document_Standard.md`   |
| **Versión**   | 1.0                                      |
| **Estado**    | Propuesta                                |
| **Autor**     | Proyecto DAPP                            |
| **Fecha**     | 17/07/2026                               |
| **Aprobador** | Product Owner                            |

---

# Objetivo

Definir el estándar oficial para la creación, mantenimiento, control de versiones y organización de toda la documentación del proyecto **Data Analytics Portfolio Platform (DAPP)**.

Este documento establece una estructura uniforme que será utilizada por:

* El equipo de desarrollo.
* GitHub Copilot.
* ChatGPT.
* NotebookLM.
* Futuros colaboradores.

Su propósito es garantizar consistencia, trazabilidad y mantenibilidad durante todo el ciclo de vida del proyecto.

---

# 1. Principios

Toda la documentación del proyecto deberá cumplir los siguientes principios:

### 1.1 Documentación como código (Docs as Code)

Toda la documentación será tratada como un activo del proyecto y estará versionada mediante Git.

No existirán documentos fuera del repositorio oficial.

---

### 1.2 Fuente única de verdad (Single Source of Truth)

Cada tema deberá documentarse una única vez.

No se duplicará información entre documentos.

Cuando un documento requiera información existente en otro, deberá referenciarlo.

---

### 1.3 Arquitectura primero

Ningún desarrollo iniciará sin contar con la documentación mínima necesaria que describa:

* objetivo
* alcance
* restricciones
* decisiones arquitectónicas

---

### 1.4 Compatibilidad con IA

Toda la documentación deberá redactarse pensando tanto en lectores humanos como en asistentes de IA.

Los documentos deberán ser:

* claros
* estructurados
* reutilizables
* fácilmente interpretables

---

# 2. Estructura del repositorio documental

Toda la documentación oficial se almacenará dentro de la carpeta:

```text
/docs
```

La estructura oficial será:

```text
docs/

00_Project/

01_Architecture/

02_Development/

03_Security/

04_AI/

05_Design/

06_Project_Management/

adr/

diagrams/

prompts/

knowledge-base/
```

Cada carpeta representa un dominio funcional del proyecto.

---

# 3. Convención de nombres

Los documentos deberán seguir el siguiente formato:

```text
Codigo-NombreDocumento.md
```

Ejemplos:

```text
00_Project_Charter.md

01_System_Architecture.md

ADR-001-Technology-Stack.md

Security_Architecture.md
```

Reglas:

* utilizar PascalCase para nombres compuestos
* evitar espacios
* evitar caracteres especiales
* utilizar inglés para nombres técnicos
* utilizar Markdown (.md)

---

# 4. Plantilla oficial

Todos los documentos deberán iniciar con la siguiente cabecera.

```markdown
# Título

---

## Información General

Proyecto:

Código:

Versión:

Estado:

Autor:

Fecha de creación:

Última actualización:

Ubicación:

Documento relacionado:
```

---

# 5. Estados de un documento

Todo documento deberá indicar uno de los siguientes estados.

| Estado     | Descripción             |
| ---------- | ----------------------- |
| Draft      | En construcción         |
| Proposed   | Pendiente de aprobación |
| Approved   | Documento oficial       |
| Deprecated | Ya no debe utilizarse   |
| Archived   | Histórico               |

---

# 6. Versionamiento

Formato oficial:

```text
Mayor.Menor
```

Ejemplos

```text
1.0

1.1

1.2

2.0
```

Reglas

### Cambio mayor

Cuando cambia el alcance del documento.

Ejemplo

```text
1.0 → 2.0
```

---

### Cambio menor

Correcciones.

Aclaraciones.

Nuevas secciones.

Ejemplo

```text
1.0 → 1.1
```

---

# 7. Historial de cambios

Todos los documentos finalizarán con la siguiente tabla.

```markdown
## Historial de versiones

| Versión | Fecha | Autor | Descripción |
|----------|--------|--------|-------------|
|1.0|17/07/2026|Proyecto DAPP|Versión inicial|
```

---

# 8. Referencias cruzadas

Cuando un documento dependa de otro, deberá incluir una sección denominada:

```markdown
## Documentos relacionados
```

Ejemplo

* DAPP-DOC-001 Project Charter
* ADR-001 Technology Stack
* Security Architecture

---

# 9. Diagramas

Los diagramas deberán almacenarse únicamente en:

```text
docs/diagrams/
```

Preferiblemente en formato:

* Mermaid
* Draw.io
* SVG

Evitar imágenes PNG cuando exista una alternativa editable.

---

# 10. Imágenes

Todas las imágenes deberán almacenarse fuera del documento.

Ruta oficial

```text
assets/images/docs/
```

No se incrustarán imágenes en base64.

---

# 11. Idioma

La documentación seguirá la siguiente política:

| Tipo                   | Idioma                                        |
| ---------------------- | --------------------------------------------- |
| Gestión del proyecto   | Español                                       |
| Arquitectura           | Español                                       |
| Desarrollo             | Inglés técnico cuando aplique                 |
| Código                 | Inglés                                        |
| Variables              | Inglés                                        |
| Comentarios del código | Inglés                                        |
| README público         | Inglés (con posibilidad de traducción futura) |

---

# 12. Estilo de redacción

Toda la documentación deberá:

* utilizar lenguaje técnico
* evitar ambigüedades
* utilizar listas cuando sea apropiado
* evitar párrafos excesivamente largos
* utilizar títulos jerárquicos
* definir términos técnicos cuando aparezcan por primera vez

---

# 13. Documentos obligatorios

La versión 1.0 del proyecto deberá contener, como mínimo:

* Project Charter
* System Architecture
* Technology Stack (ADR)
* Security Architecture
* Development Guide
* Design System
* Git Workflow
* AI Context
* Roadmap
* Backlog

---

# 14. Control de aprobación

Todo documento seguirá el flujo:

```text
Borrador
      │
      ▼
Revisión Arquitectura
      │
      ▼
Revisión Product Owner
      │
      ▼
Aprobado
      │
      ▼
Commit
      │
      ▼
GitHub
```

---

# 15. Criterios de calidad

Antes de aprobar un documento deberá verificarse que:

* Cumple el estándar definido en este documento.
* No duplica información existente.
* Está correctamente versionado.
* Tiene referencias cuando aplica.
* Es entendible para un lector externo.
* Puede ser utilizado como contexto por un agente de IA.

---

# Historial de versiones

| Versión | Fecha      | Autor         | Descripción     |
| ------- | ---------- | ------------- | --------------- |
| 1.0     | 17/07/2026 | Proyecto DAPP | Versión inicial |

---

# 🔍 Revisión del Arquitecto (mi recomendación)

Quiero proponerte una pequeña mejora antes de aprobar este documento.

En proyectos empresariales normalmente existe un **Document Standard**, pero nosotros vamos a trabajar intensivamente con IA. Por eso propongo añadir un capítulo que no suele existir:

## **16. Clasificación de documentos**

Cada documento llevará una clasificación para que los agentes de IA sepan cómo utilizarlo.

| Clasificación    | Uso                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------- |
| **Governance**   | Reglas y políticas del proyecto (Project Charter, Project Rules).                            |
| **Architecture** | Decisiones técnicas y diseño del sistema (ADR, arquitectura, seguridad).                     |
| **Development**  | Guías de implementación, estándares de código y flujo Git.                                   |
| **AI Context**   | Documentos cuyo objetivo principal es proporcionar contexto a ChatGPT, Copilot y NotebookLM. |
| **Operations**   | Roadmap, backlog, changelog, incidencias y gestión del proyecto.                             |
| **Reference**    | Manuales, glosarios, investigaciones y material de consulta.                                 |