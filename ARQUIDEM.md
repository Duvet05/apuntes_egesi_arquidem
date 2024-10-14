# Arquitectura Empresarial

## Temario

### Unidad 1: ESTRATEGIA TI PARA UNA ORGANIZACIÓN

1. **Sistemas de Información**
2. **Estrategia TI**
3. **Modelo de operación de la estrategia TI**
4. **El rol de los sistemas de información en los negocios**
5. **Ventajas competitivas**

### Unidad 2: ARQUITECTURA EMPRESARIAL

1. **Introducción y conceptos de arquitectura empresarial**
2. **Para qué arquitectura empresarial**
3. **Capas AE**
4. **Cómo abordar un proyecto de implementación de Arquitectura Empresarial**
5. **Habilitadores tecnológicos**
6. **Definición de Roadmap de implementación**

Las preguntas serán sobre **casos situacionales**. No son preguntas de opción múltiple, sino que requerirán que, con base en el análisis, comentes tu respuesta con un **sustento lógico y preciso**.

---
---
---

### **Unidad 1: Estrategia TI para una Organización**

1. **Sistemas de Información**:
   - Los sistemas de información (SI) son esenciales para la gestión de información y para facilitar las operaciones de una organización. Los SI incluyen componentes como **hardware, software, datos, procesos y personas**.
   - Existen varios tipos de SI:
     - **Front Office**: Relacionados con la interacción directa con los clientes (por ejemplo, aplicaciones de ventas y atención al cliente).
     - **Back Office - Core**: Procesos centrales que soportan las operaciones principales de la organización (como la gestión de finanzas y recursos humanos).
     - **Back Office - Soporte**: Procesos de apoyo que respaldan las funciones principales sin interactuar directamente con los clientes (como sistemas de mantenimiento y logística).
   - Los SI pueden ser desarrollados internamente (In-house) o adquiridos de terceros, hay que hacer un analisis para determinar eso.

   ![Alt text](./imagenes/unidad1_tipos_sistemas_informacion.png?raw=true "Title")

   - Los **drivers del negocio** son factores clave que impulsan el crecimiento y éxito de una organización. Los drivers del negocio guían las decisiones estratégicas y operativas, enfocando los recursos en áreas que maximizan el valor y la competitividad de la empresa. Representan los elementos críticos que afectan el rendimiento y ayudan a alcanzar los objetivos estratégicos. En una empresa, los drivers pueden incluir:

     - **Demanda del cliente**: Necesidades y expectativas de los clientes.
     - **Eficiencia operativa**: Optimización de procesos para reducir costos y tiempos.
     - **Innovación tecnológica**: Uso de nuevas tecnologías para mejorar productos o servicios.
     - **Cumplimiento regulatorio**: Asegurarse de que la empresa sigue leyes y normativas.
     - **Calidad de producto/servicio**: Mantener altos estándares para satisfacer a los clientes.

   ![Alt text](./imagenes/unidad1_drivers_negocio.png?raw=true "Title")


