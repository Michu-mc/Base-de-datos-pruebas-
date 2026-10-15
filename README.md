Es una base de datos basada en el servicio de urgencias de un hospital ficticio.
Empezamos con tres tablas sencillas que incluyen:
  - personal: ahora incluye cargo, especialidad y turno del personal médico
  - entradas: registra pacientes con datos demográficos, motivo de consulta, prioridad de triage y médico asignado
  - salidas: vinculada a la entrada del paciente, con diagnóstico, tratamiento y destino del paciente

Agregado un script con un par de INSERTS para llenar las tablas .

Nota importante: Los INSERT de salidas asumen que los id de las entradas son 1, 2, 3, 4 y 5 (lo cual es cierto si las tablas están recién creadas). 
Si ya tenías datos previos, deberías verificar los ids reales con:
      SELECT id FROM entradas;
