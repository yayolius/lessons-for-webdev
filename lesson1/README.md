# Objetivo:

Simular un login, mediante un formulario html sencillo que tiene 3 campos email, password, submit que se envian via POST

Acciones.
* Se entrega el archivo login.html, no se deben hacer modificaciones al archivo, excepto cambiar la ruta a donde se dirige para validar el formulario.
* Se debe verificar que en la combinación email/password el password  sea igual a lo que viene antes de la arroba en el campo email más un numero 1 al final.
* Si el login es correcto, se debe guardar una cookie "logueado" con valor 1, y una hora de vida, y redirigir a dashboard.html
* Si el login es incorrecto, se debe guardar una cookie "logueoerroneo" con valor de 3 minutos y redigir a login.html

# Lenguajes

El problema debe ser resuelto en 2 o 3 lenguajes/frameworks

1. PHP Puro
2. NodeJs utilizando la libreria Express
3. Python utilizando flask (voluntario)

