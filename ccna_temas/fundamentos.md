# Fundamentos de red

## Conceptos básicos

### Infraestructuras de red

Las infraestructuras varian dependiendo: del tamaño que cubren, el numero de usuarios, numero y tipos de servicios ofrecidos y el area de responsabilidad.

Las más comunes son: 

- Local Area Network (LAN)
    
    Son usadas en departamentos o lugares como una empresa, una casa o un negocio pequeño, donde interconecta dispositivos finales y dispositivos intemedios con un alto ancho de banda. Un control de administracion a niveles de red, gobernanza y politicas de seguridad 
    
- Wide Area Network (WAN)
    
    Es una infraestrutura que ofrece conexión con otras redes en un area geografica extendida, son usadas o manejadas en corporaciones grandes o en proveedores de servicios de telecomunicaciones. Tipicamente provee bajas velocidades
    

Small office and home office (SOHO) permiten trabajar desde casa o desde una oficina remota. Muchos trabajadores autónomos utilizan este tipo de redes para anunciar y vender productos, pedir suministros y comunicarse con los clientes.

### Tipos de dispositivos en la red

| Dispositivos Finales | Dispositivos intermedios |
| --- | --- |
| Los dispostivos finales son dispositivos que pueden obtener o ofrecer un servicio en la red (WEB,EMAIL,FILE)                                                                          La comunicación PEER to PEER o cliente-servidor permite que todos los dispositivos pueden ofrecer un servicio, usualmente puede ser en dispositivos diferentes, pero el cliente puede tener ambos roles               - Facil                                                                                    - menos complejo                                                                  - Menos costo (los dispositivos dedicados pueden no ser necesarios)                                                                      - Usados para transferir archivos y compartir impresoras                                                                          - Pero, no son seguras, no escalables, no tienen administracion centralizada y baja el rendimiento de los equipos | Los dispositivos intermedios tienen como proposito conectar los dispositivos finales:                                                      -Regeneran o transmiten las señales de comunicacion                                                               - Mantiene informacion sobre las rutas que existen entre los dispositivos                                                           - Notifica sobre errores o fallos en la comunicacion          - Direcciona los datos a otras rutas si la principal falla - Clasifica y direcciona mensajes dependiendo de las prioridades                                                                            - Permiten o deniegan el flujo de los datos, basados en las configuraciones de seguridad |



Itrusion Protection System(IPS) - Permite un analisis profundo del trafico de la red, mientras busca signos sobre alga malicioso. Si un IPS detecta una amenaza toma accion inmediata

#### Intranet y extranet

La diferencia entre intranet y extranet, es que la intranet es usada para una conexión privada a la organización, designando acceso unicamente a miembros, empleados o usuarios autorizados

Mientras, la extranet es usada para ofrecer una conexión segura a usuarios externos a la organización.

#### Conexiones de Hogar y oficinas pequeñas

- **Cable** - Envia señales datas por el proveedor, servicio de television, transmision de datos, por el mismo cable. Provee alto ancho de banda, alta disponibilidad, y siempre conexion a internet.
- **DSL (**Digital Subscriber Lines) - provee alto ancho de banda, alta disponibilidad, y siempre conexión. Corren lineas telefonicas. El hogar y las oficinas se conectan con Asymmetrical DSL (ADSL) que tiene una velocidad más alta de descargar que de subida.
- **Cellular** - Acceso a internet para telefonos celulares, se conectan donde sea que se tenga señal. El rendimiento es limitado, depende del telefono y de la torre celular.
- **Satelite** - Disponible para areas donde de otra manera no tendria acceso a internet. Requieren vista clara para conectarse al satelite.
- **Dial-up Telephone** - Usa cualquier linea telefonica y un modem. Bajo ancho de banda proveida por un modemo dial-up, no es suficiente para transferir datos grandes pero es útil para acceso movil mientras se viaja.

#### Conexiones entre empresas

- **Dedicated Leased Line** - Circuitos reservados dentro de la red del proveedor de servicios que conectan oficinas geográficamente separadas para redes privadas de voz y / o datos.
- **Metro Ethernet** - Conocido como Ethernet WAN. Extiende el acceso a la LAN  a la WAN
- **Business DSL** - Business DSL esta disponible en Symmetric digital Subcriber (SDSL) que prove velocidades de carga y descarga similares.
- **Satellite** - Esta disponible para las empresas, que esten en zonas donde es muy dificil disponer de otro tipo de conexiones.

### Redes convergentes

Las redes tradicionales constan de redes que tiene cada servicio (Voz y datos, ejemplo) pasan por diferentes medios o cables, cada medio usa diferentes tecnologias y no pueden comunicarse entre sí.

Las redes convergentes constan de servicios que pasan a través de la misma red, por el mismo medio, utilizan los mismos estandares, mismas reglas y mismo protocolos. Diferentes dispositivos dentro de la misma red.

#### Arquitectura de red

La arquitectura de red se refiere al diseño y la disposición de una red informática, incluyendo su hardware, software, protocolos y medios de comunicación. Es importante asegurarse de que la red esté diseñada para satisfacer las necesidades actuales y futuras de la organización de manera eficiente y efectiva.

Las características básicas de la arquitectura de red incluyen:

