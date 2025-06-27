# Fake Server - Datos de Práctica para Angular

Este repositorio contiene datos ficticios diseñados específicamente para estudiantes de Angular que están aprendiendo a consumir APIs REST. Los datos están estructurados para ser utilizados con [my-json-server.typicode.com](https://my-json-server.typicode.com/), que proporciona una API REST falsa basada en un archivo JSON.

## 🚀 Cómo usar este servidor

### URL del servidor
```
https://my-json-server.typicode.com/tu-usuario/fake-server-repo
```
*Reemplaza `tu-usuario` con tu nombre de usuario de GitHub*

### Endpoints disponibles

#### 👥 Usuarios (`/users`)
- **GET** `/users` - Obtiene todos los usuarios
- **GET** `/users/1` - Obtiene un usuario específico por ID
- **POST** `/users` - Crea un nuevo usuario
- **PUT** `/users/1` - Actualiza un usuario completo
- **PATCH** `/users/1` - Actualiza parcialmente un usuario
- **DELETE** `/users/1` - Elimina un usuario

#### 🛡️ Roles (`/roles`)
- **GET** `/roles` - Obtiene todos los roles
- **GET** `/roles/1` - Obtiene un rol específico por ID

#### 📦 Productos (`/products`)
- **GET** `/products` - Obtiene todos los productos
- **GET** `/products/1` - Obtiene un producto específico por ID

## 📊 Estructura de Datos

### Usuarios
Cada usuario contiene:
- **user_id**: Identificador único
- **user_gender**: Género del usuario
- **role**: Rol asignado (analyst, manager, accounting)
- **user_name**: Nombre completo (first_name, last_name)
- **user_location**: Ubicación (country, city)
- **user_email**: Correo electrónico corporativo
- **user_ultimatix**: ID de empleado
- **user_password**: Contraseña (solo para práctica)
- **user_phone**: Número de teléfono
- **user_picture**: URL de imagen de perfil

### Roles
Cada rol incluye:
- **role_id**: Identificador único
- **role_name**: Nombre del rol
- **role_description**: Descripción del rol
- **role_supported**: Si el rol está activo

### Productos
Cada producto contiene:
- **product_id**: Identificador único
- **product_name**: Nombre del producto
- **product_list_price**: Precio de lista
- **product_min_promo_quantity**: Cantidad mínima para promoción
- **product_max_promo_quantity**: Cantidad máxima para promoción
- **product_min_promo_price**: Precio promocional

## 🎯 Casos de uso perfectos para practicar

1. **Lista de usuarios con filtros por rol**
2. **Catálogo de productos con precios promocionales**
3. **Dashboard de administración con roles**
4. **Formularios de registro y edición**
5. **Sistema de autenticación básico**
6. **Carrito de compras con productos**

## ⚠️ Importante

- **Solo para práctica**: Estos datos son completamente ficticios
- **No usar en producción**: Las contraseñas están en texto plano
- **Limitaciones de my-json-server**: Los cambios no se persisten permanentemente
- **CORS habilitado**: Puedes hacer peticiones desde cualquier dominio

## 🔧 Configuración en tu proyecto Angular

1. Asegúrate de tener `HttpClientModule` importado en tu `app.module.ts`
2. Crea un servicio para manejar las peticiones HTTP
3. Usa observables para manejar las respuestas asíncronas
4. Implementa manejo de errores básico

¡Perfecto para estudiantes que están aprendiendo Angular y necesitan datos de práctica! 🚀
