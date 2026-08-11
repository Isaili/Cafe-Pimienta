<div align="center">

# ☕ Grano y grano

**Sistema de gestión de compras de café y pimienta**

Cálculo automático de totales, control de merma y panel de estadísticas de inversión, disponible en versión móvil y web.

<br/>

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Multiplataforma](https://img.shields.io/badge/Multiplataforma-Web%20%26%20M%C3%B3vil-6D28D9?style=for-the-badge)

![Status](https://img.shields.io/badge/estado-MVP%20en%20desarrollo-F59E0B?style=flat-square)
![Product](https://img.shields.io/badge/producto-Café%20%26%20Pimienta-92400E?style=flat-square)
![Made in](https://img.shields.io/badge/hecho%20en-Chiapas%2C%20México-16A34A?style=flat-square)

</div>

---

## 📋 Descripción

**Grano y grano** es una aplicación multiplataforma orientada a la gestión y trazabilidad de compras de café y pimienta. Permite registrar transacciones especificando tipo de producto (seco o verde), kilogramos adquiridos y precio unitario, con soporte para el descuento de merma ("basura") mediante tarifas diferenciadas. El sistema calcula automáticamente los totales por operación y ofrece un panel analítico con indicadores clave de inversión, historial de compras y tendencias de adquisición por periodo.

## ✨ Características principales

<table>
<tr>
<td width="50%" valign="top">

### 📝 <img src="https://img.shields.io/badge/-Registro-2563EB?style=flat-square&logoColor=white" alt="Registro"/>
Registro de compras
- Captura de kilos, tipo de producto (seco/verde), precio por kilo.
- Merma opcional ("basura") con precio diferenciado.

</td>
<td width="50%" valign="top">

### 🧮 <img src="https://img.shields.io/badge/-Cálculo-16A34A?style=flat-square&logoColor=white" alt="Cálculo"/>
Cálculo automático
- Subtotales, kilos netos y total a pagar en tiempo real.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🕒 <img src="https://img.shields.io/badge/-Historial-F59E0B?style=flat-square&logoColor=white" alt="Historial"/>
Historial de transacciones
- Consulta y edición de registros.
- Filtrado por fecha, tipo y proveedor.

</td>
<td width="50%" valign="top">

### 📊 <img src="https://img.shields.io/badge/-Estadísticas-7C3AED?style=flat-square&logoColor=white" alt="Estadísticas"/>
Panel de estadísticas
- Inversión total y precio promedio por kilo.
- Proporción seco/verde con gráficas por periodo.

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 📱 <img src="https://img.shields.io/badge/-Multiplataforma-0891B2?style=flat-square&logoColor=white" alt="Multiplataforma"/>
Interfaz responsive para **web** y **aplicación móvil**, construida con un único código base en Flutter.

</td>
</tr>
</table>

---

## 🛠️ Stack tecnológico

| Capa | Tecnología |
|---|---|
| 🎨 Frontend (móvil y web) | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) |
| ⚙️ Backend / API | 🔲 *(por definir)* |
| 🗄️ Base de datos | 🔲 *(por definir)* |
| 🔐 Autenticación | 🔲 *(por definir)* |
| ☁️ Despliegue | 🔲 *(por definir)* |

> [!NOTE]
> Ajusta esta tabla según el stack definitivo del proyecto.

---

## 🚀 Instalación

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

---

## 📁 Estructura del proyecto

```
grano-y-grano/
├── lib/
│   ├── main.dart              # Punto de entrada de la aplicación
│   ├── features/              # Módulos por funcionalidad (compras, estadísticas, auth)
│   │   ├── compras/
│   │   ├── estadisticas/
│   │   └── auth/
│   ├── core/                  # Configuración, temas, constantes
│   ├── shared/                # Widgets reutilizables
│   ├── data/                  # Modelos, repositorios, clientes API
│   └── routes/                # Definición de rutas
├── assets/                    # Imágenes, íconos, fuentes
├── test/                      # Pruebas unitarias y de widgets
├── pubspec.yaml
└── README.md
```

---

## 🔮 Visión a futuro

Más allá del registro y control de compras, el proyecto contempla evolucionar hacia una **plataforma inteligente de comercialización**:

- 🧠 **Minería de datos** — análisis del historial de compras para detectar patrones de precios, estacionalidad y comportamiento de proveedores, con el fin de anticipar tendencias de mercado.
- 🧬 **Algoritmos genéticos** — optimización de estrategias de compra (cuándo comprar, a qué precio y en qué volumen) para maximizar el margen de inversión con base en datos históricos.
- 🛒 **Módulo de marketplace** (productores y compradores) — un espacio donde los productores puedan publicar los kilos disponibles de su cosecha (café/pimienta, seco o verde) y los compradores puedan ofertar por ellos mediante un sistema de pujas/subastas, quedándose con el lote quien ofrezca el mejor precio.
- 👤 **Perfiles diferenciados** — cuentas de tipo productor/vendedor (publican inventario disponible) y comprador (ve inventario disponible, realiza ofertas y da seguimiento a sus pujas).

> [!IMPORTANT]
> Estas funcionalidades se desarrollarán en fases posteriores al MVP de registro y estadísticas.

---

## 🗺️ Roadmap

### 🎯 Fase 1 — MVP
- [ ] Registro y cálculo de compras (seco/verde/merma)
- [ ] Historial de compras con filtros
- [ ] Dashboard de estadísticas e inversión
- [ ] Autenticación de usuarios
- [ ] Exportación de reportes

### 🚀 Fase 2 — Inteligencia y marketplace
- [ ] Minería de datos sobre historial de compras
- [ ] Modelo de algoritmos genéticos para optimización de compras
- [ ] Perfiles de productor y comprador
- [ ] Publicación de kilos disponibles por parte de productores
- [ ] Sistema de pujas/subastas para compradores
- [ ] Notificaciones de ofertas y cierre de subasta

---

## 📄 Licencia

*(por definir)*

## 👤 Autor

Desarrollado por **Isai Abel López Sánchez**