- **Fault Tolerance**: se refiere a la capacidad de una red para resistir y recuperarse de fallas de hardware o software sin interrumpir el funcionamiento normal de la red. Esto se logra mediante el uso de componentes de hardware y software redundantes y mecanismos de conmutación por error.
- **Scalability**: la capacidad de una red para adaptarse a las necesidades y el crecimiento cambiantes. Una red escalable puede acomodar fácilmente un aumento en el número de usuarios, dispositivos y tráfico sin afectar el rendimiento.
- **Quality of Service (QoS)**: se refiere a un conjunto de técnicas y protocolos que garantizan que la red pueda proporcionar el nivel de servicio requerido para diferentes tipos de tráfico, aplicaciones y usuarios. Esto incluye aspectos como la asignación de ancho de banda, la cola de prioridad y la conformación de tráfico.
- **Security**: este es un aspecto crítico de la arquitectura de red e incluye medidas como la confidencialidad (Confidentialy), la disponibilidad (Availability) y la integridad (Integrity). La confidencialidad garantiza que la información confidencial esté protegida contra el acceso no autorizado, la disponibilidad garantiza que la red esté siempre disponible para los usuarios autorizados y la integridad garantiza que los datos no sean manipulados o alterados.
- **Reliability**: se refiere a la capacidad de la red para funcionar de manera consistente y predecible con el tiempo. Es un factor que depende de la percepción, ya que los usuarios esperan que la red esté disponible y sea receptiva en todo momento.
- **Cost**: se refiere al costo total de diseñar, implementar y mantener la red. Es importante encontrar un equilibrio entre el costo y el rendimiento, la seguridad y la confiabilidad de la red.

Otro aspecto importante de la arquitectura de red es la virtualización (Virtualization). La virtualización se refiere a la creación de una versión virtual de un dispositivo o recurso, como un servidor, dispositivo de almacenamiento o red. La virtualización permite la consolidación de recursos, una mejor utilización del hardware y una gestión más fácil de la red.

En general, la arquitectura de red es un aspecto crítico de la infraestructura de TI de cualquier organización y debe diseñarse para satisfacer las necesidades actuales y futuras mientras se garantiza la seguridad, la confiabilidad y la rentabilidad.

### Tendencias

-El mundo de la tecnología está en constante evolución y cambio. Aquí hay algunas de las tendencias actuales que están moldeando la industria:

- **Bring your own devices (BYOD)**: Esta tendencia se refiere al número creciente de empleados que utilizan sus propios dispositivos personales, como teléfonos inteligentes y computadoras portátiles, para fines laborales. Esta tendencia tiene tanto beneficios como desventajas, como un aumento en la productividad y preocupaciones de seguridad.
- **Colaboraciones**: Con el aumento del trabajo remoto y los equipos distribuidos, las herramientas de colaboración se han vuelto cada vez más importantes. Desde software de videoconferencia hasta herramientas de gestión de proyectos, hay muchas formas de colaborar con colegas y clientes.
- **Comunicaciones de video**: La comunicación de video se ha convertido en una herramienta esencial tanto para las empresas como para los individuos. Desde videoconferencias hasta transmisiones en vivo, la comunicación de video está cambiando la forma en que nos conectamos con los demás.
- **Computación en la nube**: El uso de la computación en la nube se ha vuelto cada vez más popular en los últimos años. La computación en la nube permite a las empresas y a los individuos acceder a sus archivos y aplicaciones desde cualquier lugar con una conexión a Internet.
- **Tendencias en el hogar**: El uso de la tecnología en el hogar también ha estado en aumento. Dos tendencias actuales en esta área son la tecnología de línea eléctrica, que utiliza el cableado eléctrico para transmitir datos, y WISP (Proveedor de Servicios de Internet Inalámbrico), que proporciona acceso a Internet a áreas rurales.

A medida que la tecnología sigue evolucionando, es importante mantenerse al día con las últimas tendencias y desarrollos para seguir siendo competitivo en la industria.

#### Cómo se comunican los dispositivos

Los dispositivos necesitan seguir ciertas reglas y estándares para comunicarse entre sí. Estas reglas incluyen la codificación, el formato y la encapsulación del mensaje, el tamaño, el tiempo y las opciones de entrega.

- **Message encoding** se refiere a la forma en que los datos se convierten en un formato que puede transmitirse a través de una red. Los diferentes dispositivos y redes pueden utilizar diferentes métodos de codificación.
- **Message formatting and encapsulation** se refieren a la forma en que se estructura y empaqueta los datos para la transmisión. Esto incluye cosas como encabezados y remolques que indican el inicio y el final de los mensajes, y otra información necesaria para que los datos se transmitan y reciban correctamente.
- **Message size** se refiere a la cantidad de datos que pueden transmitirse en un solo mensaje. Esto es importante para garantizar que los mensajes se puedan transmitir de manera eficiente y que puedan recibirse y procesarse rápidamente.
- **Message timing** se refiere a la forma en que se envían y reciben los mensajes a través de una red. Esto incluye cosas como el **Flow control**, **Response timeout** y **Access method**. El control de flujo garantiza que los mensajes se envíen y reciban a una velocidad adecuada para el dispositivo receptor. El tiempo de respuesta asegura que el remitente reciba una respuesta dentro de un cierto período de tiempo. El método de acceso se refiere a la forma en que se permite a los dispositivos acceder a la red para enviar y recibir mensajes.
- **Message delivery options** se refieren a la forma en que se entregan los mensajes a sus destinatarios previstos. Esto incluye cosas como los protocolos de enrutamiento, que garantizan que los mensajes se entreguen al destino correcto, y la corrección de errores, que garantiza que los mensajes se transmitan y reciban sin errores.

Cuando todos estos elementos funcionan correctamente juntos, los dispositivos pueden comunicarse entre sí de manera rápida y eficiente, lo que permite que los datos se transmitan y procesen en tiempo real.

