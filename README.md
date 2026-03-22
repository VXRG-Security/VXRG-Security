<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VXRG Security | Professional Cyber Defense</title>
    <style>
        :root {
            --primary-green: #00ff41;
            --dark-bg: #0a0a0a;
            --card-bg: #111111;
            --text-gray: #a0a0a0;
        }

        body {
            background-color: var(--dark-bg);
            color: #ffffff;
            font-family: 'Inter', -apple-system, sans-serif;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        /* Navigation */
        nav {
            background: rgba(10, 10, 10, 0.9);
            padding: 20px 10%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #222;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo { font-size: 22px; font-weight: 800; color: var(--primary-green); letter-spacing: 3px; }

        /* Hero Section */
        .hero {
            padding: 100px 10% 60px;
            text-align: center;
            background: radial-gradient(circle at center, #003311 0%, #0a0a0a 70%);
        }

        .hero h1 { font-size: 4em; margin-bottom: 20px; letter-spacing: -1px; }
        .hero p { color: var(--text-gray); font-size: 1.2em; max-width: 700px; margin: 0 auto 30px; }

        .btn-main {
            background: var(--primary-green);
            color: #000;
            padding: 12px 30px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: 0.3s;
        }

        .btn-main:hover { box-shadow: 0 0 20px var(--primary-green); transform: scale(1.05); }

        /* Stats Section */
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 40px 10%;
        }

        .stat-card {
            background: var(--card-bg);
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid var(--primary-green);
            text-align: center;
        }

        /* Services */
        .section-title { text-align: center; font-size: 2.5em; margin: 60px 0 40px; }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            padding: 0 10% 80px;
        }

        .service-card {
            background: var(--card-bg);
            padding: 30px;
            border-radius: 15px;
            border: 1px solid #222;
            transition: 0.4s;
        }

        .service-card:hover {
            border-color: var(--primary-green);
            background: #161616;
        }

        .service-card h3 { color: var(--primary-green); margin-bottom: 15px; }

        /* Footer */
        footer {
            background: #050505;
            padding: 40px 10%;
            border-top: 1px solid #222;
            text-align: center;
            color: #555;
        }

        .badge {
            display: inline-block;
            border: 1px solid var(--primary-green);
            color: var(--primary-green);
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.8em;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

<nav>
    <div class="logo">VXRG SECURITY</div>
    <div style="font-size: 0.8em; color: #555;">LEAD RESEARCHER: HACKER</div>
</nav>

<section class="hero">
    <div class="badge">SECURED BY VXRG GENIX</div>
    <h1>The Future of Cyber Defense</h1>
    <p>Providing advanced security auditing, vulnerability research, and digital protection for global infrastructures.</p>
    <a href="#" class="btn-main">Get a Security Audit</a>
</section>

<div class="stats-grid">
    <div class="stat-card">
        <h3>NASA VDP</h3>
        <p>Recognized Contributor</p>
    </div>
    <div class="stat-card">
        <h3>OSCP / CEH</h3>
        <p>Future Roadmap</p>
    </div>
    <div class="stat-card">
        <h3>Switzerland</h3>
        <p>Global Mission</p>
    </div>
</div>

<h2 class="section-title">Core Operations</h2>
<div class="services-grid">
    <div class="service-card">
        <h3>Vulnerability Disclosure</h3>
        <p>Independent security research and ethical disclosure of critical vulnerabilities in enterprise systems.</p>
    </div>
    <div class="service-card">
        <h3>Penetration Testing</h3>
        <p>Simulating real-world cyber attacks to identify and patch security gaps before malicious actors find them.</p>
    </div>
    <div class="service-card">
        <h3>Digital Forensics</h3>
        <p>Analyzing system breaches and providing comprehensive technical reports on security incidents.</p>
    </div>
</div>

<footer>
    <p>&copy; 2026 VXRG Security | Valthronis Xyro Genix. All Rights Reserved.</p>
    <p style="font-size: 0.8em; margin-top: 10px;">Managed by Hacker | Cybersecurity Researcher</p>
</footer>

</body>
</html>
