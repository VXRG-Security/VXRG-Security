<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VXRG | Global Cyber Defense & Intelligence</title>
    <style>
        :root {
            --primary-green: #00ff41;
            --bg-black: #050505;
            --surface-dark: #0f0f0f;
            --border-color: #1a1a1a;
            --text-main: #e0e0e0;
            --text-dim: #888888;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }

        body { background-color: var(--bg-black); color: var(--text-main); line-height: 1.6; overflow-x: hidden; }

        /* Navigation */
        nav { display: flex; justify-content: space-between; align-items: center; padding: 25px 8%; background: rgba(0,0,0,0.9); border-bottom: 1px solid var(--border-color); position: sticky; top: 0; z-index: 1000; }
        .brand { font-size: 1.6rem; font-weight: 800; color: var(--primary-green); letter-spacing: 2px; }
        .nav-links { display: flex; gap: 30px; }
        .nav-links a { color: var(--text-main); text-decoration: none; font-size: 0.85rem; text-transform: uppercase; letter-spacing: 1px; transition: 0.3s; }
        .nav-links a:hover { color: var(--primary-green); }

        /* Hero Section */
        .hero { height: 80vh; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; padding: 0 20px; background: radial-gradient(circle at center, #111 0%, #050505 100%); }
        .hero h1 { font-size: 3.5rem; margin-bottom: 15px; letter-spacing: -1px; }
        .hero p { color: var(--text-dim); max-width: 600px; font-size: 1.1rem; margin-bottom: 30px; }
        .btn-main { padding: 12px 35px; border: 1px solid var(--primary-green); color: var(--primary-green); text-decoration: none; font-weight: bold; text-transform: uppercase; letter-spacing: 2px; transition: 0.4s; }
        .btn-main:hover { background: var(--primary-green); color: black; box-shadow: 0 0 20px rgba(0, 255, 65, 0.4); }

        /* Services Section */
        .services { padding: 100px 8%; background: var(--bg-black); }
        .section-title { text-align: center; margin-bottom: 60px; }
        .section-title h2 { font-size: 2rem; color: var(--primary-green); margin-bottom: 10px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 30px; }
        .service-card { background: var(--surface-dark); padding: 40px; border: 1px solid var(--border-color); border-radius: 4px; transition: 0.4s; }
        .service-card:hover { border-color: var(--primary-green); transform: translateY(-10px); }
        .service-card h3 { margin-bottom: 15px; font-size: 1.2rem; color: white; }
        .service-card p { color: var(--text-dim); font-size: 0.95rem; }

        /* Footer */
        footer { padding: 60px 8%; border-top: 1px solid var(--border-color); text-align: center; background: #000; }
        .footer-text { color: var(--text-dim); font-size: 0.8rem; letter-spacing: 1px; }
    </style>
</head>
<body>

<nav>
    <div class="brand">VXRG™</div>
    <div class="nav-links">
        <a href="#">Network</a>
        <a href="#">Cloud Security</a>
        <a href="#">Intelligence</a>
    </div>
</nav>

<section class="hero">
    <h1>Securing the Digital Frontier</h1>
    <p>Advanced Vulnerability Research & Tactical Cyber Defense Solutions for Enterprise Infrastructure.</p>
    <a href="#" class="btn-main">Get Secure Now</a>
</section>

<section class="services">
    <div class="section-title">
        <h2>Our Core Capabilities</h2>
        <p style="color: var(--text-dim);">Engineered for high-stakes digital environments.</p>
    </div>
    <div class="grid">
        <div class="service-card">
            <h3>Vulnerability Disclosure</h3>
            <p>Identifying and mitigating critical security flaws before they are exploited. Trusted by top-tier agencies.</p>
        </div>
        <div class="service-card">
            <h3>Penetration Testing</h3>
            <p>Comprehensive offensive security assessments to strengthen organizational resilience.</p>
        </div>
        <div class="service-card">
            <h3>Global Threat Intel</h3>
            <p>Real-time monitoring and analysis of emerging cyber threats across international borders.</p>
        </div>
    </div>
</section>

<footer>
    <p class="footer-text">© 2026 VALTHRONIS XYRO GENIX (VXRG) GLOBAL. OPERATING WORLDWIDE. <br> 
    SWITZERLAND | GLOBAL OPERATIONS | QUANTUM SECURE</p>
</footer>

</body>
</html>
