# RetroTracks

[![Made with](https://img.shields.io/badge/Made%20with-Power%20Apps-blue?style=for-the-badge&logo=microsoft)](https://powerapps.microsoft.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

RetroTracks es una aplicación que ofrece una compilación de canciones cuidadosamente seleccionadas para evocar recuerdos y emociones. Esta aplicación permite al usuario sumergirse en una experiencia musical nostálgica, ofreciendo una variedad de géneros y éxitos de diferentes épocas.

## Contexto del Proyecto

Este proyecto fue desarrollado como el trabajo final para el curso de **Introducción a la Ingeniería de Sistemas** durante el primer semestre académico del año 2023. El objetivo principal era aplicar los conceptos fundamentales de análisis, diseño y desarrollo de software en una solución funcional y creativa, utilizando las herramientas de la plataforma Microsoft Power Platform.

## Arquitectura de la Solución

La aplicación se construyó siguiendo una arquitectura simple y eficiente, aprovechando las capacidades nativas de Power Platform:

* **Interfaz de Usuario (Frontend):** Desarrollada como una **Power Apps Canvas App**, que controla toda la lógica de presentación y la interacción con el usuario.
* **Fuente de Datos (Backend):** La información de las pistas, artistas y géneros se gestiona a través de (aqui puedes poner **Microsoft Dataverse, una lista de SharePoint, o un archivo de Excel alojado en OneDrive**). Esto permite una administración de datos desacoplada y escalable.
* **Lógica de Negocio:** Las funciones y fórmulas nativas de Power Fx se utilizan para manejar la reproducción, la navegación entre pantallas y la filtración de canciones.

## Acceso a la Aplicación

* **Vínculo Web:** [**Abrir RetroTracks**](https://apps.powerapps.com/play/e/default-e994072b-523e-4bfe-86e2-442c5e10b244/a/daea9434-beec-4599-844d-9a51110acb5c)

## Logros y Aprendizajes

* Diseño y desarrollo de una aplicación funcional desde cero con una interfaz de usuario intuitiva.
* Aplicación de conceptos de ingeniería de sistemas en un ciclo de vida de proyecto real.
* Experiencia práctica en el desarrollo *low-code* con Microsoft Power Apps y Power Fx.
* Gestión de datos y lógica de negocio para crear una experiencia de usuario fluida.
* Colaboración en equipo utilizando metodologías ágiles para la gestión de tareas y entregas.

## Prerrequisitos

Para importar y ejecutar esta aplicación en un entorno propio, se necesita:

* Un entorno de Microsoft Power Platform.
* Una licencia de Power Apps (una licencia de desarrollador o de la organización es suficiente).
* Permisos para crear conexiones a (menciona el conector que usaste, ej: **Dataverse, SharePoint, OneDrive**).

## Futuras Mejoras (Roadmap)

Se ha contemplado una lista de posibles mejoras para futuras versiones de RetroTracks:

* **Autenticación de Usuarios:** Permitir a los usuarios iniciar sesión para guardar sus preferencias.
* **Playlists Personalizadas:** Funcionalidad para que los usuarios creen y guarden sus propias listas de reproducción.
* **Modo sin Conexión:** Posibilidad de descargar ciertas canciones o listas para escucharlas sin acceso a internet.
* **Integración con APIs Externas:** Conectar con servicios como Spotify o Last.fm para obtener más información de las canciones y artistas.

## Contribuidores

Este proyecto fue posible gracias al trabajo en equipo de:

* **[Renzo Fernando Mosquera Daza](https://github.com/RenzoFernando)**
* **[Luna Martinez](https://github.com/LunaKatalina)**
* **[Nicolas Gongora](https://github.com/rlsnigori)**

## Licencia

Este proyecto está distribuido bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
