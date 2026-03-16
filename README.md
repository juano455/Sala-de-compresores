# Sistema de Control Térmico en Sala de Compresores

Proyecto de automatización industrial desarrollado para la regulación automática de temperatura en una sala de compresores.

## Descripción

El sistema permite controlar la apertura y cierre de compuertas de un ducto de aire caliente proveniente de los compresores, con el objetivo de aprovechar el calor residual para calefaccionar el sector de trabajo.

El control se realiza mediante un PLC Siemens LOGO 8.4 y un sensor de temperatura PT100 conectado a un transmisor industrial 0–10 V.

## Tecnologías utilizadas

- PLC Siemens LOGO 8.4
- Sensor de temperatura PT100
- Transmisor industrial 0–10 V
- Node-RED
- Protocolo MQTT
- Dashboard IoT para monitoreo
- Registro histórico de temperatura

## Arquitectura del sistema

PT100 → Transmisor 0-10V → PLC LOGO → Node-RED → MQTT → Dashboard / Data Logger

## Objetivos del proyecto

- Automatizar la regulación térmica de la sala de compresores
- Aprovechar el calor residual de los compresores
- Permitir monitoreo remoto del sistema
- Registrar datos históricos de temperatura
- Mejorar el confort térmico del sector

## Autor

Juan Ocampo  
Proyecto Final – Automatización y Robótica
