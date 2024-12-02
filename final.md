### PREGUNTAS TRABAJO INTEGADOR – SUSTENTACIÓN FINAL (5 puntos)

**Llenar los siguientes datos:**

- **Nombre del grupo:** Grupo B  
- **Empresa:** América Móvil Perú (Claro)  
- **Rubro de la empresa:** Telecomunicaciones  

---

**Listado de Problemas Identificados que serán resueltos en el TO BE:**  

1. **Falta de Integración:** Los sistemas clave de Claro Perú funcionan de manera independiente, lo que genera duplicación de esfuerzos, errores en la actualización de datos y retrasos en la transmisión de información.  
   **Solución en TO BE:** Implementación de Apache NiFi para centralizar la integración de datos entre todos los sistemas clave, eliminando la falta de comunicación y garantizando un flujo de datos coherente y eficiente.

2. **Inconsistencia de Datos:** La falta de sincronización en tiempo real entre los sistemas provoca inconsistencias en los datos de ventas, cuotas y rentas, lo que afecta la facturación y el reporte de información. Provoca desactualización y errores entre sistemas de ventas, cobranzas, facturación y SAP.  
   **Solución en TO BE:** Apache NiFi permitirá la sincronización en tiempo real de los datos entre los sistemas, asegurando que la información esté actualizada y consistente en todo momento.

3. **Retrasos en el Flujo de Información:** La transferencia de datos entre sistemas es lenta e ineficiente, lo que retrasa la toma de decisiones operativas y estratégicas. Procesamiento lento de transacciones y decisiones operativas.  
   **Solución en TO BE:** Con Apache NiFi, los datos serán transferidos de manera más rápida y eficiente, eliminando los retrasos y mejorando la agilidad operativa.

4. **Riesgo de Errores Humanos:** La transferencia manual de datos entre sistemas aumenta la probabilidad de errores humanos, lo que puede resultar en datos incorrectos y pérdidas financieras. Transferencia manual de datos aumenta la probabilidad de fallos.  
   **Solución en TO BE:** La automatización completa de los flujos de datos mediante Apache NiFi eliminará los errores humanos y reducirá los riesgos asociados con procesos manuales.

5. **Desempeño Subóptimo:** La falta de integración y la dependencia de procesos manuales afectan la eficiencia de los sistemas, lo que impacta negativamente el desempeño global. Baja eficiencia operativa por sistemas no integrados.  
   **Solución en TO BE:** La implementación de Apache NiFi optimizará el desempeño de los sistemas, al permitir la transferencia eficiente y continua de datos entre ellos, maximizando el uso de los recursos tecnológicos disponibles.

6. **Falta de Visibilidad y Control en los Flujos de Datos:** No existe un monitoreo en tiempo real de los flujos de datos, lo que dificulta la detección y resolución de errores o incidencias rápidamente.  
   **Solución en TO BE:** Con Apache NiFi, se tendrá monitoreo y control centralizado en tiempo real, lo que facilitará la gestión proactiva de los flujos de datos y la resolución de problemas de manera oportuna.

7. **Infraestructura Obsoleta y Costosa de Mantener:** El uso de servidores obsoletos, como el RHEL 5.5 y procesos basados en scripts Shell y servidores FTP, incrementa la complejidad operativa y los costos de mantenimiento.  
   **Solución en TO BE:** Se eliminarán componentes obsoletos y se simplificará la infraestructura, reduciendo los costos de mantenimiento y mejorando la eficiencia operativa.

8. **Limitada Escalabilidad y Flexibilidad:** La infraestructura actual no es lo suficientemente escalable ni flexible para adaptarse a las necesidades crecientes y cambiantes del negocio.  
   **Solución en TO BE:** La nueva arquitectura basada en Apache NiFi proporciona una infraestructura más flexible y escalable, permitiendo a Claro Perú adaptarse rápidamente a los desafíos del mercado y las nuevas demandas tecnológicas.

---

**Capacidades de negocio que están impactando (con base en el alcance definido):**

1. **Gestión de Ventas:** La capacidad de realizar ventas de manera eficiente es fundamental. Esto incluye la gestión de cuotas de venta y la integración con sistemas de facturación y cobranza. La falta de un flujo de información adecuado entre estos sistemas puede afectar la efectividad de las ventas y la satisfacción del cliente.

