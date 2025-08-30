**Diseño de Redes LAN - Unidad III: Instalación, Configuración y Mantenimiento**

**Duración:** 30 horas

**Competencias a Desarrollar:**

Al finalizar la Unidad III, el alumno será capaz de:

*   Simular la instalación física y la configuración básica de dispositivos de red (switches y routers).
*   Realizar pruebas de conectividad y diagnosticar problemas básicos.
*   Aplicar principios de mantenimiento preventivo y correctivo en una red LAN.
*   Implementar buenas prácticas de diseño, documentación, etiquetado y seguridad básica en redes.
*   Diseñar e implementar una red LAN funcional en Packet Tracer, documentando todo el proceso.
*   Valorar la importancia de una planificación adecuada y la documentación de la red.



**Secuencia Didáctica - Unidad III**

**Momento 1: Apertura (6 horas)**

**Objetivo:** Conectar los conceptos de diseño con la implementación práctica, introduciendo la configuración de dispositivos y las pruebas de conectividad.

| Actividad del Docente | Actividad del Alumno | Recursos/Herramientas | Tiempo Estimado |
| :-------------------- | :------------------- | :-------------------- | :--------------- |
| **1. Repaso de Unidad II y Enlace con Unidad III:**<br>    *   Revisión de componentes, herramientas, cableado y diagramación.<br>    *   Pregunta disparadora: "Ahora que sabemos diseñar, ¿cómo hacemos que funcione?"<br>    *   Introducción a la configuración y la importancia de la fase de implementación. | **1. Recordatorio y conexión:**<br>    *   Responder preguntas de repaso.<br>    *   Participar en la discusión sobre el paso de diseño a implementación.<br>    *   Plantear dudas iniciales sobre la configuración. | Pizarra/Proyector, Diagrama de flujo del proceso de red. | 0.5 horas |
| **2. Instalación Física de la Red (6.1):**<br>    *   Discusión sobre la preparación del sitio, tendido de cableado, montaje de racks y equipos (Switch, Router, Patch Panel).<br>    *   Énfasis en la organización, limpieza y estándares de seguridad en la instalación.<br>    *   Presentación de fotos/videos de instalaciones profesionales vs. desordenadas. | **2. Visualización y concientización:**<br>    *   Observar ejemplos y contrastar.<br>    *   Discutir la importancia de una instalación ordenada y profesional.<br>    *   Plantear posibles desafíos en una instalación real. | Proyector, Fotos/Videos de instalaciones de red (buenas y malas prácticas). | 1.5 horas |
| **3. Configuración Básica de Dispositivos (Switch y Router) (6.2):**<br>    *   Introducción a la interfaz de línea de comandos (CLI) de Cisco (modo usuario, modo privilegiado, modo configuración global).<br>    *   Configuración básica de Switch: nombre de host, contraseñas, descripción de interfaces (conceptualmente).<br>    *   Configuración básica de Router: nombre de host, contraseñas, configuración de interfaces IP, ruta estática (concepto).<br>    *   **Práctica Guiada 1 (Packet Tracer):** Acceso a CLI de un Switch y Router, configuración de nombre de host y contraseñas simples. | **3. Familiarización con CLI y configuración:**<br>    *   Observar la demostración.<br>    *   Identificar los diferentes modos de la CLI.<br>    *   Realizar la práctica guiada en Packet Tracer, configurando los parámetros básicos. | Computadoras con Packet Tracer, Proyector, Guías de comandos CLI básicos. | 3 horas |
| **4. Pruebas de Conectividad (6.3):**<br>    *   Explicación de herramientas de prueba: `ping`, `traceroute` (Packet Tracer), `ipconfig` (PC).<br>    *   Interpretación de resultados (paquetes perdidos, tiempo de respuesta).<br>    *   **Práctica Guiada 2 (Packet Tracer):** Realizar `ping` entre dispositivos de una pequeña LAN. Identificar y solucionar un problema de conectividad sencillo (ej. IP mal configurada). | **4. Diagnóstico inicial:**<br>    *   Aprender a usar las herramientas de prueba.<br>    *   Realizar las pruebas indicadas.<br>    *   Practicar la identificación y corrección de un error básico. | Computadoras con Packet Tracer, Escenarios simples con errores predefinidos. | 1 hora |

