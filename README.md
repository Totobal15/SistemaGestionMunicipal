# Sistema de Gestión de Automóviles y Funcionarios Municipales

## Descripción
Este proyecto implementa un sistema para la **Ilustre Municipalidad de Los Ángeles** que permite gestionar los **automóviles municipales** y los **funcionarios** autorizados para usarlos. Incluye un sistema de usuarios con **login y encriptación de contraseñas** y una interfaz gráfica desarrollada en **Tkinter** para facilitar la interacción.

## Características del Proyecto
1. **Gestión de Funcionarios**: Formulario para ingresar, editar, eliminar y listar funcionarios.
2. **Gestión de Automóviles**: Formulario para ingresar, editar, eliminar y listar automóviles municipales.
3. **Gestión de Usuarios**: Formulario para crear usuarios con contraseñas encriptadas, además de editar, eliminar y listar usuarios.
4. **Login de Usuario**: Sistema de login que se muestra al inicio de la aplicación.
5. **Validaciones**: Validación para campos vacíos, eliminaciones de datos, y detección de duplicados en todos los formularios.
6. **Menú de Navegación**: Menú que permite moverse entre los formularios de automóviles, funcionarios y usuarios.

## Requisitos
- Python 3.x
- Biblioteca Tkinter (para la interfaz gráfica)
- MySQL (para la base de datos)
- Paquetes adicionales:
  - `mysql-connector-python` (para conexión con MySQL)
  - `bcrypt` (para encriptación de contraseñas).
