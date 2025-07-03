<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tiana's Carteras - Tu tienda de carteras exclusivas</title>
    <style>
        :root {
            --primary-color: #8e44ad;
            --secondary-color: #f39c12;
            --light-bg: #f9e9f2;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }

        body {
            background: var(--light-bg);
        }

        /* Header */
        header {
            background: white;
            padding: 20px 5%;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            font-size: 28px;
            font-weight: 700;
            color: var(--primary-color);
            font-family: 'Brush Script MT', cursive;
        }

        .nav-links {
            display: flex;
            gap: 30px;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--primary-color);
            font-weight: 500;
            transition: color 0.3s;
        }

        /* Products */
        .products {
            padding: 120px 5% 80px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .section-title {
            text-align: center;
            margin-bottom: 50px;
            color: var(--primary-color);
            font-size: 2.5em;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .product-card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .product-card:hover {
            transform: translateY(-10px);
        }

        .product-img {
            height: 250px;
            background: #f1f1f1;
            background-size: cover;
            background-position: center;
        }

        .product-info {
            padding: 20px;
        }

        .price {
            color: var(--secondary-color);
            font-size: 1.4em;
            font-weight: 600;
            margin: 10px 0;
        }

        .btn {
            background: var(--primary-color);
            color: white;
            padding: 10px 25px;
            border: none;
