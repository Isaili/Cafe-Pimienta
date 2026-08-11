# Cafe-Pimienta

Sistema de gestión de compras de café y pimienta con cálculo automático de totales, control de merma y panel de estadísticas de inversión, disponible en versión móvil y web.

## Descripción

**Grano y grano** es una aplicación multiplataforma orientada a la gestión y trazabilidad de compras de café y pimienta. Permite registrar transacciones especificando tipo de producto (seco o verde), kilogramos adquiridos y precio unitario, con soporte para el descuento de merma ("basura") mediante tarifas diferenciadas. El sistema calcula automáticamente los totales por operación y ofrece un panel analítico con indicadores clave de inversión, historial de compras y tendencias de adquisición por periodo.

## Características principales

- **Registro de compras**: captura de kilos, tipo de producto (seco/verde), precio por kilo y merma opcional con precio diferenciado.
- **Cálculo automático**: subtotales, kilos netos y total a pagar en tiempo real.
- **Historial de transacciones**: consulta, filtrado por fecha/tipo/proveedor y edición de registros.
- **Panel de estadísticas**: indicadores de inversión total, precio promedio por kilo y proporción seco/verde, con gráficas por periodo.
- **Multiplataforma**: interfaz responsive para web y aplicación móvil.

## Stack tecnológico

| Capa | Tecnología |
|---|---|
| Frontend (móvil y web) | Flutter, Dart |
| Backend / API | *(por definir)* |
| Base de datos | *(por definir)* |
| Autenticación | *(por definir)* |
| Despliegue | *(por definir)* |

> Ajusta esta tabla según el stack definitivo del proyecto.

## Instalación

```bash
# Clonar el repositorio
git clone https://github.com/isaili/grano-y-grano.git
cd grano-y-grano

# Obtener dependencias
flutter pub get

# Ejecutar en modo desarrollo (dispositivo/emulador conectado)
flutter run

# Ejecutar en modo web
flutter run -d chrome
```

## Estructura del proyecto

```
grano-y-grano/
├── lib/
│   ├── main.dart             # Punto de entrada de la aplicación
│   ├── features/             # Módulos por funcionalidad (compras, estadísticas, auth)
│   │   ├── compras/
│   │   ├── estadisticas/
│   │   └── auth/
│   ├── core/                 # Configuración, temas, constantes
│   ├── shared/                # Widgets reutilizables
│   ├── data/                  # Modelos, repositorios, clientes API
│   └── routes/                 # Definición de rutas
├── assets/                    # Imágenes, íconos, fuentes
├── test/                      # Pruebas unitarias y de widgets
├── pubspec.yaml
└── README.md
```

## Roadmap

- [ ] Registro y cálculo de compras (seco/verde/merma)
- [ ] Historial de compras con filtros
- [ ] Dashboard de estadísticas e inversión
- [ ] Autenticación de usuarios
- [ ] Exportación de reportes
- [ ] Versión móvil nativa

## Licencia

*(por definir)*

## Autor

Desarrollado por [Isai Abel López Sánchez](https://github.com/isaili) — Softvana.