2. **Cobranzas Efectivas:** La capacidad de gestionar cobranzas de manera efectiva es crucial para la salud financiera de la organización. Esto implica la integración de datos de ventas y cobranzas para asegurar que los estados de cuenta reflejen con precisión las transacciones realizadas.

3. **Facturación Precisa:** La capacidad de emitir facturas de manera precisa y oportuna es esencial. La arquitectura actual presenta limitaciones en este aspecto, lo que puede llevar a errores en la facturación y problemas de cumplimiento con las regulaciones fiscales.

4. **Análisis de Datos:** La capacidad de realizar análisis avanzados sobre los datos de ventas y cobranzas es vital para la toma de decisiones estratégicas. La arquitectura futura busca mejorar la ingesta y transformación de datos, lo que permitirá un análisis más profundo y en tiempo real.

5. **Relación con el Cliente:** La capacidad de gestionar la relación con el cliente, incluyendo la evaluación de crédito y la personalización de ofertas, es fundamental para mejorar la experiencia del cliente y fomentar la lealtad.

6. **Adaptabilidad a Cambios:** La capacidad de adaptarse a cambios en el mercado y en las necesidades del cliente es crucial. La arquitectura "To Be" está diseñada para ser modular y escalable, lo que permitirá a la organización responder rápidamente a nuevas oportunidades y desafíos.

---

**Principios de Arquitectura Priorizados para la Solución "To Be":**

1. **Interoperabilidad:** La solución "To Be" prioriza la interoperabilidad entre sistemas, lo que es fundamental para asegurar que todos los componentes de la arquitectura puedan comunicarse y trabajar juntos de manera efectiva.

2. **Simplicidad y Eficiencia:** Se busca una implementación sencilla que minimice las dependencias externas y agilice la puesta en marcha de la arquitectura futura. Esto se alinea con el principio de mantener la complejidad al mínimo.

3. **Control de Datos:** Mantener la infraestructura on-premise permite un mayor control sobre los datos y procesos críticos, lo que es esencial para la seguridad de la información y la continuidad operativa.

---

### 1. **Estrategia de Implementación en el ADM**

**Fase del ADM:** Fase de Implementación

Como arquitecto líder, es probable que se encuentre en la Fase de Implementación del Architecture Development Method (ADM). Esta fase se centra en la ejecución de la estrategia de implementación y en la transición hacia la arquitectura futura.

**Artefactos a Mostrar:**

- **Plan de Implementación:** Un documento que detalla las etapas, recursos y cronograma para la implementación de la arquitectura.
  
- **Diagrama de Arquitectura Futura (TO BE):** Un diagrama que ilustra cómo se verá la arquitectura una vez que se complete la implementación.
  
- **Diagrama de Arquitectura de Transición:** Un diagrama que muestra cómo se moverá la organización desde la arquitectura actual (AS IS) a la futura (TO BE).
  
- **Mapa de Capacidades:** Un documento que muestra las capacidades de negocio que se verán impactadas y cómo se alinean con la estrategia de implementación.

**Comentarios al Patrocinador:**

Si el patrocinador no está de acuerdo con la estrategia de implementación, le comentaría lo siguiente:

- **Revisar los Objetivos de Negocio:** Es importante asegurarse de que la estrategia de implementación esté alineada con los objetivos estratégicos del negocio. Podríamos revisar juntos cómo la propuesta apoya estos objetivos.

- **Escuchar sus Preocupaciones:** Preguntaría sobre sus inquietudes específicas para entender mejor su perspectiva y ajustar la estrategia si es necesario.

- **Proponer un Taller de Revisión:** Sugeriría realizar un taller donde se puedan discutir las preocupaciones y explorar alternativas, asegurando que todos los interesados estén alineados.

- **Próximos Pasos:** Si se requiere un cambio en la estrategia, se debe definir un plan de acción claro para abordar las preocupaciones y ajustar la estrategia de implementación en consecuencia.

---

### 2. **Arquitectura de Aplicaciones (TO BE)**

**a. Diagrama de Componentes y/o Servicios de Aplicación**

