# ewaste-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reduce E-Waste | Take Action Today</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f7f6;
            color: #333;
        }

        header {
            background: #1b5e20;
            color: white;
            padding: 2rem 1rem;
            text-align: center;
        }

        nav {
            background: #2e7d32;
            padding: 0.8rem;
            text-align: center;
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

        section {
            padding: 2rem;
            max-width: 1000px;
            margin: auto;
        }

        .card-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        .cta {
            background: #a5d6a7;
            text-align: center;
            padding: 2rem;
            border-radius: 8px;
        }

        footer {
            background: #1b5e20;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }

        button {
            background: #2e7d32;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
        }

        button:hover {
            background: #1b5e20;
        }
    </style>
</head>
<body>

<header>
    <h1>Reduce E-Waste</h1>
    <p>Small Actions. Big Environmental Impact.</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#problems">The Problem</a>
    <a href="#solutions">Solutions</a>
    <a href="#contact">Get Involved</a>
</nav>

<section id="about">
    <h2>About E-Waste</h2>
    <p>
        Electronic waste (e-waste) includes discarded phones, computers, TVs, and other electronics. 
        When not disposed of properly, these devices release harmful materials into the environment.
    </p>
</section>

<section id="problems">
    <h2>The Problem</h2>
    <div class="card-container">
        <div class="card">
            <h3>Toxic Materials</h3>
            <p>Electronics contain lead, mercury, and cadmium that can contaminate soil and water.</p>
        </div>
        <div class="card">
            <h3>Overproduction</h3>
            <p>Frequent upgrades increase demand for raw materials and energy consumption.</p>
        </div>
        <div class="card">
            <h3>Low Recycling Rates</h3>
            <p>Many electronics are thrown away instead of being recycled responsibly.</p>
        </div>
    </div>
</section>

<section id="solutions">
    <h2>What You Can Do</h2>
    <div class="card-container">
        <div class="card">
            <h3>Repair Devices</h3>
            <p>Fix electronics instead of replacing them to extend their lifespan.</p>
        </div>
        <div class="card">
            <h3>Recycle Properly</h3>
            <p>Use certified e-waste recycling centers in your community.</p>
        </div>
        <div class="card">
            <h3>Buy Refurbished</h3>
            <p>Choose refurbished or second-hand electronics to reduce demand.</p>
        </div>
        <div class="card">
            <h3>Donate Old Devices</h3>
            <p>Give working electronics to schools or charities instead of throwing them away.</p>
        </div>
    </div>
</section>

<section class="cta" id="contact">
    <h2>Take Action Today</h2>
    <p>Join the movement to reduce electronic waste and protect our planet.</p>
    <button onclick="alert('Thank you for supporting e-waste reduction!')">Pledge to Reduce E-Waste</button>
</section>

<footer>
    <p>© 2026 Reduce E-Waste Initiative | Designed for Awareness</p>
</footer>

</body>
</html>
