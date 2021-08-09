# bookstore-back

Proyecto de ejemplo para el curso ISIS2603 - Desarrollo de Software en Equipos

## Requisitos para la ejecución

- [JDK 11](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Spring Tools para Eclipse](https://spring.io/tools)
- [Postman](https://www.postman.com/downloads/)

## Pasos para la ejecución

### Abrir el proyecto en SpringTool
- Ejecute SpringTool
- Seleccione la opción "Import projects"
- Seleccione Git > Projects from Git (with smart import)
- Seleccione Clone URI
- Ingrese la URI del repositorio (https://github.com/Uniandes-isis2603/bookstore-back)
- En el siguiente paso seleccione la rama master
- Escoga el directorio local donde se clonará el repo
- Eclipse detectará el proyecto denominado bookstore-back
- Luego de unos minutos el proyecto se cargará

### Configurar Lombok en Eclipse
- Vaya a su directorio personal (en Windows sería, por ejemplo c:\Usuarios\estudiante\)
- Haga doble clic al archivo .m2\repository\org\projectlombok\lombok\1.18.20
- Cuando se ejecute la aplicación verifique que en la sección IDEs este seleccionado el ejecutable SpringToolSuite4
- Haga clic en Install/Update
- Cierre la aplicación 
- Reinicie SpringTools

### Ejecutar el back
- En SpringTools vaya a Boot Dashboard
- Seleccione la opción local > bookstore-back
- Haga clic en el ícono Start. Esto iniciará un servidor que escucha peticiones en el puerto 8080

### Probar el API
- Inicie Postman e importe las colecciones que están en el directorio collections
- Seleccione el entorno denominado "Entorno Colecciones Book"
- Ejecute las colecciones importadas