Para la capa de aplicaciones, el diagrama podría incluir los siguientes componentes:

- **Sistema de Ventas:** Maneja las transacciones de ventas y la gestión de cuotas.
- **Sistema de Cobranzas:** Gestiona el proceso de cobranza y la integración con los entes recaudadores.
- **Sistema de Facturación:** Genera facturas y gestiona la información financiera.
- **Sistema de Análisis de Datos:** Proporciona herramientas para el análisis de datos de ventas y cobranzas.
- **Integración con SAP:** Conexión con el sistema SAP para la gestión de datos y reportes.

**b. Diagrama de la Arquitectura de Transición**

El diagrama de la arquitectura de transición podría mostrar:

- **Fase 1:** Implementación de Apache NiFi para la integración de datos.
- **Fase 2:** Reemplazo de scripts Shell y mejora de la comunicación entre sistemas.
- **Fase 3:** Eliminación de scripts restantes y optimización de procesos.
- **Fase 4:** Implementación completa de la arquitectura TO BE.

**c. Principios de Arquitectura Empresarial (AE)**

Los principios de AE utilizados para la capa de aplicaciones podrían incluir:

- **Interoperabilidad:** Asegurar que todos los sistemas y aplicaciones puedan comunicarse entre sí de manera efectiva. En el diseño TO BE, se implementa Apache NiFi para facilitar la integración de datos entre sistemas.
  
- **Modularidad:** Diseñar aplicaciones como módulos independientes que pueden ser actualizados o reemplazados sin afectar al sistema en su totalidad. Esto se refleja en la arquitectura TO BE, donde se planifica la eliminación de scripts obsoletos y la implementación de soluciones más modernas.

- **Escalabilidad:** La arquitectura debe ser capaz de crecer y adaptarse a las necesidades futuras del negocio. La implementación de soluciones en la nube y la modularidad de los componentes permiten que la arquitectura se escale fácilmente.

- **Eficiencia Operativa:** Optimizar los procesos para reducir costos y mejorar la productividad. La transición hacia una arquitectura más automatizada y menos dependiente de scripts manuales contribuye a este principio.

### **Fases del ADM Según TOGAF**

El Architecture Development Method (ADM) de TOGAF es el ciclo de vida de desarrollo de una arquitectura empresarial que se utiliza para crear y gestionar la arquitectura en una organización. El proceso se organiza en fases que guían la creación, implementación y mantenimiento de la arquitectura. Las fases del ADM son las siguientes:

Fase A: Visión de la Arquitectura (Architecture Vision):
En esta fase, se define el alcance de la arquitectura y se establece una visión clara del futuro. Se identifican los requisitos de alto nivel y los objetivos estratégicos del negocio. La fase incluye la creación de la "visión de la arquitectura", que es un documento que describe los objetivos del proyecto y las expectativas de los stakeholders.

Fase B: Arquitectura de Negocio (Business Architecture):
Esta fase se enfoca en la definición y diseño de la arquitectura de negocio. Se analizan los procesos de negocio, las funciones y las interacciones, para crear una representación clara de cómo debería funcionar el negocio en el futuro. El objetivo es identificar las capacidades de negocio que deben ser respaldadas por la tecnología.

Fase C: Arquitectura de Sistemas de Información (Information Systems Architectures):
En esta fase, se desarrollan dos arquitecturas clave: la arquitectura de datos y la arquitectura de aplicaciones. La arquitectura de datos define cómo se manejarán y almacenarán los datos dentro de la organización, mientras que la arquitectura de aplicaciones define cómo se organizarán y desplegarán las aplicaciones dentro del entorno empresarial.

Fase D: Arquitectura Tecnológica (Technology Architecture):
Aquí se define la infraestructura tecnológica necesaria para soportar las arquitecturas de negocio, datos y aplicaciones. Esta fase incluye el diseño de la infraestructura de hardware, software y las redes necesarias para permitir la ejecución de los sistemas de información y las aplicaciones.

Fase E: Oportunidades y Soluciones (Opportunities and Solutions):
En esta fase, se identifican las soluciones y las oportunidades para implementar la arquitectura. Esto puede incluir la identificación de proyectos específicos, la selección de plataformas tecnológicas y la asignación de recursos. El objetivo es asegurar que la solución propuesta sea viable desde el punto de vista económico y técnico.

