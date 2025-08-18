# Resumen del Repositorio – Grupo 8
# Integrantes: 
- Omar Larrea
- Rommel Arevalo
- Henry Barreno
 
## Proyecto elegido: ZMap

## Aportes Personales:
## Omar Larrea
ZMap es una herramienta de código abierto diseñada para realizar escaneos masivos de Internet de manera rápida y eficiente. Permite recorrer grandes rangos de direcciones IP en pocos minutos, identificando hosts activos y servicios disponibles. A diferencia de Nmap, que se centra en el detalle, ZMap está optimizado para la velocidad y el análisis a gran escala, siendo capaz de escanear toda la red IPv4 pública en un tiempo reducido. Se utiliza ampliamente en investigaciones académicas y de seguridad, por ejemplo, para medir la adopción de protocolos como HTTPS o IPv6. Su uso requiere precaución, ya que el volumen de tráfico que genera puede confundirse con un ataque si no se maneja de forma responsable.

## Rommel Arevalo
La herramienta zmap resulta en una opcion interesante en comparación con la comunmente utilizada para escaneo de red NMAP, ademas de brindarnos mas información para la fase del descubrimiento, misma que puede ser utilizada para diversos laboratorios o ejercicios de pentester.

## Henry Barreno
ZMap es un escáner de red de alto rendimiento diseñado para realizar exploraciones masivas de Internet de forma rápida y eficiente, gracias a un algoritmo de permutación de direcciones IP basado en aritmética modular que permite recorrer el espacio IPv4 sin repeticiones ni altos consumos de memoria; esta arquitectura le permite enviar más de un millón de paquetes por segundo en hardware convencional, lo que lo convierte en una herramienta idónea para estudios de gran escala como la recolección de certificados TLS, la detección de servicios expuestos y la investigación en seguridad de IoT, diferenciándose de Nmap por priorizar velocidad y amplitud en lugar de profundidad, y consolidándose como una de las herramientas más citadas tanto en el ámbito académico como en la industria de la ciberseguridad

## ELECCION DEL REPOSITORIO
Elegimos el repositorio Zmap porque es una herramienta ampliamente reconocida en el ámbito de la ciberseguridad y la investigación académica. Su capacidad para realizar escaneos de red de alta velocidad lo convierte en un recurso ideal para analizar la superficie de ataque de grandes infraestructuras en Internet. Según el libro Network Security Assessment de Chris McNab (O’Reilly, 2016), herramientas de escaneo a gran escala como Zmap permiten a los analistas detectar servicios expuestos y evaluar riesgos de forma eficiente. Además, en foros como Security StackExchange y la propia documentación de GitHub, Zmap es recomendado por la comunidad para tareas de auditoría y pruebas de penetración en entornos controlados. Estos criterios técnicos, sumados a su constante mantenimiento y popularidad en proyectos de seguridad, justifican su elección como repositorio de trabajo.

## DESCRICIÓN GENERAL 

**ZMap** es una herramienta de *scanning* de red de código abierto diseñada para realizar escaneos masivos de Internet de manera rápida y eficiente. Permite descubrir dispositivos conectados, servicios expuestos y configuraciones inseguras en cuestión de minutos.
 
## Utilidad

- **Escaneo de redes a gran escala**: Puede analizar el espacio IPv4 completo en menos de una hora usando hardware estándar.

- **Detección de vulnerabilidades**: Identificación de puertos abiertos y servicios potencialmente inseguros.

- **Investigación académica y científica**: Se utiliza en estudios sobre seguridad de Internet, censura y medición de protocolos.

- **Resiliencia y respuesta a incidentes**: Útil para identificar activos expuestos de una organización y reducir superficie de ataque.
 
## Justificación técnica de la elección

1. **Alto rendimiento**: A diferencia de herramientas tradicionales como Nmap, ZMap está optimizado para escaneos a gran escala, con soporte para millones de paquetes por segundo.

2. **Relevancia en investigación**: Ha sido utilizado en múltiples papers académicos sobre seguridad de Internet y ciberinfraestructura.

3. **Código abierto y comunidad activa**: Más de 5K estrellas en GitHub y mantenido por la Universidad de Míchigan, lo que aporta respaldo académico y técnico.

4. **Aplicabilidad en ciberseguridad ofensiva y defensiva**: Es útil tanto para pentesters (red teaming) como para defensores (blue teaming) en la gestión de exposición de activos.
 
## Referencias

- Durumeric, Z., et al. (2013). *ZMap: Fast Internet-wide Scanning and its Security Applications*. USENIX Security Symposium.  

- Allman, M., & Paxson, V. (2007). *Issues and etiquette concerning use of shared measurement data*. IMC.  

- GitHub – ZMap repository: [https://github.com/zmap/zmap](https://github.com/zmap/zmap)
 
