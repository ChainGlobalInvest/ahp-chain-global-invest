# Chain Global Invest - Modelo de Decisión Multicriterio

## Resumen Ejecutivo
Este repositorio contiene el script de priorización de cadenas productivas de la plataforma Chain Global Invest:

https://chainglobalinvest.com/

Desarrollada por **Alan Párraga**. Está diseñada para el análisis multicriterio de siete cadenas productivas de una provincia del sur del Perú en su primera versión demo.

## Metodología y Fundamento Matemático
El motor decisor se basa en el **Proceso Analítico Jerárquico (AHP)**, con dinamismo cíclico discreto incorporando la técnica de **Agregación de Prioridades Individuales (AIP)**. 

Este marco metodológico garantiza:
* **Rigor Matemático:** Cálculo preciso de pesos de prioridad y descomposición de autovectores.
* **Validación de Consistencia:** Monitoreo automatizado de la Razón de Consistencia (CR) para asegurar la confiabilidad de los juicios de los expertos.
* **Escalabilidad Operativa:** Estructurado para gestionar conjuntos complejos de datos orientados al análisis territorial, pero bajo las consignas y disposiciones técnicas recomendadas por Thomás Saaty.

## Arquitectura del Proyecto
* **`motor-chain-global-invest-demo.py`**: Script principal que gestiona la ejecución del motor de decisión AHP.
* **Datos (`*.csv`)**: Repositorio de matrices de comparación por pares y conjuntos de datos de evaluación multicriterio para priorizar cadenas productivas.
* **Dependencias**: Construido sobre librerías como `pandas` y `numpy`.

## Propiedad intelectual
* **Autoría y Desarrollo: Alan Párraga**: Alan Párraga (Founder, Chain Global Invest).
* **Modelado**: Realidad productiva bajo el contexto de una provincia del sur del Perú en el marco del programa de estado PROCOMPITE.
* **License**: CC BY-NC 4.0
* **Observación**: Los datos originales han sido editados para proteger la identidad de los que toman decisiones y participaron en esta investigación. De igual manera, se omitido parte del código completo original por propiedad intelectual.

## Ejecución Local
Para desplegar el modelo en tu entorno local, asegúrate de tener Python instalado y ejecuta los siguientes comandos en tu terminal:

```bash
# Instalar las dependencias necesarias
pip install -r requirements.txt
