PREGUNTAS TRABAJO INTEGADOR – SUSTENTACIÓN FINAL (5 puntos)
Llenar los siguientes datos:

Nombre del grupo: Grupo B
Empresa: América Móvil Perú (Claro)
Rubro de la empresa: Telecomunicaciones

Listado de Problemas Identificados que serán resueltos en el TO BE: 
    * Falta de Integración: Los sistemas clave de Claro Perú funcionan de manera independiente, lo que genera duplicación de esfuerzos, errores en la actualización de datos y retrasos en la transmisión de información.
    Solución en TO BE: Implementación de Apache NiFi para centralizar la integración de datos entre todos los sistemas clave, eliminando la falta de comunicación y garantizando un flujo de datos coherente y eficiente.

    * Inconsistencia de Datos: La falta de sincronización en tiempo real entre los sistemas provoca inconsistencias en los datos de ventas, cuotas y rentas, lo que afecta la facturación y el reporte de información. Provoca desactualización y errores entre sistemas de ventas, cobranzas, facturación y SAP.
    Solución en TO BE: Apache NiFi permitirá la sincronización en tiempo real de los datos entre los sistemas, asegurando que la información esté actualizada y consistente en todo momento.

    * Retrasos en el Flujo de Información: La transferencia de datos entre sistemas es lenta e ineficiente, lo que retrasa la toma de decisiones operativas y estratégicas. Procesamiento lento de transacciones y decisiones operativas.
    Solución en TO BE: Con Apache NiFi, los datos serán transferidos de manera más rápida y eficiente, eliminando los retrasos y mejorando la agilidad operativa.

    * Riesgo de Errores Humanos: La transferencia manual de datos entre sistemas aumenta la probabilidad de errores humanos, lo que puede resultar en datos incorrectos y pérdidas financieras. Transferencia manual de datos aumenta la probabilidad de fallos.
    Solución en TO BE: La automatización completa de los flujos de datos mediante Apache NiFi eliminará los errores humanos y reducirá los riesgos asociados con procesos manuales.

    * Desempeño Subóptimo: La falta de integración y la dependencia de procesos manuales afectan la eficiencia de los sistemas, lo que impacta negativamente el desempeño global. Baja eficiencia operativa por sistemas no integrados.
    Solución en TO BE: La implementación de Apache NiFi optimizará el desempeño de los sistemas, al permitir la transferencia eficiente y continua de datos entre ellos, maximizando el uso de los recursos tecnológicos disponibles.
--
    * Falta de Visibilidad y Control en los Flujos de Datos: No existe un monitoreo en tiempo real de los flujos de datos, lo que dificulta la detección y resolución de errores o incidencias rápidamente.
    Solución en TO BE: Con Apache NiFi, se tendrá monitoreo y control centralizado en tiempo real, lo que facilitará la gestión proactiva de los flujos de datos y la resolución de problemas de manera oportuna.

    * Infraestructura Obsoleta y Costosa de Mantener: El uso de servidores obsoletos, como el RHEL 5.5 y procesos basados en scripts Shell y servidores FTP, incrementa la complejidad operativa y los costos de mantenimiento.
    Solución en TO BE: Se eliminarán componentes obsoletos y se simplificará la infraestructura, reduciendo los costos de mantenimiento y mejorando la eficiencia operativa.

    * Limitada Escalabilidad y Flexibilidad: La infraestructura actual no es lo suficientemente escalable ni flexible para adaptarse a las necesidades crecientes y cambiantes del negocio.
    Solución en TO BE: La nueva arquitectura basada en Apache NiFi proporciona una infraestructura más flexible y escalable, permitiendo a Claro Perú adaptarse rápidamente a los desafíos del mercado y las nuevas demandas tecnológicas.


---
Capacidades de negocio que están impactando (con base al alcance que definieron):
    Gestión de Ventas: La capacidad de realizar ventas de manera eficiente es fundamental. Esto incluye la gestión de cuotas de venta y la integración con sistemas de facturación y cobranza. La falta de un flujo de información adecuado entre estos sistemas puede afectar la efectividad de las ventas y la satisfacción del cliente .

    Cobranzas Efectivas: La capacidad de gestionar cobranzas de manera efectiva es crucial para la salud financiera de la organización. Esto implica la integración de datos de ventas y cobranzas para asegurar que los estados de cuenta reflejen con precisión las transacciones realizadas .

    Facturación Precisa: La capacidad de emitir facturas de manera precisa y oportuna es esencial. La arquitectura actual presenta limitaciones en este aspecto, lo que puede llevar a errores en la facturación y problemas de cumplimiento con las regulaciones fiscales .

    Análisis de Datos: La capacidad de realizar análisis avanzados sobre los datos de ventas y cobranzas es vital para la toma de decisiones estratégicas. La arquitectura futura busca mejorar la ingesta y transformación de datos, lo que permitirá un análisis más profundo y en tiempo real .

    Relación con el Cliente: La capacidad de gestionar la relación con el cliente, incluyendo la evaluación de crédito y la personalización de ofertas, es fundamental para mejorar la experiencia del cliente y fomentar la lealtad .

    Adaptabilidad a Cambios: La capacidad de adaptarse a cambios en el mercado y en las necesidades del cliente es crucial. La arquitectura "To Be" está diseñada para ser modular y escalable, lo que permitirá a la organización responder rápidamente a nuevas oportunidades y desafíos

