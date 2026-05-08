# PAC_PRJ001_Dewatering_Panel
# Tablero de Control para Bombeo Dewatering

**Proyecto 001 | Prada Automation & Control S.A.C.**

## Descripción del Proyecto
Diseño de ingeniería "As-Built" para un tablero de control de arranque directo, destinado a una bomba de extracción de agua (Dewatering) en operaciones mineras subterráneas. 

## Objetivo del Proyecto
Diseñar y documentar, bajo la norma internacional IEC 60617, un sistema de control electromecánico confiable para la extracción ininterrumpida de agua (Dewatering) en socavones mineros. 

El proyecto tiene tres metas fundamentales:
1. **Seguridad Humana:** Garantizar la integridad del operador aislando el circuito de maniobra a un nivel de tensión seguro (24VDC).
2. **Protección de Activos:** Salvaguardar el motor de la bomba sumergible contra sobrecargas térmicas y cortocircuitos mediante coordinación de protecciones.
3. **Escalabilidad:** Establecer una arquitectura eléctrica base que permita una transición fluida hacia la automatización total (Industria 4.0) mediante la futura integración de PLCs y sensores de instrumentación.

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
