## Registro de Usuario

**ID:** 010

**Breve descripción:** El usuario se registra en el sistema con una serie de datos básicos para su identificación

**Actores principales:** Usuario.  

**Actores secundarios:** Sistema.

**Precondiciones:**

1. No puede haber un usuario con los datos idénticos aunque si puede haber datos similares como el nombre o los apellidos.

**Flujo principal:**

  1. El caso de uso empieza cuando el usuario desea registrarse en el sistema para poder acceder al mismo.

  2. El sistema lanza una ficha de registro para que el usuario rellene los párametros necesarios para su registro.

  3. Los datos requeridos para el registro son nombre, apellidos, nombre de usuario que quiere utilizar, contraseña, DNI y si su función es como coordinador o como ayudante.


**Postcondiciones:**  

   * El sistema guarda los datos del registro para su posterior uso si son requeridos.

**Flujos alternativos:**  

   3.a. En caso de que los datos estén repetidos se pedirá que el usuario vuelva a rellenarlo hasta que estén corrector para el registro.
