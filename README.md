# AlertaPeru360 acceptance test
US13:
Feature: Iniciar sesión

  Como usuario registrado en la landing page
  quiero iniciar sesión
  para volver a acceder a mi cuenta.

  Scenario: Iniciar sesión correctamente
    Dado que el usuario registrado está en la página de inicio de sesión
    Cuando ingresa su correo electrónico y su contraseña y presiona el botón ingresar
    Entonces accede a su cuenta y es redirigido a la página principal


US42:
Feature: Video explicativo de uso de la app

  Como usuario registrado en la landing page
  quiero ver un video explicativo de la app
  para poder usarla de forma eficaz.

  Scenario: Ver video tutorial
    Dado que el usuario registrado está en la página principal
    Cuando empieza a navegar y encuentra la sección “Protege a tu comunidad con información precisa” y presiona el botón “Aprende más”
    Entonces podrá visualizar en una nueva pantalla el video explicativo de la app


US46:
Feature: Funciones de la app

  Como usuario registrado en la landing page
  quiero leer información con las funciones que tiene la app
  para tener una idea general de cómo la usaré.

  Scenario: Ver funciones de la app
    Dado que el usuario registrado está en la página principal
    Cuando empieza a navegar y encuentra la sección “Protege a tu comunidad con información precisa” y presiona el botón “Aprende más”
    Entonces podrá leer las funciones principales de la app


US51:
Feature: Visualizar zona de riesgo

  Como usuario registrado en la landing page
  quiero un botón que me dirija a un mapa con las zonas de riesgo
  para estar mejor preparado ante posibles desastres en mi área.

  Scenario: Visor de mapas interactivos
    Dado que el usuario registrado está en la sección de “Consulta las zonas de riesgo de tu zona”
    Cuando presiona en el botón “Ver mapas ahora”
    Entonces se redirigirá al visor de mapas interactivos


US52:
Feature: Zona de riesgo de Lima

  Como usuario registrado en la landing page
  quiero poder visualizar la zona de riesgo de Lima
  para poder tomar precauciones.

  Scenario: Mapa de Lima
    Dado que el usuario registrado está en la pestaña de visor de mapas interactivos
    Cuando presiona en el botón “Ver Lima”
    Entonces el mapa mostrará el mapa de zona de riesgo de Lima


US53:
Feature: Zona de riesgo de Cusco

  Como usuario registrado en la landing page
  quiero poder visualizar la zona de riesgo de Cusco
  para poder tomar precauciones.

  Scenario: Mapa de Cusco
    Dado que el usuario registrado está en la pestaña de visor de mapas interactivos
    Cuando presiona en el botón “Ver Cusco”
    Entonces el mapa mostrará el mapa de zona de riesgo de Cusco


US54:
Feature: Zona de riesgo de Piura

  Como usuario registrado en la landing page
  quiero poder visualizar la zona de riesgo de Piura
  para poder tomar precauciones.

  Scenario: Mapa de Piura
    Dado que el usuario registrado está en la pestaña de visor de mapas interactivos
    Cuando presiona en el botón “Ver Piura”
    Entonces el mapa mostrará el mapa de zona de riesgo de Piura


US55:
Feature: Volver a la ventana principal desde el visor de mapas

  Como usuario registrado que ya revisó el mapa de zona de riesgo de su ciudad
  quiero poder regresar a la ventana principal
  para poder seguir navegando en las otras secciones de la landing page.

  Scenario: Volver al inicio
    Dado que el usuario registrado está en la pestaña de visor de mapas interactivos
    Cuando presiona en el botón “Volver al inicio”
    Entonces se redirigirá a la página principal


US56:
Feature: Información acerca de los mapas de riesgo

  Como usuario registrado en la landing page
  quiero ver información acerca de los mapas de riesgo
  para saber qué muestran, quién los usa, para qué sirven y su importancia.

  Scenario: Información acerca de mapas de riesgo
    Dado que el usuario registrado está en la sección de “Consulta las zonas de riesgo de tu zona”
    Cuando presiona en el botón “¿Qué son los Mapas de Riesgo?”
    Entonces se redirigirá a la pestaña con información acerca de los mapas de riesgo junto con una imagen
             del mapa sísmico de la ciudad de Limatambo


