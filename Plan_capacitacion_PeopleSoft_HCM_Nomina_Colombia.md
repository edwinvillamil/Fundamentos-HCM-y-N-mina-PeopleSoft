# Plan de capacitación

## Fundamentos funcionales de Oracle PeopleSoft HCM y Nómina -- Legislación colombiana

**Duración:** 8 horas\
**Público objetivo:** Consultores junior de soporte funcional\
**Nivel:** Básico\
**Enfoque:** Comprensión integral del proceso de administración de
personal y nómina, con capacidad para realizar diagnóstico inicial de
incidentes de primer nivel.

------------------------------------------------------------------------

## 1. Presentación

Este plan busca proporcionar a consultores junior una visión de punta a
punta del proceso de gestión de personal y liquidación de nómina en
Oracle PeopleSoft HCM, considerando los principales conceptos
funcionales de la legislación colombiana.

La capacitación se orienta a reconocer cómo los datos del trabajador,
sus movimientos laborales y las novedades de tiempo alimentan el proceso
de nómina; cómo se ejecuta y valida la liquidación; y qué verificaciones
iniciales deben realizarse cuando se presenta un incidente.

El alcance es funcional y de primer nivel. No pretende formar
especialistas en parametrización, desarrollo, interpretación jurídica o
administración técnica de la plataforma.

## 2. Objetivo general

Capacitar a los participantes para comprender el ciclo básico de
administración del empleado y procesamiento de nómina en PeopleSoft HCM,
identificar los principales componentes funcionales involucrados y
ejecutar verificaciones iniciales que permitan clasificar, documentar y
escalar incidentes.

## 3. Objetivos específicos

Al finalizar, el participante estará en capacidad de:

-   Reconocer los componentes generales de PeopleSoft HCM y su relación
    con nómina.
-   Consultar la información básica de un empleado y su historial
    laboral.
-   Comprender la importancia de las fechas efectivas, secuencias y
    registros laborales.
-   Identificar novedades que impactan la liquidación, como ausencias,
    incapacidades, vacaciones y horas extras.
-   Reconocer conceptos generales de nómina colombiana.
-   Entender las etapas de ejecución de Global Payroll y consultar
    resultados.
-   Diferenciar problemas de liquidación, contabilización y pago.
-   Aplicar una lista básica de validaciones y documentar evidencias
    para escalar incidentes.

## 4. Alcance y prerrequisitos

### Incluye

-   Visión funcional de PeopleSoft HCM y Global Payroll.
-   Administración básica del trabajador.
-   Novedades que afectan la nómina.
-   Fundamentos de nómina colombiana.
-   Ejecución y consulta de procesos y resultados.
-   Contabilización y pago desde una perspectiva funcional.
-   Diagnóstico inicial de incidentes.

### No incluye

-   Configuración detallada de elementos de Global Payroll.
-   Desarrollo PeopleCode, Application Engine, integraciones o reportes.
-   Administración de infraestructura, base de datos o seguridad.
-   Asesoría jurídica o interpretación exhaustiva de la normativa
    laboral y tributaria.
-   Resolución de casos complejos de liquidación o parametrización.

### Prerrequisitos recomendados

-   Conocimientos básicos de procesos administrativos de recursos
    humanos.
-   Familiaridad general con conceptos de nómina.
-   Acceso de consulta a un ambiente de capacitación o pruebas, si se
    realizarán ejercicios en línea.

## 5. Distribución de las 8 horas

  Sesión      Tema                                         Duración
  ----------- ------------------------------------------ ----------
  1           Contexto general de PeopleSoft HCM              0,5 h
  2           Administración del personal -- Core HR         1,25 h
  3           Novedades, tiempo y ausencias                     1 h
  4           Fundamentos de nómina colombiana               1,25 h
  5           Proceso de liquidación -- Global Payroll          2 h
  6           Contabilización, pagos y obligaciones             1 h
  7           Diagnóstico de incidentes y evaluación            1 h
  **Total**                                                 **8 h**

## 6. Desarrollo de las sesiones

### Sesión 1. Contexto general de PeopleSoft HCM --- 30 minutos

**Objetivo:** Comprender la estructura general de PeopleSoft HCM y
ubicar los módulos que intervienen en el proceso de administración de
personal y nómina.

**Temas:** - Visión general de PeopleSoft HCM. - Relación entre Recursos
Humanos, Administración de Personal y Global Payroll. - Conceptos
organizacionales: Business Unit, SetID, Company, Department, Job Code y
Position. - Identificadores del trabajador: EmplID y Empl_Rcd. -
Ambientes de trabajo: desarrollo, pruebas y producción. - Navegación,
menús, componentes, páginas y búsquedas.

