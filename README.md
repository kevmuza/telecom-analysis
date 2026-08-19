## 📊 Análisis de clientes — ConnectaTel

### el objetivo del proyecto
  El objetivo del proyecto es analizar el comportamiento de los clientes de **ConnectaTel** a partir de sus características demográficas y patrones de consumo.

  El análisis busca identificar segmentos de clientes según su **edad** y **nivel de uso**, analizar su comportamiento frente a los **planes básicos y premium**, detectar patrones de consumo extremo y generar recomendaciones que ayuden a ConnectaTel a mejorar su oferta de planes, aumentar la migración al **plan premium** y fortalecer la retención de clientes.
### los datasets utilizados
  El proyecto utiliza tres datasets principales:

  - plans.csv: contiene la información de los planes ofrecidos por **ConnectaTel**, incluyendo las características de los planes básico y premium.
  - users_latam.csv: contiene la información de los usuarios, como edad, ciudad, plan contratado y fecha de baja.
  - usage.csv: contiene los registros de uso del servicio, principalmente relacionados con llamadas y mensajes.
### las etapas del análisis realizadas
  1. **Exploración de los datasets**
    - Revisión de dimensiones, tipos de datos y estadísticas descriptivas.
    - Identificación de valores faltantes.
    - Análisis inicial de las variables.
  2. **Limpieza y preparación de datos**
    - Tratamiento de valores faltantes según su importancia.
    - Se conservaron los valores nulos de churn_date, ya que representan usuarios activos.
    - Se decidió ignorar city, porque no era necesaria para los objetivos del análisis.
    - Identificación y análisis de outliers.
  3. **Integración de la información**
    - Se relacionaron los datos de usuarios, planes y uso.
    - Se creó el dataframe user_profile para analizar el comportamiento individual de los clientes.
  4. **Análisis de consumo**
    - Cantidad de mensajes.
    - Cantidad de llamadas.
    - Minutos de llamadas.
    - Distribución y valores extremos del consumo.
  5. **Segmentación**<br>
   - Segmentación por edad:
      - Joven: < 30
      - Adulto: 30–59
      - Adulto Mayor: ≥ 60<br>
      
   - Segmentación por nivel de uso:
      - Bajo uso.
      - Uso medio.
      - Alto uso.
  6. **Análisis de planes**
    - Comparación entre usuarios del plan básico y premium.
    - Identificación de oportunidades de migración y retención.
  7. **Conclusiones y recomendaciones**
    - Identificación de segmentos relevantes.
    - Interpretación de patrones de consumo.
    - Recomendaciones para mejorar la oferta de planes de ConnectaTel.

### cómo ejecutar el notebook

### una breve guía de reproducción