2. **Estrategia TI**:
   - ¿Qué es Estrategia TI?
     - La **estrategia TI** es un **proceso continuo** diseñado para alinear la tecnología con los objetivos estratégicos de la organización. No se trata solo de implementar tecnología, sino de estructurarla para apoyar el crecimiento y la competitividad de la empresa a largo plazo. Es importante destacar lo que **no es** la estrategia TI:
         - No es un conjunto de técnicas o normas.
         - No es un conjunto de tecnologías.
         - No es un lenguaje de programación.
         - No es una certificación internacional.
         - No es simplemente la adquisición de una marca o solución tecnológica.

     - En lugar de esto, la estrategia TI implica:
         - **Decisiones basadas en el conocimiento** del futuro de la organización y el mercado.
         - **Organización de esfuerzos** (personas, finanzas, recursos) para ejecutar estas decisiones.
         - **Medición de resultados** para asegurarse de que la estrategia cumple con las expectativas y permite realizar ajustes si es necesario.

     - Tríada para Diseñar Estrategias: Para formular una estrategia efectiva, se utilizan tres componentes clave:
         1. **Objetivos**: Define el propósito y las metas que se desean alcanzar. Responde a la pregunta “¿Qué queremos lograr?”
         2. **Recursos**: Incluye los medios y capacidades con los que cuenta la organización, tanto tangibles (financieros, humanos, tecnológicos) como intangibles (conocimiento, cultura organizacional). Responde a “¿Con qué contamos para lograrlo?”
         3. **Plan de Acción**: Define los pasos específicos que se implementarán para alcanzar los objetivos, indicando cómo, cuándo y quién estará a cargo de cada acción. Responde a “¿Cómo lo lograremos?”

      ![Estrategia Tríada](./imagenes/unidad1_estrategia.png?raw=true "Tríada para Diseñar Estrategias")

   - Componentes de una Estrategia TI: La estrategia TI se compone de varios elementos clave que ayudan a orientar la organización hacia sus objetivos estratégicos:
       - **Aplicaciones**: Software y plataformas que soportan las funciones empresariales.
       - **Infraestructura Tecnológica**: Hardware, redes y sistemas que permiten la operación de las aplicaciones.
       - **Información**: Datos relevantes y organizados para la toma de decisiones.
       - **Seguridad**: Protección de los activos tecnológicos e información de la empresa, asegurando la integridad y confidencialidad de los datos.


   - Decisión Estratégica: ¿Construir (Build) o Comprar (Buy)?
     Una de las decisiones clave en la estrategia TI es determinar si es más conveniente **construir** una solución a medida o **comprarla** a un proveedor externo. 
      Build vs. Buy: Cinco Factores a Considerar:
        1. **Time to Market**: ¿Cuánto tiempo tomará implementar la solución? Comprar software suele acelerar el proceso, mientras que construirlo puede requerir un tiempo de desarrollo considerable.
        2. **Total Cost of Ownership**: Considera el costo total, incluyendo implementación, mantenimiento y actualizaciones. Construir a menudo puede ser más costoso a largo plazo.
        3. **Features and Functionality**: Evalúa si el software comprado cumple con todas las funcionalidades necesarias o si construirlo permite una personalización más profunda.
        4. **Knowledge and Expertise**: ¿Tu equipo tiene la experiencia y conocimientos para construir la solución, o será necesario soporte externo?
        5. **Core Competencies**: Si la creación de software no es una competencia central de tu negocio, puede ser más efectivo comprar una solución ya desarrollada.

   - ¿Cómo implementar la Arquitectura Empresarial (AE)? Para poner en práctica la AE, sigue estos pasos:
     1. **Definir la dirección**: No inicies nada sin entender hacia dónde vas y cómo medirás el éxito de tus iniciativas.
     2. **Identificar un problema o necesidad**: Encuentra un área de mejora o un "dolor" en la organización que la AE pueda resolver.

      ![Estrategia Tríada](./imagenes/unidad1_evolucion.png?raw=true "Tríada para Diseñar Estrategias")

   - Problemas Comunes en TI: Algunos problemas generales que pueden surgir al no tener una estrategia TI adecuada incluyen:
       - **Plataformas mal asignadas**: Sistemas que manejan capacidades inadecuadas, lo que genera complejidad operativa, degradación de servicio y altos costos.
       - **Múltiples fuentes de información**: Diversidad de plataformas y datos sin centralización, generando problemas de calidad en la información.
       - **Adquisición sin estrategia clara**: Plataformas compradas sin una guía estratégica, resultando en recursos desperdiciados y sistemas subutilizados.
       - **Capacidades duplicadas**: Múltiples plataformas con funciones similares, lo que lleva a una falta de estandarización y dificultades de mantenimiento.
       - **Falta de capacidad para soportar productos futuros**: La ausencia de un modelo único de integración ralentiza el time-to-market y aumenta la complejidad de mantenimiento.

      ![Estrategia Tríada](./imagenes/unidad1_identificacion_problemas.png?raw=true "Tríada para Diseñar Estrategias")