Fase F: Planificación de la Implementación (Migration Planning):
Se desarrollan planes de implementación detallados para la transición de la arquitectura actual (AS IS) a la arquitectura futura (TO BE). En esta fase se define el cronograma de las actividades, los recursos necesarios y el enfoque de transición.

Fase G: Implementación (Implementation Governance):
Esta fase se centra en la gobernanza durante la implementación de la arquitectura. Se realiza un seguimiento de los proyectos para garantizar que se alineen con la arquitectura empresarial y los principios definidos, y se asegura que la implementación siga los planes y especificaciones establecidos.

Fase H: Gestión de la Arquitectura (Architecture Change Management):
Una vez implementada la arquitectura, esta fase se dedica a la gestión de los cambios y la evolución de la arquitectura. Aquí se lleva a cabo el monitoreo y ajuste continuo de la arquitectura para asegurar que continúe alineada con los objetivos del negocio y las necesidades emergentes.

--

Los **principios y lineamientos de arquitectura empresarial** son guías fundamentales que definen las normas, valores y directrices para el diseño y gestión de la arquitectura dentro de una organización. Ayudan a garantizar que todas las decisiones y actividades arquitectónicas estén alineadas con los objetivos estratégicos y las mejores prácticas. En el contexto de **TOGAF (The Open Group Architecture Framework)**, estos principios y lineamientos establecen un marco sólido para guiar la creación, implementación y mantenimiento de la arquitectura empresarial.

### **Principios de Arquitectura Empresarial**

Los **principios de arquitectura empresarial** representan normas generales que guían las decisiones de arquitectura a lo largo del ciclo de vida de la organización. Los principios de TOGAF incluyen los siguientes:

1. **Interoperabilidad:**  
   Asegurar que los sistemas y aplicaciones dentro de la organización puedan comunicarse entre sí de manera eficiente, sin fricciones, a través de interfaces estandarizadas. La interoperabilidad permite que la infraestructura de TI funcione como un sistema cohesivo.

2. **Simplicidad:**  
   Buscar soluciones simples que no introduzcan complejidad innecesaria. Esto no significa eliminar las soluciones sofisticadas, sino que cada elemento de la arquitectura debe tener un propósito claro y ser lo más sencillo posible para cumplir con los requisitos sin exceso de complicaciones.

3. **Modularidad:**  
   Diseñar soluciones como componentes independientes o módulos que puedan ser gestionados y cambiados sin afectar a toda la infraestructura. La modularidad permite mayor flexibilidad, facilitando actualizaciones o reemplazos sin interrumpir el funcionamiento global.

4. **Escalabilidad:**  
   La arquitectura debe ser capaz de crecer con las necesidades del negocio. Esto implica que los sistemas deben poder manejar un aumento en la carga de trabajo, el volumen de datos o el número de usuarios sin perder rendimiento.

5. **Reusabilidad:**  
   Los componentes arquitectónicos deben ser diseñados para ser reutilizados en diferentes contextos dentro de la organización, maximizando el valor de la inversión en tecnología.

6. **Eficiencia Operativa:**  
   Los procesos y sistemas deben estar diseñados para maximizar la eficiencia en las operaciones. Esto incluye la reducción de costos, la eliminación de redundancias y la mejora de la productividad a través de la automatización y la optimización de recursos.

7. **Seguridad:**  
   La arquitectura debe garantizar que todos los componentes sean seguros. Esto incluye la protección de los datos, la privacidad y la integridad de los sistemas frente a posibles amenazas externas e internas.

8. **Flexibilidad y Adaptabilidad:**  
   Los sistemas deben ser flexibles y capaces de adaptarse rápidamente a cambios en el entorno de negocio, las necesidades de los clientes y la evolución tecnológica. La arquitectura debe poder ajustarse a nuevas tecnologías y modelos de negocio sin grandes reestructuraciones.

9. **Gestión de Riesgos:**  
   La arquitectura debe estar diseñada para minimizar los riesgos asociados con la TI, como la pérdida de datos, los fallos de sistemas, la no disponibilidad de servicios y otros eventos imprevistos.

