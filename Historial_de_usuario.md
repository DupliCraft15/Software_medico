**ID**:04 **Nombre**:Añadir nuevo usuario

**Prioridad** *(de 1 a 10)*: 8 **Puntos estimado**: 6 **Iteracion**: 1

**Responsable**: *Sergey Beryuza*

**Descripción**

  *Como administrador quiero añadir un nuevo paciente, con todos los datos que este tiene, a la base de datos de todos los pacientes*  

**Validación**

	* Se tiene que rellenar todos los campos para añadir un paciente.
	* Se debe siempre poder añadir un paciente siempre y cuando se cumpla la anterior validación.
	* La opcion añadir usuario debe de devolverte al menú cuando finalize.

---
---

**ID**:99 **Nombre**:Buscar cita

**Prioridad** *(de 1 a 10)*: 6 **Puntos estimado**: 4 **Iteracion**: 1

**Responsable**: *Sergey Beryuza*

**Descripción**

  *Como administrador quiero ver las citas que he tenido o voy a tener de cada paciente o de la fecha introducida*  

**Validación**

	* Siempre se debe mostrar la opcion de busquedad por nombre o por fecha.
	* Si el nombre o la fecha no existe, el programa tiene que decir el error y salirse.
	* Se tiene que mostrar todos los datos de la cita.
	* La opcion buscar cita debe de devolverte al menú cuando finalize.

---
---

**ID**:07 **Nombre**:Cancelar cita

**Prioridad** *(de 1 a 10)*: 6 **Puntos estimado**: 2 **Iteracion**: 1

**Responsable**: *Sergey Beryuza*

**Descripción**

  *Como administrador quiero cancelar una cita que se encuentra programada en la base de datos de citas*  

**Validación**

	* Si el administrador intenta entrar en cancelar cita y no hay citas para el futuro, el programa debe de decirlo y salir.
	* No se debe de poder cancelar citas que ya han sido realizadas.
	* Una vez eliminada, no debe de quedar rastro de esta en la base de datos de citas.
	* La opcion cancelar cita debe de devolverte al menú cuando finalize.

---
---

**ID**:08 **Nombre**:Consultar Historial Medico.

**Prioridad** *(de 1 a 10)*: 8 **Puntos estimado**: 8 **Iteracion**: 1

**Responsable**: *Sergey Beryuza*

**Descripción**

  *Como administrador quiero consultar el historial de cada paciente introduciendo el DNI en el cual se muestre todos los datos acerca de dicha persona*  

**Validación**

	* El DNI introducido debe de corresponder a un paciente registrado anteriormente.
	* Si el DNI es erroneo, el programa se lo comunica al administrador y se sale.
	* Debe de aparecer todos los datos acerca del paciente.
	* La opcion Consultar Historial Medico debe de devolverte al menú cuando finalize.
