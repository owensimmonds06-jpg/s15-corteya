**Propósito**

“CorteYa” es una plataforma digital diseñada para optimizar la reserva de citas en peluquerías. Permite a los clientes consultar horarios disponibles, seleccionar servicios y agendar o reprogramar sus citas de forma rápida, mientras ofrece al estilista una herramienta clara para visualizar y reorganizar su agenda de trabajo. 

---
**Alcance**

_Qué SÍ hace el sistema_

- Permite a los clientes consultar en tiempo real los horarios libres de los estilistas.
- Permite agendar citas seleccionando un servicio específico y confirmando la reserva.
- Permite tanto al cliente como al estilista reprogramar citas previamente agendadas.


_Qué NO hace el sistema_

- _No gestiona pagos en línea_: La transacción monetaria se realiza de forma presencial o externa al sistema.
- _No gestiona inventario_: No lleva el control de insumos, tintes ni productos consumibles de la peluquería.
- _No realiza facturación electrónica ni contabilidad_: No emite comprobantes fiscales ni lleva balances financieros.
---
**Actores**

- _Cliente_: Usuario que consulta la disponibilidad, agenda un servicio deseado y reprogramar sus citas cuando lo requiere.
- _Estilista_: Profesional de la peluquería que visualiza las citas asignadas a su agenda y reprograma reservas según su disponibilidad o eventualidades.
---
**RF - Requisitos Funcionales**
| Código | Descripción | Prioridad |
| :--- | :--- | :--- |
| **RF-01** | El sistema debe permitir al cliente consultar los horarios disponibles de los estilistas. | Alta |
| **RF-02** | El sistema debe permitir al cliente agendar una cita eligiendo un servicio específico y emitir una confirmación de la reserva. | Alta |
| **RF-03** | El sistema debe permitir al cliente o al estilista reprogramar una cita existente a una nueva fecha u horario disponible. | Media |

---

**RNF - Requisito No Funcional**
| Código | Categoría | Descripción | Criterio de Aceptación |
| :--- | :--- | :--- | :--- |
| **RNF-01** | Usabilidad | El proceso completo de selección de servicio, consulta de horario y confirmación de la cita debe garantizar una experiencia rápida e intuitiva. | El flujo completo desde la selección del servicio hasta la confirmación debe realizarse en un **máximo de 3 pantallas**. |
