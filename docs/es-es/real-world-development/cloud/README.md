---
slug: es-es/real-world-development/cloud
title: "GitHub Copilot cloud agent"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

**[GitHub Copilot cloud agent](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent)** permite que GitHub Copilot trabaje de forma asíncrona en la nube. Asignas trabajo en GitHub y el agente en la nube lo realiza en segundo plano: explora el repositorio, hace cambios y abre una solicitud de incorporación de cambios, mientras tú puedes dedicarte a otras tareas.

En estos ejercicios añadirás instrucciones personalizadas que seguirá el agente en la nube y, después, le asignarás una incidencia de GitHub para que implemente el trabajo. Revisarás y usarás agentes personalizados para definir su enfoque, supervisarás y orientarás las sesiones desde el panel de agentes y, por último, revisarás sus solicitudes de incorporación de cambios e iterarás sobre los resultados.

## Ejercicios

| Ejercicio | Tema | Descripción |
|----------|-------|-------------|
| [0. Requisitos previos][ex0] | Configuración | Crea el repositorio y el Codespace |
| [1. Instrucciones personalizadas][ex1] | Contexto | Añade instrucciones personalizadas que seguirá el agente en la nube |
| [2. Cloud Agent][ex2] | Agente asíncrono | Asigna incidencias a GitHub Copilot cloud agent |
| [3. Agentes personalizados][ex3] | Agentes especializados | Revisa y usa agentes personalizados |
| [4. Administración de agentes][ex4] | Supervisión | Supervisa y orienta las sesiones de agente |
| [5. Iteraciones][ex5] | Revisión | Revisa las solicitudes de incorporación de cambios, itera sobre el trabajo de Copilot y elige los siguientes pasos |

## Requisitos previos

Antes de participar en este taller, asegúrate de tener:

- [ ] Una cuenta de GitHub con un plan **Copilot Student, Pro, Pro+, Business o Enterprise** activo
- [ ] GitHub Copilot cloud agent habilitado en tu cuenta u organización

> [!TIP]
> ¿No tienes un plan de pago? Los estudiantes verificados pueden obtener GitHub Copilot gratis a través de [GitHub Education][callout-student-plan-education]. El plan **Copilot Student** incluye el agente, MCP, la revisión de código y Copilot CLI que se usan en este taller, así que puedes completar todos los itinerarios.

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> Cloud agent está disponible en los planes **Copilot Student, Pro, Pro+, Business y Enterprise**; no está disponible en Copilot Free. En Copilot Business o Enterprise, un administrador debe habilitarlo para la organización.

> [!NOTE]
> Este itinerario no incluye MCP. Para aprender a usar servidores MCP con Copilot, consulta el [itinerario de CLI][cli] o el [itinerario de VS Code][vscode].

## Empieza

**[Empieza con el ejercicio 0: Requisitos previos →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
[cli]: ../cli/
[vscode]: ../vscode/
