# 🗒️ Registro de Trabajo en Clase - Taller X

## 📆 Fecha de la sesión
10/04

## 👥 Integrantes presentes
- Valentina Alejandra López Romero
- Mariana Valle Moreno
- Laura Camila Rodriguez Leon

## 🧠 Actividades realizadas en clase

Durante la sesión trabajamos en el análisis del caso GobData, que es un portal del gobierno para hacer trámites en línea. La idea principal era identificar qué normas aplican y empezar a armar un checklist para el manejo de datos sensibles. También revisamos normas de sectores como salud, educación y gobierno digital, además de leyes de protección de datos y algunas referencias como ISO 27001 y lineamientos de entidades como MinSalud, MinTIC, SuperSalud y la SFC.

En general, se avanzó bastante en la construcción del checklist. Se organizó la información y empezamos a definir criterios de cumplimiento, niveles y evidencia con base en las normas que encontramos. Esto nos dejó una buena base para seguir trabajando fuera de clase, donde vamos a completar las brechas, hallazgos y mejorar las recomendaciones.

- ¿Qué se discutió con el equipo?
Hablamos principalmente de cuáles normas eran más importantes para este caso y cómo organizarlas dentro del checklist. Coincidimos en que no era solo listar cosas, sino conectar cada criterio con algo normativo, por ejemplo: ISO 27001 para controles de seguridad, Ley 1581 para temas de datos personales y GDPR para reforzar temas como consentimiento y derechos del titular.

También definimos trabajar sobre varias categorías clave como trazabilidad, autenticación, clasificación de datos, consentimiento, derechos ARCO y retención. La idea fue que cada una tuviera su criterio claro, su nivel (si cumple o no) y una justificación coherente. Además, dejamos claro cómo íbamos a registrar las recomendaciones para que no fueran genéricas sino aplicables al caso.

- ¿Qué decisiones de modelado se tomaron?
Decidimos estructurar todo como un checklist, donde cada fila representa un criterio de cumplimiento ligado a una norma específica. No queríamos algo solo descriptivo, sino que realmente sirviera para evaluar si GobData cumple o no. También acordamos que cada evaluación debía tener una justificación basada en el contexto (tipo de datos, uso de la plataforma, etc.) y que las recomendaciones debían apuntar directamente a cerrar esto. Básicamente, que sirviera tanto para analizar como para proponer mejoras.

- ¿Qué herramientas se usaron (papel, pizarra, draw.io, Astah)?
Trabajamos principalmente en Excel, porque era lo más práctico para organizar todo el checklist. Ahí pudimos estructurar las columnas, ir llenando la información y dejar espacio para completar después. Además, permitió que todos trabajáramos al mismo tiempo sin complicarnos con herramientas más pesadas.

- ¿Qué parte del trabajo se alcanzó a desarrollar?
Durante la clase logramos armar la base del checklist y hacer una primera evaluación de varias categorías, asignando niveles de cumplimiento, justificando cada caso y proponiendo recomendaciones iniciales. También dejamos definida la forma en la que vamos a seguir trabajando fuera de clase, sobre todo para completar las cosas, ajustar mejor las recomendaciones y terminar de amarrar todo con las normas correspondientes.

## 🧩 Boceto inicial del modelo

| N° | Categoría                   | Criterio de Cumplimiento                                                            | Nivel de Cumplimiento (✅ / ⚠️ / ❌) | Evidencia / Justificación                                                                                                                                         | Recomendación                                                                                                                                     |
| -- | --------------------------- | ----------------------------------------------------------------------------------- | ---------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1  | Trazabilidad Operativa      | Existencia de mecanismos de trazabilidad y acceso a registros por parte del titular | ❌                                  | No se ofrecen herramientas que permitan al ciudadano visualizar los accesos realizados a su información, lo que reduce la transparencia del tratamiento de datos. | Incorporar un registro de accesos accesible al titular que permita monitorear el uso de su información y fortalezca la confianza.                 |
| 2  | Autenticación               | Implementación de controles robustos de autenticación                               | ❌                                  | Se evidencia el uso de autenticación básica sin factores adicionales que validen de manera sólida la identidad del usuario.                                       | Adoptar autenticación multifactor y aplicar el principio de privilegios mínimos para reducir accesos indebidos.                                   |
| 3  | Clasificación de Datos      | Clasificación adecuada de la información según su nivel de sensibilidad             | ⚠️                                 | No existe una segmentación clara de los datos, lo que implica que la información sensible no recibe un tratamiento diferenciado.                                  | Establecer un modelo de clasificación que diferencie entre datos públicos, personales y sensibles, con controles específicos para cada categoría. |
| 4  | Consentimiento Informado    | Gestión de consentimiento informado, específico y verificable                       | ❌                                  | No se identifican mecanismos que permitan recolectar y evidenciar el consentimiento por finalidad o servicio.                                                     | Implementar un sistema de consentimiento detallado, previo y auditable, alineado con cada finalidad del tratamiento.                              |
| 5  | Derechos del Titular (ARCO) | Disponibilidad de canales para el ejercicio de derechos del titular (ARCO)          | ⚠️                                 | No se cuenta con un canal unificado que facilite a los usuarios ejercer sus derechos sobre sus datos personales.                                                  | Desarrollar una plataforma centralizada que permita gestionar los derechos ARCO con seguimiento y trazabilidad.                                   |
| 6  | Retención y Supresión       | Definición de políticas de retención y eliminación de datos                         | ❌                                  | No se observan lineamientos claros sobre tiempos de conservación ni procesos periódicos de depuración de la información.                                          | Definir políticas de retención según el tipo de dato e implementar procesos automáticos de eliminación o anonimización.                           |

## 🔁 Tareas definidas para complementar el taller

Anote las responsabilidades acordadas entre los miembros del equipo para completar la entrega final:

| Tarea asignada | Responsable | Fecha estimada |
|----------------|-------------|----------------|
| Modelado final excel | Camila Rodriguez | 10/04 |
| Actividad fuera de clase     | Mariana Valle | 10/04 |
| Investigación y referencias | Valentina López | 10/04 |

---

_Este documento resume el trabajo colaborativo realizado durante la sesión del taller X en el curso AREM - Universidad de La Sabana._
