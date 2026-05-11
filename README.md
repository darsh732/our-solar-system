<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Grand Tour | Our Solar System</title>
    <style>
        :root {
            --space-black: #02040a;
            --sun-glow: #ff9d00;
            --accent-blue: #00d4ff;
            --text-gray: #b1b1b1;
        }

        body {
            font-family: 'Segoe UI', Roboto, sans-serif;
            background-color: var(--space-black);
            color: white;
            margin: 0;
            scroll-behavior: smooth;
        }

        /* Hero Section for the Sun */
        .sun-hero {
            background: radial-gradient(circle, #ffcc00 0%, #ff5e00 70%, #02040a 100%);
            padding: 100px 20px;
            text-align: center;
            border-bottom: 4px solid var(--sun-glow);
        }

        .sun-hero h1 {
            font-size: 4rem;
            margin: 0;
            text-shadow: 0 0 20px rgba(255, 157, 0, 0.8);
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        .planet-section {
            margin-bottom: 80px;
            padding: 30px;
            background: rgba(255, 255, 255, 0.03);
            border-left: 5px solid var(--accent-blue);
            border-radius: 0 15px 15px 0;
        }

        .planet-section h2 {
            font-size: 2.5rem;
            color: var(--accent-blue);
            margin-top: 0;
        }

        .stats-box {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            margin: 20px 0;
            font-size: 0.9rem;
            color: var(--sun-glow);
            font-weight: bold;
        }

        .stats-item {
            background: rgba(255, 157, 0, 0.1);
            padding: 5px 15px;
            border-radius: 20px;
            border: 1px solid var(--sun-glow);
        }

        p {
            line-height: 1.8;
            color: var(--text-gray);
        }

        footer {
            text-align: center;
            padding: 50px;
            border-top: 1px solid #222;
        }
    </style>
</head>
<body>

    <section class="sun-hero">
        <h1>The Sun</h1>
        <p style="color: white; max-width: 700px; margin: 20px auto;">
            The heart of our solar system. A nearly perfect sphere of hot plasma, the Sun provides the energy that sustains life on Earth and drives our weather. It contains 99.8% of the total mass of the entire solar system.
        </p>
    </section>

    <div class="container">
        
        <!-- Mercury -->
        <article class="planet-section">
            <h2>Mercury</h2>
            <div class="stats-box">
                <span class="stats-item">Distance from Sun: 58M km</span>
                <span class="stats-item">Moons: 0</span>
                <span class="stats-item">Year: 88 Days</span>
            </div>
            <p>Mercury is the smallest planet and the fastest traveler, zipping around the Sun every 88 Earth days. Because it lacks a substantial atmosphere to trap heat, temperatures swing wildly from 430°C during the day to -180°C at night. Its surface is heavily cratered, resembling Earth's Moon.</p>
        </article>

        <!-- Venus -->
        <article class="planet-section">
            <h2>Venus</h2>
            <div class="stats-box">
                <span class="stats-item">Distance from Sun: 108M km</span>
                <span class="stats-item">Moons: 0</span>
                <span class="stats-item">Temp: 471°C</span>
            </div>
            <p>Venus is often called Earth’s "evil twin." While similar in size, its thick atmosphere of carbon dioxide creates a runaway greenhouse effect, making it the hottest planet in our solar system. It rotates in the opposite direction of most planets (retrograde) and does so very slowly.</p>
        </article>

        <!-- Earth -->
        <article class="planet-section">
            <h2>Earth</h2>
            <div class="stats-box">
                <span class="stats-item">Distance from Sun: 150M km</span>
                <span class="stats-item">Moons: 1</span>
                <span class="stats-item">Water Surface: 71%</span>
            </div>
            <p>The only known world to support life. Earth is perfectly positioned in the "Goldilocks Zone"—not too hot, not too cold. It has a protective magnetic field and an atmosphere rich in nitrogen and oxygen, allowing liquid water to exist on the surface for billions of years.</p>
        </article>

        <!-- Mars -->
        <article class="planet-section">
            <h2>Mars</h2>
            <div class="stats-box">
                <span class="stats-item">Distance from Sun: 228M km</span>
                <span class="stats-item">Moons: 2</span>
                <span class="stats-item">Day: 24.6 Hours</span>
            </div>
            <p>Known as the Red Planet due to iron oxide (rust) in its soil. Mars is home to Olympus Mons, the largest volcano in the solar system, and Valles Marineris, a canyon system that would stretch across the entire United States. Scientists are currently searching for signs of ancient microbial life there.</p>
        </article>

        <!-- Jupiter -->
        <article class="planet-section">
            <h2>Jupiter</h2>
            <div class="stats-box">
                <span class="stats-item">Distance from Sun: 778M km</span>
                <span class="stats-item">Moons: 95+</span>
                <span class="stats-item">Mass: 318x Earth</span>
            </div>
            <p>A gas giant composed mostly of hydrogen and helium. Jupiter acts as a "cosmic vacuum cleaner," its massive gravity protecting inner planets from many comet impacts. Its most famous feature is the Great Red Spot—a storm larger than Earth that has raged for centuries.</p>
        </article>

        <!-- Saturn -->
        <article class="planet-section">
            <h2>Saturn</h2>
            <div class="stats-box">
                <span class="stats-item">Distance from Sun: 1.4B km</span>
                <span class="stats-item">Moons: 146</span>
                <span class="stats-item">Rings: 7 Main Rings</span>
            </div>
            <p>Adorned with a dazzling, complex system of icy rings, Saturn is the second-largest planet. It is so light (low density) that it would actually float in a giant bathtub of water if one existed. Its moon, Titan, is the only moon in the solar system with a dense atmosphere and liquid lakes of methane.</p>
        </article>

        <!-- Uranus -->
        <article class="planet-section">
            <h2>Uranus</h2>
            <div class="stats-box">
                <span class="stats-item">Distance from Sun: 2.9B km</span>
                <span class="stats-item">Moons: 28</span>
                <span class="stats-item">Tilt: 98 Degrees</span>
            </div>
            <p>An "Ice Giant" with a unique blue-green color caused by methane in its atmosphere. Unlike any other planet, Uranus rotates on its side, likely due to a massive collision billions of years ago. This causes extreme seasonal variations that last for decades.</p>
        </article>

        <!-- Neptune -->
        <article class="planet-section">
            <h2>Neptune</h2>
            <div class="stats-box">
                <span class="stats-item">Distance from Sun: 4.5B km</span>
                <span class="stats-item">Moons: 16</span>
                <span class="stats-item">Wind Speed: 2,000+ km/h</span>
            </div>
            <p>Neptune is the most distant major planet and was the first to be discovered through mathematical prediction rather than direct observation. It is a dark, cold world whipped by supersonic winds—the fastest recorded in the solar system.</p>
        </article>

    </div>

    <footer>
        <p>Voyage Complete. Created for Astronomy Enthusiasts.</p>
    </footer>

</body>
</html>
