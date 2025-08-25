# ZuvoPetNuget - Librería .NET para Gestión de Adopciones y Refugios de Mascotas

## 🚀 Descripción

ZuvoPetNuget es una librería desarrollada en .NET que facilita la gestión de adopciones, refugios y usuarios en aplicaciones relacionadas con mascotas. Proporciona modelos y DTOs para estructurar datos de adoptantes, refugios, mascotas, notificaciones y más, permitiendo una integración sencilla y eficiente en proyectos .NET.

## 🛠️ Tecnologías Utilizadas

- **Framework:** .NET (compatible con net8.0 y net9.0)
- **Lenguajes:** C#
- **Distribución:** NuGet Package
- **CI/CD:** Integración con Visual Studio y GitHub

## ✨ Características

- ✅ Modelos completos para adoptantes, refugios, mascotas y usuarios
- ✅ DTOs para transferencia eficiente de datos entre capas
- ✅ Estructura modular y fácil de integrar en cualquier solución .NET
- ✅ Soporte para notificaciones, mensajes y favoritos
- ✅ Versionado y distribución mediante NuGet
- ✅ Compatible con .NET 8 y .NET 9

## 📱 Funcionalidades Principales

### 🏠 Gestión de Adopciones y Refugios
Modelos y DTOs para representar adoptantes, refugios, mascotas y solicitudes de adopción, facilitando la lógica de negocio en aplicaciones de gestión animal.

### 📦 Transferencia de Datos
DTOs optimizados para la transferencia de información entre backend y frontend, mejorando la eficiencia y claridad del código.

### 🔔 Notificaciones y Mensajes
Soporte para la gestión de notificaciones y mensajes entre usuarios y refugios, mejorando la comunicación en la plataforma.

## 🏗️ Estructura del Proyecto

```
ZuvoPetNuget/
├── Dtos/
│   ├── AdoptanteDTO.cs
│   ├── DetallesAdoptanteUpdateDTO.cs
│   ├── DetallesRefugioDTO.cs
│   ├── FotoPerfilDTO.cs
│   ├── HistoriaExitoCreacionDTO.cs
│   ├── HistoriaExitoLandingDTO.cs
│   ├── LikeHistoriaDTO.cs
│   ├── MensajeCreacionDTO.cs
│   ├── NotificacionCreacionDTO.cs
│   ├── PerfilAdoptanteDTO.cs
│   ├── PerfilRefugioDTO.cs
│   ├── PerfilUsuarioDTO.cs
│   ├── RefugioDTO.cs
│   ├── RegistroDTO.cs
│   ├── SolicitudAdopcionDTO.cs
│   ├── SolicitudRefugioDTO.cs
│   ├── UbicacionRefugioDTO.cs
│   └── UsuarioTokenDTO.cs
├── Models/
│   ├── Adoptante.cs
│   ├── BlobModel.cs
│   ├── ChatViewModel.cs
│   ├── ConversacionViewModel.cs
│   ├── ErrorViewModel.cs
│   ├── Favorito.cs
│   ├── HistoriaExito.cs
│   ├── HistoriaExitoConDetalles.cs
│   ├── KeysModel.cs
│   ├── LikeHistoria.cs
│   ├── LoginModel.cs
│   ├── Mascota.cs
│   ├── MascotaAdoptada.cs
│   ├── MascotaCard.cs
│   ├── Mensaje.cs
│   ├── Notificacion.cs
│   ├── PerfilAdoptanteViewModel.cs
│   ├── PerfilRefugioViewModel.cs
│   ├── PerfilUsuario.cs
│   ├── Refugio.cs
│   ├── RefugioCard.cs
│   ├── SolicitudAdopcion.cs
│   ├── Usuario.cs
│   ├── VistaInicioAdoptante.cs
│   ├── VistaPerfilAdoptante.cs
│   └── VistaPerfilRefugio.cs
├── ZuvoPetNuget.csproj
├── ZuvoPetNuget.sln
└── bin/
    └── Release/
        └── ZuvoPetNuget.1.0.x.nupkg
```

## 🌐 Integración

La librería se distribuye como paquete NuGet, permitiendo su integración rápida en cualquier proyecto .NET. Incluye modelos y DTOs listos para usar en aplicaciones de gestión de adopciones y refugios.

## 📈 Rendimiento y Optimización

- 📦 Estructura modular para fácil mantenimiento y escalabilidad
- ⚡ Compatible con las últimas versiones de .NET
- 🔄 Versionado y actualizaciones continuas mediante NuGet
- 🎨 Modelos y DTOs optimizados para transferencia eficiente de datos

## 🔄 Actualizaciones Recientes

**v1.0.10** (2025) - Última versión publicada
- Nuevos DTOs y modelos añadidos
- Mejoras en la estructura de datos
- Compatibilidad con .NET 9
- Optimización de transferencia de datos
- Corrección de errores menores

---

## 📄 Licencia

Este proyecto está disponible para visualización y evaluación profesional. Ver el archivo [LICENSE](LICENSE) para más detalles sobre términos de uso y restricciones.