**Momento 2: Desarrollo (18 horas)**

**Objetivo:** Desarrollar habilidades en configuración más avanzada, mantenimiento y aplicación de buenas prácticas de diseño.

| Actividad del Docente | Actividad del Alumno | Recursos/Herramientas | Tiempo Estimado |
| :-------------------- | :------------------- | :-------------------- | :--------------- |
| **1. Configuración Detallada de Switch (Packet Tracer):**<br>    *   Configuración de VLANs (introducción, creación, asignación de puertos).<br>    *   Configuración de Spanning Tree Protocol (STP) - concepto básico.<br>    *   **Práctica Guiada 3:** Crear dos VLANs en un Switch, asignar puertos y verificar conectividad entre dispositivos de la misma VLAN. | **1. Configuración avanzada de Switch:**<br>    *   Seguir la guía para configurar VLANs.<br>    *   Verificar que la separación de redes funcione.<br>    *   Experimentar con la asignación y reasignación de puertos a VLANs. | Computadoras con Packet Tracer, Escenario con Switch, PCs. | 4 horas |
| **2. Configuración Detallada de Router (Packet Tracer):**<br>    *   Configuración de enrutamiento estático.<br>    *   Configuración de DHCP (para asignar IPs automáticamente a PCs).<br>    *   **Práctica Guiada 4:** Configurar enrutamiento estático entre dos redes conectadas por un Router. Configurar un servidor DHCP en el Router para una de las redes. | **2. Configuración de enrutamiento y DHCP:**<br>    *   Configurar las rutas estáticas necesarias.<br>    *   Configurar el servidor DHCP y verificar que los clientes obtengan IPs.<br>    *   Probar la conectividad entre las redes. | Computadoras con Packet Tracer, Escenario con Router, 2 Switches, PCs. | 4 horas |
| **3. Mantenimiento Preventivo y Correctivo (7.1 - 7.3):**<br>    *   **Preventivo:** Importancia de la limpieza (ventiladores, puertos), orden y etiquetado (cables, puertos, equipos).<br>    *   **Correctivo:** Metodología para la detección de fallas (capas del modelo OSI - breve, enfoque de arriba hacia abajo/abajo hacia arriba). Ejemplos de fallas comunes (cable desconectado, IP duplicada, configuración errónea).<br>    *   **Práctica Autónoma 1 (Packet Tracer):** Dado un escenario con una falla predefinida (ej. un cable desconectado o una IP mal configurada), diagnosticar y solucionar el problema usando `ping`/`ipconfig`. | **3. Diagnóstico y soluciones:**<br>    *   Discutir la importancia del mantenimiento.<br>    *   Aplicar la metodología de detección de fallas.<br>    *   Resolver el escenario de falla en Packet Tracer y documentar el proceso de solución. | Proyector, Casos de estudio de fallas, Escenarios de Packet Tracer con fallas. | 4 horas |
| **4. Buenas Prácticas de Diseño de Redes LAN:**<br>    *   **Documentación de la Red:** Qué documentar (diagramas, IPs, configuraciones, contraseñas, inventario).<br>    *   **Uso de Normas de Color y Etiquetado:** Ejemplos prácticos y su impacto en el mantenimiento.<br>    *   **Seguridad Básica en la Red:** Contraseñas seguras, deshabilitar puertos no usados, firewall básico (conceptos).<br>    *   **Planificación de Crecimiento Futuro:** Diseñar redes escalables, considerar expansiones. | **4. Aplicación de estándares:**<br>    *   Crear una plantilla simple para documentar una red.<br>    *   Diseñar un esquema de etiquetado para un rack de servidores.<br>    *   Discutir cómo implementar medidas de seguridad básicas. | Pizarra/Proyector, Ejemplos de documentación, Plantillas. | 3 horas |
| **5. Práctica Autónoma 2 (Packet Tracer):**<br>    *   Diseñar y configurar una red LAN para un escenario dado (ej. una oficina con dos departamentos, cada uno en una VLAN, con un Router conectándolos y proporcionando DHCP). Los alumnos deben aplicar todo lo aprendido: configuración de Switch, Router, DHCP, pruebas de conectividad. | **5. Diseño y configuración integral:**<br>    *   Diseñar la red según el escenario.<br>    *   Configurar todos los dispositivos.<br>    *   Verificar la conectividad completa. | Computadoras con Packet Tracer, Descripción del escenario. | 3 horas |

