Las cadenas de suministro minoristas enfrentan dos problemas recurrentes: quiebres de stock que deterioran el servicio al cliente y sobreinventario que inmoviliza capital y genera mermas.
Estos fenómenos se intensifican por la estacionalidad, las promociones, la variación de precios y cambios abruptos en la demanda, factores que los enfoques manuales o reglas estáticas no 
capturan con suficiente precisión. Frente a ello, el aprendizaje automático ofrece una vía práctica para anticipar ventas y planificar el reabastecimiento con mayor exactitud y rapidez.
Este trabajo propone un sistema de pronóstico de demanda a nivel SKU–tienda basado en modelos supervisados (en particular, LightGBM) que integran señales de calendario, precio y comportamiento
histórico (lags y promedios móviles). La solución traduce el pronóstico en políticas de inventario (stock objetivo, punto de pedido y stock de seguridad) evaluadas mediante simulación con
métricas de negocio como fill-rate, OTIF y costo total. Como evidencia y base reproducible se emplea el dataset público M5 Forecasting (Walmart), estándar del sector para validar pronósticos jerárquicos.
