Es una base de datos basada en el servicio de urgencias de un hospital ficticio.
Empezamos con tres tablas sencillas que incluyen:
  - personal: datos del personal con id autoincremental
  - entradas: registro de entradas con referencia al personal que las registró
  - salidas: registro de salidas con referencia al personal que las autorizó
  - Llave foránea (personal_id) que relaciona ambas tablas con personal
  - Restricciones de validación (cantidad > 0)
