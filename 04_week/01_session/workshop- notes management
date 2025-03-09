# 📘 Sistema de Gestión de Citas en la Clínica

## 📌 Resumen Ejecutivo

Este documento presenta el diseño e implementación de un sistema de gestión de citas médicas, con el objetivo de optimizar la organización y la atención en la clínica. Se describen los problemas del sistema actual, los requerimientos funcionales necesarios para una solución automatizada y las entidades clave involucradas en el proceso.

---

## 🔎 Requerimientos Funcionales (RF)

### *RF1: Registro de Datos Básicos de los Usuarios*
*Descripción:* Se requiere registrar los datos básicos de los futuros usuarios del sistema. Los datos incluyen:
- Nombre
- Fecha de nacimiento
- Correo electrónico
- Tipo de documento
- Número de documento
- Teléfono

*Flujo:*
1. Ingresar al formulario Registro de Personas.
2. Diligenciar los datos solicitados.
3. Confirmar el registro.

*Precondiciones:*
- El usuario administrador debe estar autenticado.

*Postcondiciones:*
- El sistema debe verificar que la persona no esté previamente registrada.

*RF Ref:* N/A

### *RF2: Registro de Historia Clínica de los Pacientes*
*Descripción:* Se requiere registrar la historia clínica de los pacientes en el sistema, vinculándola a su registro de persona (RF1).

*Campos de entrada:*
- Historia clínica

*Flujo:*
1. Ingresar al formulario Registro de Historia Clínica.
2. Diligenciar la historia clínica del paciente.
3. Confirmar el registro.

*Precondiciones:*
- El usuario administrador debe estar autenticado.
- El paciente debe estar registrado en el sistema (RF1).

*Postcondiciones:*
- La historia clínica queda asociada al paciente registrado.

*RF Ref:* RF1

### *RF3: Gestión de Citas Médicas*
*Descripción:* Permitir la asignación, modificación y cancelación de citas a través del sistema.

*Flujo:*
1. Escoger el servicio médico.
2. Seleccionar el paciente.
3. Elegir al médico y el horario disponible.
4. Confirmar la cita.

*Precondiciones:*
- El paciente y el médico deben estar registrados en el sistema.
- El servicio debe estar disponible.

*Postcondiciones:*
- La cita queda registrada y notificada a las partes involucradas.

*RF Ref:* RF1, RF2

### *RF4: Notificaciones y Recordatorios de Citas*
*Descripción:* Enviar alertas automáticas a los pacientes y médicos sobre sus citas.

*Flujo:*
1. El sistema genera recordatorios de citas mediante correo o SMS.
2. Se envían confirmaciones y cancelaciones de citas.

*Precondiciones:*
- La cita debe estar registrada en el sistema.

*Postcondiciones:*
- Se reducen las inasistencias y los tiempos de espera.

*RF Ref:* RF3

---

## 📌 Entidades Clave en el Sistema

### *📍 Pacientes*
- Nombre
- Fecha de nacimiento
- Correo electrónico
- Tipo y número de documento
- Teléfono
- Historial médico

### *📍 Médicos*
- Nombre
- Fecha de nacimiento
- Correo electrónico
- Tipo y número de documento
- Teléfono
- Tipo de contrato
- Fecha de vinculación
- Especialidad

### *📍 Servicios Médicos*
- Nombre del servicio
- Descripción del servicio
- Tiempo requerido por el servicio

### *📍 Citas Médicas*
- Servicio seleccionado
- Paciente asignado
- Médico asignado
- Horario según disponibilidad

---

## 📌 1. Contexto y Situación Actual de la Gestión de Citas en la Clínica

### 1.1. Método Tradicional de Agendamiento
Actualmente, la clínica maneja la asignación de citas de manera manual, utilizando llamadas telefónicas y un registro en un libro físico o en hojas de cálculo básicas. Este proceso implica que los pacientes deben comunicarse directamente con el personal administrativo de la clínica para solicitar, modificar o cancelar sus citas.

Este método ha sido utilizado durante mucho tiempo y ha permitido a la clínica mantener cierto nivel de organización. Sin embargo, con el crecimiento del número de pacientes y la mayor demanda de servicios, el sistema manual se ha vuelto ineficiente y ha comenzado a presentar diversos problemas.

### 1.2. Problemas Identificados en la Gestión de Citas
El sistema actual presenta una serie de deficiencias que afectan tanto al personal de la clínica como a los pacientes. Los problemas más relevantes son los siguientes:

#### a) Conflictos en la Asignación de Citas
- Errores al asignar citas pueden derivar en conflictos de horarios o en la sobrecarga de ciertos profesionales.

#### b) Doble Reserva y Horarios Duplicados
- Falta de sincronización que genera que dos pacientes sean agendados en el mismo horario.

#### c) Reprogramaciones y Cancelaciones Problemáticas
- Procesos complicados que requieren intervención manual, aumentando la posibilidad de errores.

#### d) Falta de Recordatorios y Notificaciones
- Ausencias de pacientes debido a la falta de alertas automatizadas.

#### e) Tiempo de Espera Prolongado
- Falta de control en la programación de citas, afectando la experiencia del paciente.

---

## 📌 3. Propuesta de Solución: Implementación de un Sistema Automatizado de Citas

### 3.1. Características del Nuevo Sistema
El sistema propuesto contará con las siguientes funcionalidades clave:

- *Plataforma en Línea:* Permite a los pacientes agendar, cancelar o reprogramar citas desde cualquier dispositivo.
- *Calendario Digital Sincronizado:* Evita errores de doble reserva y conflictos de horarios.
- *Notificaciones Automáticas:* Reduce la tasa de inasistencia mediante recordatorios por SMS o correo.
- *Reportes y Análisis de Datos:* Permite evaluar la eficiencia del sistema y ajustar procesos.

---

## 📌 4. Beneficios de la Implementación del Nuevo Sistema

### 4.1. Optimización del Tiempo y Recursos
- Reducción de la carga administrativa y mejor planificación de citas.

### 4.2. Mayor Comodidad para los Pacientes
- Flexibilidad para gestionar citas sin necesidad de llamadas telefónicas.

### 4.3. Aumento en la Eficiencia Operativa
- Eliminación de errores en la asignación de horarios.

### 4.4. Incremento en la Satisfacción de los Pacientes
- Un sistema fluido mejora la relación paciente-clínica.

---

## 📌 5. Conclusión
El sistema manual de gestión de citas presenta múltiples problemas que afectan la eficiencia operativa y la experiencia del paciente. La implementación de un sistema automatizado optimizará la administración, reducirá errores y ofrecerá un servicio más eficiente. Se recomienda avanzar en la adopción de esta solución lo antes posible para mejorar la experiencia de todos los involucrados.