# PMMM
Project Manager Multilingual Marketplace


La plataforma que describes tiene el potencial de ser una herramienta valiosa para desarrolladores de todos los niveles, desde principiantes hasta expertos. La capacidad de crear, editar y ejecutar proyectos Knative fácilmente desde una interfaz web intuitiva, similar a Gittea o Gitcode, simplificaría enormemente el proceso de desarrollo y despliegue de aplicaciones. Además, la implementación de plantillas para diferentes lenguajes de Knative facilitaría aún más la creación de proyectos, especialmente para usuarios nuevos en informática.

Funcionalidades clave:

Interfaz web intuitiva: La plataforma debería contar con una interfaz web fácil de usar, similar a Gittea o Gitcode, que permita a los usuarios crear, editar y gestionar sus proyectos Knative de forma sencilla.
Creación de plantillas: La plataforma debería ofrecer una variedad de plantillas para diferentes lenguajes de Knative, lo que facilitaría la creación de proyectos para usuarios nuevos en informática.
Ejecución de proyectos: La plataforma debería permitir a los usuarios ejecutar sus proyectos Knative directamente en su sistema.
Creación de repositorios Git: Para cada proyecto creado, la plataforma debería crear automáticamente un repositorio Git, lo que facilitaría el seguimiento de los cambios y la colaboración entre usuarios.
Despliegue automático: La plataforma debería realizar un despliegue automático de Knative cada vez que se realice un cambio en la rama principal del repositorio Git asociado al proyecto.
Sistema de puntos: La plataforma debería implementar un sistema de puntos que permita a los usuarios consumidores de la aplicación adquirir puntos para utilizarlos en la compra de funciones predefinidas.
Venta de funciones: La plataforma debería permitir a los desarrolladores expertos vender sus funciones predefinidas a otros usuarios a cambio de puntos.
Ejemplos de funciones: La plataforma podría ofrecer una variedad de funciones predefinidas, como la conversión de archivos PPTX a video, con un costo asociado en puntos para cada función.
Beneficios:

Facilidad de uso: La plataforma simplificaría enormemente el proceso de desarrollo y despliegue de aplicaciones Knative, haciéndolo accesible a usuarios de todos los niveles.
Aceleración del desarrollo: Las plantillas predefinidas y el despliegue automático ayudarían a los usuarios a desarrollar y desplegar sus aplicaciones Knative más rápidamente.
Colaboración: La creación automática de repositorios Git facilitaría la colaboración entre usuarios en el desarrollo de proyectos.
Monetarización: La plataforma permitiría a los desarrolladores expertos monetizar sus habilidades y conocimientos vendiendo sus funciones predefinidas a otros usuarios.
Consideraciones adicionales:

Seguridad: La plataforma debería implementar medidas de seguridad adecuadas para proteger los datos de los usuarios y los proyectos.
Escalabilidad: La plataforma debería ser escalable para soportar un gran número de usuarios y proyectos.
Documentación: La plataforma debería contar con documentación completa y fácil de entender para ayudar a los usuarios a aprovechar al máximo sus funcionalidades.


1. ¿Se debe usar un ejecutor de comandos en el host machine para crear los proyectos?

No es estrictamente necesario usar un ejecutor de comandos en el host machine para crear los proyectos. La plataforma debería proporcionar una interfaz web intuitiva que permita a los usuarios crear proyectos de forma sencilla, sin necesidad de conocimientos técnicos avanzados. Sin embargo, si se desea automatizar el proceso de creación de proyectos o realizar tareas más complejas, se podría utilizar un ejecutor de comandos en el host machine.

2. ¿Cómo hacer para que los clientes puedan crear un proyecto nuevo?

La plataforma debería ofrecer una interfaz web con un formulario para la creación de nuevos proyectos. El formulario debería solicitar información esencial del proyecto, como el nombre, la descripción, el lenguaje de Knative a utilizar y la plantilla deseada. Una vez completado el formulario, la plataforma debería crear el proyecto, inicializar el repositorio Git asociado y proporcionar al usuario acceso a la interfaz de usuario de VS Code Web para el proyecto.

3. ¿Cómo se inicia un repositorio de Git para ese proyecto?

La plataforma debería automatizar la creación de un repositorio Git para cada proyecto nuevo. Esto se puede lograr utilizando herramientas como GitLab API o GitHub API. El repositorio debería almacenarse en un servidor Git remoto, como GitLab o GitHub, para facilitar la colaboración entre usuarios.

4. ¿Cómo se muestra una UI para vscode web del proyecto?

La plataforma debería integrar una extensión de VS Code Web que permita a los usuarios acceder a la interfaz de usuario de VS Code para sus proyectos. La extensión debería conectarse al repositorio Git del proyecto y proporcionar al usuario las herramientas necesarias para desarrollar, editar y probar su código Knative.

5. ¿Cómo se hace deploy al proyecto?

La plataforma debería ofrecer opciones de despliegue automatizado y manual. El despliegue automático debería realizarse cada vez que se realice un cambio en la rama principal del repositorio Git asociado al proyecto. El despliegue manual debería permitir a los usuarios realizar despliegues a petición. La plataforma debería utilizar herramientas como kubectl o kn para realizar los despliegues en el clúster de Kubernetes.

6. ¿Cómo se listan los posibles templates de proyectos de Knative?

La plataforma debería proporcionar una interfaz web o una API que permita a los usuarios listar los templates de proyectos Knative disponibles. Los templates deberían estar organizados por categorías, como lenguaje de Knative, tipo de aplicación o función. La plataforma debería proporcionar una descripción detallada de cada template, incluyendo las características y funcionalidades que ofrece.

7. ¿Se necesitan scripts en el host machine para facilitar el trabajo?

El uso de scripts en el host machine puede ser útil para automatizar tareas repetitivas o complejas, como la creación de proyectos, la configuración de entornos de desarrollo o la ejecución de pruebas. Sin embargo, la plataforma debería estar diseñada para ser lo más intuitiva y fácil de usar posible, minimizando la necesidad de scripts en el host machine para los usuarios no técnicos.


