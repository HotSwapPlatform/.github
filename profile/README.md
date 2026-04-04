# HotSwap Platform

A portfolio project demonstrating **hexagonal architecture** with runtime-swappable adapters built on Spring Boot 4 and Java 21.

AI models, databases, and UI adapters can be switched while the application is running — without restarting or modifying core logic.

## Architecture

![Architecture overview](docs/architecture.svg)

## Data flow

![Data flow](docs/dataflow.svg)

## Repositories

| Repository | Description |
|------------|-------------|
| [hotswap-platform-ui](https://github.com/HotSwapPlatform/hotswap-platform-ui) | React + TypeScript console — adapter control, real-time status polling |
| [hotswap-framework](https://github.com/HotSwapPlatform/hotswap-framework) | Reusable library; ports and adapters pattern |
| [hotswap-postgis-railways](https://github.com/HotSwapPlatform/hotswap-postgis-railways) | railway station map application; PostGIS, Leaflet, Thymeleaf, Spring JDBC; Aineisto: [Digitraffic / Fintraffic](https://www.digitraffic.fi/) [(CC 4.0 BY)](https://creativecommons.org/licenses/by/4.0/deed.fi) |
| [hotswap-finance-ai](https://github.com/HotSwapPlatform/hotswap-finance-ai) | finance + AI demo application; Spring Boot backend — hexagonal architecture, ports and adapters, Spring AI, TDD |

## Author

**Ilkka Nieminen**
- GitHub: [github.com/ilkka-n](https://github.com/ilkka-n)
- LinkedIn: [linkedin.com/in/ilkka-n](https://www.linkedin.com/in/ilkka-n/)