US57:
Feature: Preguntas frecuentes sobre los mapas de riesgo

  Como usuario registrado en la landing page
  quiero ver una sección de preguntas frecuentes
  para saber acerca de quién elabora los mapas de riesgo, con qué frecuencia se actualizan y si puedo usarlos sin internet.

  Scenario: ¿Quién elabora los mapas de riesgo?
    Dado que el usuario registrado está en la ventana de “Qué son los mapas de riesgo” y va a la sección de preguntas frecuentes
    Cuando presiona en el botón “¿Quién elabora los mapas de riesgo?”
    Entonces debajo se desplegará la respuesta: “Instituciones como INDECI, municipalidades, y organismos técnicos como CENEPRED o INGEMMET”

  Scenario: ¿Con qué frecuencia se actualizan?
    Dado que el usuario registrado está en la ventana de “Qué son los mapas de riesgo” y va a la sección de preguntas frecuentes
    Cuando presiona en el botón “¿Con qué frecuencia se actualizan?”
    Entonces debajo se desplegará la respuesta: “Dependiendo del tipo de amenaza, pueden actualizarse cada año o luego de un evento crítico.”

  Scenario: ¿Puedo usarlo sin internet?
    Dado que el usuario registrado está en la ventana de “Qué son los mapas de riesgo” y va a la sección de preguntas frecuentes
    Cuando presiona en el botón “¿Puedo usarlo sin internet?”
    Entonces debajo se desplegará la respuesta: “Sí, AlertaPerú360 te permite ver mapas descargados previamente en modo offline.”

US12:
Feature: Cerrar sesión

  Como usuario registrado en la landing page
  quiero cerrar sesión
  para salir de mi cuenta de forma segura.

  Scenario: Cerrar sesión desde la página principal
    Dado que el usuario registrado está en la página principal
    Cuando presiona el botón de “Cerrar sesión” de la parte superior
    Entonces su cuenta se cierra correctamente y es redirigido a la página de inicio de sesión


US15:
Feature: Cambiar idioma de la landing page

  Como usuario registrado en la landing page
  quiero cambiar el idioma a inglés
  para poder entender lo que dice la página.

  Scenario: Cambiar idioma a inglés
    Dado que el usuario registrado está en la página principal
    Cuando presiona el botón “EN”
    Entonces el contenido se cambiará al idioma inglés

  Scenario: Regresar al idioma original (español)
    Dado que el usuario registrado está en la página principal con idioma inglés
    Cuando presiona el botón “ES”
    Entonces el contenido se cambiará al idioma español


US26:
Feature: Ver información sobre la importancia de estar informado

  Como usuario registrado en la landing page
  quiero saber porqué es importante estar informado con AlertPerú360
  para convencerme de que vale la pena usarlo en situaciones de emergencia.

  Scenario: Ver sección “Acerca de nosotros”
    Dado que el usuario registrado está en la página principal
    Cuando empieza a navegar y encuentra la sección “Acerca de nosotros” y presiona el botón “Descubre más”
    Entonces puede leer la información sobre porqué es importante mantenerse informado con AlertPerú360


US27:
Feature: Ver información sobre cómo AlertPerú360 mantiene informado

  Como usuario registrado en la landing page
  quiero saber cómo AlertPerú360 nos mantiene informado
  para saber el contenido de la app.

  Scenario: Ver sección “Acerca de nosotros”
    Dado que el usuario registrado está en la página principal
    Cuando empieza a navegar y encuentra la sección “Acerca de nosotros” y presiona el botón “Descubre más”
    Entonces puede leer la información del contenido de AlertPerú360



