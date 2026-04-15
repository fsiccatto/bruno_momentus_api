# Momentus Enterprise API

Coleccion de requests para la API de Momentus Enterprise, migrada de Postman a [Bruno](https://www.usebruno.com/).

## Estructura

```
├── V1/              # Endpoints generales (Accounts, Activities, Opportunities, etc.)
├── V1_EVENTS/       # Endpoints de eventos (Events, Bookings, WorkOrders, etc.)
├── Source PRIAVA/   # Endpoints legacy / Source PRIAVA
├── environments/    # Variables de entorno (PROD y TEST)
└── collection.bru   # Coleccion principal
```

## Environments

- `Momentus_PROD` — produccion
- `Momentus_TEST` — testing

## Requisitos

- [Bruno](https://www.usebruno.com/) (cliente de API, alternativa open-source a Postman)

## Configuración Inicial
Para utilizar esta colección en tu entorno local, sigue estos pasos:
- Clonar el repositorio: Descarga el código en tu equipo.

  ``` git clone https://github.com/fsiccatto/bruno_momentus_api ```

- Abrir la colección en Bruno:
  - Abre la aplicación Bruno.
  - Selecciona la opción Open Collection desde la pantalla de inicio o el menú lateral.
  - Navega hasta la carpeta raíz del repositorio clonado y selecciónala.
 
- Configurar Credenciales Locales (Crítico):
  - Por estándares de seguridad, los tokens y contraseñas no se versionan en este repositorio.
  - Selecciona un ambiente en la esquina superior derecha (Momentus_TEST o Momentus_PROD).
  - Haz clic en el ícono del engranaje (Configure) al lado del nombre del ambiente.
  - Ingresa los valores de las variables marcadas como Secret. Bruno guardará estos datos en un archivo local bru.env que ya está excluido en el .gitignore.

- Probar conexión: Selecciona cualquier endpoint, verifica que el ambiente correcto esté activo y ejecuta la petición.
