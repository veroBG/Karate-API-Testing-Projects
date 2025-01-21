# Karate Testing Suite

Este repositorio contiene una colección de pruebas automatizadas desarrolladas con [Karate](https://github.com/karatelabs/karate), enfocadas en la validación de endpoints utilizando el API de prueba proporcionado por [DummyJSON](https://dummyjson.com).

## Descripción
Las pruebas incluidas están diseñadas para demostrar las capacidades de Karate como framework para pruebas de API. Estas incluyen escenarios comunes de testing, desde validaciones básicas hasta casos de borde y pruebas de caminos negativos (unhappy paths).

### Funcionalidades principales

1. **Pruebas de Request Body**  
   - Validación de datos enviados en el cuerpo de la solicitud.

2. **Variables globales**  
   - Uso de variables globales para compartir datos entre escenarios.

3. **Uso de Background**  
   - Configuración inicial reutilizable para múltiples escenarios.

4. **Verificación de Response Time**  
   - Aseguramiento de que los tiempos de respuesta cumplen con los límites esperados.

5. **Validación de Response Body**  
   - Verificación de los datos devueltos en la respuesta.

6. **Schema Validation**  
   - Validación de los esquemas de respuesta para garantizar que los datos cumplen con el formato esperado.

7. **Autenticación**  
   - Implementación de pruebas que incluyen autenticación con credenciales.

8. **Pruebas de Unhappy Path**  
   - Manejo de casos con datos incorrectos, como:
     - Credenciales inválidas.
     - IDs inexistentes.
     - Solicitudes sin autorización.
