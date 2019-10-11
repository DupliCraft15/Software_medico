# MODIFICACIÓN DE LOS DATOS DE UN USUARIO
---
**ID :** 03 **Descripción :**  Una vez encontrado el usuario a partir de la función búsqueda, el sistema pide por teclado el dato a modificar, así como su contenido.

**Actores principales :** Secretario  **Actores secundarios :** Paciente

**Precondiciones :**
   * Se necesita haber llamado a la función búsqueda

**Flujo principal :**

1. El Secretario desea modificar los datos de un paciente
2. El Secretrario realiza la búsqueda del paciente
3. El Secretario abre la opción de modificación de los datos del paciente
4. El Sistema hace elegir al Secretario el/los datos a modificar
5. El Secretario introduce el/los datos a modificar
6. El Sistema muestra por pantalla los datos modificados

**Postcondiciones**
   * Se muestran al Secretario las diferentes opciones relativas al paciente

**Flujos alternativos**

   a. Si el/los datos no es/son válido/s el sistema muestra un mensaje de error;

---

# BORRADO DE LOS DATOS DE UN USUARIO
---
**ID :** 05 **Descripción :**  Una vez encontrado el usuario a partir de la función búsqueda, el sistema pide confirmación para el borrado de los datos del mismo.

**Actores principales :** Secretario  **Actores secundarios :** Paciente

**Precondiciones :**
   * Se necesita haber llamado a la función búsqueda

**Flujo principal :**

1. El Secretario desea borrar los datos de un paciente
2. El Secretrario realiza la búsqueda del paciente
3. El Secretario abre la opción de borrado del paciente
4. El Sistema pide confirmación del inminente borrado
5. El Secretario confirma el borrado
6. El Sistema muestra por pantalla un mensaje donde se confirma que el borrado se ha realizado correctamente

**Postcondiciones**
   * Se muestran al Secretario las diferentes opciones relativas al paciente

**Flujos alternativos**

   a. Si el borrado no se produce correctamete el Sistema manda un mensaje de error;


---

# AÑADIR CITA
---
**ID :** 06 **Descripción :**  Se pide por teclado la fecha, hora, nombre y DNI del paciente para la creacion de una nueva cita en la agenda

**Actores principales :** Secretario  **Actores secundarios :** Paciente

**Precondiciones :**
   * Se necesita haber entrado en las opciones de la agenda

**Flujo principal :**

1. El Secretario desea añadir una cita a la agenda
2. El Secretrario selecciona "AÑADIR CITA" entre las opciones de la agenda
3. El Sistema pide por teclado la fecha, hora y nombre del paciente así como su DNI
4. El Sistema pide confirmación para la creación de dicha cita
5. El Sistema muestra un mensaje indicando el éxito o fracaso al añadir la cita en la agenda

**Postcondiciones**
   * Se muestran al Secretario las diferentes opciones de la agenda

**Flujos alternativos**

   a. Si la fecha hora o DNI no son correctos el sistema mostrará un mansaje de error;


---

# CANCELAR CITA
---
**ID :** 07 **Descripción :**  Tras la seleccion de una cita en el listado de la agenda, se pide confirmación para su consiguiente eliminación

**Actores principales :** Secretario  **Actores secundarios :** Paciente

**Precondiciones :**
   * Se necesita haber entrado en las opciones de la agenda

**Flujo principal :**

1. El Secretario desea cancelar la cita de un paciente
2. El Secretrario selecciona "CANCELAR CITA" entre las opciones de la agenda
3. El Sistema muestra un listado con las citas creadas
4. El Secretario selecciona la cita a cancelar
5. El Sistema pide confirmación de la consiguiente cancelación de la cita


**Postcondiciones**
   * Se muestran al Secretario las diferentes opciones de la agenda

**Flujos alternativos**

   a. Si la cita ya ha ocurrido en el tiempo, o no es posible su cancelación se muestra un mensaje de error;


---

# CONSULTAR HISTORIAL MÉDICO
---
**ID :** 08 **Descripción :**  Tras la busqueda por DNI de un paciente se muestra su historial médico

**Actores principales :** Secretario  **Actores secundarios :** Paciente

**Precondiciones :**
   * Se necesita haber entrado en las opciones del Paciente, asi como la existencia del paciente

**Flujo principal :**

1. El Secretario debe haber realizado la búsqueda del paciente por DNI
2. El Secretrario selecciona "CONSULTAR HISTORIAL" entre las opciones del Paciente
3. El Sistema muestra un listado con el historial médico del paciente



**Postcondiciones**
   * Se necesita haber buscado al paciente y haber mostrado al Secretario las diferentes opciones del Paciente

**Flujos alternativos**

   a. Si el DNI es erróneo (num de dígitos no correcto u otro fallo del tipo) mostrará un mensaje de error, así mismo si no existe historial del paciente el sistema mostrará un mensaje diciendo que el paciente no ha sido añadido o no tiene historial médico todavía;


---


# CONSULTAR TRATAMIENTO MÉDICO
---
**ID :** 08 **Descripción :**  Tras la busqueda por DNI de un paciente se muestra su tratamiento

**Actores principales :** Secretario  **Actores secundarios :** Paciente

**Precondiciones :**
   * Se necesita haber entrado en las opciones del Paciente, asi como la existencia del paciente

**Flujo principal :**

1. El Secretario debe haber realizado la búsqueda del paciente por DNI
2. El Secretrario selecciona "CONSULTAR TRATAMIENTO" entre las opciones del Paciente
3. El Sistema muestra un listado con el tratamiento médico del paciente



**Postcondiciones**
   * Se necesita haber buscado al paciente y haber mostrado al Secretario las diferentes opciones del Paciente

**Flujos alternativos**

   a. Si el DNI es erróneo (num de dígitos no correcto u otro fallo del tipo) mostrará un mensaje de error, así mismo si no existe tratamiento del paciente el sistema mostrará un mensaje diciendo que el paciente no ha sido añadido o no tiene tratamiento médico todavía;