US36:
Feature: Conocer servicios de AlertPerú360

  Como usuario registrado en la landing page
  quiero saber qué ofrece AlertPerú360
  para entender cómo puede ayudarme.

  Scenario: Ver sección “Protege a tu comunidad con información precisa”
    Dado que el usuario registrado está en la página principal
    Cuando empieza a navegar y encuentra la sección “Protege a tu comunidad con información precisa”
    Entonces puede ver información sobre protección de comunidad y cantidad de comunidades protegidas por AlertPerú360

US20.feature

Feature: Visualizar la descripción del producto

  Como visitante de la página
  quiero acceder a una landing page clara y atractiva que explique qué es AlertaPerú360
  para entender de inmediato cómo puede ayudarme ante emergencias.

  Scenario: Visualización de sección principal
    Dado que el usuario ingresa a la página
    Cuando empieza a navegar
    Entonces visualiza la sección principal con el nombre del producto y un resumen de su propósito

US21.feature

Feature: Visualización de beneficios de la plataforma

  Como usuario potencial
  quiero ver en la landing los beneficios de usar AlertaPerú360
  para decidir si vale la pena registrarme o descargar la app.

  Scenario: Ver sección de beneficios
    Dado que el usuario está en la landing page
    Cuando va a la sección de “Protege a tu comunidad con información precisa” y presiona el botón “Aprende más” y se desplaza a la parte inferior de la nueva página
    Entonces visualiza los beneficios de usar AlertPerú360

US33.feature

Feature: Adaptabilidad móvil

  Como visitante desde mi celular
  quiero que la landing page se vea bien y funcione correctamente
  para navegar sin problemas.

  Scenario: Navegación desde celular
    Dado que el usuario está usando su dispositivo móvil
    Cuando accede a la landing page
    Entonces el contenido se adapta automáticamente al tamaño de pantalla

US34.feature

Feature: Traducción automática de reportes comunitarios

  Como turista
  quiero ver los reportes ciudadanos traducidos
  para entender los eventos locales.

  Scenario: Traducción automática activada
    Dado que tengo el idioma inglés activo
    Cuando leo un reporte en español
    Entonces se muestra traducido automáticamente

 US35.feature

Feature: Sección de consulta de zonas de riesgo

  Como ciudadano que vive en zona de riesgo
  quiero acceder desde la landing a una sección de consulta de zonas de riesgo
  para saber si mi zona es vulnerable.

  Scenario: Acceso al mapa de zonas de riesgo desde la landing page
    Dado que el usuario está en la parte principal de la landing page
    Cuando presiona el botón "Explora los mapas de riesgo"
    Entonces puede acceder a una vista previa del mapa

 US37.feature

Feature: Sección de protege a tu comunidad

  Como persona que vive en zona de riesgo que quiere estar informado
  quiero leer textos claros que expliquen cómo la plataforma ayuda durante emergencias
  para comprender su utilidad sin necesidad de descargarla aún.

  Scenario: Navegación en distintas secciones de landing page
    Dado que el usuario explora la página
    Cuando encuentra la sección de “Protege a tu comunidad con información precisa”
    Entonces lee información de cómo AlertPerú360 ayuda

US43.feature

Feature: Sección de noticias

  Como usuario que vive en zona de riesgo
  quiero ver noticias y actualizaciones recientes sobre AlertaPerú360
  para mantenerme informado desde el inicio.

  Scenario: Ver sección de noticias y actualizaciones
    Dado que el usuario está navegando en la landing page
    Cuando llega a la sección de noticias
    Entonces visualiza titulares con fechas recientes y enlaces a artículos completos

US50.feature

Feature: Pie de página

  Como visitante de la landing page
  quiero que la landing tenga un pie de página con información útil (enlaces, derechos, contacto)
  para poder acceder rápidamente a lo esencial al final de la página.

  Scenario: Visualizar pie de página
    Dado que el usuario está navegando en la landing page
    Cuando llega al final de la página
    Entonces encuentra un pie de página con la descripción de AlertaPerú360, enlaces rápidos, datos de contacto y redes sociales
