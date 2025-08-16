# 📊 Telecom X - Análisis de Abandono de Clientes (Churn)

![Telecom Analytics](https://img.freepik.com/free-vector/telecommunications-networks-concept_23-2147505732.jpg?w=1380&t=st=1690835932~exp=1690836532~hmac=abc123)

## 📌 Propósito del Análisis

El objetivo de este proyecto es identificar y analizar los factores clave que influyen en la tasa de abandono de clientes (churn) en Telecom X. Mediante análisis exploratorio y modelado predictivo, buscamos:

- 🔍 Identificar patrones de comportamiento en clientes que abandonan
- 📈 Analizar características demográficas y de uso del servicio
- 💡 Proponer estrategias efectivas para retención de clientes

# Análisis de Evasión de Clientes en Telecom X

## Hallazgos clave del análisis

1. **Tasa de evasión (Churn)**: 
   - 26.54% de los clientes dieron de baja su servicio ("Yes")
   - 73.46% permanecieron activos ("No")

2. **Distribución de clientes**:
   - Total de clientes analizados: 7,267
   - Clientes que cancelaron: 1,869
   - Clientes activos: 5,174

3. **Características principales**:
   - La data incluye información demográfica (género, edad), tipo de contrato, servicios contratados (teléfono, internet) y datos de facturación.

4. **Transformaciones realizadas**:
   - Normalización de datos JSON
   - Renombrado de columnas para mayor claridad
   - Tratamiento de valores nulos y duplicados
   - Creación de nueva columna "cargo_diario" calculada a partir del cargo total y antigüedad del cliente

## Recomendaciones

1. **Análisis profundo de causas**:
   - Investigar patrones comunes entre los clientes que dieron de baja (tipo de contrato, servicios contratados, método de pago)
   - Analizar relación entre antigüedad del cliente y probabilidad de churn

2. **Acciones preventivas**:
   - Programas de fidelización para clientes con alto riesgo de cancelación
   - Mejorar servicio al cliente en áreas identificadas como problemáticas

3. **Seguimiento continuo**:
   - Monitorear la tasa de churn periódicamente
   - Implementar sistema de alerta temprana para clientes en riesgo

4. **Mejoras en data**:
   - Considerar incluir datos adicionales como motivo de cancelación
   - Segmentar análisis por tipo de servicio contratado

El análisis muestra que aproximadamente 1 de cada 4 clientes cancela su servicio, lo que representa una oportunidad significativa para mejorar la retención mediante estrategias basadas en los insights obtenidos de los datos.
