Esta entrega final se compone de 4 apartados diferenciados: Multimedia, Sensórica, Producto Mínimo Viable y Modelo de Negocio.

# Multimedia

Nuestra aplicación no tiene funciones multimedia para sacar fotografías, por lo que lo hemos indicado en el manifest.xml con  
`<uses-feature android:name="android.hardware.camera"`
        `android:required="false" />`.
Teniendo en cuenta esto, sí trabajamos con elementos de multimedia de dos formas distintas, directamente, mediante fotos de perfil que almacenamos en nuestra base de datos, e indirectamente, a través de canciones de Spotify, de las cuales únicamente almacenamos un indicador de la API de Spotify.
En cuanto a audios, cabe mencionar el uso de Shazam para reconocimiento de audios, que usamos para, a partir del micrófono del móvil, ofrecerle la funcionalidad al usuario de reconocer canciones automáticamente para incluirlas en publicaciones.

# Sensórica
En la aplicación hacemos uso de varios sensores, estos son:
## Sensor de posición
Hacemos uso del sensores de posición del dispositivo para obtener la geolocalización del usuario, la cual seguimos a tiempo real, además de añadir esta información a los posts para que se vean reflejados en el mapa de la aplicación.
## Sensor de giroscopio
Hacemos uso de la función implementada de base en todos los dispositivos android para girar la pantalla entre modo vertical y apaisado, ya que el usuario tiene la opción de utilizar la aplicación en ambas orientaciones.
## Micrófono
El propio micrófono del dispositivo cuenta como sensor, y lo utilizamos como mencionamos en el apartado anterior para reconocimiento automático de canciones mediante Shazam.
# Producto Mínimo Viable (PMV)

Finalizamos las funcionalidades que nos quedaban pendientes hasta el momento y ofrecemos una aplicación completa con los apartados que pretendíamos cubrir, junto con una documentación detallada a lo largo de esta wiki que ayude a comprender el proceso seguido para su realización.

# Modelo de negocio