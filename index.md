<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Jade Macaambac</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #fff;
        }

        header {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.8);
        }

        header h1 {
            font-size: 2.5rem;
            color: #00d1ff;
            text-transform: uppercase;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 40px;
        }

        nav a {
            text-decoration: none;
            padding: 10px 20px;
            font-size: 1rem;
            color: #fff;
            background: linear-gradient(90deg, #0f9b0f, #00ff95);
            border-radius: 25px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        nav a:hover {
            transform: scale(1.1);
            box-shadow: 0 4px 15px rgba(0, 255, 150, 0.75);
        }

        section {
            padding: 40px 20px;
        }

        section h2 {
            font-size: 2rem;
            color: #00d1ff;
            margin-bottom: 20px;
            text-align: center;
        }

        section p, ul {
            font-size: 1rem;
            line-height: 1.8;
            max-width: 800px;
            margin: 0 auto;
            text-align: left;
        }

        section ul {
            list-style: none;
            padding: 0;
        }

        section ul li {
            margin-bottom: 10px;
        }

        .skills ul {
            text-align: left;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.9);
        }

        footer p {
            color: #00d1ff;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            nav {
                flex-direction: column;
                gap: 10px;
            }

            nav a {
                font-size: 0.9rem;
                padding: 8px 15px;
            }

            section h2 {
                font-size: 1.5rem;
            }

            section p {
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Jade Macaambac</h1>
        <p>Professional Portfolio</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#skills">Skills</a>
        <a href="#experience">Experience</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>A meticulously dedicated professional looking for a job as a Security Professional in a company where I can share my abilities and knowledge while being given opportunities for career growth.</p>
    </section>

    <section id="skills" class="skills">
        <h2>Skills</h2>
        <ul>
            <li>Lean Six Sigma White Belt</li>
            <li>ASQ Certified MBB - 65316044 (February 1, 2023)</li>
            <li>Loss Control Management and HIRAC (SO3) - DOLE Prescribed 40-Hour Training Course in LCM (September 12-15, 2022)</li>
            <li>16TH NOSH CONGRESS (November 20-21, 2018)</li>
            <li>PRIVATE SECURITY EXECUTIVE MANAGEMENT (September 29-30, 2016)</li>
            <li>INFORMATION SECURITY MANAGEMENT SYSTEMS TRAINING (February 24-25, 2011)</li>
            <li>FIRST AID TRAINING (STANDARD) - September 6-9, 2010</li>
            <li>Quality Management System - ISO 9001:2015 (May 11, 2018)</li>
            <li>CERTIFIED SECURITY TRAINER (May 17, 2015)</li>
            <li>BASIC OCCUPATIONAL SAFETY AND HEALTH (April 30, 2014 - Present)</li>
            <li>CERTIFIED SECURITY PROFESSIONAL (February 2013 - Present)</li>
            <li>BUSINESS CONTINUITY MANAGEMENT TRAINING (March 1, 2011)</li>
            <li>BASIC LIFE SUPPORT (September 14-15, 2010)</li>
        </ul>
    </section>

    <section id="experience">
        <h2>Experience</h2>
        <ul>
            <li>Security and Loss Prevention Operations - Airfreight2100 Inc.</li>
            <li>Security and Loss Prevention Operations - Entrego Express Corporation</li>
            <li>Corporate Security Assistant Manager - Aseana Real Estate Services and Management</li>
            <li>General Manager - Detectnet Security Agency Corporation</li>
            <li>Operations Manager - Detectnet Security Agency Corporation</li>
            <li>Project Manager - MG Lanting Security Specialist Agency Inc.</li>
            <li>Physical Security Lead (Assistant Security Manager) - Teleperformance Philippines</li>
            <li>Site Commander - Teleperformance Philippines</li>
            <li>Area Coordinator - BULLDOG Security Agency Inc.</li>
            <li>Officer in Charge - Accenture Account - BULLDOG Security Agency Inc.</li>
            <li>Detachment Commander - RCC Land Development Property</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <p>From ensuring secure environments to designing innovative layouts, here are some of the works I'm proud of. Stay tuned for updates!</p>
        <a href="projects-folder-link" target="_blank">View Projects</a>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Feel free to reach out for collaborations or inquiries. Together, we can create something amazing!</p>
        <ul>
            <li>+639666096060</li>
            <li>+639988596060</li>
            <li><a href="mailto:jade.macaambac@gmail.com">jade.macaambac@gmail.com</a></li>
            <li><a href="mailto:jade.macaambac@outlook.com">jade.macaambac@outlook.com</a></li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 Jade Macaambac. All Rights Reserved.</p>
    </footer>
