# Informe Técnico del Taller

## Nombre del Taller
_Taller 6 - Checklist de Cumplimiento Normativo_

## Integrantes del equipo
| Nombre | Correo Electrónico |
|---|---|
| Valentina Alejandra López Romero | valentinalopro@unisabana.edu.co |
| Mariana Valle Moreno | marianavamo@unisabana.edu.co |
| Laura Camila Rodriguez Leon | laurarodleo@unisabana.edu.co |  

## Descripción general del trabajo
El objetivo del taller fue evaluar el nivel de cumplimiento normativo del sistema del cliente, utilizando un checklist basado en marcos como ISO 27001, GDPR, Habeas Data y la Ley 1581 de Protección de Datos en Colombia.

El análisis se aplicó al sistema de logística de aplicación de encuestas institucionales de la Universidad de La Sabana, el cual soporta la planeación, coordinación y ejecución del proceso de recolección de información académica para fines de autoevaluación y acreditación. Este sistema involucra el manejo de datos personales de estudiantes y profesores, así como información académica relacionada con materias, horarios y salones.

Actualmente, el proceso se apoya en herramientas manuales como archivos Excel y en la interacción con un proveedor externo encargado de la recolección y anonimización de las respuestas. Esto implica flujos de información distribuidos, múltiples actores involucrados y ausencia de una base de datos centralizada. A partir de este contexto, se evaluaron los controles existentes frente a los marcos normativos anteriormente mencionados.

Como resultado, se determinaron las principales brechas de cumplimiento y los riesgos asociados al manejo actual de la información, especialmente en términos de seguridad, integridad, confidencialidad y cumplimiento legal, evidenciando oportunidades de mejora en la estructuración del proceso y el uso de herramientas tecnológicas disponibles en la organización.

## Proceso de desarrollo
El trabajo se desarrolló en tres etapas principales:

1. **Comprensión del sistema del cliente**: Se analizó el proceso actual de aplicación de encuestas, identificando actores, flujos de información y herramientas utilizadas.
2. **Aplicación del checklist normativo**: Se evaluaron los criterios de cumplimiento en categorías como protección de datos, seguridad de la información, gestión de datos y gobierno. Para cada criterio se determinó si el sistema cumple, presenta brechas o no cumple.
3. **Identificación de brechas y riesgos**: Se consolidaron las principales brechas, asociándolas con riesgos operativos y legales, y se definieron recomendaciones priorizadas para su mitigación.

Durante el desarrollo se utilizaron herramientas como Excel para estructurar el checklist.

## Análisis del modelo propuesto
### Estructura del modelo
El modelo se estructuró en cuatro dimensiones: protección de datos personales, seguridad de la información, gestión de datos y gobierno y roles. Para cada una se evaluaron criterios de cumplimiento, evidencia del sistema actual y acciones recomendadas, alineadas con ISO 27001, GDPR y la Ley 1581.

### Representación de las necesidades del cliente
El modelo responde directamente a las necesidades del cliente al enfocarse en los principales riesgos del proceso: manejo manual en Excel, falta de estandarización, ausencia de controles de acceso y trazabilidad, y dependencia de un proveedor externo. Estos aspectos impactan la confidencialidad, integridad y control de la información en la aplicación de encuestas.

### Supuestos tomados
- El sistema maneja datos personales de estudiantes y profesores.
- La operación se basa principalmente en el uso de Excel.
- No existe una base de datos centralizada ni automatización del proceso.

## Diagrama final entregado
> En esta sesión no se realizó un diagrama visual formal, pero se estructuró de manera conceptual el modelo de cumplimiento normativo del sistema, identificando las dimensiones clave: protección de datos personales, seguridad de la información, gestión de datos y gobierno y roles, así como sus principales controles y brechas asociadas.

📊 Tabla de checklist y análisis de brechas: [tabla_checklist.xlsx](./tabla_checklist.xlsx)

## Investigación Complementaria

### Tema investigado: Marcos normativos de cumplimiento en protección de datos: ISO 27001, GDPR y Ley 1581

---

El cumplimiento normativo en sistemas que manejan datos personales exige evaluar los controles existentes frente a estándares internacionales y leyes locales. Este proceso —conocido como *compliance*— permite identificar brechas, reducir riesgos legales y demostrar responsabilidad ante las partes interesadas. Para sistemas como el analizado en este taller, que gestiona información sensible de estudiantes y profesores en un contexto de acreditación universitaria, esta evaluación resulta especialmente crítica [1].

