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
