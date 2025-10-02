# 🐧 Script de Configuración Automática para Linux

## 📖 Descripción del Proyecto

Este proyecto es una **versión modificada** de un script originalmente creado por el **Director del Grado de la Carrera de Informática de la Universidad Europea del Atlántico**. El script original tenía como objetivo preconfigurar distribuciones Linux con herramientas básicas del sistema.

### 🔧 Modificaciones y Mejoras

La versión actual ha sido **modificada y ampliada** por mi persona para incluir funcionalidades adicionales específicamente orientadas al **desarrollo backend**, agregando soporte para la instalación automatizada de las siguientes herramientas:

- 🐳 **Docker** - Plataforma de contenedores
- 📮 **Postman** - Herramienta para testing de APIs
- 🟢 **Node.js** - Runtime de JavaScript
- 🐘 **PHP** - Lenguaje de programación para desarrollo web

## ✨ Características Principales

### 🎯 Detección Automática de Distribución
- ✅ **Ubuntu/Debian** y derivados (Linux Mint, Elementary OS, Pop!_OS, Zorin OS)
- ✅ **Fedora/RHEL** y derivados (CentOS, Rocky Linux, AlmaLinux)
- ✅ **Arch Linux** y derivados (Manjaro, EndeavourOS)

### 🛠️ Herramientas del Sistema
- Actualización automática de repositorios
- Instalación de dependencias básicas (curl, wget, git, zip/unzip)
- Configuración de repositorios adicionales según la distribución

### 💻 Herramientas de Desarrollo Backend

#### 🐳 Docker
- Instalación completa de Docker CE
- Docker Compose incluido
- Configuración automática de permisos de usuario
- Soporte para todas las distribuciones principales

#### 🟢 Node.js
- Instalación vía NodeSource (versión LTS)
- NPM incluido automáticamente
- Configuración optimizada para desarrollo

#### 🐘 PHP
- Soporte para múltiples versiones (7.4, 8.2, 8.4)
- Extensiones esenciales incluidas:
  - php-cli, php-curl, php-mbstring
  - php-mysql, php-xml, php-zip
  - php-gd, php-intl, php-bcmath
- Instalación de Composer (gestor de dependencias)

#### 📮 Postman e Insomnia
- Postman para testing de APIs REST
- Insomnia como alternativa de código abierto
- Instalación vía Snap o descarga directa

### 🎨 Interfaz de Usuario
- **Mensajes coloreados** para mejor legibilidad
- **Confirmaciones interactivas** antes de cada instalación
- **Logging detallado** de todas las operaciones
- **Manejo de errores** robusto

## 🚀 Uso del Script

### Prerrequisitos
- Sistema operativo Linux (Ubuntu, Debian, Fedora, Arch, o derivados)
- Acceso a `sudo`
- Conexión a internet

### Instalación y Ejecución

1. **Clonar o descargar el script:**
   ```bash
   git clone https://github.com/kevinponce237/configuracion-automatica-linux.git
   cd configuracion-automatica-linux
   ```

2. **Dar permisos de ejecución:**
   ```bash
   chmod +x setup.sh
   ```

3. **Ejecutar el script:**
   ```bash
   ./setup.sh
   ```

### 📋 Flujo de Ejecución

1. **Detección automática** de la distribución Linux
2. **Instalación de dependencias** básicas del sistema
3. **Menú interactivo** para seleccionar herramientas backend:
   - Opción para instalar Docker
   - Opción para instalar Node.js
   - Opción para instalar PHP
   - Opción para instalar Postman/Insomnia

4. **Configuración automática** de cada herramienta seleccionada
5. **Verificación final** de las instalaciones

## 🎯 Casos de Uso

### Para Desarrolladores Backend
- **Configuración rápida** de entornos de desarrollo
- **Instalación consistente** en diferentes distribuciones
- **Ahorro de tiempo** en configuraciones manuales

### Para Administradores de Sistemas
- **Automatización** de instalaciones en múltiples servidores
- **Estandarización** de entornos de desarrollo en equipos

### Para Estudiantes y Educadores
- **Preparación rápida** de entornos de laboratorio
- **Uniformidad** en configuraciones académicas

## 🔍 Distribuciones Soportadas

| Distribución | Familia | Estado | Gestor de Paquetes |
|--------------|---------|--------|-------------------|
| Ubuntu | Debian | ✅ Completo | apt |
| Debian | Debian | ✅ Completo | apt |
| Linux Mint | Debian | ✅ Completo | apt |
| Elementary OS | Debian | ✅ Completo | apt |
| Pop!_OS | Debian | ✅ Completo | apt |
| Zorin OS | Debian | ✅ Completo | apt |
| Fedora | RPM | ✅ Completo | dnf |
| RHEL | RPM | ✅ Completo | dnf |
| CentOS | RPM | ✅ Completo | dnf |
| Rocky Linux | RPM | ✅ Completo | dnf |
| AlmaLinux | RPM | ✅ Completo | dnf |
| Arch Linux | Arch | ✅ Completo | pacman |
| Manjaro | Arch | ✅ Completo | pacman |
| EndeavourOS | Arch | ✅ Completo | pacman |

## 🛡️ Características de Seguridad

- ✅ **Verificación de distribución** antes de proceder
- ✅ **Confirmaciones manuales** para cada instalación
- ✅ **Instalación desde repositorios oficiales**
- ✅ **Verificación de integridad** de paquetes
- ✅ **Configuración segura** de Docker con permisos de usuario

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas:
- ➕ Agregar soporte para nuevas distribuciones
- 🔧 Incluir nuevas herramientas de desarrollo
- 🐛 Reportar bugs o problemas
- 📚 Mejorar la documentación

Por favor, abre un issue o envía un pull request.

## 📄 Licencia

Este proyecto mantiene el espíritu educativo del script original, siendo utilizado para fines académicos y de desarrollo.

## 🙏 Agradecimientos

- **Universidad Europea del Atlántico** - Por el script base original
- **Director del Grado de Informática** - Por la creación del script fundacional
- **Comunidad Open Source** - Por las herramientas y tecnologías incluidas

---

> **Nota:** Este script está diseñado para facilitar la configuración de entornos de desarrollo. Se recomienda revisar el código antes de ejecutarlo en sistemas de producción.