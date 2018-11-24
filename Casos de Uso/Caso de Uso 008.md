## Crear copia de seguridad

**ID:** 008  

**Breve descripción:** El sistema crea una copia de seguridad.

**Actores principales:** Usuario.  

**Actores secundarios:** Sistema.

**Precondiciones:**

1. Debe existir un fichero binario.

**Flujo principal:**

  1. El caso de uso empieza cuando el usuario desea realizar una copia de seguridad o cuando existe un fichero binario.

  2. El sistema crea un fichero binario igual con el nombre que desee el usuario.


**Postcondiciones:**  

   * El sistema crea la copia de seguridad en un repositorio remoto.

**Flujos alternativos:**  

2.a. Si no existe fichero binario al que hacer una copia, se mostrará un mensaje error.
