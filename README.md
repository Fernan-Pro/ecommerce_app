# Proyecto Ecommerce App

Este proyecto es una aplicación de comercio electrónico construida con un backend en Django y un frontend en TypeScript.

## Características

- Gestión de productos.
- Gestión de usuarios y autenticación.
- Gestión de pedidos.
- Interfaz de usuario moderna y responsiva.

## Requisitos

- Python 3.x
- Node.js y npm

## Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/Fernan-Pro/ecommerce_app.git
   cd ecommerce_app
   ```

2. Instala las dependencias del backend:

   ```bash
   cd backend
   pip install -r requirements.txt
   ```

3. Instala las dependencias del frontend:

   ```bash
   cd ../frontend
   npm install
   ```

## Uso

1. Realiza las migraciones de la base de datos:

   ```bash
   cd backend
   python manage.py migrate
   ```

2. Inicia el servidor backend:

   ```bash
   python manage.py runserver
   ```

3. Inicia el servidor frontend:

   ```bash
   cd ../frontend
   npm start
   ```

4. Abre tu navegador y navega a `http://localhost:3000` para usar la aplicación.

## Estructura del Proyecto

```plaintext
.
├── README.md
├── backend
│   ├── manage.py
│   ├── requirements.txt
│   └── ...
├── deploy
│   └── ...
├── frontend
│   ├── package.json
│   ├── src
│   │   ├── index.tsx
│   │   └── ...
│   └── ...
├── media
│   └── ...
├── orders
│   └── ...
├── products
│   └── ...
├── users
│   └── ...
└── db.sqlite3
```

- `backend`: Contiene el código y dependencias del servidor backend hecho con Django.
- `frontend`: Contiene el código y dependencias del cliente frontend hecho con TypeScript.
- `deploy`: Contiene configuraciones y scripts de despliegue.
- `media`: Contiene archivos de medios, como imágenes de productos.
- `orders`: Gestión de pedidos.
- `products`: Gestión de productos.
- `users`: Gestión de usuarios y autenticación.
- `db.sqlite3`: Archivo de la base de datos SQLite.

## Contacto

Para cualquier consulta o sugerencia, puedes contactarme a través de ferqtexwinner@gmail.com.