--
Principios de Arquitectura Priorizados para la Solución "To Be"
    1. Interoperabilidad: La solución "To Be" prioriza la interoperabilidad entre sistemas, lo que es fundamental para asegurar que todos los componentes de la arquitectura puedan comunicarse y trabajar juntos de manera efectiva .

    2. Simplicidad y Eficiencia: Se busca una implementación sencilla que minimice las dependencias externas y agilice la puesta en marcha de la arquitectura futura. Esto se alinea con el principio de mantener la complejidad al mínimo .

    3. Control de Datos: Mantener la infraestructura on-premise permite un mayor control sobre los datos y procesos críticos, lo que es esencial para la seguridad de la información y la continuidad operativa

1. Estrategia de Implementación en el ADM

Fase del ADM: Fase de Implementación

Como arquitecto líder, es probable que se encuentre en la Fase de Implementación del Architecture Development Method (ADM). Esta fase se centra en la ejecución de la estrategia de implementación y en la transición hacia la arquitectura futura.

Artefactos a Mostrar

En esta fase, los artefactos que se mostrarían incluyen:

- Plan de Implementación: Un documento que detalla las etapas, recursos y cronograma para la implementación de la arquitectura.

- Diagrama de Arquitectura Futura (TO BE): Un diagrama que ilustra cómo se verá la arquitectura una vez que se complete la implementación.

- Diagrama de Arquitectura de Transición: Un diagrama que muestra cómo se moverá la organización desde la arquitectura actual (AS IS) a la futura (TO BE).

- Mapa de Capacidades: Un documento que muestra las capacidades de negocio que se verán impactadas y cómo se alinean con la estrategia de implementación.

Comentarios al Patrocinador

Si el patrocinador no está de acuerdo con la estrategia de implementación, le comentaría lo siguiente:

- Revisar los Objetivos de Negocio: Es importante asegurarse de que la estrategia de implementación esté alineada con los objetivos estratégicos del negocio. Podríamos revisar juntos cómo la propuesta apoya estos objetivos.

- Escuchar sus Preocupaciones: Preguntaría sobre sus inquietudes específicas para entender mejor su perspectiva y ajustar la estrategia si es necesario.

- Proponer un Taller de Revisión: Sugeriría realizar un taller donde se puedan discutir las preocupaciones y explorar alternativas, asegurando que todos los interesados estén alineados.

- Próximos Pasos: Si se requiere un cambio en la estrategia, se debe definir un plan de acción claro para abordar las preocupaciones y ajustar la estrategia de implementación en consecuencia.

2. Arquitectura de Aplicaciones (TO BE)

a. Diagrama de Componentes y/o Servicios de Aplicación

Para la capa de aplicaciones, el diagrama podría incluir los siguientes componentes:

- Sistema de Ventas: Maneja las transacciones de ventas y la gestión de cuotas.

- Sistema de Cobranzas: Gestiona el proceso de cobranza y la integración con los entes recaudadores.

- Sistema de Facturación: Genera facturas y gestiona la información financiera.

- Sistema de Análisis de Datos: Proporciona herramientas para el análisis de datos de ventas y cobranzas.

- Integración con SAP: Conexión con el sistema SAP para la gestión de datos y reportes.

b. Diagrama de la Arquitectura de Transición

El diagrama de la arquitectura de transición podría mostrar:

- Fase 1: Implementación de Apache NiFi para la integración de datos.

- Fase 2: Reemplazo de scripts Shell y mejora de la comunicación entre sistemas.

- Fase 3: Eliminación de scripts restantes y optimización de procesos.

- Fase 4: Implementación completa de la arquitectura TO BE.

c. Principios de Arquitectura Empresarial (AE)

Los principios de AE utilizados para la capa de aplicaciones podrían incluir:

- Interoperabilidad: Asegurar que todos los sistemas y aplicaciones puedan comunicarse entre sí de manera efectiva. En el diseño TO BE, se implementa Apache NiFi para facilitar la integración de datos entre sistemas.

- Modularidad: Diseñar aplicaciones como módulos independientes que pueden ser actualizados o reemplazados sin afectar al sistema en su totalidad. Esto se refleja en la arquitectura TO BE, donde se planifica la eliminación de scripts obsoletos y la implementación de soluciones más modernas.

- Escalabilidad: La arquitectura debe ser capaz de crecer y adaptarse a las necesidades futuras del negocio. La implementación de soluciones en la nube y la modularidad de los componentes permiten que la arquitectura se escale fácilmente.

- Eficiencia Operativa: Optimizar los procesos para reducir costos y mejorar la productividad. La transición hacia una arquitectura más automatizada y menos dependiente de scripts manuales contribuye a este principio.