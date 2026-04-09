##Nombre del sistema 
Riego-TEC 
##Descripción general
 Riego-TEC un sistema interactivo que monitorea automáticamente la humedad del suelo en macetas o jardines pequeños. Utiliza un sensor para detectar niveles bajos de humedad y activa una bomba de agua para regar las plantas solo cuando es necesario. Esto previene el exceso o déficit de agua, ahorrando recursos y manteniendo las plantas saludables

## c. Usuario Objetivo
- **Jardineros aficionados** o dueños de plantas de interior (ej. oficinas, hogares).
- **Estudiantes de electrónica/IoT** para proyectos educativos.
- Personas con poco tiempo para cuidar plantas, como profesionales ocupados en entornos urbanos.

## d. Entradas
- **Sensor**: Sensor de humedad del suelo capacitivo.
- **Tipo de señal**: Analógica (0-1023 en Arduino, donde valores bajos indican suelo seco). 
  - Umbral configurable: Si humedad < 30%, activa riego.
- Opcional: Botón manual para riego forzado (señal digital).

## e. Salidas
- **Actuador**: Bomba de agua sumergible de 5V (con relé para control seguro).
- **Tipo de señal**: Digital (HIGH/LOW vía relé para encender/apagar la bomba por 5-10 segundos).
- Indicadores adicionales:
  - LED verde (suelo húmedo) / rojo (seco y regando) - Señal digital.
  - Notificación vía Serial Monitor o app (texto: "Regando plantas").

## d. Entradas
- **Sensor**: Sensor de humedad del suelo capacitivo.
- **Tipo de señal**: Analógica (0-1023 en Arduino, donde valores bajos indican suelo seco). 
  - Umbral configurable: Si humedad < 30%, activa riego.
- Opcional: Botón manual para riego forzado (señal digital).
