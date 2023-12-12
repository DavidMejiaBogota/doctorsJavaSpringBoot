API REST Citas Consultorio Médico:
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

Modelo de la base de datos:

![Alt text](<img/Drigrama Modelo Entiendad Relacional..png>)



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

5. Eliminar paciente.

![Alt text](img/paciente/5eliminarPaciente.png)


### CRUD Doctor

1.	Consultar todos los doctores de la base de datos:

![Alt text](img/doctor/TodosDoctores.png)

2. Consultar todos los doctores de la base de datos buscando un id que no existe:

![Alt text](img/doctor/IdnoExiste.png)

3. Crear doctor:

![Alt text](img/doctor/CrearDoctor.png)

4. Consultar doctor por especialidad:

![Alt text](img/doctor/porEspecialidad.png)

5. Eliminar doctor:

![Alt text](img/doctor/EliminarDoctor.png)

6. Error por creación del mismo doctor que ya existe en la bd:

![Alt text](img/doctor/ErrorDobleCreacion.png)



### CRUD Cita


1.	Consultar todas las citas de la base de datos:

![Alt text](img/cita/1.ConsultarDB.png)

2.  Consultar cita 1 por 1 en la base de datos que no existe en ella con sus parametros:

![Alt text](img/cita/2.1por1noExisten.png)

3. Se Crea una cita con los datos de Doctor y Paciente:

![Alt text](img/cita/3.Creacitas.png)

4. Se Realiza un mapeo, me la Busca por el ID de Paciente y Doctor, que no es solo el fecha y Hora si no tambien me trae la informacion de ellos mismos asi seria seria el mapeo:

![Alt text](img/cita/4.MapeodeCita.png)

5. Se Realiza una actualización en fechaHora principalmente en la Hora:

![Alt text](img/cita/5.ActualizaDatos.png)

6. Se Realiza la Eliminacion de Datos de la cita:

![Alt text](img/cita/6.EliminalaCita.png)


