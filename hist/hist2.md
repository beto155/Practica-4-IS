### Modificar animal

**ID:** 002  
**Breve descripción:** El usuario introduce los datos de los parámetros a modificar y el sistema lleva a cabo la acción.

**Actores principales:** Profesor.  
**Actores secundarios:** Alumno.

**Precondiciones:**
1. El alumno debe existir en el sistema.

**Flujo principal:**
1. El caso de uso empieza cuando el profesor quiere modificar un alumno.
2. El sistema comprueba si los datos introducidos son correctos.
3. El sistema busca al alumno según nombre o DNI.
4. El sistema recoge los datos de los parámetros a modificar.
5. El sistema actualiza y guarda los datos introducidos por el usuario.

**Postcondiciones:**
* El sistema muestra el alumno con los datos modificados por pantalla.

**Flujos alternativos:**

3.a. Si los datos no son correctos, se muestra un mensaje de error y se da la posibilidad de volver a introducirlos.

4.a. Si el alumno no existe, se muestra un mensaje de error correspondiente.