1. **Modelo de Operación de la Estrategia TI**:
   - El modelo de operación define cómo TI contribuye a las actividades del negocio, desde un enfoque tradicional hasta uno digital o ágil.
   - Ejemplos de modelos de operación:
     - **Tradicional**: Se centra en la estabilidad y el control, siendo adecuado para empresas con bajo nivel de cambio.
     - **Ágil**: Permite respuestas rápidas a cambios y es ideal para entornos de alta innovación, como en proyectos de transformación digital【40†source】.
   - Building Blocks del modelo:
     - **Infraestructura**: Los recursos tecnológicos básicos.
     - **Procesos y Servicios de TI**: Como desarrollo, soporte y mantenimiento.
     - **Gestión y Gobernanza**: Asegura la alineación de TI con los objetivos del negocio y regula la operación.

2. **Rol de los Sistemas de Información en los Negocios**:
   - Los SI son críticos para **la toma de decisiones, optimización de procesos, mejora de la relación con clientes y proveedores**, y la generación de ventajas competitivas.
   - Objetivos estratégicos de los SI:
     - **Excelencia Operacional**: Mejorar la productividad y eficiencia para reducir costos y aumentar la rentabilidad.
     - **Nuevos Productos y Servicios**: Facilitar la creación de nuevos productos y servicios mediante la innovación tecnológica.
     - **Cercanía con Clientes y Proveedores**: Permitir una relación más estrecha mediante la gestión efectiva de datos.
     - **Toma de Decisiones en Tiempo Real**: Acceso a información actualizada para responder a cambios en el mercado【41†source】.

3. **Ventajas Competitivas**:
   - Los SI pueden ser una fuente de **ventajas competitivas** al permitir que la organización:
     - **Automatice y optimice procesos**: Reduciendo costos y mejorando la eficiencia.
     - **Personalice sus servicios**: Entendiendo las necesidades específicas de sus clientes a través del análisis de datos.
     - **Innove en productos y servicios**: Adaptándose rápidamente a las tendencias del mercado y a las preferencias de los clientes.
     - **Mejore el time-to-market**: Implementando soluciones digitales que permiten respuestas más rápidas y eficaces【41†source】.

### **Ejemplos de Aplicación de Estrategia TI en los Negocios**

- **Caso de Transformación Digital**:
   - Implementación de una **plataforma digital de negocios** que facilite la integración de distintos sistemas de información para optimizar el flujo de datos y mejorar la experiencia del cliente.
   - Un ejemplo real es cómo **Walmart** utiliza su sistema de abastecimiento de tiendas para reducir costos y maximizar la eficiencia, mejorando la experiencia de compra y manteniendo precios competitivos【41†source】.

- **Innovación en Nuevos Modelos de Negocio**:
   - **Apple** y **Uber** son ejemplos de cómo los sistemas de información han permitido transformar modelos de negocio en sus industrias respectivas. Apple redefinió el negocio de la música digital con iTunes, y Uber revolucionó el transporte privado con su plataforma de movilidad.
   - Estas transformaciones han sido posibles gracias a una estrategia de TI enfocada en la experiencia del cliente y en aprovechar al máximo las tecnologías emergentes【41†source】.


---

### **Unidad 2: Arquitectura Empresarial (AE)**

1. **Introducción y Conceptos de Arquitectura Empresarial**:
   - La AE es un **marco de referencia para alinear TI con los objetivos de negocio** mediante una estructura organizada que define procesos, datos, aplicaciones y tecnología【26†source】.

2. **¿Para qué sirve la Arquitectura Empresarial?**:
   - La AE permite **transformar la organización desde el modelo AS-IS (actual) hacia el TO-BE (objetivo futuro)**, optimizando los recursos y promoviendo decisiones estratégicas alineadas con la misión y visión de la empresa【23†source】.

3. **Capas de AE**:
   - La AE se estructura en capas: 
     - **Negocios**: Define la misión, visión y procesos estratégicos.
     - **Aplicaciones**: Incluye el software de soporte para los procesos de negocio.
     - **Datos**: Engloba el manejo y almacenamiento de la información.
     - **Infraestructura**: Hardware y redes que soportan las aplicaciones y datos【26†source】.

