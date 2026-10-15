# Laboratorio DevOps - Convenia

Proyecto de práctica para registrar cambios de forma trazable con Git.

Convenia compara precios de supermercados de Bucaramanga: cada día captura los
precios, los procesa y los publica en una API que consume la aplicación móvil.

## Flujo diario de datos (resumen)

1. 00:00  corrida automática: respaldo, scrapers, ETL y homologación.
2. 10:00, 15:00, 20:00  reintentos solo de las tiendas con datos anormales.
3. La API publica lo cargado y la app lo muestra al usuario.
