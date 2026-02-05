## Conclusiones

A lo largo de este trabajo se ha demostrado que la disponibilidad de conectividad IPv6
depende en gran medida del soporte ofrecido por el operador, siendo el escenario con
IPv6 nativo el que presenta mejores resultados en todos los parámetros evaluados
(latencia, pérdida de paquetes, estabilidad y simplicidad de configuración).

En aquellos casos en los que el operador no ofrece soporte IPv6, las soluciones basadas
en túneles y VPNs permiten una transición funcional, aunque introducen penalizaciones
derivadas del encapsulamiento y del número adicional de saltos en la red.

Entre las alternativas analizadas, la solución basada en WireGuard sobre un VPS con
direccionamiento IPv6 global ha demostrado ser la opción más equilibrada, ofreciendo
un buen rendimiento, mayor control sobre la infraestructura y una estabilidad superior
frente a soluciones de túneles automáticos o VPNs comerciales.

El uso de túneles IPv6 sobre IPv4, como TunnelBroker, resulta viable para entornos de
pruebas o uso doméstico, pero presenta mayores valores de latencia y dependencia de
infraestructura externa, lo que limita su idoneidad para entornos productivos exigentes.

Finalmente, este estudio pone de manifiesto que la transición a IPv6 no debe abordarse
únicamente desde un punto de vista teórico, sino mediante pruebas reales, mediciones
objetivas y un análisis comparativo que permita seleccionar la solución más adecuada
según el contexto operativo, los requisitos de rendimiento y el nivel de control deseado
sobre la red.
