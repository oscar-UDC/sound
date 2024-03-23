# ¿Qué se pretende implementar como una actividad?
* Login
* SignUp
* Post
* Shazam (reconocimiento de música)
* Main

# ¿Qué se va a implementar como un servicio?
* Lógica interna del post
* Lógica de actualización de perfil
* Lógica de actualización de posts

# ¿Qué se va a implementar con fragments?
El resto de elementos de la barra de navegación:
* Home - Posts
* Home - Daily posts
* Barra de búsqueda
* Ver perfil
* Notificaciones
* Mapa

# ¿Quién lanza a quién y quién hace uso de los fragments o los servicios?
La actividad de login lanza la de registro. Estas dos lanzan la actividad principal, la cual navega entre los distintos fragments y lanza tanto la actividad de Shazam como la de Posts. 