**Momento 3: Cierre (6 horas)**

**Objetivo:** Consolidar el aprendizaje a través de un proyecto final integrador, evaluar la adquisición de competencias y reflexionar sobre la importancia del diseño de redes.

| Actividad del Docente | Actividad del Alumno | Recursos/Herramientas | Tiempo Estimado |
| :-------------------- | :------------------- | :-------------------- | :--------------- |
| **1. Revisión General y Preparación para el Proyecto Final:**<br>    *   Repaso de los puntos clave de la Unidad III.<br>    *   Sesión de preguntas y respuestas para resolver cualquier duda antes del proyecto. | **1. Consolidación de conocimientos:**<br>    *   Participar activamente en el repaso.<br>    *   Plantear dudas finales. | Pizarra/Proyector, Resumen de comandos clave. | 1 hora |
| **2. Presentación del Proyecto Final Integrador:**<br>    *   Explicar detalladamente el proyecto (ver sección "Proyecto Final").<br>    *   Presentar y explicar la Lista de Cotejo y la Rúbrica de evaluación.<br>    *   Aclarar todas las dudas sobre las expectativas del proyecto. | **2. Comprender y planificar el proyecto:**<br>    *   Tomar notas sobre los requisitos y criterios de evaluación.<br>    *   Comenzar la planificación de su enfoque para el proyecto. | Descripción del Proyecto Final, Lista de Cotejo, Rúbrica. | 1 hora |
| **3. Desarrollo del Proyecto Final Integrador:**<br>    *   Asesoramiento y soporte continuo a los alumnos mientras trabajan en el proyecto.<br>    *   Revisión de avances y provisión de feedback. | **3. Ejecución del proyecto:**<br>    *   Diseñar, configurar y documentar la red según el proyecto.<br>    *   Realizar pruebas exhaustivas de conectividad.<br>    *   Preparar la presentación o entrega final. | Computadoras con Packet Tracer, Draw.io, Materiales de apoyo del curso. | 3 horas |
| **4. Conclusiones y Evaluación Final del Curso:**<br>    *   Recopilación y evaluación de los proyectos finales.<br>    *   Discusión grupal sobre la experiencia y aprendizajes del curso.<br>    *   Resumen de la importancia de diseñar correctamente una red LAN.<br>    *   Recopilación de encuestas de satisfacción. | **4. Entrega y reflexión:**<br>    *   Entregar el proyecto final.<br>    *   Participar en la discusión final.<br>    *   Completar la encuesta de retroalimentación del curso. | Proyector (para posibles presentaciones de proyectos), Encuesta de satisfacción. | 1 hora |

---

**Proyecto Final Integrador: "Diseño e Implementación de la Red LAN para una Sucursal Bancaria Pequeña"**

**Descripción:**

Una pequeña sucursal bancaria necesita una red LAN segura y funcional. La sucursal consta de:

*   **Área de Atención al Cliente:** 3 estaciones de trabajo para cajeros, 1 impresora de red.
*   **Oficina de Gerencia:** 1 PC.
*   **Oficina de Asesoría:** 2 PCs.
*   **Sala de Reuniones:** Acceso Wi-Fi para invitados (con una VLAN separada por seguridad).
*   **Sala de Servidores:** 1 servidor (para aplicaciones bancarias), 1 Firewall (simulado por un Router con ACLs).
*   **Conectividad a Internet:** Necesaria para todas las áreas.

**Objetivo:** Diseñar, configurar y documentar una red LAN completa en Packet Tracer que satisfaga estos requerimientos, aplicando todas las competencias adquiridas en el curso.

**Tareas a Realizar:**

