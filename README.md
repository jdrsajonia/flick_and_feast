# Flick and Feast

Proyecto académico de bases de datos.  
El código se encuentra en un estado **mezclado y acoplado**, por lo que este repositorio es una forma **temporal** de mantenerlo disponible.

## Requisitos

- [Apache NetBeans](https://netbeans.apache.org/)
- [MySQL](https://dev.mysql.com/downloads/mysql/) instalado y corriendo
- [MySQL Connector/J](https://dev.mysql.com/downloads/connector/j/) (archivo `.jar`)

## Cómo ejecutar

1. **Descargar el proyecto**  
   Clonar este repositorio.

2. **Abrir en NetBeans**  
   - En NetBeans, ir a `File > Open Project`.
   - Seleccionar la carpeta `FLickandFeast.zip` del proyecto.

3. **Añadir el conector de MySQL**  
   - Hacer clic derecho sobre el proyecto en NetBeans.  
   - Ir a `Properties > Libraries > Add JAR/Folder`.  
   - Seleccionar el archivo `mysql-connector-j-x.x.x.jar`.

4. **Configurar credenciales de MySQL**  
   - Editar en el código la sección donde se define el usuario y contraseña de la base de datos.  
   - Ejemplo:  

     ```java
     String url = "jdbc:mysql://localhost:3306/flickandfeast";
     String user = "tu_usuario";
     String password = "tu_contraseña";
     ```

   ⚠️ Se asume que la base de datos ya está creada y contiene las tablas necesarias.

5. **Ejecutar el programa desde NetBeans**  
   El proyecto debería compilar y correr dentro del entorno.

## Notas

- En **Visual Studio Code no corría** en las pruebas realizadas.  
- La estructura del proyecto aún requiere refactorización.  

---
✍️ Proyecto desarrollado como trabajo académico en la materia de **Bases de Datos**.
