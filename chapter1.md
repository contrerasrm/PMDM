# Introducción a las aplicaciones de Android



![](/diagramas/Esquema genérico de aplicacion android.png)

Aqui arriba tenemos el esquema básico de lo que es una aplicación de android, en general. Básicamente está compuesta por una serie de actividades, esas actividades lanzan intents para lanzar otras actividades, y a la vez, usan otros servicios, los cuales no requieren la atención del usuario y por lo tanto se encargan ellos mismos de funcionar.

De todas las actividades que puedan haber en una aplicación android, siempre sera una de ellas la principal, y por tanto la que nos dará siempre la bienvenida.

Las intents son intermediarios entre dos activities, y a traves de ellas podemos intercambiar información entre ellas. Las activities son pantallas de nuestro android, en las que hay botones, imagenes, listas, texto, etc... Y los servicios como ya se dijo antes, son agentes internos que realizan alguna actividad diversa sin requerir la atención del usuario, estos pueden ser:

* Reproducir música
* Estar pentiente de mensajes entrantes
* Entre otros

Todos estos tipo de elementos se llaman contextos y tienen un ciclo de vida concreto cada uno:



