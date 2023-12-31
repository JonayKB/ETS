<div align="justify">

# Sistema de Gestión Hospitalaria

## Ejercicio


### Descripción
El sistema de gestión hospitalaria tiene como objetivo mejorar la eficiencia y coordinación de los procesos dentro de un hospital. 
En el sistema participan distantas personas, como son: Paciente, Médico, Enfermero, Administrador del Sistema y Recepcionista. A continuación, se presentan algunos casos de uso para este sistema:

### La información que se posee de cada uno de ellos es la siguiente:
- Paciente: Un individuo que busca servicios médicos en el hospital.
- Médico: Profesional médico encargado de diagnosticar y tratar a los pacientes.
- Enfermero: Encargado de asistir a los médicos y cuidar a los pacientes.
- Administrador del Sistema: Responsable de la configuración y administración del sistema.
- Recepcionista: Encargado de la recepción de pacientes y asignación de citas.

### Las acciones que se realizarán en el sistema son las que siguen:
- El paciente se registra en el sistema proporcionando información personal y médica.
- El paciente o la recepcionista programa citas médicas para los pacientes. (Debe autenticado)
- El médico realiza diagnósticos, prescribe tratamientos y registra la información médica del paciente.(Debe autenticado)
- El médico y el enfermero pueden acceder y actualizar el historial médico del paciente.(Debe autenticado)
- El médico asigna tareas específicas a los enfermeros relacionadas con la atención del paciente.(Debe autenticado)
- El administrador del sistema realiza configuraciones y actualizaciones del sistema.(Debe autenticado)
- El personal administrativo realiza tareas relacionadas con la facturación y el procesamiento del seguro médico.(Debe autenticado)
- El administrador del sistema gestiona los recursos hospitalarios, como camas, equipos médicos y suministros.(Debe autenticado)

Como podemos observar, el sistema tiene distintos actores, casos de uso y relaciones entre ellos. Se pide realizar el diagrama de casos de uso, identificando: los actores, casos de uso y realizando la especificación.
## Diagrama
<div align = "center">
<img src= "./images/CasosDeUso1.png"/>
</div>

## Actores

|  Actor | Paciente |
|---|---|
| Descripción  | Un individuo que busca servicios médicos en el hospital  |
| Características  |  |
| Relaciones | Regristrarse en el sistema y programar una cita |
| Referencias | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md) |   
|  Notas |   |
| Autor  | JonayKB|
|Fecha | 15-11-2023 |

|  Actor | Médico |
|---|---|
| Descripción  | Profesional médico encargado de diagnosticar y tratar a los pacientes  |
| Características  |  |
| Relaciones | Realizar diagnosticos, acceder al historial médico, actualizar el historial médico, asignar tareas, prescribir tratamientos, registrar información médica y actualizar el historial médico |
| Referencias | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md) |   
|  Notas |   |
| Autor  | JonayKB|
|Fecha | 15-11-2023 |

|  Actor | Enfermero |
|---|---|
| Descripción  | Encargado de asistir a los médicos y cuidar a los pacientes  |
| Características  |  |
| Relaciones | Acceder al historial médico y realizar tareas |
| Referencias | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md) |   
|  Notas |   |
| Autor  | JonayKB|
|Fecha | 15-11-2023 |

|  Actor | Administrador |
|---|---|
| Descripción  | Responsable de la configuración y administración del sistema  |
| Características  |  |
| Relaciones | Realiza configuraciones y actualizaciones, tareas relacionadas con el seguro medico y gestiona los recursos del hospital |
| Referencias | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md) |   
|  Notas |   |
| Autor  | JonayKB|
|Fecha | 15-11-2023 |

|  Actor | Recepcionista |
|---|---|
| Descripción  | Encargado de la recepción de pacientes y asignación de citas  |
| Características  |  |
| Relaciones | Programa citas |
| Referencias | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md) |   
|  Notas |   |
| Autor  | JonayKB|
|Fecha | 15-11-2023 |

## Casos de Uso

  |  Caso de Uso    CU | 1  |
  |---|---|
  | Fuentes  | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md)  |
  | Actor  |  Paciente |
  | Descripción | Registrarse en el sistema  |
  | Flujo básico | 1- Registrarse |
  | Pre-condiciones |   |  
  | Post-condiciones  |   |  
  |  Requerimientos |  |
  |  Notas |   |
  | Autor  | JonayKB |
  |Fecha | 15-11-2023 |

  |  Caso de Uso    CU | 2  |
  |---|---|
  | Fuentes  | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md)  |
  | Actor  |  Paciente y Recepcionista |
  | Descripción | Programar Cita  |
  | Flujo básico | 1- Programar la cita |
  | Pre-condiciones | Autenticarse  |  
  | Post-condiciones  |   |  
  |  Requerimientos | Estar autenticado |
  |  Notas |   |
  | Autor  | JonayKB |
  |Fecha | 15-11-2023 |

  |  Caso de Uso    CU | 3  |
  |---|---|
  | Fuentes  | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md)  |
  | Actor  |  Médico |
  | Descripción | Realizar diagnostico  |
  | Flujo básico | 1- Realiza el diagnostico |
  | Pre-condiciones | Autenticarse  |  
  | Post-condiciones  |   |  
  |  Requerimientos | Estar autenticado |
  |  Notas |   |
  | Autor  | JonayKB |
  |Fecha | 15-11-2023 |

  |  Caso de Uso    CU | 4  |
  |---|---|
  | Fuentes  | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md)  |
  | Actor  |  Médico y enfermero |
  | Descripción | Acceder al historial medico  |
  | Flujo básico | 1- Acceder al historial medico |
  | Pre-condiciones | Autenticarse  |  
  | Post-condiciones  |   |  
  |  Requerimientos | Estar autenticado |
  |  Notas |   |
  | Autor  | JonayKB |
  |Fecha | 15-11-2023 |

  |  Caso de Uso    CU | 5  |
  |---|---|
  | Fuentes  | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md)  |
  | Actor  |  Médico  |
  | Descripción | Asignar tareas  |
  | Flujo básico | 1- Asignar tareas |
  | Pre-condiciones | Autenticarse  |  
  | Post-condiciones  |   |  
  |  Requerimientos | Estar autenticado |
  |  Notas |   |
  | Autor  | JonayKB |
  |Fecha | 15-11-2023 |

  |  Caso de Uso    CU | 6  |
  |---|---|
  | Fuentes  | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md)  |
  | Actor  |  Enfermero  |
  | Descripción | Realizar tareas  |
  | Flujo básico | 1- Realizar tareas |
  | Pre-condiciones | Autenticarse  |  
  | Post-condiciones  |   |  
  |  Requerimientos | Estar autenticado |
  |  Notas |   |
  | Autor  | JonayKB |
  |Fecha | 15-11-2023 |

  |  Caso de Uso    CU | 7  |
  |---|---|
  | Fuentes  | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md)  |
  | Actor  |  Administrador  |
  | Descripción | Realizar configuraciones  |
  | Flujo básico | 1- Realizar configuraciones |
  | Pre-condiciones | Autenticarse  |  
  | Post-condiciones  |   |  
  |  Requerimientos | Estar autenticado |
  |  Notas |   |
  | Autor  | JonayKB |
  |Fecha | 15-11-2023 |

  |  Caso de Uso    CU | 8  |
  |---|---|
  | Fuentes  | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md)  |
  | Actor  |  Administrador  |
  | Descripción | Realizar actualizaciones  |
  | Flujo básico | 1- Realizar actualizaciones |
  | Pre-condiciones | Autenticarse  |  
  | Post-condiciones  |   |  
  |  Requerimientos | Estar autenticado |
  |  Notas |   |
  | Autor  | JonayKB |
  |Fecha | 15-11-2023 |

  |  Caso de Uso    CU | 9  |
  |---|---|
  | Fuentes  | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md)  |
  | Actor  |  Administrador  |
  | Descripción | Realizar tareas del seguro medico  |
  | Flujo básico | 1- Realizar tareas del seguro medico |
  | Pre-condiciones | Autenticarse  |  
  | Post-condiciones  |   |  
  |  Requerimientos | Estar autenticado |
  |  Notas |   |
  | Autor  | JonayKB |
  |Fecha | 15-11-2023 |

  |  Caso de Uso    CU | 10  |
  |---|---|
  | Fuentes  | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md)  |
  | Actor  |  Administrador  |
  | Descripción | Gestionar recursos  |
  | Flujo básico | 1- Gestionar recursos |
  | Pre-condiciones | Autenticarse  |  
  | Post-condiciones  |   |  
  |  Requerimientos | Estar autenticado |
  |  Notas |   |
  | Autor  | JonayKB |
  |Fecha | 15-11-2023 |

  |  Caso de Uso    CU | 11  |
  |---|---|
  | Fuentes  | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md)  |
  | Actor  |  Medico  |
  | Descripción | Preescribir tratamientos  |
  | Flujo básico | 1- Preescribir tratamientos |
  | Pre-condiciones | Autenticarse  |  
  | Post-condiciones  |   |  
  |  Requerimientos | Estar autenticado |
  |  Notas |   |
  | Autor  | JonayKB |
  |Fecha | 15-11-2023 |

  |  Caso de Uso    CU | 12  |
  |---|---|
  | Fuentes  | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md)  |
  | Actor  |  Medico  |
  | Descripción | Registrar información médica  |
  | Flujo básico | 1- Registrar información médica |
  | Pre-condiciones | Autenticarse  |  
  | Post-condiciones  |   |  
  |  Requerimientos | Estar autenticado |
  |  Notas |   |
  | Autor  | JonayKB |
  |Fecha | 15-11-2023 |

  |  Caso de Uso    CU | 13  |
  |---|---|
  | Fuentes  | [Casos de uso](https://github.com/jpexposito/docencia/blob/master/Primero/ETS/DIAGRAMAS/tareas/gestion-hospitalaria.md)  |
  | Actor  |  Medico  |
  | Descripción | Actualizar historial médico  |
  | Flujo básico | 1- Actualizar historial médico |
  | Pre-condiciones | Autenticarse  |  
  | Post-condiciones  |   |  
  |  Requerimientos | Estar autenticado |
  |  Notas |   |
  | Autor  | JonayKB |
  |Fecha | 15-11-2023 |



</div>