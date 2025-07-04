# 4. Direccionamiento IP: IPv4 vs IPv6
¿Qué es una dirección IP?
Una dirección IP (Internet Protocol) es un identificador numérico único que se asigna a cada dispositivo conectado a una red que utiliza el protocolo de Internet. Funciona como una "dirección postal" digital que permite que los datos encuentren su camino hacia el dispositivo correcto en la red.
Estructura básica de una dirección IP
IPv4

Formato: Cuatro octetos separados por puntos
Ejemplo: 192.168.1.1
Rango por octeto: 0 a 255
Total de direcciones: ~4.3 mil millones
Representación binaria: 32 bits divididos en 4 grupos de 8 bits

IPv6

Formato: Ocho grupos de cuatro dígitos hexadecimales separados por dos puntos
Ejemplo: 2001:0db8:85a3:0000:0000:8a2e:0370:7334
Rango por grupo: 0000 a FFFF
Total de direcciones: ~340 undecillones
Representación binaria: 128 bits divididos en 8 grupos de 16 bits

Diferencia entre IP pública y privada
Direcciones IP públicas

Únicas globalmente en Internet
Asignadas por el proveedor de servicios de Internet (ISP)
Permiten comunicación directa con otros dispositivos en Internet
Son enrutables a través de Internet

Direcciones IP privadas

Solo válidas dentro de una red local
Se utilizan para comunicación interna entre dispositivos
No son enrutables directamente por Internet
Rangos reservados para IPv4:

10.0.0.0 a 10.255.255.255
172.16.0.0 a 172.31.255.255
192.168.0.0 a 192.168.255.255



Principales diferencias entre IPv4 e IPv6
Ventajas de IPv6

✅ Mayor espacio de direcciones (soluciona el agotamiento de IPv4)
✅ Mejor seguridad integrada con IPSec
✅ Configuración automática más eficiente
✅ Mejor calidad de servicio (QoS)
✅ Eliminación de la necesidad de NAT (Network Address Translation)

Desafíos de la transición

⚠️ Falta de compatibilidad directa entre IPv4 e IPv6
⚠️ Necesidad de infraestructura dual durante la transición
⚠️ Complejidad en la configuración inicial
⚠️ Adopción gradual por parte de proveedores y organizaciones

Conclusión
La transición hacia IPv6 es inevitable debido al agotamiento de direcciones IPv4, pero ambos protocolos seguirán coexistiendo durante muchos años mientras se completa la migración global.

Tabla comparativa rápida
CaracterísticaIPv4IPv6Longitud32 bits128 bitsFormatoDecimal con puntosHexadecimal con dos puntosDirecciones disponibles~4.3 mil millones~340 undecillonesSeguridadOpcionalIntegradaConfiguraciónManual/DHCPAutomáticaNATRequeridoNo necesario

# 5. 🌐 Puertos y Protocolos Comunes para Desarrolladores Web
¿Qué es un puerto?
Un puerto es un punto de conexión lógico que permite a los programas de computadora comunicarse entre sí a través de una red. En el contexto de desarrollo web, los puertos actúan como "puertas" específicas por las cuales los servicios y aplicaciones pueden enviar y recibir datos.
Los puertos se identifican mediante números del 0 al 65535, donde:

Puertos 0-1023: Puertos privilegiados o del sistema, reservados para servicios estándar
Puertos 1024-49151: Puertos registrados, asignados por la IANA para aplicaciones específicas
Puertos 49152-65535: Puertos dinámicos o privados, disponibles para uso general

Puertos Típicos en Desarrollo Web
Puerto 80 (HTTP)

Protocolo: HTTP (HyperText Transfer Protocol)
Uso: Navegación web estándar, páginas web no cifradas
Características: Puerto predeterminado para sitios web, no requiere especificación en la URL

Puerto 443 (HTTPS)

Protocolo: HTTPS (HTTP Secure)
Uso: Navegación web segura con cifrado SSL/TLS
Características: Puerto predeterminado para sitios web seguros, datos cifrados en tránsito

Puerto 22 (SSH)

Protocolo: SSH (Secure Shell)
Uso: Acceso remoto seguro a servidores, transferencia de archivos
Características: Conexión cifrada, autenticación mediante claves o contraseñas

Puerto 3306 (MySQL)

Protocolo: MySQL Database Protocol
Uso: Conexión a bases de datos MySQL
Características: Puerto predeterminado para servidores MySQL, comunicación cliente-servidor

Otros Puertos Relevantes para Desarrolladores

Puerto 21: FTP (File Transfer Protocol)
Puerto 25: SMTP (Simple Mail Transfer Protocol)
Puerto 53: DNS (Domain Name System)
Puerto 110: POP3 (Post Office Protocol)
Puerto 143: IMAP (Internet Message Access Protocol)
Puerto 993: IMAPS (IMAP Secure)
Puerto 995: POP3S (POP3 Secure)
Puerto 3000: Desarrollo local (Node.js, React, etc.)
Puerto 5000: Desarrollo local (Flask, otros frameworks)
Puerto 8000: Desarrollo local (Django, servidores de prueba)
Puerto 8080: Proxy HTTP alternativo, servidores de desarrollo

