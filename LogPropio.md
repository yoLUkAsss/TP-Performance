LOG DE ERRORES Y CORRECCIONES

  Error 1 ..:::..
    [main] ERROR org.hibernate.tool.hbm2ddl.SchemaValidator  - could not get database metadata
    com.mysql.jdbc.exceptions.jdbc4.CommunicationsException: Communications link failure

    Causa: Se encontraba en el archivo de configuracion, tratando de entrar a la base por puerto 3307 (incorrecto)

    Solucion... Modificar, el puerto, usando el 3306...

  
