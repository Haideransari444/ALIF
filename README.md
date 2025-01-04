<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alif - Your AI-Powered Tutor</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css">
</head>
<body>
    <style>
        :root {
            --primary-color: #000000;
            --secondary-color: #333333;
            --text-color: #1a1a1a;
            --bg-color: #ffffff;
            --section-bg: #f5f5f5;
            --hover-color: #e0e0e0;
            --border-color: #dcdcdc;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .hero {
            background: var(--primary-color);
            color: white;
            padding: 4rem 2rem;
            text-align: center;
            margin-bottom: 2rem;
        }

        .hero img {
            max-width: 200px;
            margin-bottom: 1rem;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }

        .feature-card {
            background: var(--section-bg);
            padding: 1.5rem;
            border-radius: 8px;
            transition: transform 0.2s;
        }

        .feature-card:hover {
            transform: translateY(-5px);
        }

        .section {
            margin: 3rem 0;
            padding: 2rem;
            background: var(--section-bg);
            border-radius: 8px;
        }

        .code-block {
            background: #1e1e1e;
            padding: 1rem;
            border-radius: 4px;
            overflow-x: auto;
        }

        .tech-stack {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin: 1rem 0;
        }

        .tech-item {
            background: white;
            padding: 1rem;
            border-radius: 4px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .collapsible {
            background: white;
            border: none;
            padding: 1rem;
            width: 100%;
            text-align: left;
            cursor: pointer;
            border-radius: 4px;
            margin: 0.5rem 0;
        }

        .content {
            padding: 0 1rem;
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease-out;
        }

        .active {
            max-height: 500px;
        }
    </style>

    

    <div class="hero">
        <img src="![WhatsApp Image 2024-11-18 at 21 50 40_665b38d8](https://github.com/user-attachments/assets/23809b4b-25d9-4dbb-9215-05557de0270c)">
        <h1>Alif - Your AI-Powered Tutor</h1>
        <p>An innovative AI-driven tutor app designed to provide personalized and interactive learning experiences.</p>
    </div>
    <!-- Architecture Section -->
    <div class="architecture-section">
    <h2>App Architecture</h2>
    <img src="![archtecture](https://github.com/user-attachments/assets/d8c009b8-8d6a-4724-a6a4-337f7e4050bc)" alt="Architecture Diagram" class="architecture-image">
    </div>

    <div class="container">
        <div class="feature-grid">
            <div class="feature-card">
                <h3>📚 Personalized Learning</h3>
                <ul>
                    <li>Adapts to individual user needs</li>
                    <li>Tracks progress and adjusts difficulty</li>
                </ul>
            </div>
            <div class="feature-card">
                <h3>🎤 Voice Assistance</h3>
                <ul>
                    <li>AI-powered voice recognition</li>
                    <li>Hands-free interaction</li>
                </ul>
            </div>
            <div class="feature-card">
                <h3>⚡ Interactive Sessions</h3>
                <ul>
                    <li>Engaging quizzes and flashcards</li>
                    <li>Active participation focus</li>
                </ul>
            </div>
            <div class="feature-card">
                <h3>📊 Smart Progress Tracking</h3>
                <ul>
                    <li>Detailed learning insights</li>
                    <li>Visual performance data</li>
                </ul>
            </div>
        </div>

        <div class="section">
            <h2>How It Works</h2>
            <div class="tech-stack">
                <div class="tech-item">
                    <h4>1. User Registration</h4>
                    <p>Create account & start learning</p>
                </div>
                <div class="tech-item">
                    <h4>2. Voice/Text Input</h4>
                    <p>Multiple interaction methods</p>
                </div>
                <div class="tech-item">
                    <h4>3. AI Processing</h4>
                    <p>Smart response generation</p>
                </div>
                <div class="tech-item">
                    <h4>4. Content Delivery</h4>
                    <p>Personalized learning material</p>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>Technology Stack</h2>
            <button class="collapsible">Backend Stack</button>
            <div class="content">
                <ul>
                    <li>FastAPI for high-performance API</li>
                    <li>Supabase for real-time database</li>
                </ul>
            </div>

            <button class="collapsible">AI Integration</button>
            <div class="content">
                <ul>
                    <li>Google Gemini API</li>
                    <li>OpenAI Whisper</li>
                    <li>Llama AI</li>
                </ul>
            </div>

            <button class="collapsible">Frontend Stack</button>
            <div class="content">
                <ul>
                    <li>HTML/CSS</li>
                    <li>Vanilla JavaScript</li>
                </ul>
            </div>
        </div>

        <div class="section">
            <h2>Installation & Setup</h2>
            <div class="code-block">
                <pre><code class="language-bash">
git clone https://github.com/Talnz007/Alif.git
cd alif
pip install -r requirements.txt
uvicorn main:app --reload</code></pre>
            </div>
        </div>

        <div class="section">
            <h2>Contributing</h2>
            <p>We welcome contributions to improve Alif! Follow these steps:</p>
            <ol>
                <li>Fork the repository</li>
                <li>Create a feature branch</li>
                <li>Commit your changes</li>
                <li>Open a pull request with a detailed description</li>
            </ol>
        </div>

        <div class="section">
            <h2>License</h2>
            <p>This project is licensed under the MIT License.</p>
        </div>
    </div>

    <script>
        var coll = document.getElementsByClassName("collapsible");
        for (var i = 0; i < coll.length; i++) {
            coll[i].addEventListener("click", function() {
                this.classList.toggle("active");
                var content = this.nextElementSibling;
                if (content.style.maxHeight) {
                    content.style.maxHeight = null;
                } else {
                    content.style.maxHeight = content.scrollHeight + "px";
                }
            });
        }

        // Initialize Prism.js for syntax highlighting
        Prism.highlightAll();
    </script>
</body>
</html>
