# Analisis-estadistico-de-datos

### Descripción del Proyecto
Este proyecto tiene como objetivo analizar el comportamiento de los clientes y determinar cuál de las dos tarifas de prepago, Surf o Ultimate, genera más ingresos para la empresa de telecomunicaciones Megaline. Mediante un análisis estadístico riguroso, se busca ofrecer insights clave que permitan optimizar el presupuesto publicitario y tomar decisiones estratégicas basadas en datos.

El análisis incluye información de 500 clientes durante 2018, detallando sus hábitos de consumo en llamadas, mensajes de texto y uso de datos móviles. Este trabajo culminará con la identificación del plan más rentable, utilizando pruebas estadísticas para validar las conclusiones.

### Descripción de las Tarifas
Las tarifas analizadas son:

Surf:
- Pago mensual: $20.
- Límites: 500 minutos, 50 SMS, 15 GB de datos.
- Costos adicionales:
    - 1 minuto: $0.03.
    - 1 SMS: $0.03.
    - 1 GB: $10.

Ultimate:
- Pago mensual: $70.
- Límites: 3000 minutos, 1000 SMS, 30 GB de datos.
- Costos adicionales:
    - 1 minuto: $0.01.
    - 1 SMS: $0.01.
    - 1 GB: $7.
 
### Metodología
Etapa 1: Exploración de los Datos
- Revisar y entender la estructura de los datos.
- Identificar posibles problemas como valores ausentes o duplicados.

Etapa 2: Preparación de los Datos
- Conversión de columnas a tipos de datos adecuados.
- Cálculo de métricas relevantes:
    - Minutos, SMS y datos consumidos por usuario al mes.
    - Ingresos mensuales de cada cliente (considerando costos adicionales y cuota mensual).

Etapa 3: Análisis Exploratorio
- Análisis del consumo promedio por plan (minutos, SMS, datos).
- Estadísticas descriptivas: media, varianza, desviación estándar.
- Visualización de distribuciones mediante histogramas.

Etapa 4: Pruebas de Hipótesis
- Se pondrán a prueba las siguientes hipótesis:
    - El ingreso promedio de los usuarios de Surf y Ultimate difiere.
    - El ingreso promedio de los usuarios de Nueva York-Nueva Jersey es diferente al de otras regiones.
      
### Conclusión 
Como conclusión final para este proyecto se puede decir que las diferencias encontradas en el uso de cada uno de los planes varían, ya que los usuarios del plan surf llegan a exceder los límites de sus paquetes por mucho tanto en minutos llamadas, mensajes y megas. En los cálculos realizados no se encontraron excesos en los usuarios de ultimate, cabe mencionar que los usuarios del plan ultimate apenas llegaron a consumir lo que paquete incluye. Es importante mencionar también que la mayoría de los excesos se dieron durante la segunda mitad del año, incluso en la tarifa normal de cada plan se observó que los usuarios de ambos planes usan sus líneas con mayor frecuencia la segunda mitad del año. Con esto se puede decir que se le puede ofrecer el plan de ultimate a los usuarios de surf que excedieron sus tarifas mostrándoles una comparación de los gastan en excesos de sus paquetes y lo que gastaría si usan el plan ultimate, sería más conveniente para quienes excedan su plan surf cambiarlo a ultimate. 
