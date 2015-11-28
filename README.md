Como generar una imagen?

    http://sne.apinic.org/?text=Desayunar nacatamal todos los domingos

# Jugar con el código

Este proyecto requiere registrar una aplicación en www.imgur.com (https://api.imgur.com/#register) para obtener un client_id.

Este proyecto esta almacenado en Heroku y requiere esta configuración:

    heroku config:set BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi

Más información en: https://github.com/ello/heroku-buildpack-imagemagick-cedar-14

Para crear la variable de entorno en heroku debes ejecutar este comando:

    heroku config:set IMGUR_CLIENT_ID=Aqui tu client_id
