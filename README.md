# Estudio y Comparación de Métodos para Implementar IPv6 en Redes sin Soporte Nativo

Trabajo Fin de Grado – Ingeniería de Telecomunicaciones (ETSI Sevilla)  
Autor: Adrián Garrido Real  
Calificación: 10 (Sobresaliente)

## 📌 Descripción del proyecto
Este proyecto analiza distintas soluciones para proporcionar conectividad IPv6
en redes donde el ISP no ofrece soporte nativo, comparando su rendimiento real
en escenarios prácticos.

Las soluciones estudiadas incluyen:
- IPv6 nativo proporcionado por el operador
- Túneles IPv6 sobre IPv4 (Hurricane Electric)
- VPN con soporte IPv6
- VPN WireGuard sobre VPS con direccionamiento IPv6 global

## 🧪 Parámetros evaluados
- Latencia y RTT
- Pérdida de paquetes
- Ancho de banda
- Jitter
- MTU y Path MTU Discovery
- Tiempo de resolución DNS
- Número de saltos

## 🛠️ Herramientas utilizadas
- Wireshark
- PingPlotter
- MTR
- NetScanTools
- dig / nslookup
- SpeedTest (Cloudflare)

## 🏗️ Arquitecturas implementadas
Se incluyen diagramas de las distintas topologías empleadas:
- Conectividad IPv6 nativa
- TunnelBroker (Hurricane Electric)
- WireGuard + VPS (Hetzner)

## ⚙️ Configuraciones
En la carpeta `configs/` se incluyen ejemplos reales de configuración:
- TunnelBroker en Windows y Ubuntu
- WireGuard cliente-servidor
- Reglas de forwarding y firewall IPv6

## 📊 Resultados
Los resultados completos de las pruebas están documentados en la carpeta `tests/`,
incluyendo comparativas objetivas entre los distintos métodos.

## 📌 Conclusiones
- IPv6 nativo ofrece el mejor rendimiento general
- WireGuard + VPS es la mejor alternativa controlada y estable
- TunnelBroker es viable pero introduce mayor latencia
- VPNs comerciales son funcionales pero menos predecibles

## 🚀 Posibles mejoras futuras
- Automatización del despliegue con Ansible
- Monitorización continua
- Integración con entornos cloud
- Extensión a escenarios de Data Center


