# Crew Streamers App

Aplicación web desarrollada en PHP para la gestión de un crew de streamers.  
El sistema permite administrar usuarios, generar equipos, realizar sorteos, gestionar sponsors y mantener estadísticas mediante el uso de sesiones, cookies y almacenamiento en archivos.

---

## Objetivo del proyecto

Simular una plataforma completa de gestión de streamers aplicando conceptos fundamentales de desarrollo backend sin frameworks, incluyendo:

- Desarrollo backend en PHP puro
- Persistencia de datos mediante archivos (JSON, TXT, CSV)
- Gestión de sesiones y cookies
- Validación segura de formularios
- Manipulación de datos y generación dinámica de contenido

---

## Estructura del proyecto
/crew-streamers/
├── index.php
├── desafio1.php
├── desafio2.php
├── desafio3.php
├── desafio4.php
├── desafio5.php
├── config.php
├── /images/
│ └── /streamers/
├── /data/
│ ├── featured_streamers.json
│ ├── roster_completo.json
│ ├── juegos_trending.txt
│ ├── sponsors.txt
│ ├── colaboraciones.csv
│ └── visitas.txt
├── /logs/
│ ├── sorteos.txt
│ ├── busquedas.txt
│ └── errores.log
└── /css/
└── gaming-styles.css


---

## Funcionalidades principales

### Dashboard
- Sistema de autenticación basado en username mediante sesiones
- Control de visitas mediante cookies y almacenamiento en archivos
- Visualización dinámica de streamers
- Sistema de racha de actividad de usuarios

---

## Desafío 1: Sorteo de viewers
- Validación de formularios en PHP
- Generación aleatoria de ganadores
- Registro de resultados en logs del sistema

---

## Desafío 2: Streamers destacados
- Gestión dinámica de streamers destacados
- Persistencia de datos en formato JSON
- Sistema de reinicio de rotación de destacados

---

## Desafío 3: Equipos de torneo
- Generación dinámica de roster de streamers
- División automática en equipos
- Cálculo de estadísticas de rendimiento
- Identificación de MVP y rookie del torneo
- Persistencia de resultados en JSON

---

## Desafío 4: Rankings y búsqueda
- Ordenación de streamers por popularidad y criterios alfabéticos
- Sistema de búsqueda con validación segura
- Registro de consultas en logs del sistema

---

## Desafío 5: Gestión de sponsors
- Gestión de sponsors mediante estructuras dinámicas
- Asignación aleatoria de sponsors a streamers
- Exportación de datos en formato CSV
- Incorporación dinámica de nuevos sponsors

---

## Tecnologías utilizadas

- PHP (backend)
- HTML5
- CSS3
- JavaScript
- JSON, TXT y CSV para persistencia de datos

---

## Seguridad

- Validación de datos en servidor
- Sanitización de entradas (`htmlspecialchars`, `filter_var`)
- Uso de sesiones para control de acceso
- Gestión de cookies para seguimiento de actividad
- Validación de datos mediante expresiones regulares

---

## Gestión de datos

- Lectura y escritura de archivos mediante funciones nativas de PHP
- Uso de JSON para estructuras de datos complejas
- Sistema de logs para auditoría de acciones
- Persistencia de información entre sesiones

---

## Diseño

- Interfaz con temática gaming
- Estilo visual oscuro con elementos de contraste
- Componentes dinámicos orientados a experiencia de usuario

---

## Estado del proyecto

Proyecto finalizado en su versión académica.  
Se contemplan futuras mejoras orientadas a optimización, refactorización y migración a arquitectura MVC o base de datos relacional.

---

## Autor

Jose Miguel Risco Muñoz  
Estudiante de Desarrollo de Aplicaciones Web (DAW)

---

## Nota

Proyecto académico enfocado en la aplicación práctica de conceptos de backend en PHP, manipulación de datos, persistencia mediante archivos y seguridad en aplicaciones web.
