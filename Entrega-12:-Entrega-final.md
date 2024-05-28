Esta entrega final se compone de 4 apartados diferenciados: Multimedia, Sensórica, Producto Mínimo Viable y Modelo de Negocio.

# Multimedia

En cuanto a elementos multimedia, utilizamos la cámara del dispositivo para establecer las fotos de perfil de los usuarios, además de ofrecer la posibilidad de escoger una imagen de su galería. Teniendo en cuenta esto, trabajamos con elementos de multimedia de dos formas distintas, directamente, mediante fotos de perfil que almacenamos en nuestra base de datos, e indirectamente, a través de canciones de Spotify, de las cuales únicamente almacenamos un indicador de la API de Spotify.
En cuanto a audios, cabe mencionar el uso de Shazam para reconocimiento de audios, que usamos para, a partir del micrófono del móvil, ofrecerle la funcionalidad al usuario de reconocer canciones automáticamente para incluirlas en publicaciones.

# Sensórica
En la aplicación hacemos uso de varios sensores, estos son:
## Sensor de posición
Hacemos uso del sensores de posición del dispositivo para obtener la geolocalización del usuario, la cual seguimos a tiempo real, además de añadir esta información a los posts para que se vean reflejados en el mapa de la aplicación.
## Sensor de giroscopio
Hacemos uso de la función implementada de base en todos los dispositivos Android para girar la pantalla entre modo vertical y apaisado, ya que el usuario tiene la opción de utilizar la aplicación en ambas orientaciones.
## Micrófono
El propio micrófono del dispositivo cuenta como sensor, y lo utilizamos como mencionamos en el apartado anterior para reconocimiento automático de canciones mediante Shazam.

## Integración con Shazam
Al agitar el teléfono, se abre la funcionalidad de Shazam y se comienza a analizar el audio entrante para mostrar la canción que se está escuchando:

![Screenshot_2024-05-28-23-03-18-281_com muei soundshare](https://github.com/ikergcalvino/SoundShare/assets/90251807/3f7becb2-a28b-410d-aea9-b280e90a3033)

# Producto Mínimo Viable (PMV)

Finalizamos las funcionalidades que nos quedaban pendientes hasta el momento y ofrecemos una aplicación completa con los apartados que pretendíamos cubrir, junto con una documentación detallada a lo largo de esta wiki que ayude a comprender el proceso seguido para su realización.

# Modelo de negocio

![Edit org_design (2)](https://github.com/ikergcalvino/SoundShare/assets/90251807/e3375f13-78d1-4f59-a7e9-a1199e3b5b6e)
