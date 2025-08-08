<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sam Adedamola's Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: #f5f5f5; /* Light grey background */
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            max-width: 1100px; /* Wider container for balanced content */
            margin: 0 auto;
            padding: 0 1.5em;
        }
        header {
            background: linear-gradient(135deg, #333, #4a4a4a);
            color: white;
            text-align: center;
            padding: 3.5em 1em;
        }
        header h1 {
            font-size: 2.8em;
            font-weight: 600;
            margin: 0;
            opacity: 0;
            transform: translateY(20px);
            animation: fadeInUp 1s ease-out forwards;
        }
        header p {
            font-size: 1.3em;
            font-weight: 300;
            margin: 0.5em 0 0;
        }
        nav {
            background-color: #444;
            padding: 1.2em 0;
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 1px solid #555;
        }
        nav .container {
            display: flex;
            justify-content: center;
            gap: 2em;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-size: 1.1em;
            font-weight: 400;
            padding: 0.5em 1em;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #007BFF; /* Accent color */
        }
        .section {
            padding: 3em 2.5em; /* Increased padding */
            margin: 2em 0; /* Increased margin */
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 6px 12px rgba(0,0,0,0.1);
            border: 1px solid #e8e8e8;
        }
        .section h2 {
            color: #007BFF; /* Accent color */
            font-size: 2em;
            font-weight: 600;
            margin-bottom: 1.2em;
            text-align: left;
        }
        ul {
            list-style-type: disc;
            padding-left: 25px;
            font-size: 1.1em;
            line-height: 1.8;
        }
        ul ul {
            list-style-type: circle;
            padding-left: 30px;
        }
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); /* Slightly wider cards */
            gap: 2em; /* Increased gap */
        }
        .project {
            background-color: #f9f9f9; /* Slightly lighter background */
            padding: 1.8em;
            border-radius: 8px;
            box-shadow: 0 3px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            display: flex;
            flex-direction: column;
        }
        .project:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0,0,0,0.15);
        }
        .project h3 {
            color: #333;
            font-size: 1.5em;
            font-weight: 600;
            margin-bottom: 0.6em;
        }
        .project img {
            max-width: 100%;
            height: auto;
            border-radius: 6px;
            margin-bottom: 1em;
            display: block;
            max-height: 250px;
            object-fit: cover;
            border: 1px solid #e0e0e0;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .project p {
            font-size: 1em;
            line-height: 1.7;
            flex-grow: 1; /* Ensures text fills space evenly */
        }
        footer {
            background: linear-gradient(135deg, #333, #4a4a4a);
            color: white;
            text-align: center;
            padding: 2em;
            margin-top: 3em;
        }
        footer p {
            margin: 0;
            font-size: 1.1em;
            font-weight: 300;
        }
        /* Animation for the title */
        @keyframes fadeInUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        /* Responsive design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.2em;
            }
            header p {
                font-size: 1.1em;
            }
            nav .container {
                flex-wrap: wrap;
                gap: 1em;
            }
            nav a {
                font-size: 1em;
                padding: 0.4em 0.8em;
            }
            .section {
                padding: 2em 1.5em;
                margin: 1.5em 1em;
            }
            .section h2 {
                font-size: 1.6em;
            }
            .project h3 {
                font-size: 1.3em;
            }
            .project img {
                max-height: 200px;
            }
            .projects-grid {
                grid-template-columns: 1fr; /* Single column on mobile */
            }
            ul {
                font-size: 1em;
            }
        }
        @media (max-width: 480px) {
            header h1 {
                font-size: 1.8em;
            }
            header p {
                font-size: 0.9em;
            }
            .section {
                padding: 1.5em 1em;
            }
            .section h2 {
                font-size: 1.4em;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Sam Adedamola's Portfolio</h1>
            <p>Full-Stack Developer | Graphic Designer | Brand Marketer</p>
        </div>
    </header>

    <nav>
        <div class="container">
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#experience">Experience</a>
            <a href="#education">Education</a>
            <a href="#contact">Contact</a>
            <a href="#blog">Blog</a>
        </div>
    </nav>

    <div class="container">
        <div class="section" id="home">
            <h2>Home</h2>
            <p>Welcome to my portfolio! Explore my work in full-stack development, graphic design, and brand marketing.</p>
        </div>

        <div class="section" id="about">
            <h2>About Me</h2>
            <p>I'm Sam Adedamola, a skilled full-stack developer, graphic designer, and brand marketer dedicated to delivering high-quality solutions that drive results. With expertise in crafting innovative digital experiences, visually appealing designs, and effective brand strategies, I help businesses thrive in the digital landscape.</p>
        </div>

        <div class="section" id="skills">
            <h2>Technical Skills</h2>
            <ul>
                <li><strong>Full-Stack Development:</strong>
                    <ul>
                        <li>Programming languages: JavaScript, HTML/CSS, Python</li>
                        <li>Frameworks: React, Node.js, Django</li>
                        <li>Databases: MongoDB, MySQL</li>
                    </ul>
                </li>
                <li><strong>Graphic Design:</strong>
                    <ul>
                        <li>Design tools: Adobe Creative Suite (Photoshop, Illustrator, InDesign)</li>
                        <li>UI/UX design</li>
                        <li>Branding and visual identity</li>
                    </ul>
                </li>
                <li><strong>Brand Marketing:</strong>
                    <ul>
                        <li>Digital marketing strategies</li>
                        <li>Social media marketing</li>
                        <li>Content creation and copywriting</li>
                    </ul>
                </li>
            </ul>
        </div>

        <div class="section" id="projects">
            <h2>Projects</h2>
            <div class="projects-grid">
                <div class="project">
                    <h3>E-commerce Website</h3>
                    <p>Developed a responsive e-commerce website using React, Node.js, and MongoDB, featuring user authentication, payment gateway integration, and product management.</p>
                </div>
                <div class="project">
                    <h3>Task Management App</h3>
                    <p>Built a task management app using Django, allowing users to create, assign, and track tasks, with features like notifications and reporting.</p>
                </div>
                <div class="project">
                    <h3>Personal Finance Tracker</h3>
                    <p>Created a personal finance tracker using Python and MySQL, enabling users to track expenses, income, and budgets, with data visualization and alerts.</p>
                </div>
                <div class="project">
                    <h3>Brand Identity</h3>
                    <p>Designed a brand identity for a startup, including a logo, color palette, typography, and business cards, using Adobe Creative Suite.</p>
                </div>
                <div class="project">
                    <h3>UI/UX Design</h3>
                    <p>Created a user interface and user experience design for a mobile app, focusing on intuitive navigation, wireframing, and high-fidelity prototyping.</p>
                </div>
                <div class="project">
                    <h3>Marketing Materials</h3>
                    <p>Designed marketing materials, such as brochures, flyers, and social media graphics, for a local business, using Adobe InDesign and Photoshop.</p>
                </div>
                <div class="project">
                    <h3>Social Media Campaign</h3>
                    <p>Developed and executed a social media campaign for a new product launch, including content creation, influencer partnerships, and paid advertising.</p>
                </div>
                <div class="project">
                    <h3>Content Strategy</h3>
                    <p>Created a content strategy for a blog, including topic research, content calendar planning, and SEO optimization.</p>
                </div>
                <div class="project">
                    <h3>Rebranding</h3>
                    <p>Led a rebranding effort for a company, including market research, brand positioning, and visual identity design.</p>
                </div>
            </div>
        </div>

        <div class="section" id="experience">
            <h2>Work Experience</h2>
            <p>Currently seeking opportunities to apply my skills in full-stack development, graphic design, and brand marketing. Available for freelance Graduatedfull-time roles.</p>
        </div>

        <div class="section" id="education">
            <h2>Education</h2>
            <p><strong>BSc Computer Science</strong>D-Globalgrowthfield Tech centre centre: 2021</p>
        </div>

        <div class="section" id="contact">
            <h2>Contact</h2>
            <p><strong>Email:</strong> <a href="mailto:samadedamola4@gmail.com">samadedamola4@gmail.com</a></p>
            <p><strong>Phone:</strong> +2349032830132</p>
        </div>

        <div class="section" id="blog">
            <h2>Blog</h2>
            <p>Coming soon! Stay tuned for insights on web development, design trends, and brand marketing.</p>
        </div>
    </div>

    <footer>
        <div class="container">
            <p>&copy; 2025 Sam Adedamola. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
