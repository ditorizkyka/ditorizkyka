```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile README Preview - @ditorizkyka</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            color: #e2e8f0;
            line-height: 1.6;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #1e293b;
            border-radius: 12px;
            padding: 40px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.5);
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
        }

        h1 {
            font-size: 3em;
            margin-bottom: 10px;
            background: linear-gradient(135deg, #0ea5e9, #22c55e);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .subtitle {
            font-size: 1.3em;
            color: #94a3b8;
            margin-bottom: 20px;
        }

        .links {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-bottom: 20px;
        }

        .links a {
            color: #0ea5e9;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s ease;
        }

        .links a:hover {
            color: #22c55e;
        }

        .badges {
            display: flex;
            justify-content: center;
            gap: 10px;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .badge {
            display: inline-block;
            padding: 5px 12px;
            background: #334155;
            border-radius: 20px;
            font-size: 0.85em;
            color: #cbd5e1;
        }

        hr {
            border: none;
            height: 1px;
            background: #334155;
            margin: 30px 0;
        }

        h2 {
            color: #0ea5e9;
            font-size: 1.8em;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .description {
            background: #0f172a;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            border-left: 4px solid #0ea5e9;
        }

        .description p {
            margin-bottom: 15px;
            color: #cbd5e1;
        }

        .description ul {
            list-style: none;
            margin-left: 20px;
        }

        .description li {
            margin-bottom: 10px;
            color: #cbd5e1;
        }

        .stack-section {
            margin-bottom: 30px;
        }

        .stack-note {
            color: #94a3b8;
            font-style: italic;
            margin-bottom: 15px;
            font-size: 0.95em;
        }

        .tech-badges {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-bottom: 20px;
        }

        .tech-badge {
            display: inline-flex;
            align-items: center;
            padding: 8px 16px;
            background: #334155;
            border-radius: 6px;
            font-size: 0.9em;
            font-weight: 600;
            color: #e2e8f0;
            transition: transform 0.2s ease;
        }

        .tech-badge:hover {
            transform: translateY(-2px);
        }

        .projects {
            display: grid;
            gap: 15px;
        }

        .project {
            background: #0f172a;
            padding: 20px;
            border-radius: 8px;
            border-left: 4px solid #22c55e;
            transition: transform 0.2s ease;
        }

        .project:hover {
            transform: translateX(5px);
        }

        .project-title {
            color: #22c55e;
            font-weight: 700;
            margin-bottom: 8px;
            font-size: 1.1em;
        }

        .project-desc {
            color: #cbd5e1;
            margin-bottom: 10px;
        }

        .project-link {
            color: #0ea5e9;
            text-decoration: none;
            font-size: 0.9em;
            transition: color 0.2s ease;
        }

        .project-link:hover {
            color: #22c55e;
        }

        .stats-section {
            background: #0f172a;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            text-align: center;
        }

        .stats-section p {
            color: #94a3b8;
            margin-bottom: 15px;
        }

        .focus-list {
            background: #0f172a;
            padding: 20px;
            border-radius: 8px;
            border-left: 4px solid #f97316;
        }

        .focus-list ul {
            list-style: none;
            margin-left: 0;
        }

        .focus-list li {
            margin-bottom: 12px;
            color: #cbd5e1;
            padding-left: 25px;
            position: relative;
        }

        .focus-list li:before {
            content: "🚀";
            position: absolute;
            left: 0;
        }

        .facts {
            background: #0f172a;
            padding: 20px;
            border-radius: 8px;
            border-left: 4px solid #06b6d4;
        }

        .facts ul {
            list-style: none;
            margin-left: 0;
        }

        .facts li {
            margin-bottom: 12px;
            color: #cbd5e1;
            padding-left: 25px;
            position: relative;
        }

        .facts li:before {
            content: "•";
            position: absolute;
            left: 0;
            color: #06b6d4;
            font-weight: bold;
        }

        .footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #334155;
        }

        .footer p {
            color: #94a3b8;
            font-size: 1.1em;
        }

        .footer strong {
            color: #fbbf24;
        }

        @media (max-width: 768px) {
            .container {
                padding: 20px;
            }

            h1 {
                font-size: 2em;
            }

            .links {
                gap: 10px;
            }

            .tech-badges {
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <div class="header">
            <h1>Hello i'm Dito</h1>
            <p class="subtitle">Mobile Developer • AI Developer</p>
            
            <div class="links">
                <a href="https://ditorizkyka.is-a.dev/" target="_blank">Portfolio</a>
                <a href="https://github.com/ditorizkyka" target="_blank">GitHub</a>
                <a href="https://www.linkedin.com/in/anditorizkyka/" target="_blank">LinkedIn</a>
                <a href="mailto:rizkykandito@gmail.com" target="_blank">Email</a>
                <a href="https://wa.me/6281389018701" target="_blank">WhatsApp</a>
                <a href="https://www.instagram.com/ditorizkyka_/" target="_blank">Instagram</a>
            </div>

            <div class="badges">
                <span class="badge">Profile views</span>
                <span class="badge">Followers</span>
            </div>
        </div>

        <hr>

        <!-- Description -->
        <h2>📝 Description</h2>
        <div class="description">
            <p><strong>Andito Rizkyka R.</strong>, a <strong>final-semester Informatics student at Telkom University (AI focus)</strong> with a strong interest in building <strong>real-world AI systems</strong> and shipping them into <strong>mobile apps</strong>.</p>
            <p>I enjoy working on <strong>Computer Vision</strong>, <strong>ML prototyping</strong>, and <strong>product-oriented mobile development</strong>—turning models into features that people can actually use.</p>
            
            <ul>
                <li>🎓 <strong>Telkom University</strong> — Informatics (AI Focus), <strong>GPA 3.92/4.00</strong></li>
                <li>🧠 Focus areas: <strong>Computer Vision</strong>, <strong>Machine Learning</strong>, <strong>Data Science</strong>, <strong>AI in Mobile</strong></li>
                <li>🧩 I like building end-to-end: dataset → training → evaluation → deployment → app UI</li>
            </ul>
        </div>

        <hr>

        <!-- Power Stack -->
        <h2>⚡ Power Stack</h2>
        <p class="stack-note">The tools I'm most confident shipping with.</p>
        <div class="tech-badges">
            <span class="tech-badge">Flutter</span>
            <span class="tech-badge">YOLO</span>
            <span class="tech-badge">React</span>
            <span class="tech-badge">Python</span>
            <span class="tech-badge">Tailwind</span>
            <span class="tech-badge">TensorFlow</span>
            <span class="tech-badge">Firebase</span>
        </div>

        <!-- Other Stack -->
        <h2>🛠️ Other Stack</h2>
        <div class="tech-badges">
            <span class="tech-badge">MySQL</span>
            <span class="tech-badge">Hugging Face</span>
            <span class="tech-badge">Kotlin</span>
        </div>

        <hr>

        <!-- What I Build -->
        <h2>🎯 What I Build</h2>
        <div class="description">
            <ul>
                <li>📱 <strong>Mobile apps</strong> with clean architecture, smooth UX, and scalable state management</li>
                <li>👁️ <strong>Computer Vision</strong> projects (classification, detection, model experimentation)</li>
                <li>🔥 <strong>AI-powered products</strong>: from notebook experiments → deployable features</li>
            </ul>
        </div>

        <hr>

        <!-- Featured Projects -->
        <h2>⭐ Featured Projects</h2>
        <div class="projects">
            <div class="project">
                <div class="project-title">MedPelvis-Mobile</div>
                <div class="project-desc">Educational anatomy & childbirth mechanism app (Flutter)</div>
                <a href="https://github.com/ditorizkyka/MedPelvis-Mobile" target="_blank" class="project-link">View on GitHub →</a>
            </div>

            <div class="project">
                <div class="project-title">Pollusafe-App</div>
                <div class="project-desc">Air quality monitoring & alerting app (Flutter)</div>
                <a href="https://github.com/ditorizkyka/Pollusafe-App" target="_blank" class="project-link">View on GitHub →</a>
            </div>

            <div class="project">
                <div class="project-title">InsightHire</div>
                <div class="project-desc">NLP-based candidate screening (classification + keyword extraction)</div>
                <a href="https://github.com/ditorizkyka/InsightHire" target="_blank" class="project-link">View on GitHub →</a>
            </div>

            <div class="project">
                <div class="project-title">KuizKuy-App</div>
                <div class="project-desc">Quiz app (Kotlin)</div>
                <a href="https://github.com/ditorizkyka/KuizKuy-App" target="_blank" class="project-link">View on GitHub →</a>
            </div>
        </div>

        <hr>

        <!-- Currently Focusing -->
        <h2>🎯 Currently Focusing</h2>
        <div class="focus-list">
            <ul>
                <li>Shipping <strong>AI features inside mobile apps</strong></li>
                <li>Improving <strong>CV pipelines</strong> (data → training → inference → optimization)</li>
                <li>Building projects that have <strong>real social impact</strong></li>
            </ul>
        </div>

        <hr>

        <!-- Quick Facts -->
        <h2>💡 Quick Facts</h2>
        <div class="facts">
            <ul>
                <li>📍 Bandung, West Java, Indonesia (WIB)</li>
                <li>🤝 Open to collaboration: <strong>Mobile / AI / CV / NLP</strong></li>
                <li>🧾 Portfolio: <a href="https://ditorizkyka.is-a.dev/" target="_blank" style="color: #0ea5e9;">ditorizkyka.is-a.dev</a></li>
            </ul>
        </div>

        <hr>

        <!-- Footer -->
        <div class="footer">
            <p>If you're here to stalk my profile…<br><strong>at least star one repo before you leave.</strong> 😄</p>
        </div>
    </div>
</body>
</html>
```

This HTML preview includes:

✨ **Features:**
- Responsive design that works on mobile and desktop
- Gradient backgrounds and modern styling
- Interactive hover effects on links and project cards
- Color-coded sections matching the original markdown
- Organized layout with clear visual hierarchy
- Smooth transitions and animations
- Professional typography and spacing

🎨 **Design Elements:**
- Dark theme with blue/green accent colors
- Gradient text for main heading
- Colored left borders for different sections
- Hover effects on interactive elements
- Mobile-friendly responsive layout

The preview maintains the structure and content of the original GitHub profile README while presenting it as a beautiful, interactive HTML page.