**Agenda del instructor:** 1. Presentar el mapa general del proceso. 2.
Explicar los principales conceptos organizacionales. 3. Mostrar la
navegación básica y la consulta de un registro. 4. Relacionar los
módulos con las etapas del proceso.

**Ejercicio:** Ubicar en el sistema o en capturas de pantalla la
información de una persona, identificar su EmplID, Empl_Rcd, unidad de
negocio y compañía.

**Evidencia esperada:** El participante identifica los componentes
básicos y sabe dónde iniciar una consulta funcional.

### Sesión 2. Administración del personal -- Core HR --- 1 hora y 15 minutos

**Objetivo:** Entender cómo se registra y mantiene la información
laboral que sirve de base para los procesos de nómina.

**Temas:** - Datos personales y datos laborales. - Job Data e historial
de empleo. - Contratación, reingreso, terminación y movimientos. -
Acciones y motivos. - Fechas efectivas y secuencia efectiva. - Cambios
de cargo, departamento, ubicación, jornada y salario. - Diferencia entre
EmplID y Empl_Rcd; casos de múltiples registros laborales. - Impacto de
la información laboral en la nómina.

**Agenda del instructor:** 1. Explicar la estructura del registro
laboral. 2. Mostrar la consulta de Job Data. 3. Explicar fechas
efectivas y secuencia. 4. Revisar ejemplos de movimientos y su efecto en
nómina. 5. Presentar errores frecuentes de captura o vigencia.

**Ejercicio:** Analizar el historial de un empleado con los siguientes
movimientos: - 01/01/2026: ingreso con salario de \$3.000.000. -
01/04/2026: ascenso con salario de \$3.800.000. - 01/08/2026: cambio
salarial a \$4.200.000.

El participante debe identificar qué registro está vigente para una
fecha de liquidación y qué validaría si el salario no se refleja
correctamente.

**Evidencia esperada:** Reconocimiento de la fila laboral aplicable y de
la importancia de las fechas efectivas.

### Sesión 3. Novedades, tiempo y ausencias --- 1 hora

**Objetivo:** Reconocer las novedades que pueden modificar los valores
liquidados y las validaciones iniciales relacionadas con su registro y
aprobación.

**Temas:** - Concepto de novedad y su ciclo de vida. - Ausencias,
vacaciones, incapacidades y licencias. - Horas extras, recargos y
novedades de tiempo. - Fechas de inicio y fin, unidades y cantidades. -
Aprobaciones y estados de las novedades. - Integración o transferencia
de novedades hacia nómina. - Periodos de corte y oportunidad de
registro.

**Agenda del instructor:** 1. Clasificar las principales novedades. 2.
Mostrar dónde se consultan y qué datos deben revisarse. 3. Explicar el
impacto de fechas y estados. 4. Relacionar una novedad aprobada con el
periodo de nómina.

**Ejercicio:** Una incapacidad del 10 al 15 de septiembre de 2026 no se
refleja en la nómina. El participante debe proponer verificaciones sobre
fechas, estado, aprobación, trabajador y periodo de liquidación.

**Evidencia esperada:** Lista de verificaciones iniciales antes de
escalar un incidente de novedades.

### Sesión 4. Fundamentos de nómina colombiana --- 1 hora y 15 minutos

**Objetivo:** Comprender los conceptos generales de la nómina colombiana
y reconocer cómo se agrupan los conceptos que intervienen en la
liquidación.

**Temas:** - Devengados y deducciones. - Conceptos salariales y no
salariales. - Aportes del trabajador y del empleador. - Ingreso Base de
Cotización (IBC). - Seguridad social y parafiscales, desde una
perspectiva general. - Prestaciones sociales: prima, cesantías e
intereses a las cesantías. - Vacaciones. - Retención en la fuente:
nociones generales. - Salario ordinario, integral y variable. -
Importancia de vigencias, topes y reglas normativas.

**Agenda del instructor:** 1. Explicar la estructura de una liquidación.
2. Diferenciar devengados, deducciones y aportes. 3. Presentar conceptos
propios del contexto colombiano. 4. Relacionar los conceptos con las
reglas de liquidación del sistema.

**Ejercicio:** Clasificar una lista de conceptos de nómina en
devengados, deducciones, aportes del empleador y conceptos asociados a
prestaciones o bases de cálculo. Identificar cuáles requieren validación
normativa o de parametrización.

**Evidencia esperada:** El participante comprende la estructura general
de la nómina y evita asumir que todos los conceptos tienen el mismo
tratamiento.

### Sesión 5. Proceso de liquidación -- Global Payroll --- 2 horas

**Objetivo:** Entender el flujo general de ejecución de nómina en
PeopleSoft Global Payroll y realizar verificaciones básicas sobre el
procesamiento y sus resultados.

