# Monitor de Cuotas de Caballos

Aplicación de escritorio para Windows que monitoriza en tiempo real las cuotas de carreras de caballos de Sportsbet.

## Características

- Scraper automatizado con Playwright/Selenium
- Interfaz gráfica PyQt6
- Almacenamiento en SQLite
- Actualización configurable (30s, 1min, 5min)
- Cálculo de porcentaje de cambio en cuotas

## Estructura del Proyecto

```
monitor_cuotas_caballos/
├── README.md
├── requirements.txt
├── setup.py
├── .gitignore
├── config/
│   └── settings.yaml
├── data/
│   └── cuotas.db
├── scraper/
│   ├── __init__.py
│   └── sportsbet_scraper.py
├── gui/
│   ├── __init__.py
│   ├── main_window.py
│   └── widgets.py
├── core/
│   ├── __init__.py
│   ├── db.py
│   ├── models.py
│   └── updater.py
├── tests/
│   ├── test_scraper.py
│   └── test_db.py
└── main.py
```

## Instalación

Próximamente...

## Configuración

Próximamente...

## Uso

Próximamente...
