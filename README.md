# Arreglo con DOA para sala de juntas

Este proyecto implementa un sistema de captura y visualización de audio multicanal en tiempo real, diseñado para mejorar la calidad del sonido durante las juntas de consejo en la ESIME Culhuacán.
Se utiliza un ReSpeaker USB Mic Array v2.0 para procesar y grabar señales de múltiples micrófonos al mismo tiempo.

## 🎯 Descripción

El objetivo es facilitar la supervisión y posterior análisis del audio capturado en la sala de consejo, permitiendo una visualización clara de cada micrófono individual, así como de la señal sumada,
que representa una mezcla acústica de todos ellos. Esto puede usarse para evaluar calidad de grabación, fuentes dominantes de sonido, o alimentar un sistema de dirección de llegada (DOA).

## 🎤 Requisitos de hardware

- ReSpeaker USB Mic Array **v2.0**
- Computadora con sistema operativo compatible con Python (Windows, Linux o macOS)

## 🛠️ Requisitos de software

1. Python 3.13
2. Modificar dirección de guardado
```bash
    Tiempo_Real_Guardado-----Línea 60
```
3. Instalar los paquetes necesarios con:

```bash
pip install -r requirements.txt
```