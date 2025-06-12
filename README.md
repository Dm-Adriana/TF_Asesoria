# T&F Asesoría y Consultoría Inmobiliaria E.I.R.L  
### Sistema Integral de Gestión Inmobiliaria y Plataforma Web  

---

## 📌 Descripción del Proyecto  
Este proyecto consiste en el desarrollo de un **sistema de escritorio** para la gestión administrativa integral de propiedades, proyectos, asesores y clientes, junto con la implementación de una **página web** para la visualización de propiedades, contacto con clientes y promoción de servicios inmobiliarios de **T&F Asesoría y Consultoría Inmobiliaria E.I.R.L**.  

El objetivo es optimizar los procesos internos, mejorar la captación de clientes y centralizar la información, eliminando las ineficiencias actuales.  

---

## 🔎 Problemática Actual  
La empresa enfrenta los siguientes desafíos:  
- **Falta de seguimiento y control** en las operaciones inmobiliarias  
- **Estancamiento en la captación de clientes** debido a métodos tradicionales  
- **Gestión ineficiente** de propiedades, proyectos y asesores  
- **Información desarticulada** que dificulta la toma de decisiones  

---

## 🎯 Objetivos del Proyecto  
### Sistema de Escritorio  
- Gestión administrativa integral de:  
  - 📌 Propiedades  
  - 🏗️ Proyectos inmobiliarios  
  - 👥 Asesores  
  - 🤝 Clientes  

### Página Web Corporativa  
- 🌐 Visualización de propiedades disponibles  
- 📞 Canal de contacto directo con clientes  
- 📢 Promoción de servicios inmobiliarios  

---

## ⚙️ Requisitos de Instalación  

### 📦 Dependencias Principales  
- PHP (>= 8.0)  
- Composer (Gestor de paquetes PHP)  
- Node.js (Para el entorno de Electron)  


# Instalación y Configuración

## 1. Requisitos Previos

- Tener instalado **Composer** en tu sistema.
- PHP con las siguientes extensiones habilitadas en el archivo `php.ini`:

```ini
extension=gd
extension=zip
extension=xml
extension=simplexml
extension=fileinfo
```

Para ubicar el archivo `php.ini` y verificar las extensiones, usa:

```bash
php --ini
```

---

## 2. Instalación del Proyecto

Abre la terminal y sigue estos pasos:

```bash
# Navegar al directorio del proyecto
cd C:\xampp\htdocs\TF

# Inicializar composer sin interacción
composer init --no-interaction --type=project

# Instalar PHPSpreadsheet para gestión de reportes en Excel
composer require phpoffice/phpspreadsheet
```

---

## 3. Uso de Electron para el Panel de Escritorio

Si quieres usar Electron para la interfaz de escritorio, ejecuta:

```bash
npm init -y
npm install electron --save-dev
npm start
```

---