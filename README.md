<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AyH CO - Tienda Online</title>
    <link rel="icon" type="image/png" href="img/logo.png">
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #fff; color: #333; }
        header { background-color: #000; color: white; padding: 20px; text-align: center; }
        nav { background-color: #222; color: white; text-align: center; padding: 10px; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        section { padding: 20px; }
        .productos { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
        .producto { border: 1px solid #ddd; border-radius: 8px; padding: 10px; text-align: center; background-color: #f9f9f9; }
        .producto img { width: 100%; height: auto; border-radius: 5px; }
        .producto h3 { margin: 10px 0 5px 0; }
        .producto p { margin: 5px 0; }
        .btn { background-color: #28a745; color: white; padding: 8px 12px; text-decoration: none; border-radius: 5px; display: inline-block; margin-top: 10px; }
        .btn:hover { background-color: #218838; }
        footer { background-color: #000; color: white; text-align: center; padding: 15px; margin-top: 20px; }
    </style>
</head>
<body>
    <header>
        <img src="img/logo.png" alt="Logo AyH CO" style="width: 100px; border-radius: 50%;">
        <h1>AyH CO</h1>
        <p>Ropa y Accesorios | Envíos a toda Colombia</p>
    </header>

    <nav>
        <a href="#camisetas">Camisetas</a>
        <a href="#bermudas">Bermudas</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section id="camisetas">
        <h2>Camisetas</h2>
        <div class="productos">
            <div class="producto">
                <img src="img/camiseta-gris.jpg" alt="Camiseta gris vintage">
                <h3>Camiseta gris vintage</h3>
                <p>$65.000 COP</p>
                <a class="btn" href="https://wa.me/57XXXXXXXXX">Comprar por WhatsApp</a>
            </div>
            <div class="producto">
                <img src="img/camiseta-mostaza.jpg" alt="Camiseta mostaza vintage">
                <h3>Camiseta mostaza vintage</h3>
                <p>$65.000 COP</p>
                <a class="btn" href="https://wa.me/57XXXXXXXXX">Comprar por WhatsApp</a>
            </div>
        </div>
    </section>

    <section id="bermudas">
        <h2>Bermudas</h2>
        <div class="productos">
            <div class="producto">
                <img src="img/bermuda-verde.jpg" alt="Bermuda verde militar">
                <h3>Bermuda verde militar</h3>
                <p>$85.000 COP</p>
                <a class="btn" href="https://wa.me/57XXXXXXXXX">Comprar por WhatsApp</a>
            </div>
            <div class="producto">
                <img src="img/bermuda-gris.jpg" alt="Bermuda gris">
                <h3>Bermuda gris</h3>
                <p>$85.000 COP</p>
                <a class="btn" href="https://wa.me/57XXXXXXXXX">Comprar por WhatsApp</a>
            </div>
            <div class="producto">
                <img src="img/bermuda-negra.jpg" alt="Bermuda negra">
                <h3>Bermuda negra</h3>
                <p>$85.000 COP</p>
                <a class="btn" href="https://wa.me/57XXXXXXXXX">Comprar por WhatsApp</a>
            </div>
        </div>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>¿Tienes preguntas? Escríbenos por WhatsApp o correo electrónico.</p>
        <p><strong>WhatsApp:</strong> <a href="https://wa.me/57XXXXXXXXX">+57 XXXXXXXXX</a></p>
        <p><strong>Email:</strong> contacto@ayhco.com</p>
    </section>

    <footer>
        <p>&copy; 2025 AyH CO. Todos los derechos reservados. Envíos a toda Colombia.</p>
    </footer>
</body>
</html>
# Ayhco2
