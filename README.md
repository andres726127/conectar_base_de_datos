# conectar_base_de_datos
Nombre: Leonardo Mendieta

1. ¿Qué es JDBC y cuáles son sus componentes?

JDBC (Java Database Connectivity) es una API de Java que permite a los programas Java interactuar con bases de datos mediante una interfaz común. JDBC es una tecnología clave para acceder y manipular datos en bases de datos relacionales utilizando el lenguaje SQL.
Componentes de JDBC:
1.	Driver JDBC: El driver JDBC es el software que permite la comunicación entre Java y el sistema de gestión de bases de datos (DBMS). Existen varios tipos de drivers JDBC, tales como:
*	Driver tipo 1: Conecta a la base de datos a través de ODBC (Open Database Connectivity).
*	Driver tipo 2: Utiliza las bibliotecas nativas del DBMS para la conexión.
*	Driver tipo 3: Usa un intermediario o middleware para la conexión.
*	Driver tipo 4: Utiliza una comunicación directa entre la aplicación y la base de datos a través de un protocolo específico del DBMS.
2.	Connection: Es la interfaz que establece una conexión con la base de datos. Permite el manejo de las transacciones, el manejo de sentencias SQL y la interacción con la base de datos.
3.	Statement: El objeto Statement se usa para ejecutar consultas SQL. Existen tres tipos:
*	Statement: Para consultas SQL simples.
*	PreparedStatement: Para consultas SQL con parámetros (más eficiente y seguro).
*	CallableStatement: Para llamar procedimientos almacenados.
4.	ResultSet: El ResultSet es una estructura de datos que contiene los resultados de una consulta SQL ejecutada a través de Statement. Permite recorrer los resultados.
5.	SQLException: Excepción que se lanza cuando ocurre un error al interactuar con la base de datos, como problemas de conexión o errores en la consulta SQL.
____________________________________________________________________
2. Librerías de Scala para conectarse a bases de datos relacionales
![image](https://github.com/user-attachments/assets/987c3e69-4f2e-46e2-8c4a-90e2f97cc2e5)

4. Establecer una conexión a una base de datos MySQL desde Scala
![image](https://github.com/user-attachments/assets/88500c15-1b8c-40dd-b9bb-a0334ba365cf)
![image](https://github.com/user-attachments/assets/8279fea2-8552-4053-b06e-73f5eed9c708)
