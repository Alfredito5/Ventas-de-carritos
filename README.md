# Ventas-de-carritos
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Hot Wheels</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }

        header {
            background-color: #f1c40f;
            color: white;
            text-align: center;
            padding: 20px;
        }

        nav {
            text-align: center;
            background-color: #2c3e50;
            padding: 10px;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            width: 80%;
            margin: 20px auto;
        }

        .product {
            display: inline-block;
            width: 30%;
            margin: 15px;
            text-align: center;
            background-color: white;
            padding: 20px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }

        .product img {
            width: 100%;
            height: auto;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
        }

        .contact-form button {
            background-color: #f1c40f;
            border: none;
            color: white;
            padding: 10px 20px;
            cursor: pointer;
        }

        .contact-form button:hover {
            background-color: #e67e22;
        }
    </style>
</head>
<body>

    <!-- Encabezado -->
    <header>
        <h1>Tienda de Carritos Hot Wheels</h1>
        <p>Compra los mejores Hot Wheels ¡y empieza tu colección hoy!</p>
    </header>

    <!-- Navegación -->
    <nav>
        <a href="#">Inicio</a>
        <a href="#">Productos</a>
        <a href="#">Contacto</a>
    </nav>

    <!-- Contenedor principal -->
    <div class="container">
        <!-- Productos -->
        <div class="product">
            <img src="nissanskyline.jpg" alt="Hot Wheels 1">
            <h3>Hot Wheels - Nissan Skyline Gt-R(R32)</h3>
            <p>Precio: $34.00</p>
            <button>Agregar al carrito</button>
        </div>
        <div class="product">
            <img src="fordgt.jpg" alt="Hot Wheels 2">
            <h3>Hot Wheels - Ford Gt40</h3>
            <p>Precio: $34.00</p>
            <button>Agregar al carrito</button>
        </div>
        <div class="product">
            <img src="porshe.jpg" alt="Hot Wheels 3">
            <h3>Hot Wheels - 96 Porsche Carrera</h3>
            <p>Precio: $34.00</p>
            <button>Agregar al carrito</button>
        </div>
    </div>

    <!-- Formulario de Contacto -->
    <div class="container">
        <h2>Contacto</h2>
        <form class="contact-form">
            <input type="text" name="name" placeholder="Tu nombre" required>
            <input type="email" name="email" placeholder="Tu email" required>
            <textarea name="message" placeholder="Escribe tu mensaje" required></textarea>
            <button type="submit">Enviar mensaje</button>
        </form>
    </div>

    <!-- Pie de página -->
    <footer>
        <p>&copy; 2025 Tienda de Hot Wheels. Todos los derechos reservados.</p>
    </footer>
<script src="//code.tidio.co/dua4jkwxomeij5rdv0dhjzpyowjoqpyi.js" async></script>
</body>
</html>
