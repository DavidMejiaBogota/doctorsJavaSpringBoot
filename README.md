API REST Citas Consultorio Médico
    -java
    -spring boot
    -maven
    -sql

Creado por:
    -Giovanna Astrid Rueda C
    -Alejandro Rey Vera
    -José David Mejía Meneses
    2023 diciembre

Guía paso a paso para crear una API REST básica con java, spring boot, maven y sql:
    1. Clonar este repositorio utilizando el siguiente comando en Git:
    
    https://github.com/DavidMejiaBogota/doctorsJavaSpringBoot.git

    2. Instalar el paquete requerido :

    mvn clean install

    3. Correr la aplicaión en apiCitasApplication.java

Pruebas postman

Con el objetivo de realizar las pruebas y validaciones del adecuado funcionamiento de la APP Doctors, se realiza un paquete de pruebas con el cliente Postman y el servidor de la aplicación, verificando los tres modelos existentes: Doctores, Pacientes y Citas, a continuación se plasma evidencia del proceso:

### CRUD Paciente

1.	Consultar todos los pacientes de la base de datos:

![Alt text](img/paciente/pacienteTodos.png)

2. Consultar todos los pacientes de la base de datos buscando un id que no existe:

![Alt text](img/paciente/pacienteTodosError.png)

3. Crear paciente

![Alt text](img/paciente/3crearPaciente.png)

4. Actualizar paciente.

![Alt text](img/paciente/4actualizarPaciente.png)

5. Elimninar paciente.

![Alt text](img/paciente/5eliminarPaciente.png)

