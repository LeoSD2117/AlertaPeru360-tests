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
