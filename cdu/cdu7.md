## Importar datos

**ID:** 004  
**Breve descripción:** El sistema carga datos desde un fichero binario.

**Actores principales:** Datos.  
**Actores secundarios:** Usuario.

**Precondciones:**
  1. Debe existir una copia de seguridad (fichero binario) y otro fichero binario al que vamos a importar los datos.

**Flujo principal:**
1. El caso de uso empieza cuando el usuario quiere importar datos de la copia de seguridad.
2. El sistema carga los datos de la copia de seguridad en un buffer y los vuelca a un fichero binario.

**Postcondiciones:**
* El sistema imprime los nuevos datos como comprobación de la actualización.  

**Flujos alternativos:**  
1.a. Si no existe una copia de seguridad, se crea.  
2.a. Si no existe el fichero binario donde volcar los datos de la copia de seguridad, se creará uno con el nombre que el usuario desee.
