# Laboratorio_7

## ¿Cuál es la diferencia entre autenticación y autorizacion?
    La autenticación en una página web es el proceso mediante el cual el sistema verifica la identidad del usuario, usualmente a través de credenciales como usuario y contraseña, mientras que la autorización ocurre después y determina qué acciones o recursos están permitidos para ese usuario ya autenticado. Es decir, primero el sistema confirma quién sos, y luego decide qué podés hacer dentro de la plataforma según tus permisos o rol asignado. Ambos procesos son esenciales para garantizar la seguridad y el control de acceso en aplicaciones web.

## ¿Cuál es la función del token JWT en la guía?
    En la guía, el token JWT (JSON Web Token) se utiliza como mecanismo de autenticación sin estado entre el cliente (React) y el servidor (Express). Una vez que el usuario inicia sesión correctamente, el servidor genera un token JWT que se guarda en el localStorage del navegador.