1.  **Recolección de Requerimientos:** (Simulado) Detallar necesidades de usuarios, seguridad, rendimiento y crecimiento.
2.  **Diseño Lógico de la Red (en Packet Tracer):**
    *   Seleccionar y ubicar los dispositivos de red (Routers, Switches, Access Points, Servidores, PCs, Impresoras).
    *   **Segmentación con VLANs:** Crear al menos 3 VLANs:
        *   VLAN 10: Área de Atención al Cliente y Oficinas.
        *   VLAN 20: Servidores (Alta Seguridad).
        *   VLAN 30: Wi-Fi Invitados (Aislamiento total).
    *   **Direccionamiento IP:** Planificar y asignar direccionamiento IP estático para servidores, Router y Switch. Configurar DHCP en el Router para las VLANs de usuarios y Wi-Fi.
    *   **Enrutamiento:** Configurar el Router para permitir la comunicación entre las VLANs y el acceso a Internet.
    *   **Seguridad Básica (ACLs):** Implementar una ACL (Access Control List) en el Router para simular un Firewall, permitiendo solo el acceso del área de servidores a la red principal, y denegando el acceso de la VLAN de invitados a la red principal.
    *   **Conectividad:** Verificar la conectividad completa entre todas las áreas autorizadas y el acceso a Internet.
3.  **Diseño Físico de la Red (en Draw.io o similar):**
    *   Crear un diagrama físico de la red sobre un plano de planta (proporcionado por el docente o dibujado).
    *   Indicar la ubicación de todos los dispositivos, el tendido estimado del cableado y los puntos de red.
    *   Utilizar esquemas de etiquetado para cables y puertos.
4.  **Configuración de Dispositivos:**
    *   Configurar los nombres de host, contraseñas y mensajes de banner en todos los dispositivos de red.
    *   Guardar la configuración.
5.  **Documentación Completa:**
    *   Entregar un documento de Word con:
        *   Requerimientos detallados.
        *   Diagrama Lógico (captura de Packet Tracer).
        *   Diagrama Físico (creado en Draw.io o similar).
        *   Tabla de Direccionamiento IP (incluyendo VLANs, subredes, IPs de gateway, DHCP ranges).
        *   Configuraciones completas de Switch(es) y Router (comandos utilizados).
        *   Justificación de las decisiones de diseño (VLANs, seguridad, etc.).
        *   Listado de materiales y herramientas requeridas para una implementación real.
        *   Conclusiones y reflexiones sobre el proyecto.
    *   Archivo `.pkt` de Packet Tracer con la configuración funcionando.

---

**Lista de Cotejo para Evaluación del Proyecto Final**

| Criterio | Sí/No | Observaciones |
| :------- | :---- | :------------ |
| **Diseño Lógico (Packet Tracer)** | | |
| Se utilizan dispositivos adecuados (Router, Switches, APs, PCs, Servidor). | | |
| Se implementan 3 VLANs según lo solicitado. | | |
| El direccionamiento IP es coherente y sin conflictos. | | |
| DHCP está correctamente configurado para las VLANs de usuarios y Wi-Fi. | | |
| Se configura el enrutamiento para comunicación entre VLANs y a Internet. | | |
| Se implementa una ACL básica para seguridad entre VLANs. | | |
| La conectividad es total entre dispositivos autorizados (ping exitoso). | | |
| **Configuración de Dispositivos** | | |
| Nombre de host configurado en todos los dispositivos. | | |
| Contraseñas de acceso a la CLI configuradas. | | |
| Configuración guardada en los dispositivos. | | |
| **Diseño Físico (Diagrama)** | | |
| El diagrama físico es claro y fácil de entender. | | |
| Incluye ubicación de todos los dispositivos de red y puntos de red. | | |
| El tendido de cableado se representa de forma lógica. | | |
| Se utilizan esquemas de etiquetado o referencias claras. | | |
| **Documentación Escrita** | | |
| Se detallan los requerimientos de la red. | | |
| Se incluye tabla de direccionamiento IP completa. | | |
| Se anexan las configuraciones de los dispositivos. | | |
| Se justifica claramente las decisiones de diseño (VLANs, seguridad). | | |
| Se presenta un listado de materiales y herramientas. | | |
| La redacción y ortografía son correctas. | | |
| **Presentación y Entrega** | | |
| Archivo `.pkt` entregado y funcional. | | |
| Documento de Word completo y organizado. | | |

