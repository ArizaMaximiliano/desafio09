Implemente  logger de winston 
    Mediante la variable en .env elijo si es prod o dev
    dev solo por consola
    prod por consola y un archivo error.logger

En indexRouter esta un endpoint para probar los logs
    http://localhost:8080/loggerTest

    info: Conexión exitosa con la base de datos
    info: Server iniciado en http://localhost:8080
    debug: Este es un mensaje de depuración
    info: Esta es una información relevante
    warn: Este es un mensaje de advertencia
    error: Este es un mensaje de error
    info: Productos encontrados: {"0":{"availability":true... etc}