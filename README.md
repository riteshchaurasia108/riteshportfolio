<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ritesh Chaurasia | Growth & Retention Marketing</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #6366f1; /* Indigo */
            --bg-dark: #0f172a;
            --card-bg: #1e293b;
            --text-main: #f8fafc;
            --text-dim: #94a3b8;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-dark);
            color: var(--text-main);
            line-height: 1.6;
            scroll-behavior: smooth;
        }

        /* Navigation */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            padding: 1.5rem 10%;
            background: rgba(15, 23, 42, 0.9);
            backdrop-filter: blur(10px);
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 1000;
            border-bottom: 1px solid rgba(255,255,255,0.1);
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary-color);
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin-left: 2rem;
        }

        nav ul li a {
            text-decoration: none;
            color: var(--text-main);
            font-weight: 500;
            transition: 0.3s;
        }

        nav ul li a:hover {
            color: var(--primary-color);
        }

        /* Hero Section */
        header {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 10%;
            background: radial-gradient(circle at center, #1e293b 0%, #0f172a 100%);
        }

        header h1 {
            font-size: 4rem;
            margin-bottom: 1rem;
            background: linear-gradient(to right, #818cf8, #c084fc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        header p {
            font-size: 1.5rem;
            color: var(--text-dim);
            max-width: 700px;
            margin-bottom: 2rem;
        }

        .cta-button {
            padding: 1rem 2.5rem;
            background-color: var(--primary-color);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: 0.3s;
            box-shadow: 0 10px 20px rgba(99, 102, 241, 0.3);
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 25px rgba(99, 102, 241, 0.4);
        }

        /* Sections */
        section {
            padding: 100px 10%;
        }

        h2 {
            font-size: 2.5rem;
            margin-bottom: 3rem;
            text-align: center;
            position: relative;
        }

        h2::after {
            content: '';
            width: 50px;
            height: 4px;
            background: var(--primary-color);
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
        }

        /* Experience Cards */
        .timeline {
            max-width: 900px;
            margin: 0 auto;
        }

        .exp-card {
            background: var(--card-bg);
            padding: 2rem;
            border-radius: 15px;
            margin-bottom: 2rem;
            border-left: 5px solid var(--primary-color);
            transition: 0.3s;
        }

        .exp-card:hover {
            transform: scale(1.02);
        }

        .exp-card h3 {
            color: var(--primary-color);
            margin-bottom: 0.5rem;
        }

        .exp-card .company {
            font-weight: bold;
            display: flex;
            justify-content: space-between;
        }

        .exp-card .duration {
            color: var(--text-dim);
            font-size: 0.9rem;
        }

        .exp-card ul {
            margin-top: 1rem;
            padding-left: 1.2rem;
            color: var(--text-dim);
        }

        /* Skills */
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }

        .skill-tag {
            background: rgba(99, 102, 241, 0.1);
            border: 1px solid var(--primary-color);
            padding: 0.8rem 1.5rem;
            border-radius: 50px;
            font-weight: 500;
        }

        /* Contact Section */
        .contact-container {
            text-align: center;
        }

        .social-links {
            margin-top: 2rem;
        }

        .social-links a {
            font-size: 2rem;
            color: var(--text-main);
            margin: 0 15px;
            transition: 0.3s;
        }

        .social-links a:hover {
            color: var(--primary-color);
        }

        footer {
            text-align: center;
            padding: 2rem;
            border-top: 1px solid rgba(255,255,255,0.1);
            color: var(--text-dim);
        }

        @media (max-width: 768px) {
            header h1 { font-size: 2.5rem; }
            nav ul { display: none; }
            section { padding: 60px 5%; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">RITESH.</div>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <header>
        <p style="color: var(--primary-color); font-weight: bold; margin-bottom: 0;">Hi, I'm Ritesh Chaurasia</p>
        <h1>Growth & Retention Expert</h1>
        <p>Driving data-driven customer engagement and campaign effectiveness at the intersection of Marketing and Technology.</p>
        <a href="mailto:riteshchaurasia108@gmail.com" class="cta-button">Get In Touch</a>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <div style="max-width: 800px; margin: 0 auto; text-align: center; color: var(--text-dim);">
            <p>Based in Noida, I am currently an Executive in Growth & Retention Marketing at <strong>Brevistay</strong>. My journey started in Biotechnology and evolved through Data Science and Machine Learning, giving me a unique analytical edge in the MarTech space.</p>
            <br>
            <p>I specialize in streamlining marketing processes, managing high-impact campaigns, and analyzing performance data to optimize business growth.</p>
        </div>
    </section>

    <section id="experience">
        <h2>Work Experience</h2>
        <div class="timeline">
            <!-- Current Role -->
            <div class="exp-card">
                <div class="company">Brevistay <span>Jan 2025 - Present</span></div>
                <h3>Executive - Growth & Retention Marketing</h3>
                <p>Noida, Uttar Pradesh</p>
            </div>

            <!-- Badho -->
            <div class="exp-card">
                <div class="company">Badho <span>Aug 2024 - Dec 2024</span></div>
                <h3>Marketing Ops</h3>
                <ul>
                    <li>Streamlined marketing processes and managed multi-channel campaigns.</li>
                    <li>Analyzed performance data to optimize customer engagement and ROI.</li>
                    <li>Aligned operations with core business goals to drive campaign success.</li>
                </ul>
            </div>

            <!-- foundit -->
            <div class="exp-card">
                <div class="company">foundit <span>Jan 2024 - Aug 2024</span></div>
                <h3>Growth and Retention Marketing Intern</h3>
                <ul>
                    <li>Honed skills in customer engagement and retention strategies.</li>
                    <li>Contributed to strategic initiatives driving user growth.</li>
                </ul>
            </div>

            <!-- Data Science -->
            <div class="exp-card">
                <div class="company">CognoRise InfoTech <span>Sept 2023 - Oct 2023</span></div>
                <h3>Data Science Intern</h3>
                <ul>
                    <li>Developed ML models and performed predictive analysis using Python (Pandas, Scikit-learn).</li>
                    <li>Visualized insights using Matplotlib and Seaborn.</li>
                </ul>
            </div>

            <!-- ML Intern -->
            <div class="exp-card">
                <div class="company">IIIT Allahabad <span>May 2023 - June 2023</span></div>
                <h3>Machine Learning Intern</h3>
                <p>Applied statistical techniques to optimize models and analyze large datasets.</p>
            </div>
        </div>
    </section>

    <section id="skills">
        <h2>Expertise</h2>
        <div class="skills-container">
            <span class="skill-tag">Market Segmentation</span>
            <span class="skill-tag">Campaign Analytics</span>
            <span class="skill-tag">Campaign Effectiveness</span>
            <span class="skill-tag">Growth Marketing</span>
            <span class="skill-tag">Retention Strategy</span>
            <span class="skill-tag">Python (Data Science)</span>
            <span class="skill-tag">Machine Learning</span>
            <span class="skill-tag">SQL & Data Analysis</span>
            <span class="skill-tag">Marketing Operations</span>
            <span class="skill-tag">Front-end Web Dev</span>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <div class="contact-container">
            <p>Looking for a growth partner or MarTech expert?</p>
            <p style="font-size: 1.2rem; margin-top: 1rem; font-weight: bold;">riteshchaurasia108@gmail.com</p>
            <div class="social-links">
                <a href="https://www.linkedin.com/in/riteshchaurasia02" target="_blank"><i class="fab fa-linkedin"></i></a>
                <a href="mailto:riteshchaurasia108@gmail.com"><i class="fas fa-envelope"></i></a>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Ritesh Chaurasia. Built with passion & precision.</p>
    </footer>

</body>
</html>
