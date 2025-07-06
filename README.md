# AlertaPeru360 acceptance test

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
