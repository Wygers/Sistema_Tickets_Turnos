# Sistema de Solicitud de Ticket de Turnos – (Tunomático)

✅ DESCRIPCIÓN GENERAL DEL SISTEMA DESARROLLADO:

Este proyecto corresponde al modelado completo de un sistema de solicitud y gestión de turnos en una carnicería, enfocado en optimizar la atención al cliente, reducir tiempos de espera y mejorar la trazabilidad del flujo de atención, mediante una solución informática profesional.

El sistema abarca componentes operativos clave como:

Solicitud remota o presencial de turnos.

Gestión de tickets por número secuencial y tipo de atención.

Asignación de turnos a módulos de atención disponibles.

Visualización de llamados y seguimiento en tiempo real.

Generación de reportes de atención diaria y por módulo.

Configuración centralizada de parámetros de operación.


🔍 OBJETIVOS DEL MODELADO:

Realizar una transición progresiva desde el análisis funcional hasta el diseño físico del sistema.

Aplicar patrones de diseño en la etapa lógica para garantizar mantenibilidad, modularidad y escalabilidad.

Desarrollar pensamiento arquitectónico a través de la separación de capas, responsabilidades y nodos físicos.


🔹 1. DIAGRAMA CASO DE USO UML:

![diagrama_casouso](https://github.com/user-attachments/assets/39ff3c70-2c91-4399-bade-6d070e73a23d)

-> para acciones opcionales como métricas posteriores a la atención o cancelación de turnos.

-> en la auditoría ya que esta misma incluye la revisión de métricas de atención a clientes.

🔹 2. DIAGRAMA DE CLASES UML APLICADO AL CASO :
![diagrama_clases](https://github.com/user-attachments/assets/3567f356-0871-4456-b586-a26186c5606f)


📌 Patrones Aplicados:

Singleton –> ConfiguracionSistema

Asegura una única instancia global de configuración.

Prototype –> TurnoPrototype

Permite clonar turnos con parámetros estándar.

Adapter –> AdaptadorNotificaciones

Facilita integración con APIs de notificación (correo, WhatsApp).

Controller –> implícito en SistemaTurnos

Orquesta la lógica entre vistas e instancias del modelo.

🔹 3. DIAGRAMA DE IMPLEMENTACIÓN UML (DESPLIEGUE SISTEMA) : 
![diagrama_implementacion](https://github.com/user-attachments/assets/8320295c-9220-46e1-b086-0fc55445ccff)


📌 Decisiones Técnicas:

Separación de nodos para robustecer la seguridad y disponibilidad.

Desacoplamiento de componentes críticos como Configuración y Notificaciones.

Posibilidad de escalar horizontalmente las interfaces.


🔹 REFLEXIONES FINALES DE ESTE MODELADO DEL SISTEMA:


Este modelado refleja una arquitectura robusta y profesional con los siguientes atributos:

Patrones seleccionados según criterios de eficiencia, mantenibilidad y escalabilidad.

Trazabilidad entre requisitos funcionales, diseño lógico y despliegue físico.

Claridad de responsabilidades y modularidad en los componentes.

Base sólida para extensiones futuras como integración con APIs de fila virtual, métricas avanzadas o interfaces vocales.
