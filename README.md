# Urban Scooter | Pruebas web, móviles y API

## Descripción del proyecto

Proyecto de pruebas de Urban Scooter enfocado en validar las funcionalidades de la plataforma web, la aplicación móvil y los servicios API.

Se realizaron actividades de análisis de requisitos, diseño de pruebas, elaboración de listas de comprobación, validación de datos y documentación de errores.

## Pruebas web

Se elaboró y ejecutó una lista de comprobación para validar el proceso de solicitud y seguimiento de pedidos de scooters.

Las pruebas se realizaron en los navegadores:

- Google Chrome
- Mozilla Firefox

También se aplicaron técnicas de diseño de pruebas:

- Clases de equivalencia.
- Valores límite.
- Validación de campos y datos de entrada.

## Pruebas de aplicación móvil

Se diseñaron casos de prueba para validar funcionalidades relacionadas con los pedidos y las notificaciones de la aplicación móvil.

Las pruebas se documentaron utilizando Android 9.0.

## Pruebas de API

Se realizaron pruebas de los siguientes endpoints utilizando Postman:

| Método | Endpoint | Funcionalidad |
|---|---|---|
| POST | `/api/v1/courier` | Crear repartidor |
| POST | `/api/v1/courier/login` | Iniciar sesión |
| DELETE | `/api/v1/courier/:id` | Eliminar repartidor |
| GET | `/api/v1/orders/track?t=123456` | Obtener información de un pedido |
| PUT | `/api/v1/orders/cancel` | Cancelar pedido |

Se validaron datos de entrada, respuestas de las solicitudes y diferentes escenarios positivos y negativos.

## Gestión de incidencias

Se identificaron y documentaron **33 incidencias en JIRA**, relacionadas con el comportamiento de la plataforma web, la aplicación móvil y los servicios API.

## Herramientas y técnicas utilizadas

- **Postman:** ejecución y validación de solicitudes API.
- **JIRA:** registro y seguimiento de incidencias.
- **Google Chrome y Mozilla Firefox:** pruebas de compatibilidad web.
- **Android 9.0:** pruebas de aplicación móvil.
- **Excel:** documentación de listas de comprobación, casos de prueba y validación de datos.
- **Clases de equivalencia y valores límite:** técnicas de diseño de pruebas.

## Documentación del proyecto

El archivo Excel contiene las actividades y evidencias documentadas durante el proyecto:

- Análisis de requisitos y técnicas de diseño de pruebas.
- Listas de comprobación para la aplicación web.
- Validación de datos de entrada.
- Casos de prueba para la aplicación móvil.
- Listas de comprobación para los endpoints API.
- Enlaces a las incidencias registradas en JIRA.

[Consultar documentación de pruebas (Excel)](Proyecto%20Urban%20Scooter.xlsx)

## Objetivo del proyecto

Aplicar técnicas de pruebas de software en plataformas web, móviles y servicios API para identificar comportamientos inesperados, validar requisitos y documentar incidencias.
