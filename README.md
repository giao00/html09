<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tasty Food</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
        }

        header {
            background-color: black;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header .logo {
            font-size: 24px;
            font-weight: bold;
            color: white;
        }

        header nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        header nav a:hover {
            color: #f39c12;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background: url('https://via.placeholder.com/1500x600') no-repeat center/cover;
            color: white;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }

        .hero button {
            padding: 10px 20px;
            background-color: #f39c12;
            border: none;
            color: white;
            font-size: 1rem;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }

        .hero button:hover {
            background-color: #e67e22;
            transform: scale(1.1);
        }

        .section {
            text-align: center;
            padding: 50px 20px;
        }

        .section img {
            width: 100%;
            max-width: 400px;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .section h2 {
            font-size: 2rem;
            margin-bottom: 10px;
        }

        .section p {
            font-size: 1rem;
            line-height: 1.6;
            margin-bottom: 20px;
        }

        footer {
            background-color: black;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 30px;
        }

        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            animation: fadeIn 1s forwards;
        }

        @keyframes fadeIn {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Tasty Food</div>
        <nav>
