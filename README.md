# PAC_PRJ001_Dewatering_Panel
# Tablero de Control para Bombeo Dewatering

**Proyecto 001 | Prada Automation & Control S.A.C.**

## Descripción del Proyecto
Diseño de ingeniería "As-Built" para un tablero de control de arranque directo, destinado a una bomba de extracción de agua (Dewatering) en operaciones mineras subterráneas. 

El diseño prioriza la seguridad integral del operador al implementar una lógica de mando completamente aislada a 24VDC, separada del circuito de fuerza trifásico, cumpliendo con los exigentes estándares de protección de la industria pesada.

## Especificaciones Técnicas
* **Consumidor:** Motor de inducción trifásico de 7.5 kW (10 HP) / 380 VAC.
* **Corriente Nominal (In):** 14.5 A.
* **Tensión de Control:** 24 VDC (Fuente Conmutada Trifásica 120W).
* **Normativa Aplicada:** IEC 60617 para esquemas y simbología eléctrica.
* **Software de Diseño:** EPLAN Electric P8.

## Criterios de Diseño y Seguridad
* **Selectividad:** Coordinación de protecciones con guardamotor ajustado (10-16A) para la carga y disyuntor termomagnético Curva C independiente para la protección de la fuente de mando.
* **Aislamiento:** Eliminación del riesgo de electrocución en botoneras de campo gracias a la conversión DC.
* **Jerarquía de Parada:** Parada de emergencia de accionamiento manual positivo, cableada con prioridad absoluta en la lógica de control.

## Siguientes Fases (Roadmap)
Este diseño es la Fase 1 (Control Manual Seguro). La arquitectura del tablero ha sido preparada para una futura integración (Fase 2) que incluirá:
- [ ] Integración de Autómata Programable (PLC).
- [ ] Control automático mediante sensores de nivel ultrasónicos en poza.
- [ ] Alternancia automática para sistemas de bombeo redundantes.
