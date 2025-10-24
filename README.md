# PruebaMonitor
preciso servir una pagina para un test OAth para un test de recupero token en un callback

estoy dentro de una VPN y mi prueba require un mock de pagina publica

#caso no-ok 
es llamar a la pagina (mejor en modo incognito) y no encuentra el tole

#caso ok
el que usa la pagina le envia un token (para la prueba va un token de prueba; sirve igual porque el redirect lo lleva a loguearse si o si)
la prueba es: https://buffarinidany.github.io/PruebaMonitor/monitor.html#access_token=TEST123&expires_in=86399&token_type=bearer

#caso ok segundo paso: salta el pop-up