---

**Rúbrica de Evaluación del Proyecto Final**

| Criterio | Sobresaliente (4 puntos) | Notable (3 puntos) | Aprobado (2 puntos) | Insuficiente (1 punto) |
| :------- | :----------------------- | :------------------- | :------------------ | :--------------------- |
| **1. Diseño Lógico y Configuración (30%)** | La red es completamente funcional, todas las VLANs y el enrutamiento están impecablemente configurados. DHCP y ACLs operan sin errores. Alta eficiencia y robustez. | La red es funcional con algunas pequeñas configuraciones menores que optimizar. DHCP, VLANs y enrutamiento funcionan correctamente. ACLs presentes. | La red es parcialmente funcional, algunas configuraciones presentan errores que impiden la conectividad total. DHCP o ACLs con fallos. | La red no es funcional o presenta fallos críticos en la mayoría de sus configuraciones. |
| **2. Aplicación de Buenas Prácticas (25%)** | Demuestra una aplicación ejemplar de VLANs, seguridad básica, direccionamiento IP optimizado y escalabilidad. | Buena aplicación de las prácticas, con pequeñas áreas de mejora en la optimización o seguridad. | Aplicación básica de las prácticas, con algunas omisiones o errores conceptuales. | Poca o nula aplicación de buenas prácticas en el diseño y configuración. |
| **3. Diseño Físico y Etiquetado (20%)** | Diagrama físico profesional, claro, preciso y detallado. Etiquetado lógico y coherente. | Diagrama físico claro y correcto. Etiquetado presente y funcional. | Diagrama físico entendible, pero con detalles omitidos o inexactos. Etiquetado inconsistente. | Diagrama físico confuso, incompleto o incorrecto. Sin etiquetado. |
| **4. Documentación Completa (15%)** | Documento exhaustivo, profesional y claro, que incluye todos los ítems solicitados con gran detalle y justificación. | Documento completo con todos los ítems solicitados, bien organizado. | Documento con omisiones menores o falta de detalle en algunos apartados. | Documento incompleto, desorganizado o con información incorrecta. |
| **5. Pruebas y Solución de Fallas (10%)** | Pruebas de conectividad exhaustivas, que demuestran la funcionalidad de toda la red. Capacidad de identificar y solucionar problemas eficientemente. | Pruebas de conectividad correctas. Identificación y solución de la mayoría de los problemas. | Pruebas de conectividad básicas, con algunos errores no identificados o solucionados. | No se realizaron pruebas de conectividad o se muestran fallos evidentes sin solución. |
| **Puntuación Final** | **17-20** | **13-16** | **9-12** | **<9** |

---

**Glosario de Términos (Adicionales y Repaso de Unidad III)**

*   **ACL (Access Control List):** Lista de reglas configurada en un router o firewall para controlar el tráfico de red, permitiendo o denegando el paso de paquetes.
*   **CLI (Command Line Interface):** Interfaz de línea de comandos; método para interactuar con dispositivos de red (como routers y switches) mediante comandos de texto.
*   **Configuración Básica:** Ajustes iniciales de un dispositivo de red, como nombre de host, contraseñas, y direcciones IP de interfaz.
*   **DHCP (Dynamic Host Configuration Protocol):** Protocolo que asigna automáticamente direcciones IP y otros parámetros de red a los dispositivos clientes.
*   **Detección de Fallas:** Proceso sistemático para identificar la causa raíz de un problema en la red.
*   **Documentación de Red:** Registros detallados de la configuración, topología, inventario y políticas de una red.
*   **Enrutamiento Estático:** Configuración manual de rutas en un router para dirigir el tráfico hacia destinos específicos.
*   **`ipconfig`:** Comando en sistemas Windows para ver la configuración de red de un adaptador (dirección IP, máscara, gateway).
*   **Mantenimiento Correctivo:** Acciones tomadas para reparar una falla o interrupción en la red.
*   **Mantenimiento Preventivo:** Acciones regulares realizadas para evitar fallas y asegurar el correcto funcionamiento de la red (limpieza, etiquetado).
*   **`ping`:** Utilidad de red para comprobar la accesibilidad de un host en una red IP y medir el tiempo que tardan en llegar los paquetes.
*   **`traceroute` (o `tracert`):** Utilidad de red que muestra la ruta que toman los paquetes a través de una red hasta un destino, identificando cada salto (router).
*   **VLAN (Virtual Local Area Network):** Red de área local lógica que permite agrupar dispositivos de red, aunque estén conectados físicamente a diferentes switches, como si estuvieran en la misma red.