4. **Cómo abordar un Proyecto de Implementación de AE**:
   - Inicia con la **definición del modelo AS-IS**, análisis de brechas y diseño del modelo TO-BE. Posteriormente, se desarrollan proyectos que permitan la transformación gradual hacia el modelo deseado【25†source】.

5. **Habilitadores Tecnológicos**:
   - Son las herramientas que impulsan la arquitectura empresarial, como **Big Data, Inteligencia Artificial, IoT, y la nube**. Estos habilitadores facilitan la implementación de la AE y su alineación con la estrategia organizacional【23†source】.

6. **Definición de Roadmap de Implementación**:
   - Es una **hoja de ruta que define los proyectos y fases necesarios para la transformación**. Incluye priorización de iniciativas, tiempos y recursos necesarios para lograr el estado TO-BE【26†source】.

---

### **Unidad 3: Arquitectura en el Mundo Ágil**

1. **Transformación Digital**:
   - La transformación digital implica una **restructuración profunda de la organización**, impulsada por un cambio cultural y la adopción de tecnologías disruptivas. No se trata solo de digitalizar procesos, sino de innovar y crear valor centrado en el cliente【22†source】.

2. **Mindset Ágil**:
   - El enfoque ágil en AE incluye la **flexibilidad y adaptación al cambio**, utilizando marcos como Scrum, Lean Startup y Design Thinking. La agilidad permite iterar rápidamente en función de las necesidades del cliente y del negocio【22†source】.

3. **Arquitectura Transicional y Evolutiva**:
   - La AE en un entorno ágil no es estática; evoluciona conforme cambian las necesidades del negocio. Combina la visión AS-IS y TO-BE en transiciones intermedias, ajustando la arquitectura progresivamente【22†source】.

4. **Modelo de Gobierno en AE Ágil**:
   - Este modelo se basa en **tribus, capítulos y squads** que gestionan diferentes áreas de la arquitectura empresarial en un esquema de colaboración y autonomía. Cada equipo tiene objetivos claros y se alinea con la estrategia general【22†source】.

5. **Otros Artefactos de AE en un Contexto Ágil**:
   - Incluyen *Value Stream Mapping*, *Domain-Driven Design*, *Customer Journey Maps*, y *Minimum Viable Architecture*, herramientas que ayudan a mapear procesos y mejorar la experiencia del cliente de manera continua.

---
---
---

## **Trabajo Integrador - Claro Perú**

### **Descripción de la Organización**

**Claro Perú** es una de las principales compañías de **telecomunicaciones** en el país y opera como subsidiaria de **América Móvil** desde el 10 de agosto de 2005. Su sólida experiencia en el sector y su compromiso con la innovación tecnológica le han permitido consolidarse como líder en telecomunicaciones en Perú, proporcionando servicios de alta calidad y fomentando la inclusión digital. La empresa se centra en la mejora de su infraestructura, incluyendo redes 4G LTE y conexiones de fibra óptica, para expandir su alcance en todo el país.

### **Misión y Visión**

- **Misión**: "Brindamos la mejor experiencia de servicio a través de las más avanzadas soluciones de comunicación, tecnología de información y contenido digital para acelerar el desarrollo de los países donde operamos y promover la igualdad de oportunidades entre la gente."

- **Visión**: "Consolidarnos como un agente de cambio al proporcionar servicios de conectividad y alta tecnología; preservando nuestro liderazgo en la industria de las telecomunicaciones y reafirmando nuestro compromiso con las personas para hacer un mundo más próspero para todos."

### **Valores**

1. **Sustentabilidad**: Claro se compromete a fomentar la inclusión y el desarrollo en la región, buscando un balance entre aspectos económicos, sociales y ambientales.
2. **Desarrollo Humano**: Promueve el crecimiento personal y profesional en un ambiente inclusivo, valorando el respeto, la diversidad y el empoderamiento.
3. **Integridad**: La empresa prioriza la transparencia y el cumplimiento de leyes y principios éticos, generando confianza y seguridad.
4. **Experiencia de Cliente**: Claro pone al cliente en el centro de su negocio, escuchando sus necesidades y ofreciendo soluciones que maximizan su satisfacción.
5. **Eficiencia**: Optimizan sus activos y controlan costos, manteniendo calidad incluso en tiempos de crisis.
6. **Colaboración**: La empresa fomenta la integración de diferentes perspectivas y la participación activa para alcanzar objetivos comunes.
7. **Innovación**: Claro incentiva la creatividad y el aprendizaje continuo, asumiendo riesgos para mejorar y adaptarse al cambio.

