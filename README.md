<!DOCTYPE html>
<html>

<head>

    <title>My Dashboard</title>

    <style>

        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f4f6f8;
        }

        header {
            background: #111827;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 28px;
        }

        header p {
            margin: 8px 0 0;
            color: #d1d5db;
        }

        nav {
            background: white;
            padding: 12px;
            text-align: center;
            border-bottom: 1px solid #ddd;
        }

        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #111827;
            font-weight: bold;
        }

        .container {
            max-width: 1000px;
            margin: auto;
            padding: 20px;
        }

        .welcome {
            background: white;
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 20px;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 12px;
            text-align: center;
        }

        .card h2 {
            margin-top: 0;
        }

        .button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 18px;
            background: #111827;
            color: white;
            text-decoration: none;
            border-radius: 8px;
        }

        footer {
            text-align: center;
            padding: 30px;
            color: #666;
        }

        @media (max-width: 600px) {

            .cards {
                grid-template-columns: 1fr;
            }

            nav a {
                display: inline-block;
                margin: 6px;
            }

        }

    </style>

</head>

<body>

    <header>

        <h1>My Dashboard</h1>

        <p>My personal web application</p>

    </header>


    <nav>

        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>

    </nav>


    <main class="container">

        <section class="welcome">

            <h2>Welcome, Vishwas</h2>

            <p>
                This is my first proper mobile-friendly website.
            </p>

        </section>


        <section class="cards">

            <div class="card">

                <h2>📅</h2>

                <h3>Planning</h3>

                <p>Manage your daily plans.</p>

                <a href="#" class="button">Open</a>

            </div>


            <div class="card">

                <h2>📊</h2>

                <h3>Dashboard</h3>

                <p>View important information.</p>

                <a href="#" class="button">Open</a>

            </div>


            <div class="card">

                <h2>⚙️</h2>

                <h3>Settings</h3>

                <p>Manage your application.</p>

                <a href="#" class="button">Open</a>

            </div>

        </section>

    </main>


    <footer>

        My Website © 2026

    </footer>

</body>

</html>