---

**Conclusiones**

A lo largo de este curso, hemos explorado los fundamentos esenciales para el diseño de redes LAN. Desde la comprensión de los conceptos básicos y la identificación de componentes, hasta la habilidad práctica de ensamblar cables y la configuración de dispositivos, cada unidad ha construido una base sólida. Hemos aprendido que un diseño de red efectivo no solo implica la conectividad, sino también la consideración de estándares, la implementación de seguridad básica, la planificación para el futuro y, crucialmente, una documentación meticulosa.

Diseñar correctamente una red LAN es de vital importancia en el mundo actual. Una red bien diseñada es sinónimo de eficiencia operativa, alta disponibilidad, seguridad robusta y facilidad de mantenimiento. Por el contrario, un diseño deficiente puede llevar a problemas de rendimiento, vulnerabilidades de seguridad, altos costos de soporte y limitaciones en el crecimiento.

Las habilidades adquiridas, especialmente a través de la práctica con Packet Tracer, permiten a los alumnos no solo comprender la teoría, sino también aplicar esos conocimientos en escenarios realistas, preparando el terreno para futuras especializaciones en el campo de las redes y las tecnologías de la información.

---

**Referencias Bibliográficas y Recursos**

1.  **Libros:**
    *   **"Redes de Computadoras"** de Andrew S. Tanenbaum. (6ta Edición o posterior). Prentice Hall.
    *   **"Guía de redes para principiantes"** de Todd Lammle. (Colección de Cisco Press).
    *   **"CCNA 200-301 Official Cert Guide, Volume 1 & 2"** de Wendell Odom. Cisco Press. (Excelente para detalles de configuración de Cisco).
    *   **"Guía de Mantenimiento y Reparación de Redes"** de Stephen Bigelow.
2.  **Recursos en Línea:**
    *   **Cisco Networking Academy:** [https://www.netacad.com/es/](https://www.netacad.com/es/) (Plataforma oficial con cursos y recursos de Packet Tracer).
    *   **Documentación oficial de Cisco:** [https://www.cisco.com/c/en/us/support/index.html](https://www.cisco.com/c/en/us/support/index.html) (Para consultar comandos y configuraciones específicas de dispositivos Cisco).
    *   **Tutoriales en YouTube:** Canales como "Jeremy's IT Lab" (inglés) o "Configuración de redes Cisco" (español) ofrecen guías prácticas de configuración.
    *   **Websites de estándares:** IEEE (802.3, 802.11), TIA/EIA (568) para consulta de normativas.
    *   **Draw.io / Lucidchart / Miro:** Tutoriales en línea para crear diagramas de red.

---

**Anexos (Opcional - Ejemplos para incluir si el curso lo permite)**

*   **Anexo A: Diagramas Adicionales:**
    *   Ejemplo de un diagrama de cableado estructurado.
    *   Diagramas de flujo para detección de fallas comunes.
*   **Anexo B: Fotografías del Proceso de Ensamblaje:**
    *   Imágenes paso a paso de cómo crimpar un cable RJ45.
    *   Fotos de herramientas de red.
*   **Anexo C: Ejercicios Prácticos Suplementarios:**
    *   Pequeños escenarios adicionales en Packet Tracer para configuración de DHCP o VLANs.
    *   Lista de comandos esenciales de Cisco CLI para consulta rápida.

---

Este extenso documento te proporcionará una base sólida y bien organizada para impartir tu curso "Diseña la Red LAN". ¡Espero que sea de gran ayuda!
