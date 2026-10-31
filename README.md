# VetSync 1.0
# Sistema de gestión de clínica veterinaria

**Universidad Tecnológica Nacional  **
**Tecnicatura Universitaria en Programación a Distancia  **
## **Cátedra:** Organización Empresarial  
## **Integrante:** Medina Facundo  
## **Legajo:** 104614  
## **Año:** 2026  

## **Descripción del proyecto**  
Este proyecto tiene como objetivo el desarrollo de una "Plataforma veterinaria asistencial digital", enfocada en la virtualización e integración modular del negocio (turnos, historias clínicas, facturación e inventario) con el objetivo de agilizar la atención y la gestión general, mejorando la
experiencia de los usuarios finales (propietario, médicos veterinarios, auxiliares, administrativos y propietarios/tutores de mascotas).  
Siendo un sistema que organiza y automatiza tareas, mientras que asiste en otras, tanto al equipo de trabajo de la clínica veterinaria, como a los clientes.  
Brindando soporte estratégico a una organización con el formato característico de las pequeñas y medianas empresas, de poco personal que cumplen diversos roles y funciones por nivel jerárquico.  

## Estructura del repositorio
**/diagrams** Contiene archivo fuente .xml del diagrama BPMN 2.0 del sistema (Macroproceso y microproceso de consulta médica). Presentando también sus exportaciones en formato de imagen *.png
**/docs** Contiene las cuatro presentaciones del Proyecto Integrador (TPI), que documentan el recorrido realizado para el desarrollo del proyecto, como su análisis funcional y arquitectura del sistema.

## Enlaces
### Gestión del Backlog Ágil (Jira Software) 
[Link al Tablero Kanban (VetSync 1.0)](https://profesormedinafacundo.atlassian.net/jira/software/projects/TPIO/boards/2?filter=&groupBy=none&atlOrigin=eyJpIjoiY2FlMGNhMDA0NDM3NGE2OWE4YTg3MTNhYThjNGQ5YzQiLCJwIjoiaiJ9)
**Nota de acceso:** El proyecto está configurado con **acceso abierto** en Jira Cloud. En caso de que la plataforma solicite inicio de sesión o permisos de lectura para visualizar las tarjetas, solicitar acceso al correo: [profesormedinafacundo@gmail.com].

### Repositorio Público en GitHub:
[profesormedinafacundo/proyectOE](https://github.com/profesormedinafacundo/proyectOE)
(Contiene el historial de commits, flujo de ramas, Pull Requests y archivos del proyecto VetSync 1.0).\*

## Mecanismos e Indicadores de Control
**1. Control de Inventario:** Alerta automática visual cuando la cantidad disponible de medicamentos o insumos alcanza el punto reorden para reavastecerse.
**2. Validación de Agenda:** Restricción en base de datos para evitar la superposición de turnos asistenciales en el mismo horario y profesional.
**3. Trazabilidad Clínica:** Firma digital y registro de id veterinario y timestamp automático en cada actualización de la Historia Clínica Digital.
**4. Control de Autorización:** Autenticación por credenciales individuales (Usuario/Contraseña) para garantizar que cada rol acceda únicamente a los módulos autorizados (ejemplos: la Auxiliar no modifica diagnósticos médicos; el Veterinario no altera precios ni comprobantes de cobro)
**5. Auditoría de Operaciones:** Registro de *logs* internos para auditar qué usuario ejecutó la creación de un paciente, la modificación de un turno o la emisión de un comprobante.

## Declaración jurada de uso de IA
Para el desarrollo del proyecto se realizó un trabajo de exploración inicial con **Gemini IA**, sobre casos en donde la implementación de un sistema informatizado, pueda transformar la dinámica del negocio.  
El resultado de dicha búsqueda, fue la selección de una pequeña y mediana empresa, de las que se caracterizan por tener poco personal y no disponer de sistemas elaborados para desarrollar sus actividades.  
Una vez seleccionado el caso de estudio, en distintas etapas de investigación, se procedió a realizar un análisis (también con Gemini IA) de emprendimientos de similares características, para poder obtener elementos y herramientas potencialmente útiles para ser integrados al sistema.  
En aquellos segmentos del proyecto, donde era necesario incorporar aspectos técnicos o enriquecer la narrativa terminológica, incorporando vocaburario técnico y académico, e incluso correcciones gramaticales, se sometió a revisión los documentos preliminares con **Notebook Gemini**. Obteniendo así nuevas versiones, de las que se extraían sugerencias, modificaciones y agregados, así como también se descartaron otras. Completando así un doble filtrado de las presentaciones, uno con IA y otro manual.  


