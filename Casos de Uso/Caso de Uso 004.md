### **Eliminar alumno**

**ID**: 004

**Breve descripción**: El sistema permite la eliminación total o parcial de un alumno o de la completa base de datos

**Actores principales**: Profesor/usuario

**Actores secundarios**: Alumno

**Precondiciones**
   1. El/los alumno/s debe/n de existir en la base de datos

**Flujo principal**:

   1. El caso de uso empieza cuando el profesor/usuario desea eliminar los datos de un alumno o de la base de datos

   2. El sistema realiza una búsqueda del alumno que se desea eliminar

   3. EL sistema ,para la búsqueada, pediría nuevamente los datos de nombre, apellido y DNI

   4. El sistema comprueba si los datos de búsqueda son correctos

   5. El sistema da paso a la eliminación

**Postcondiciones:**

   * El sistema realiza la eliminación

**Flujos alternativos:**

   5.a. en caso de no estar seguro, el sistema da la opción de continuar con el proceso o de revocarlo