### **Mapa de Procesos**

**Claro Perú** organiza sus actividades en tres niveles de procesos para maximizar su eficiencia operativa y alinearse con sus objetivos estratégicos:

1. **Procesos Estratégicos**:
   - **Planeación del Sistema de Gestión Integrado (SGI)**: Alinea las actividades con los objetivos estratégicos y normativas, asegurando la sostenibilidad.

2. **Procesos de Apoyo**:
   - **Gestión Documental**: Organiza y controla la documentación de la empresa.
   - **Gestión de Comunicaciones**: Asegura el flujo adecuado de información dentro y fuera de la empresa.
   - **Gestión de Capacitación**: Garantiza la preparación continua del personal.
   - **Gestión de Presupuesto y Contabilidad de Servicios TI**: Administra los recursos financieros de los servicios tecnológicos.

3. **Procesos Operativos y Principales**:
   - **Preventa**: Alinea los productos y servicios con las necesidades del mercado y los clientes.
   - **Descubrir, Evaluar y Contratar**: Gestión comercial que asegura que la empresa cuenta con la capacidad para satisfacer las demandas del mercado.
   - **Recepción e Implementación**: Organiza los recursos para la entrega e instalación de servicios.
   - **Operación y Mantenimiento**: Asegura el funcionamiento continuo de los servicios contratados.
   - **Experiencia del Cliente**: Escucha y responde a las necesidades del cliente para maximizar su satisfacción.

### **Análisis de Problemas y Necesidades**

Claro Perú enfrenta algunos desafíos en la estandarización de procesos y la integración de sistemas, lo que afecta la experiencia del cliente y la eficiencia operativa. Se identifican problemas tecnológicos, como la falta de registro de cuotas y rentas, así como problemas en la evaluación crediticia, los cuales impactan la satisfacción del cliente y los procesos internos.


### **Arquitectura AS-IS y Propuesta TO-BE**

#### **Arquitectura Actual (AS-IS)**

La arquitectura actual incluye una serie de aplicaciones web y servicios de infraestructura que soportan los procesos de negocio de Claro:

- **Aplicaciones Web (.NET)**:
   - **SISACT y SICAR**: Desarrolladas en .NET y alojadas en servidores Windows Server 2019, estas aplicaciones gestionan la activación y atención al cliente, respectivamente.
- **Servicios de Integración**:
   - **WebLogic, MDB, API y Data Power**: Estos servicios intermedian la comunicación entre aplicaciones y datos, optimizando el flujo de información y el rendimiento del sistema.
- **Bases de Datos Oracle**:
   - **PVUDB, MSINCDB, OAC, y BSCS**: Estas bases de datos Oracle almacenan datos de ventas, clientes y operaciones comerciales, asegurando la seguridad y disponibilidad de la información.

#### **Propuesta de Arquitectura Futura (TO-BE)**

En la arquitectura TO-BE, se plantea optimizar la experiencia del cliente y la competitividad mediante:

1. **Modernización de la Infraestructura**: Migración de servicios clave a la nube para mejorar la escalabilidad, disponibilidad y reducción de costos de mantenimiento.
2. **Integración de Sistemas**: Implementación de un middleware que permita la integración de las diferentes aplicaciones y bases de datos, asegurando una sincronización en tiempo real de la información.
3. **Automatización de Procesos**: Automatización de la evaluación crediticia y del registro de cuotas y rentas para minimizar errores y optimizar la experiencia del cliente.
4. **Habilitadores Digitales**: Uso de tecnologías emergentes como Big Data y análisis predictivo para mejorar la toma de decisiones y ofrecer soluciones personalizadas a los clientes.

---
