# CW_Basics_PromptDiag

## Antes de empezar

Plantilla del diálogo **Draft with Copilot** en la lista de proyectos/trabajos. Muestra cómo construir una sugerencia de tareas a partir de una descripción.

**Referencia del checkout:** `application 26.0.0.0`, `runtime 15.0`; extensión `1-GetStarted Demo` versión `0.1.0.0`. Es la configuración del manifiesto, no una prueba de compatibilidad con otros entornos.

1. Clona `https://github.com/javiarmesto/Lab1_1_Template_Copilot_FrameWork.git` y abre la carpeta en VS Code con AL Language.
2. Configura tu sandbox en `.vscode/launch.json` (créalo si falta), comprueba las dependencias de [app.json](app.json) y descarga símbolos con **AL: Download Symbols**.
3. Compila con `Ctrl+Shift+B`; publica en el sandbox con `F5` cuando hayas completado la configuración específica del ejemplo.
4. Abre **Job List / Proyectos**, pulsa **Draft with Copilot** y comprueba que aparece el diálogo. La generación de una lista HTML exige completar la autorización; no es un resultado disponible sin configuración.

**Mapa del ejemplo:** `DraftProject.Page.al`: PromptDialog; `ProjectListExtension.PageExt.al`: acción; `MyCapability.EnumExt.al`: capacidad.

**Límites:** GetApiKey/GetDeployment/GetEndpoint devuelven valores de ejemplo. La conexión no está lista al clonar; prepara una solución de configuración segura en tu copia. Comparte app ID/rango con Lab1_2, por lo que no deben publicarse juntos sin adaptación. La revisión documental del 6 de octubre de 2026 es estática; no acredita compilación, publicación ni llamadas a servicios externos.


## Descripción del Proyecto
Este proyecto es una extensión para Microsoft Dynamics 365 Business Central que utiliza capacidades de Azure OpenAI para generar tareas de proyectos basadas en descripciones proporcionadas por el usuario. Está diseñado para demostrar cómo integrar inteligencia artificial en aplicaciones empresariales.

## Objetivo del ejercicio
El objetivo de este workshop es introducir a los participantes en el desarrollo de extensiones para Dynamics 365 Business Central, utilizando herramientas avanzadas como Azure OpenAI para mejorar la experiencia del usuario y automatizar procesos.
Identificar las diferentes herramientas y el flujo basico para implementar capacidades mas complejas. Ayudar en la creacion de una capacidad sencilla personilzada en el siguiente ejercicio.

## Contenido del ejercicio
1. **Introducción a Capacidades Copilot**
 

2. **Exploración del Proyecto**
   - Archivos principales:
     - `app.json`: Configuración de la extensión.
     - `DraftProject.Page.al`: Página de diálogo para generar tareas.
     - `MyCapability.EnumExt.al`: Extensión de capacidades de Copilot.
     - `ProjectListExtension.PageExt.al`: Extensión de la página de lista de trabajos.
   - Uso de Azure OpenAI para generar tareas.

3. **Implementación de Funcionalidades**
   - Cómo definir páginas, acciones y capacidades.
   - Uso de código AL para interactuar con servicios de Azure Open AI.

4. **Pruebas y Despliegue**
   - Validación de la funcionalidad.
   - Despliegue de la extensión en un entorno de prueba.

## Requisitos
- Conocimientos básicos de programación.
- Acceso a un entorno de desarrollo de Dynamics 365 Business Central.
- Suscripción activa a Azure con acceso a Azure OpenAI.

## Recursos Adicionales
- [Documentación de Dynamics 365 Business Central](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/)
- [Guía de Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/)

## Ayuda

Incluye versión BC y pasos de reproducción al consultar con el instructor; no compartas secretos.