**Temas:** - Componentes funcionales de Global Payroll. - Pay Group, Pay
Entity, Pay Calendar y Pay Period. - Run Control, Process Instance y
Process Monitor. - Selección de población o payees. - Elementos de
nómina: earnings, deductions y absence elements. - Etapas generales del
procesamiento. - Resultados de liquidación y consulta por empleado. -
Errores, mensajes y advertencias. - Reprocesos, retroactividad y
recálculos: conceptos generales. - Diferencia entre proceso ejecutado,
proceso finalizado y resultado validado.

**Agenda del instructor:** 1. Explicar el calendario y la población de
nómina. 2. Mostrar cómo se identifica un proceso mediante Run Control y
Process Instance. 3. Recorrer el monitoreo de una ejecución. 4.
Consultar resultados de un empleado. 5. Revisar mensajes y errores
frecuentes. 6. Explicar cuándo un caso requiere análisis especializado.

**Ejercicio:** Se reporta que un cambio salarial y unas horas extras no
se reflejan en la liquidación. El participante debe validar: - Que el
empleado pertenezca al grupo y periodo procesados. - Que los datos
laborales estén vigentes para el periodo. - Que las novedades estén
registradas y aprobadas. - Que exista una instancia de proceso para
revisar. - Que los resultados y mensajes permitan identificar la causa
probable.

**Evidencia esperada:** El participante puede ubicar la ejecución y
recopilar evidencias básicas sin modificar configuraciones.

### Sesión 6. Contabilización, pagos y obligaciones --- 1 hora

**Objetivo:** Diferenciar la liquidación de nómina de las actividades
posteriores de contabilización, pago y cumplimiento.

**Temas:** - Resultados de nómina y comprobantes. - Procesos posteriores
a la liquidación. - Generación y validación de información contable. -
Integración con General Ledger. - Generación de archivos o interfaces de
pago. - Estados de pago y validaciones bancarias. - Obligaciones
asociadas a seguridad social y PILA. - Reportes y certificados. -
Diferencia entre nómina calculada, contabilizada y pagada.

**Agenda del instructor:** 1. Presentar el flujo posterior al cálculo.
2. Explicar los puntos de control contable. 3. Revisar el flujo general
de pagos. 4. Identificar qué equipo o módulo atiende cada tipo de
incidente.

**Ejercicio:** La nómina aparece liquidada, pero los empleados reportan
que no recibieron el pago. El participante debe diferenciar si el
incidente corresponde al cálculo, contabilización, generación del
archivo, envío bancario o confirmación del pago.

**Evidencia esperada:** Clasificación correcta de incidentes posteriores
a la liquidación.

### Sesión 7. Diagnóstico de incidentes y evaluación --- 1 hora

**Objetivo:** Aplicar un método estructurado de diagnóstico inicial,
documentar hallazgos y determinar cuándo escalar un incidente.

**Temas:** - Identificación del síntoma y alcance. - Validación del
empleado, Empl_Rcd, periodo y grupo de nómina. - Revisión de datos
laborales y novedades. - Verificación de ejecución y resultados. -
Consulta de Process Monitor, mensajes y evidencias. - Clasificación del
incidente por etapa del proceso. - Registro de pasos ejecutados y
resultado. - Criterios de escalamiento funcional, técnico o de
integración.

**Agenda del instructor:** 1. Presentar una plantilla de diagnóstico. 2.
Resolver un caso guiado. 3. Asignar escenarios breves a los
participantes. 4. Revisar respuestas y criterios de escalamiento. 5.
Aplicar evaluación de conocimientos y práctica.

**Ejercicio integrador:** Analizar uno o varios de estos escenarios: -
Un empleado no aparece en la nómina. - Un cambio salarial no se
refleja. - Una incapacidad no afecta la liquidación. - El proceso
presenta error o queda incompleto. - La nómina está liquidada, pero no
pagada.

**Evidencia esperada:** Registro de diagnóstico con síntoma, alcance,
validaciones, hallazgos, evidencias y recomendación de escalamiento.

## 7. Método básico para el diagnóstico de incidentes

Se recomienda que el consultor junior siga este orden:

1.  **Precisar el síntoma:** qué esperaba el usuario y qué ocurrió
    realmente.
2.  **Determinar el alcance:** una persona, varios empleados, un grupo o
    toda la nómina.
3.  **Identificar el contexto:** EmplID, Empl_Rcd, compañía, grupo,
    periodo y fecha de pago.
4.  **Validar los datos de origen:** Job Data, fechas efectivas, salario
    y novedades.
5.  **Ubicar la etapa del proceso:** captura, aprobación, cálculo,
    contabilización, pago o interfaz.
