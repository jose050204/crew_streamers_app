# 🎮 Crew Streamers App

Aplicación web desarrollada en **PHP** para la gestión de un crew de streamers.  
El sistema permite administrar usuarios, generar equipos, realizar sorteos, gestionar sponsors y mantener estadísticas en tiempo real utilizando **sesiones, cookies y almacenamiento en archivos**.

---

## 🚀 Objetivo del Proyecto

Simular una plataforma completa de gestión de streamers implementando:

- Backend en PHP sin frameworks
- Persistencia mediante archivos (JSON, TXT, CSV)
- Uso de sesiones y cookies
- Validación segura de formularios

---

## 🧱 Estructura del Proyecto
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

## 🏠 Funcionalidades principales

### 🖥️ Home (Dashboard)
- Sistema de login con username gamer (sesión)
- Contador de visitas y última conexión (cookies + archivos)
- Visualización dinámica de avatares de streamers
- Sistema de racha de días

---

## 🎯 Desafío 1 - Sorteo de Viewers
- Validación de formulario en PHP
- Generación aleatoria de ganadores
- Registro de sorteos en archivo log

---

## 🔥 Desafío 2 - Featured Streamers
- Gestión dinámica de streamers destacados
- Persistencia mediante JSON
- Reset del sistema de rotación

---

## ⚡ Desafío 3 - Equipos de Torneo
- Generación de roster con datos dinámicos
- División automática en equipos
- Cálculo de estadísticas (followers)
- MVP y Rookie del torneo
- Persistencia en JSON

---

## 🏆 Desafío 4 - Rankings y Búsqueda
- Ordenación por popularidad y alfabética
- Buscador con validación segura
- Registro de búsquedas en logs

---

## 💎 Desafío 5 - Sponsors
- Gestión de sponsors (string ↔ array)
- Asignación aleatoria a streamers
- Exportación de datos a CSV
- Añadir sponsors dinámicamente

---

## 🛠️ Tecnologías utilizadas

- PHP (Backend)
- HTML5
- CSS3 (Diseño gaming)
- JavaScript (interacciones básicas)
- JSON / TXT / CSV (persistencia de datos)

---

## 🔐 Seguridad

- Validación de formularios en backend
- Sanitización de datos (`htmlspecialchars`, `filter_var`)
- Uso de sesiones seguras
- Control de acceso mediante cookies
- Validación de inputs con expresiones regulares

---

## 📂 Gestión de datos

- Lectura y escritura de archivos (`file_get_contents`, `file_put_contents`)
- Uso de JSON para estructuras complejas
- Logs de acciones del sistema
- Persistencia entre sesiones

---

## 🎨 Diseño

- Tema gaming oscuro
- Uso de colores neón
- Interfaz interactiva
- Componentes visuales dinámicos

---

## 📌 Estado del proyecto

✔ Finalizado (versión académica)  
🔄 Mejoras futuras posibles (refactorización y optimización)

---

## 👨‍💻 Autor

Jose Miguel Risco Muñoz  
Estudiante de Desarrollo de Aplicaciones Web (DAW)

---

## 💡 Nota

Proyecto académico enfocado en la práctica de conceptos de backend en PHP, gestión de datos y seguridad en aplicaciones web.
