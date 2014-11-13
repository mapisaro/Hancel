hancel-factual
==============

Hancel vincula a periodistas con colegas y organizaciones dedicadas a proteger la libertad de expresión a través de su teléfono celular.

Hancel es una aplicación para teléfonos móviles que permite crear redes de contactos (colegas, organizaciones, familiares, amigos, etc) para el envío de notificaciones al encontrarse en situacion de peligro (botón de pánico), realizar llamadas utilizando VoIP, enviar SMS encriptados y programar el envio de coordenadas GPS (reastreo de ruta).  

# Características de Hancel

* Puede utilizarse por diferentes profesionales como herramienta de protección personal al realizar trabajos de campo en zonas de peligro. En el caso de los periodistas, puede utilizarse para proteger la libertad de expresión al presentarse un caso de ataque. 
* Anillos de seguridad: Permite configurar grupos de contactos(anillos de seguridad) para enviar notificaciones y alertas de peligro. 
* Rastreo: Permite programar el posicionamiento GPS por intervalo de tiempo y notificarlas al anillo de seguridado
* ¿Todo bien?: Notificaciónes automaticas enviadas al usuario en intervalos de tiempo programables que deben ser atendidas. Se envía una alerta al anillo de seguridad en caso de que el usuario no reaccione ante estas notificaciones.
* Cuenta con una alerta de emergencia a los contactos de confianza con la ubicación exacta del GPS del teléfono.
* SMS encriptados:
* VoIp:


#Screenshots

![Login](http://i.imgur.com/Zt1PDfNl.png =250x) ' ![Imgur](http://i.imgur.com/3CXg2axl.png =250x)

# ¿Cómo construir?

El proyecto se encuentra en la carpeta **hancel-project** el cual depende de las siguientes bibliotecas:

* HoloEverywhere: Version 1.6.8 de https://github.com/Prototik/HoloEverywhere
* ActionBarSherlock: http://actionbarsherlock.com/
* Google Play Services
* PageView 4.2

Google Play Services y PageView se encuentran dentro de la carpeta **hancel-project**.  Las demás bibliotecas las agregamos por conveniencia para construir la aplicación de forma más sencilla.

### Importar en eclipse

Clona éste repositorio o desde Eclipse en `Archivo`, `Importar`, `Importar desde Git` y clona la URL del proyecto. 

Después da click en `Importar proyectos existentes` e importa todos con excepto de HoloEeveryWhere "Slider", "Demo", "Application". La estructura del proyecto debe quedar similar a la siguiente:

![Importar](http://i.imgur.com/PG8ir28.png)

Tanto **Login** como **HoloEverywhere** requieren como dependencia a **Actionbarsherlock** por lo tanto, verifica en las propiedades de cada proyecto que se encuentren referenciadas. De **Login** verifica que las siguientes bibliotecas también se encuentren referenciadas correctamente: 

![Referencias](http://i.imgur.com/yoWKBan.png)

Hancel utiliza ACRA como sistema de log. Como actualmente estamos importando el JAR en lugar de compilar como biblioteca, debes verificar que el proyecto **Holo Everywhere Library** incluya la ruta correcta al archivo `acra-4.5.0.jar` localizado en la carpeta `libs` de Holo Everywhere Library

![Imgur](http://i.imgur.com/Xeh2JSc.png)

# ¿Cómo puedo contribuir?

El proyecto Hancel ha sido desarrollado como software libre. Por tanto, la aplicación puede ser modificada siempre y cuando se haga bajo los términos y condiciones de la Licencia Pública General GNU publicada por la Free Software Foundation, ya sea en su versión 2.0 o cualquier otra posterior.

Puedes reportar problemas reportandolos como issues en [Github Issue Tracker](https://github.com/juanjcsr/hancel-factual/issues) o poniendote en contacto con nostros en [@Hancel_App](https://twitter.com/Hancel_App)

# ¿Quíenes somos?

Hancel es un proyecto de un grupo de reporteros y editores que buscan contribuir con el mejoramiento de las condiciones de seguridad de los periodistas en América Latina. El proyecto nace en noviembre de 2011 y durante 18 meses fue enriqueciéndose con sugerencias y recomendaciones de colegas periodistas y expertos en protección a periodistas. En Noviembre de 2012, en el marco del 1er Foro Latinoamericano de Medios Digitales y Periodismo, se realizó un hackatón en las instalaciones de [Telmex Hub](http://www.telmexhub.com/), donde se desarrolló el primer prototipo de la aplicación. En abril 2013, la [Knight Foundation](http://www.knightfoundation.org/) ofreció financiar la programación de un prototipo de la aplicación a través de su [Prototype Fund](http://www.knightfoundation.org/blogs/knightblog/2012/6/18/knight-prototype-fund-building-and-testing-new-ideas-push-media-innovation-forward/). 
La [Fundación para la Libertad de Prensa en Colombia](http://www.flip.org.co/) asesoró el desarrollo del prototipo, mismo que está siendo probado simultáneamente en México y Colombia. Hancel es un proyecto de Factual, organización dedicada a concebir y apoyar proyectos con impacto social en América Latina a través de la generación de herramientas tecnológicas y estrategias de comunicación.


# ¿Quiéres probar la app?

Puedes bajar un APK pre-compilado aquí:

[Hancel](https://github.com/juanjcsr/Hancel/blob/master/hancel-project/bin/Login.apk?raw=true)