---

### ISO/IEC 27001: Gestión de la seguridad de la información

La norma **ISO/IEC 27001** es el estándar internacional de referencia para implementar un Sistema de Gestión de Seguridad de la Información (SGSI). Establece un ciclo de mejora continua basado en la identificación de riesgos, la aplicación de controles técnicos y organizativos, y la auditoría periódica del sistema [2].

Su **Anexo A** define controles concretos aplicables a casos como el analizado:

- Gestión de accesos por roles (*need-to-know*)
- Cifrado de datos en tránsito y en reposo
- Registro y monitoreo de actividades
- Gestión de proveedores y terceros

En Colombia, el MinTIC ha promovido la adopción de ISO 27001 como base del **Modelo de Seguridad y Privacidad de la Información (MSPI)**, adoptado por múltiples universidades públicas en sus planes de seguridad institucional [3].

---

### Ley 1581 de 2012 y el derecho al Habeas Data

En Colombia, el marco legal central para la protección de datos personales es la **Ley Estatutaria 1581 de 2012**, reglamentada por el Decreto 1377 de 2013. Esta ley reconoce el derecho constitucional de *habeas data*: toda persona puede conocer, actualizar y rectificar la información que sobre ella se haya recopilado en bases de datos públicas o privadas [4].

La ley define principios rectores del tratamiento de datos entre los que destacan:

- **Finalidad**: los datos solo pueden usarse para el propósito informado al titular.
- **Veracidad**: la información debe ser exacta y actualizada.
- **Acceso y circulación restringida**: solo personas autorizadas pueden acceder a los datos.
- **Seguridad**: se deben adoptar medidas técnicas y humanas para proteger la información.

El incumplimiento de estas obligaciones expone a la organización a sanciones administrativas por parte de la **Superintendencia de Industria y Comercio (SIC)**, entidad de control en Colombia [4].

---

### GDPR como referente internacional

El **Reglamento General de Protección de Datos (GDPR)** de la Unión Europea, aunque no es directamente aplicable en Colombia, es reconocido como el referente más completo a nivel mundial en materia de protección de datos. Sus principios de **privacidad por diseño**, **minimización de datos** y ***accountability*** (responsabilidad demostrable) complementan y refuerzan los requisitos de la Ley 1581 [5].

Entre sus exigencias más relevantes para este contexto se encuentran:

- Llevar un **Registro de Actividades de Tratamiento (RoPA)**
- Suscribir acuerdos formales de tratamiento con proveedores externos (*Data Processing Agreements*)
- Notificar brechas de seguridad en un plazo máximo de 72 horas

---

### Conclusiones

La evaluación de cumplimiento normativo no es un ejercicio puntual, sino un proceso continuo que exige que las organizaciones alineen sus controles técnicos, administrativos y legales con los marcos vigentes. En el caso del sistema analizado, la ausencia de una base de datos centralizada, la falta de acuerdos formales con el proveedor externo y el uso de Excel sin controles de acceso representan brechas directas frente a ISO 27001 y la Ley 1581. La aplicación conjunta de estos tres marcos —ISO 27001, Ley 1581 y las buenas prácticas del GDPR— ofrece una hoja de ruta integral para cerrar dichas brechas, proteger los datos de los titulares y garantizar la trazabilidad del proceso ante organismos de acreditación como el CNA [1][2][4][5].

---

## Referencias

- [1] MinTIC Colombia. *Modelo de Seguridad y Privacidad de la Información (MSPI)*. Gobierno Digital Colombia. https://www.mintic.gov.co
- [2] ISO/IEC 27001:2022. *Information security management systems — Requirements*. International Organization for Standardization.
- [3] Universidad Industrial de Santander. *Plan de Seguridad y Privacidad de la Información 2026*. https://documentos.uis.edu.co
- [4] Congreso de Colombia. *Ley Estatutaria 1581 de 2012 — Protección de Datos Personales*. http://www.secretariasenado.gov.co/senado/basedoc/ley_1581_2012.html
- [5] Regulation (EU) 2016/679. *General Data Protection Regulation (GDPR)*. European Parliament and Council, 2016.
_Este documento hace parte de la entrega del taller 6 del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._
