## Semana 6 - Implementar la creación de recursos

### Objetivos

---

El objetivo de esta actividad es:

- Implementar los componentes relacionados con las historias de usuario de crear recursos.

### Pasos previos

---

- Haber terminado la implementación de las historias de usuario de la iteración 1.

### Descripción actividad

---

#### ![](./../../assets/images/individuo.png) Actividad individual

Cada integrante selecciona dos historias de usuario de la iteración 2 para ser implementadas. Para esto, por cada HU debe: 

- Crear en el servicio del módulo del recurso la función que permite llamar al API REST para crear un recurso.
- Verificar que exista la prueba para el servicio.
- Probar el servicio del paso anterior.
- Elaborar el componente de crear el recurso correspondiente siguiendo las convenciones de nombramiento.
- Crear la vista del componente (formulario) de acuerdo con el prototipo.
- Invocar el servicio de creación.
- Verificar que la aplicación funciona correctamente
- Realizar commit y solicitar un pull request.

### Recursos

---

- Tutorial crear un formulario: https://misovirtual.virtual.uniandes.edu.co/codelabs/angular-create-simple/index.html#0.

### Entregables

---

- Repositorio de Github actualizado.

### Criterios de evaluación

---

- Cumple con la arquitectura propuesta: módulo, método del servicio, prueba del método del servicio, componente crear y prueba del componente.
- El formulario para la creación de recursos se visualiza correctamente.
- Cuando se ingresan los datos se validan antes de enviar.
- Se muestra un mensaje descriptivo de los errores del formulario.
- Si los datos son correctos y se da clic en el botón agregar se muestra un mensaje de confirmación.
- Cuando se regresa al listado de recursos, el nuevo recurso asignado se muestra correctamente.
