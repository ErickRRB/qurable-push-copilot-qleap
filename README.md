# Qurable Manager v2 · Qurable Push Copilot

Presentación HTML interactiva de una nueva funcionalidad propuesta para Qurable Manager v2: Qurable Push Copilot. El prototipo se prepara en un día durante el hackathon Q-Leap.

Al entrar, una portada visual del Grupo 3 ocupa la pantalla. Un click, Enter, Espacio o Escape abre la presentación.

La narrativa muestra:

1. El problema operativo de marketing.
2. Una bandeja priorizada para mañana y la semana.
3. La anatomía de una recomendación explicable.
4. La revisión y programación humana.
5. La separación entre capacidades existentes, funcionalidad nueva y roadmap.
6. Guardrails, alcance de un día y roadmap.
7. Una pestaña de profundización técnica basada en la API V2 publicada por Qurable.

El brainstorming mayor incluye Audiencias inteligentes por clusterización, Dashboard configurable, Push complejas inteligentes y Funnel adaptativo. La demo profundiza el foco Push; los demás conceptos permanecen como roadmap.

Jerarquía de nombres:

- Qurable: marca y plataforma completa.
- Qurable Manager v2: producto enterprise.
- Qurable Push Copilot: nueva funcionalidad propuesta dentro de Manager v2.
- Q-Leap: hackathon donde se construye y presenta el prototipo.

Estados visuales:

- `EXISTS`: capacidad disponible en Qurable Manager v2 o Qurable API.
- `NEW`: parte de Qurable Push Copilot prototipada durante el hackathon.
- `NEXT`: integración productiva o roadmap posterior.

La vista técnica distingue:

- capacidades publicadas: Insights MCP, Segments, Audiences, Activation Jobs, Events, Dashboards y Widgets;
- construcción durante el hackathon: recomendador, workflow humano, políticas demo y calendario simulado;
- roadmap: adaptador Push, operación productiva, funnel atribuible, clusterización, optimización y autonomía gradual.

Fuente técnica: <https://docs.qurable.co/api-docs/v2>.

## Contenido

- `index.html`: presentación responsive e interacción de aprobación simulada.
- `assets/qleap-grupo-3.png`: imagen de entrada de la demo.

## Alcance

El HTML no realiza envíos reales ni contiene autenticación. La integración del canal Push, el scoring con datos productivos y la medición real forman parte de una validación posterior. La disponibilidad de modelos semánticos, stored queries y permisos debe verificarse en el tenant del piloto.

## Publicación

- Repositorio: `ErickRRB/qurable-push-copilot-qleap`
- Pages: `https://ErickRRB.github.io/qurable-push-copilot-qleap/`
