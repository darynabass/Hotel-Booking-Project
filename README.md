# Hotel Booking Project

## Project Description

Hotel Booking API is an educational REST API project designed for managing hotels and hotel rooms.

The project includes an OpenAPI specification, a generated Python SDK client, and interactive API documentation.

## Main Entities

- **Hotel** — hotel information, including name, address, city and contact details.
- **Room** — hotel room information, including room number, type, price and capacity.

## API Operations

The API supports CRUD operations:

- Create hotels and rooms.
- Retrieve all hotels and rooms.
- Retrieve a hotel or room by ID.
- Update hotels and rooms.
- Delete hotels and rooms.

## Technologies

- Python
- OpenAPI 3.0.3
- YAML
- OpenAPI Generator
- Zudoku
- GitHub Pages
- GitHub Actions

## Project Structure

```text
Hotel-Booking-Project/
├── openapi/
│   └── openapi.yaml
├── documentation/
│   ├── apis/
│   │   └── openapi.yaml
│   ├── pages/
│   │   ├── installation.mdx
│   │   ├── authorization.mdx
│   │   └── about.mdx
│   └── zudoku.config.tsx
└── .github/
    └── workflows/
        └── deploy.yml
```

## Python SDK

The generated Python SDK is available in a separate repository:

[hotel-booking-python-sdk](https://github.com/darynabass/hotel-booking-python-sdk)

## API Documentation

Interactive API documentation:

[Hotel Booking API — GitHub Pages](https://darynabass.github.io/Hotel-Booking-Project/)

## OpenAPI Specification

The OpenAPI document is available at `openapi/openapi.yaml`.

## Author

Daryna Bass

Software Engineering Student.