6.  **Consultar la ejecución:** Process Instance, estado, mensajes y
    resultados.
7.  **Documentar evidencias:** consultas, capturas, identificadores de
    proceso y mensajes completos.
8.  **Escalar con contexto:** describir lo validado, el resultado y la
    pregunta concreta para el siguiente nivel.

El consultor junior no debe corregir datos productivos, alterar
resultados, ejecutar reprocesos ni modificar reglas de nómina sin
autorización y procedimiento establecido.

## 8. Evaluación de aprendizaje

### 8.1 Evaluación de conocimientos

Preguntas sugeridas:

1.  ¿Qué diferencia existe entre EmplID y Empl_Rcd?
2.  ¿Por qué son importantes las fechas efectivas en Job Data?
3.  ¿Qué información debe revisarse cuando un cambio salarial no se
    refleja?
4.  ¿Qué diferencia existe entre una novedad registrada y una novedad
    aprobada?
5.  ¿Qué representa el Pay Group?
6.  ¿Para qué se utiliza Process Monitor?
7.  ¿Qué información permite identificar una Process Instance?
8.  ¿Qué diferencia existe entre devengado y deducción?
9.  ¿Qué diferencia hay entre nómina liquidada y nómina pagada?
10. ¿Qué evidencias mínimas deben acompañar un escalamiento?

**Criterio de calificación sugerido:** 10 preguntas, 4 puntos por
respuesta correcta; total 40 puntos.

### 8.2 Evaluación práctica

El participante recibe un escenario y debe documentar: - Síntoma
reportado. - Empleado, Empl_Rcd y periodo afectados. - Etapa del proceso
posiblemente involucrada. - Validaciones realizadas. - Hallazgos y
evidencias. - Causa probable, si puede establecerse. - Recomendación y
nivel al que debe escalarse.

**Criterio de calificación sugerido:** 60 puntos distribuidos entre
comprensión del escenario, orden de validación, interpretación de
evidencias, documentación y decisión de escalamiento.

### 8.3 Aprobación

-   Conocimientos: 40%.
-   Ejercicio práctico: 60%.
-   Nota mínima sugerida: 70/100.

## 9. Plantilla para documentar incidentes

  -----------------------------------------------------------------------
  Campo                               Información que debe registrarse
  ----------------------------------- -----------------------------------
  Número de caso                      Identificador del incidente

  Fecha y reportante                  Fecha de reporte y usuario que
                                      informa

  Síntoma                             Descripción concreta del
                                      comportamiento

  Alcance                             Empleado, grupo, periodo o
                                      población afectada

  Identificadores                     EmplID, Empl_Rcd, compañía y unidad
                                      de negocio

  Periodo de nómina                   Pay Group, calendario y periodo

  Etapa del proceso                   Datos laborales, novedad, cálculo,
                                      contabilidad o pago

  Validaciones                        Consultas y pasos ejecutados

  Evidencias                          Capturas, mensajes, Process
                                      Instance y resultados

  Hallazgos                           Hechos comprobados

  Escalamiento                        Equipo o nivel sugerido y motivo
  -----------------------------------------------------------------------

## 10. Materiales y recursos requeridos

-   Presentación del instructor.
-   Guía del participante con conceptos y rutas de consulta.
-   Ambiente de capacitación o pruebas, preferiblemente con datos
    controlados.
-   Casos de práctica y sus soluciones.
-   Accesos de consulta suficientes para revisar empleados, novedades y
    resultados.
-   Plantilla para documentación de incidentes.

Si no se dispone de ambiente, los ejercicios podrán realizarse mediante
capturas, consultas previamente preparadas y casos simulados.

## 11. Resultados esperados

Al terminar las ocho horas, el consultor junior deberá poder: - Explicar
el flujo general desde la administración del empleado hasta el pago de
nómina. - Ubicar información laboral relevante. - Reconocer novedades
que impactan la liquidación. - Comprender los conceptos esenciales de
nómina colombiana. - Consultar el estado de una ejecución de Global
Payroll y sus resultados. - Diferenciar incidentes de cálculo de
incidentes posteriores. - Documentar y escalar incidentes de primer
nivel con evidencias.

## 12. Consideraciones

La capacitación utiliza conceptos generales de la legislación
colombiana. Los porcentajes, topes, bases, tratamientos y reglas deben
validarse contra la normativa vigente y la parametrización específica de
la organización. La operación de PeopleSoft puede variar según la
versión, localización, configuración y desarrollos implementados por
cada cliente.

------------------------------------------------------------------------

**Duración total:** 8 horas\
**Resultado del curso:** consultor junior con fundamentos funcionales
para comprender el proceso y realizar diagnóstico inicial de incidentes
de PeopleSoft HCM y Nómina Colombia.
