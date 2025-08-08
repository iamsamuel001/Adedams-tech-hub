<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sam Adedamola's Portfolio</title>
    <style>
        body {
            background-color: #f5f5f5; /* Light grey background */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 2em;
        }
        nav {
            background-color: #444;
            padding: 1em;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1em;
        }
        nav a:hover {
            color: #ddd;
        }
        .section {
            padding: 2em;
            margin: 1em;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
        ul ul {
            list-style-type: circle;
            padding-left: 30px;
        }
        .project {
            margin-bottom: 1.5em;
        }
        .project h3 {
            margin-bottom: 0.5em;
        }
        .project img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            margin-bottom: 1em;
            display: block;
            max-height: 200px; /* Limit image height for consistency */
            object-fit: cover; /* Ensure images fit nicely */
        }
    </style>
</head>
<body>
    <header>
        <h1>Sam Adedamola's Portfolio</h1>
        <p>Full-Stack Developer | Graphic Designer | Brand Marketer</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#experience">Experience</a>
        <a href="#education">Education</a>
        <a href="#contact">Contact</a>
        <a href="#blog">Blog</a>
    </nav>

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
        <div class="project">
            <h3>E-commerce Website</h3>
            <img src="images/ecommerce-website.jpg" alt="E-commerce Website Screenshot">
            <p>Developed a responsive e-commerce website using React, Node.js, and MongoDB, featuring user authentication, payment gateway integration, and product management.</p>
        </div>
        <div class="project">
            <h3>Task Management App</h3>
            <img src="images/task-management-app.jpg" alt="Task Management App Screenshot">
            <p>Built a task management app using Django, allowing users to create, assign, and track tasks, with features like notifications and reporting.</p>
        </div>
        <div class="project">
            <h3>Personal Finance Tracker</h3>
            <img src="images/personal-finance-tracker.jpg" alt="Personal Finance Tracker Screenshot">
            <p>Created a personal finance tracker using Python and MySQL, enabling users to track expenses, income, and budgets, with data visualization and alerts.</p>
        </div>
        <div class="project">
            <h3>Brand Identity</h3>
            <img src="images/brand-identity.jpg" alt="Brand Identity Design">
            <p>Designed a brand identity for a startup, including a logo, color palette, typography, and business cards, using Adobe Creative Suite.</p>
        </div>
        <div class="project">
            <h3>UI/UX Design</h3>
            <img src="images/ui-ux-design.jpg" alt="UI/UX Design Mockup">
            <p>Created a user interface and user experience design for a mobile app, focusing on intuitive navigation, wireframing, and high-fidelity prototyping.</p>
        </div>
        <div class="project">
            <h3>Marketing Materials</h3>
            <img src="images/marketing-materials.jpg" alt="Marketing Materials Design">
            <p>Designed marketing materials, such as brochures, flyers, and social media graphics, for a local business, using Adobe InDesign and Photoshop.</p>
        </div>
        <div class="project">
            <h3>Social Media Campaign</h3>
            <img src="images/social-media-campaign.jpg" alt="Social Media Campaign Graphic">
            <p>Developed and executed a social media campaign for a new product launch, including content creation, influencer partnerships, and paid advertising.</p>
        </div>
        <div class="project">
            <h3>Content Strategy</h3>
            <img src="images/content-strategy.jpg" alt="Content Strategy Plan">
            <p>Created a content strategy for a blog, including topic research, content calendar planning, and SEO optimization.</p>
        </div>
        <div class="project">
            <h3>Rebranding</h3>
            <img src="images/rebranding.jpg" alt="Rebranding Design">
            <p>Led a rebranding effort for a company, including market research, brand positioning, and visual identity design.</p>
        </div>
    </div>

    <div class="section" id="experience">
        <h2>Work Experience</h2>
        <p>Currently seeking opportunities to apply my skills in full-stack development, graphic design, and brand marketing. Available for freelance and full-time roles.</p>
    </div>

    <div class="section" id="education">
        <h2>Education</h2>
        <p><strong>BSc Computer Science</strong><br>University of Massachusetts<br>Graduated: 2021</p>
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

    <footer>
        <p>&copy; 2025 Sam Adedamola. All rights reserved.</p>
    </footer>
</body>
</html>
