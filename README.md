# 💡 Proyecto Despliegue de Lámparas

Este proyecto consiste en una aplicación web desarrollada en **PHP** que permite gestionar el **encendido y apagado de lámparas** en diferentes zonas de un estadio.  
El objetivo principal es simular el control de iluminación mediante una interfaz sencilla y funcional.

---

## 🚀 Características principales

- Visualización de todas las lámparas del estadio.  
- Encendido y apagado de lámparas individualmente o por zonas.  
- Filtrado por zonas.  
- Conexión a base de datos para guardar los estados.  
- Arquitectura **MVC (Modelo-Vista-Controlador)**.  
- Uso de **autoloading** y **namespaces** con **Composer**.  

---

## 🧩 Tecnologías utilizadas

- **PHP 8+**  
- **Doctrine ORM**  
- **Composer**  
- **MySQL / MariaDB**  
- **Docker** (para el entorno de desarrollo)  
- **HTML, CSS y Bootstrap 5**  

---

## 🛠️ Estructura del proyecto

despliegueLamparas/
├── src/
│ ├── Controller/ # Controladores (lógica de la aplicación)
│ ├── Entity/ # Entidades de Doctrine
│ ├── Repository/ # Repositorios de acceso a datos
│ └── View/ # Vistas HTML
├── config/
│ └── bootstrap.php # Configuración inicial de Doctrine
├── public/
│ ├── index.php # Punto de entrada
│ └── assets/ # Archivos estáticos (CSS, imágenes)
├── docker-compose.yml # Configuración del entorno Docker
├── composer.json # Dependencias del proyecto
└── README.md # Documentación del proyecto

🧠 Autor

Dolly Sarmiento

📜 Licencia

Este proyecto se distribuye bajo la licencia MIT.