10. **Costos Controlados:**  
   La arquitectura debe ser diseñada para ser coste-efectiva, no solo en su implementación, sino también en su mantenimiento a largo plazo. Esto incluye considerar costos operativos, de licencias y de infraestructura.

### **Lineamientos de Arquitectura Empresarial**

Los **lineamientos de arquitectura empresarial** son más específicos que los principios y están destinados a detallar cómo deben aplicarse los principios en situaciones concretas. Son guías operativas que ayudan a alinear la estrategia de arquitectura con las necesidades del negocio y las expectativas de los stakeholders. Algunos de los lineamientos más importantes incluyen:

1. **Desarrollo Basado en Estándares:**  
   La arquitectura debe estar construida sobre estándares abiertos y tecnológicos, como protocolos de comunicación estándar (HTTP, SOAP, etc.), lenguajes de programación comunes y tecnologías ampliamente aceptadas, como las bases de datos SQL o los sistemas operativos de código abierto. Esto facilita la interoperabilidad y reduce el riesgo de quedar atrapado en soluciones propietarias o tecnológicamente desfasadas.

2. **Priorización de la Automatización:**  
   La automatización de los procesos debe ser una prioridad para reducir el esfuerzo manual y los errores humanos. Esto implica automatizar tanto como sea posible la integración de sistemas, la gestión de infraestructuras y los flujos de trabajo empresariales.

3. **Centrado en el Negocio:**  
   La arquitectura debe alinearse estrechamente con las necesidades y objetivos estratégicos del negocio. La tecnología debe ser un habilitador para mejorar la eficiencia del negocio y no un fin en sí mismo.

4. **Governance y Control de Cambios:**  
   Se deben establecer procesos de gobernanza sólidos para gestionar y controlar los cambios en la arquitectura. Esto incluye la creación de comités de arquitectura, la documentación de decisiones clave y el establecimiento de un proceso de aprobación para cambios importantes.

5. **Orientación a Servicios (SOA - Service-Oriented Architecture):**  
   Se debe promover una arquitectura orientada a servicios, en la que los sistemas y aplicaciones se diseñan como servicios independientes que se pueden combinar y reutilizar según las necesidades del negocio. Esto ayuda a mejorar la flexibilidad y la escalabilidad de la solución.

6. **Consistencia y Calidad de los Datos:**  
   Se debe establecer una política clara sobre cómo los datos se manejan, almacenan y procesan dentro de la organización. La calidad de los datos y su consistencia son cruciales para la toma de decisiones y la eficiencia operativa.

7. **Gestión de Capacidades y Rendimiento:**  
   Los sistemas deben ser diseñados para soportar las necesidades de capacidad y rendimiento del negocio, incluso en tiempos de picos de demanda. Esto incluye la planificación de infraestructura escalable, el uso de tecnologías como la nube y la optimización de los sistemas.

8. **Arquitectura Basada en Nubes (Cloud Architecture):**  
   Se debe considerar el uso de servicios basados en la nube como parte de la infraestructura tecnológica de la organización, para mejorar la flexibilidad, la escalabilidad y reducir los costos operativos.

9. **Monitoreo y Mejora Continua:**  
   La arquitectura debe incluir mecanismos para monitorear el desempeño de los sistemas y procesos, con el objetivo de identificar áreas de mejora continua y hacer ajustes de manera proactiva.

10. **Documentación y Transparencia:**  
   Toda la arquitectura debe estar bien documentada, para que sea comprensible y accesible tanto para los diseñadores como para los stakeholders. Esto incluye diagramas, especificaciones técnicas, guías operativas y manuales de usuario.

### **Resumen de los Principios y Lineamientos de Arquitectura Empresarial**

- **Principios**: Son normas generales y abstractas que guían el desarrollo y la gestión de la arquitectura.
- **Lineamientos**: Son directrices más específicas que detallan cómo se aplican esos principios en la práctica dentro de la organización.

Ambos trabajan en conjunto para asegurar que la arquitectura empresarial sea coherente, eficiente, adaptable y alineada con las necesidades y objetivos estratégicos de la organización. Aseguran que las soluciones tecnológicas no solo sean técnicamente viables, sino también económicamente eficientes y orientadas al negocio.