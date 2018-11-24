### **Ordenar alumnos**

**ID:** 006

**Breve descripción:** El sistema permite al usuario visualizar a todos los alumnos de forma ordenada

**Actores principales**: Profesor/usuario

**Actores secundarios**: Alumno

**Precondiciones**

&nbsp;&nbsp;&nbsp;**·** Que al menos un alumno exista

**Flujo principal:**

&nbsp;&nbsp;&nbsp;**1.** EL usuario desea ordenar la lista de alumnos tanto ascendente como descendéntemente

&nbsp;&nbsp;&nbsp;**2.** El sistema Pregunta si quiere ordenarlos por DNI, nombre, apellido o curso más alto en el que está matriculado

&nbsp;&nbsp;&nbsp;**3.** El usuario selecciona la opción que desea

&nbsp;&nbsp;&nbsp;**4.** El sistema muestra el listado pedido por el usuario

**Postcondiciones:**

&nbsp;&nbsp;&nbsp;**·**  La lista de alumnos esta ordenada

**Flujos alternativos:**

&nbsp;&nbsp;&nbsp;**2.a** A la hora de ordenar la lista el sistema da error porque la lista este vacía en el apartado de DNI

&nbsp;&nbsp;&nbsp;**2.b** A la hora de ordenar la lista el sistema da error porque la lista este vacía en el apartado de nombre

&nbsp;&nbsp;&nbsp;**2.c** A la hora de ordenar la lista el sistema da error porque la lista este vacía en el apartado de apellido

&nbsp;&nbsp;&nbsp;**2.d** A la hora de ordenar la lista el sistema da error porque la lista este vacía en el apartado de curso más alto
