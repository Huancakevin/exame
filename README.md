# Sistema de Gestión de Inventario - TechNova 2026

Este proyecto es una aplicación web desarrollada con el microframework **Flask** para la administración del inventario de una tienda de tecnología. Permite realizar operaciones completas de gestión de productos, integrando una base de datos local y una interfaz de usuario moderna.

## 🚀 Características

La aplicación implementa un flujo de trabajo profesional y cumple con las siguientes funcionalidades:
* **Listado de Productos**: Visualización de todo el stock en una tabla dinámica.
* **Registro**: Formulario para añadir nuevos productos al inventario.
* **Edición**: Capacidad de actualizar detalles de productos existentes mediante rutas dinámicas.
* **Eliminación**: Remoción segura de productos de la base de datos.
* **Interfaz Responsiva**: Diseño limpio utilizando **Bootstrap 5** y herencia de plantillas con **Jinja2**.

## 🛠️ Tecnologías Utilizadas

* **Backend**: Python & Flask
* **Frontend**: HTML5, CSS3, Jinja2, Bootstrap 5
* **Base de Datos**: SQLite3
* **Control de Versiones**: Git & GitHub

## 📋 Requisitos e Instalación

### Pre-requisitos
* Python 3.x instalado.
* Git configurado en el sistema.

### Instalación del entorno
1. **Clonar el repositorio:**

2.Configurar el entorno virtual:
python -m venv venv
# Activar en Windows:
venv\Scripts\activate
# Activar en Linux/Mac:
source venv/bin/activate

3. Instalar dependencias:
pip install -r requirements.txt



Campo,Tipo,Descripción
id,INTEGER,Clave primaria autoincrementable
nombre,TEXT,Nombre del producto (No nulo)
categoria,TEXT,Categoría tecnológica (No nulo)
precio,REAL,Precio unitario (No nulo)
stock,INTEGER,Cantidad disponible (No nulo)


Desarrollado por: Kevin
Proyecto: TEM-742 Examen Práctico - Grupo A

   ```bash
   git clone [https://github.com/Huancakevin/exame.git](https://github.com/Huancakevin/exame.git)
   cd exame
