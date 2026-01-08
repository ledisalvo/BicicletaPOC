# 🚴 Sistema de Gestión para Bicicleterías

Una aplicación web moderna y completa para la gestión integral de bicicleterías, incluyendo control de ventas, inventario y administración de productos.

## 📋 Descripción

Este sistema está diseñado específicamente para bicicleterías que necesitan una solución eficiente para administrar su negocio. Permite gestionar el catálogo de productos (bicicletas, repuestos, accesorios), controlar el inventario en tiempo real, procesar ventas y generar reportes para la toma de decisiones.

## ✨ Características Principales

- **Gestión de Inventario**: Control completo del stock de productos con alertas de bajo inventario
- **Personalización en vivo del producto**: Posibilidad de armar la bicicleta seleccionando cada parte
- **Punto de Venta (POS)**: Interfaz intuitiva para procesar ventas rápidamente
- **Catálogo de Productos**: Administración de bicicletas, repuestos y accesorios con categorías y especificaciones
- **Historial de Ventas**: Registro detallado de todas las transacciones realizadas
- **Reportes y Estadísticas**: Visualización de métricas clave del negocio
- **Gestión de Clientes**: Base de datos de clientes con historial de compras
- **Búsqueda Avanzada**: Filtros y búsqueda rápida de productos
- **Diseño Responsive**: Optimizado para desktop, tablet y móvil

## 🛠️ Stack Tecnológico

- **Frontend**: Angular 17+
- **Estilización**: CSS/SCSS + Angular Material
- **Estado**: RxJS
- **Validación**: Reactive Forms
- **Iconos**: Material Icons / Font Awesome
- **Gráficos**: Chart.js / NGX-Charts

## 📦 Requisitos Previos

Antes de comenzar, asegúrate de tener instalado:

- Node.js (v18 o superior)
- npm (v9 o superior)
- Angular CLI (v17 o superior)

```bash
npm install -g @angular/cli
```

## 🚀 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/bike-shop-manager.git
cd bike-shop-manager
```

2. Instala las dependencias:
```bash
npm install
```

3. Configura las variables de entorno:
```bash
cp src/environments/environment.example.ts src/environments/environment.ts
```

4. Inicia el servidor de desarrollo:
```bash
ng serve
```

5. Abre tu navegador en `http://localhost:4200`

## 📁 Estructura del Proyecto

```
src/
├── app/
│   ├── core/              # Servicios y guards principales
│   │   ├── services/
│   │   ├── guards/
│   │   └── interceptors/
│   ├── shared/            # Componentes y utilidades compartidas
│   │   ├── components/
│   │   ├── directives/
│   │   └── pipes/
│   ├── features/          # Módulos de funcionalidades
│   │   ├── inventory/
│   │   ├── sales/
│   │   ├── products/
│   │   ├── customers/
│   │   └── reports/
│   └── layouts/           # Layouts de la aplicación
├── assets/                # Recursos estáticos
└── environments/          # Configuración de entornos
```

## 🎯 Funcionalidades en Desarrollo

- [ ] Personalización en vivo del producto
- [ ] Gestión de proveedores
- [ ] Sistema de órdenes de compra
- [ ] Módulo de servicios y reparaciones
- [ ] Integración con pasarelas de pago
- [ ] Sistema de reservas online
- [ ] App móvil complementaria
- [ ] Exportación de reportes en PDF/Excel
- [ ] Notificaciones push

## 🧪 Testing

Ejecuta las pruebas unitarias:
```bash
ng test
```

Ejecuta las pruebas end-to-end:
```bash
ng e2e
```

## 📦 Build

Para generar una versión de producción:
```bash
ng build --configuration production
```

Los archivos generados estarán en el directorio `dist/`.

## 🤝 Contribución

Las contribuciones son bienvenidas. Por favor, sigue estos pasos:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Convenciones de Código

- Seguimos la guía de estilo oficial de Angular
- Usa nombres descriptivos para variables y funciones
- Documenta funciones complejas con comentarios
- Mantén los componentes pequeños y enfocados en una sola responsabilidad

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👥 Autores

- Leonardo A. Di Salvo - *Desarrollo inicial* - [ledisalvo](https://github.com/ledisalvo)
- Ursula N. Planera - *Desarrollo inicial* - [Ursula](https://github.com/ursula)

## 🙏 Agradecimientos

- A la comunidad de Angular por sus excelentes recursos
- A todos los contribuidores que ayudan a mejorar este proyecto

## 📧 Contacto

Si tienes preguntas o sugerencias, no dudes en contactarme:

- Email: ledisalvo@gmail.com o (mail de Ursula)
- LinkedIn: [tu-perfil](https://linkedin.com/in/tu-perfil)
- GitHub: [@tu-usuario](https://github.com/tu-usuario)

---

⭐ Si este proyecto te resulta útil, considera darle una estrella en GitHub
