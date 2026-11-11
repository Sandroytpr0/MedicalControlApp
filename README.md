

 MedicalControlApp

 Aplicación Android para la gestión de citas médicas

Kotlin · Jetpack Compose · Room Database · MVVM

Proyecto académico de desarrollo de aplicaciones móviles.



 Descripción

MedicalControlApp es una aplicación Android desarrollada
con Kotlin y Jetpack Compose para gestionar información
relacionada con médicos y citas médicas.

El proyecto utiliza una arquitectura organizada por capas,
el patrón MVVM y persistencia local mediante Room Database.

 Funcionalidades

- Registro de citas médicas.
- Ingreso de datos del paciente y código del doctor.
- Registro de fecha, hora, costo y observaciones.
- Visualización de citas registradas.
- Eliminación de citas.
- Operaciones de actualización definidas en la capa lógica.
- Almacenamiento local con Room Database.

 Tecnologías

- Kotlin
- Android Studio
- Jetpack Compose
- Material Design 3
- Room Database
- Kotlin Coroutines
- StateFlow
- Android Architecture Components

 Arquitectura

El proyecto organiza sus responsabilidades en tres capas:


medicalcontrolapp/
├── data/
│   ├── entity/
│   ├── local/
│   └── repository/
├── domain/
│   ├── model/
│   └── usecase/
├── presentation/
│   ├── appointment/
│   ├── doctor/
│   ├── components/
│   └── navigation/
├── ui/
│   └── theme/
└── MainActivity.kt

 Capa de datos
Gestiona entidades, acceso a datos y almacenamiento
local mediante Room Database.

Capa de dominio
Contiene modelos y casos de uso para las operaciones
de la aplicación.

Capa de presentación
Contiene pantallas desarrolladas con Jetpack Compose
y ViewModels para administrar el estado.
 Base de datos

La aplicación utiliza una base de datos local llamada
`medical_db`, configurada mediante Room.

Entidades:
- DoctorEntity
- AppointmentEntity

Interfaces de acceso:
- DoctorDao
- AppointmentDao

 Instalación

1. Clonar este repositorio.
2. Abrir el proyecto en Android Studio.
3. Sincronizar las dependencias de Gradle.
4. Seleccionar un emulador o dispositivo Android compatible.
5. Compilar y ejecutar la aplicación.

 Contexto académico

Proyecto desarrollado durante mi formación
en Ingeniería de Software en ISIL.

 Desarrollador

Sandro Callañaupa Portal
Estudiante de Ingeniería de Software — ISIL

[GitHub](https://github.com/Sandroytpr0) |
[LinkedIn](https://www.linkedin.com/in/sandro-calla%C3%B1aupa-portal-426a1b418/)



 Proyecto incluido en mi portafolio académico.
