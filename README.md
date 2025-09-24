# 🚗 Escuela de Manejo Montejo

Sistema web para la gestión integral de la Escuela de Manejo Montejo en Tuxtla Gutiérrez, Chiapas.

## 📍 Acerca de Nosotros

La **Escuela de Manejo Montejo** es una institución educativa especializada en la enseñanza de manejo vehicular ubicada en Tuxtla Gutiérrez, Chiapas, México. Nos dedicamos a formar conductores responsables y seguros a través de programas de capacitación teórica y práctica.

### Nuestra Misión
Brindar educación vial de calidad, formando conductores competentes y responsables que contribuyan a la seguridad vial en nuestro estado.

## 🛠️ Tecnologías Utilizadas

- **PHP** - Lenguaje de programación principal
- **MySQL** - Base de datos
- **HTML5/CSS3** - Frontend
- **JavaScript** - Interactividad del cliente
- **Bootstrap** - Framework CSS para diseño responsivo

## 📋 Características del Sistema

- ✅ **Gestión de Estudiantes** - Registro y seguimiento de alumnos
- ✅ **Control de Instructores** - Administración del personal docente
- ✅ **Programación de Clases** - Calendario de clases teóricas y prácticas
- ✅ **Gestión de Vehículos** - Control de la flota vehicular
- ✅ **Reportes y Estadísticas** - Análisis de rendimiento y progreso
- ✅ **Sistema de Pagos** - Control de colegiaturas y pagos
- ✅ **Certificaciones** - Generación de certificados de finalización

## 🚀 Instalación y Configuración

### Prerrequisitos

- PHP 7.4 o superior
- MySQL 5.7 o superior
- Apache/Nginx
- Composer (opcional, para dependencias)

### Pasos de Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/danielmendez88/manejomontejo.git
   cd manejomontejo
   ```

2. **Configurar la base de datos**
   ```sql
   CREATE DATABASE escuela_manejo_montejo;
   ```

3. **Configurar el archivo de conexión**
   ```php
   // config/database.php
   $servername = "localhost";
   $username = "tu_usuario";
   $password = "tu_contraseña";
   $dbname = "escuela_manejo_montejo";
   ```

4. **Importar la estructura de la base de datos**
   ```bash
   mysql -u usuario -p escuela_manejo_montejo < database/schema.sql
   ```

5. **Configurar permisos del servidor web**
   ```bash
   chmod -R 755 public/
   chmod -R 777 uploads/
   ```

## 🖥️ Uso del Sistema

### Para Administradores
- Acceso completo al sistema
- Gestión de usuarios, instructores y estudiantes
- Generación de reportes
- Configuración del sistema

### Para Instructores
- Visualización de horarios asignados
- Registro de asistencias
- Evaluación de estudiantes
- Comunicación con la administración

### Para Estudiantes
- Consulta de horarios
- Seguimiento de progreso
- Acceso a material didáctico
- Historial de pagos

## 📁 Estructura del Proyecto

```
manejomontejo/
├── config/
│   ├── database.php
│   └── settings.php
├── controllers/
│   ├── StudentController.php
│   ├── InstructorController.php
│   └── AdminController.php
├── models/
│   ├── Student.php
│   ├── Instructor.php
│   └── Course.php
├── views/
│   ├── admin/
│   ├── instructor/
│   └── student/
├── public/
│   ├── css/
│   ├── js/
│   └── images/
├── database/
│   ├── schema.sql
│   └── migrations/
└── uploads/
    ├── documents/
    └── photos/
```

## 🎯 Servicios Ofrecidos

### Cursos Disponibles
- **Licencia Tipo A** - Motocicletas
- **Licencia Tipo B** - Automóviles particulares
- **Licencia Tipo C** - Camiones y vehículos de carga
- **Licencia Tipo D** - Transporte público
- **Cursos de Manejo Defensivo**
- **Educación Vial para Empresas**

### Modalidades
- 🏫 **Clases Presenciales** - En nuestras instalaciones
- 🚗 **Prácticas de Manejo** - Con vehículos de la escuela
- 📱 **Plataforma Digital** - Material teórico en línea
- 🏠 **Clases a Domicilio** - Servicio personalizado

## 📞 Información de Contacto

**Escuela de Manejo Montejo**
- 📍 **Dirección**: Tuxtla Gutiérrez, Chiapas, México
- ☎️ **Teléfono**: [Número de teléfono]
- 📧 **Email**: [correo@manejomontejo.com]
- 🌐 **Sitio Web**: [www.manejomontejo.com]
- 📱 **WhatsApp**: [Número de WhatsApp]

### Horarios de Atención
- **Lunes a Viernes**: 8:00 AM - 6:00 PM
- **Sábados**: 8:00 AM - 2:00 PM
- **Domingos**: Cerrado

## 🤝 Contribución

Si deseas contribuir al desarrollo de este proyecto:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -am 'Agregar nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Crea un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia [MIT](LICENSE) - ver el archivo LICENSE para más detalles.

## 🏆 Certificaciones y Reconocimientos

- ✅ Escuela autorizada por la Secretaría de Transporte de Chiapas
- ✅ Instructores certificados
- ✅ Vehículos con doble comando
- ✅ Seguros de responsabilidad civil

## 📈 Estadísticas

- 👥 **+500** Estudiantes graduados
- 🚗 **15** Vehículos en flota
- 👨‍🏫 **8** Instructores certificados
- ⭐ **4.8/5** Calificación promedio

## 🔧 Mantenimiento y Soporte

Para reportar bugs, solicitar nuevas funcionalidades o obtener soporte técnico:

- 📝 **Issues**: [GitHub Issues](https://github.com/danielmendez88/manejomontejo/issues)
- 📧 **Email**: soporte@manejomontejo.com
- 📞 **Soporte**: [Número de soporte técnico]

---

<p align="center">
  <strong>🚗 Conduciendo hacia un futuro más seguro 🛣️</strong><br>
  <em>Escuela de Manejo Montejo - Tuxtla Gutiérrez, Chiapas</em>
</p>
