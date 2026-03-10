# Análisis de Evasión de Clientes - Telecom X

## Introducción
Este proyecto analiza los factores que influyen en la **evasión de clientes (Churn)** en Telecom X.  
Se identifican patrones en variables categóricas y numéricas que ayudan a comprender por qué los clientes cancelan el servicio.

## Limpieza y Preparación de Datos
- Eliminación de registros con `Churn` vacío.  
- Conversión de columnas numéricas (`Charges.Total`) a tipo numérico.  
- Creación de columna `Cuentas_Diarias` para analizar gasto promedio diario.  

## Análisis Exploratorio
**Variables categóricas:** `gender`, `Contract`, `PaymentMethod`  
- Mayor churn en **contratos mensuales**.  
- Clientes con **electronic check** presentan más cancelaciones.  

**Variables numéricas:** `tenure`, `Charges.Monthly`, `Charges.Total`, `Cuentas_Diarias`  
- Clientes que cancelan suelen tener **menor tiempo de permanencia** y **gasto diario menor**.  
- Clientes que permanecen muestran **mayor gasto total** y fidelidad.  

## Conclusiones
- Churn significativo en **clientes nuevos y con contrato mensual**.  
- El **valor del gasto y método de pago** son indicadores de riesgo.  

## Recomendaciones
1. Implementar **programas de fidelización** para contratos mensuales.  
2. Activar **alertas tempranas** para clientes con menor tenure y bajo gasto diario.  
3. Monitorear métodos de pago y ofrecer soporte a quienes usan `electronic check`.  

> Este análisis proporciona una base para estrategias de retención y reducción de evasión en Telecom X.
