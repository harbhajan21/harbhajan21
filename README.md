<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Harbhajan Singh | Data Scientist • GenAI Engineer • Entrepreneur</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Space+Grotesk:wght@500;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #0f0f23 0%, #1a1a2e 100%);
            color: #e0e0ff;
            margin: 0;
            padding: 0;
        }
        
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        
        .hero {
            text-align: center;
            padding: 60px 20px 40px;
            background: url('https://images.unsplash.com/photo-1677442136019-21780ecad995?ixlib=rb-4.0.3&auto=format&fit=crop&q=80') no-repeat center center;
            background-size: cover;
            background-position: center;
            border-radius: 24px;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(45deg, rgba(0, 255, 200, 0.15), rgba(100, 50, 255, 0.15));
            z-index: 1;
        }
        
        .hero-content {
            position: relative;
            z-index: 2;
        }
        
        .typing {
            font-family: 'Space Grotesk', sans-serif;
            font-size: 42px;
            font-weight: 700;
            background: linear-gradient(90deg, #00ffcc, #6466ff, #ff00cc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin: 0;
        }
        
        .badge {
            display: inline-flex;
            align-items: center;
            background: rgba(255,255,255,0.1);
            padding: 6px 18px;
            border-radius: 9999px;
            font-size: 14px;
            font-weight: 600;
            margin: 12px 6px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.1);
        }
        
        .section {
            background: rgba(255,255,255,0.03);
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 40px;
            border: 1px solid rgba(255,255,255,0.08);
        }
        
        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(80px, 1fr));
            gap: 24px;
            justify-items: center;
        }
        
        .tech-item {
            text-align: center;
            transition: all 0.3s ease;
        }
        
        .tech-item:hover {
            transform: translateY(-8px) scale(1.1);
        }
        
        .tech-item img {
            width: 64px;
            height: 64px;
            filter: drop-shadow(0 10px 15px rgba(0, 255, 200, 0.3));
        }
        
        .connect-btn {
            display: inline-flex;
            align-items: center;
            gap: 12px;
            background: linear-gradient(90deg, #00ffcc, #6466ff);
            color: #0f0f23;
            padding: 14px 32px;
            border-radius: 9999px;
            font-weight: 700;
            text-decoration: none;
            transition: all 0.3s ease;
            margin: 10px;
        }
        
        .connect-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 20px 25px -5px rgba(0, 255, 204, 0.4);
        }
        
        .stat-card {
            background: rgba(255,255,255,0.05);
            border-radius: 16px;
            padding: 20px;
            text-align: center;
            transition: all 0.3s;
        }
        
        .stat-card:hover {
            background: rgba(100, 102, 255, 0.1);
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- HERO -->
        <div class="hero">
            <div class="hero-content">
                <h1 style="font-size: 18px; letter-spacing: 4px; opacity: 0.8; margin-bottom: 8px;">HARBHajan SINGH</h1>
                <p class="typing" id="typing">Data Scientist • GenAI Engineer • AI Entrepreneur</p>
                
                <div style="margin-top: 24px;">
                    <span class="badge">TD Securities</span>
                    <span class="badge">Master's in AI</span>
                    <span class="badge">Agentic RAG Architect</span>
                    <span class="badge">Startup Founder</span>
                </div>
                
                <p style="max-width: 620px; margin: 32px auto; font-size: 18px; line-height: 1.6; opacity: 0.9;">
                    Turning complex data into intelligent systems.<br>
                    Building the future with <strong>Generative AI, Agentic RAG, LLMs &amp; Computer Vision</strong>.
                </p>
                
                <a href="https://harbhajan21.github.io/portfolio/" target="_blank" class="connect-btn" style="font-size: 17px;">
                    <span>View My Portfolio →</span>
                </a>
            </div>
        </div>

        <!-- ABOUT -->
        <div class="section">
            <h2 align="center" style="font-family: 'Space Grotesk', sans-serif; font-size: 32px; margin-bottom: 24px; background: linear-gradient(90deg, #00ffcc, #6466ff); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">
                Hey there 👋
            </h2>
            
            <p style="font-size: 18px; line-height: 1.8; text-align: center; max-width: 820px; margin: 0 auto;">
                I'm <strong>Harbhajan Singh</strong> — a Data Scientist, AI Engineer, and passionate entrepreneur. 
                Currently shaping the future of finance as a <strong>Data Scientist at TD Securities (TD Bank Group)</strong>, 
                while running AI-first ventures and consulting on Generative AI solutions.
            </p>
            
            <p style="font-size: 18px; line-height: 1.8; text-align: center; max-width: 820px; margin: 24px auto 0;">
                With a <strong>Master's in Applied Computing (Artificial Intelligence)</strong>, I've spent years at the intersection of 
                <strong>Data Science • Machine Learning • Deep Learning • Computer Vision • LLMs • Agentic RAG</strong> — 
                building products that don't just analyze data, but <em>think</em> with it.
            </p>
        </div>

        <!-- CURRENT WORK -->
        <div class="section">
            <h2 align="center" style="font-size: 28px; margin-bottom: 32px;">🚀 What I'm Building Right Now</h2>
            
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(340px, 1fr)); gap: 24px;">
                <div style="background: rgba(255,255,255,0.04); padding: 28px; border-radius: 16px;">
                    <h3 style="margin-top: 0; color: #00ffcc;">🤖 Agentic RAG Systems</h3>
                    <p style="opacity: 0.9;">Autonomous AI agents powered by advanced Retrieval-Augmented Generation frameworks. Making LLMs truly intelligent and actionable.</p>
                </div>
                <div style="background: rgba(255,255,255,0.04); padding: 28px; border-radius: 16px;">
                    <h3 style="margin-top: 0; color: #6466ff;">👁️ Computer Vision &amp; Multimodal AI</h3>
                    <p style="opacity: 0.9;">Real-world AI applications using PyTorch, OpenCV, and cutting-edge vision transformers.</p>
                </div>
                <div style="background: rgba(255,255,255,0.04); padding: 28px; border-radius: 16px;">
                    <h3 style="margin-top: 0; color: #ff00cc;">🌱 AI Startups &amp; GenAI Products</h3>
                    <p style="opacity: 0.9;">Founding and advising AI-native companies. Helping businesses deploy production-grade Generative AI.</p>
                </div>
            </div>
        </div>

        <!-- EXPERTISE -->
        <div class="section">
            <h2 align="center" style="font-size: 28px; margin-bottom: 32px;">💡 Areas of Expertise</h2>
            <div style="display: flex; flex-wrap: wrap; gap: 14px; justify-content: center;">
                <div style="background: #1e1e3f; padding: 10px 22px; border-radius: 9999px; font-size: 15px;">Data Analytics</div>
                <div style="background: #1e1e3f; padding: 10px 22px; border-radius: 9999px; font-size: 15px;">Machine Learning</div>
                <div style="background: #1e1e3f; padding: 10px 22px; border-radius: 9999px; font-size: 15px;">Deep Learning</div>
                <div style="background: #1e1e3f; padding: 10px 22px; border-radius: 9999px; font-size: 15px;">Computer Vision</div>
                <div style="background: #1e1e3f; padding: 10px 22px; border-radius: 9999px; font-size: 15px;">Large Language Models</div>
                <div style="background: #1e1e3f; padding: 10px 22px; border-radius: 9999px; font-size: 15px;">Agentic RAG</div>
                <div style="background: #1e1e3f; padding: 10px 22px; border-radius: 9999px; font-size: 15px;">Generative AI</div>
                <div style="background: #1e1e3f; padding: 10px 22px; border-radius: 9999px; font-size: 15px;">MLOps &amp; Production AI</div>
                <div style="background: #1e1e3f; padding: 10px 22px; border-radius: 9999px; font-size: 15px;">Data Visualization</div>
                <div style="background: #1e1e3f; padding: 10px 22px; border-radius: 9999px; font-size: 15px;">AI Strategy &amp; Consulting</div>
            </div>
        </div>

        <!-- TECH STACK -->
        <div class="section">
            <h2 align="center" style="font-size: 28px; margin-bottom: 32px;">🛠️ My Arsenal</h2>
            
            <p align="center" style="margin-bottom: 32px; opacity: 0.8;">
                <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,keras,opencv,scikit,langchain,huggingface,ollama,openai,fastapi,flask,streamlit,gradio,jupyter,docker,kubernetes,git,github,linux,gcp,azure,aws,mysql,postgresql,sqlite,r,latex,vscode&perline=14" />
            </p>
            
            <div style="display: flex; justify-content: center; gap: 40px; flex-wrap: wrap; margin-top: 20px;">
                <div class="tech-item">
                    <img src="https://matplotlib.org/3.2.1/_images/sphx_glr_logos2_003.png" width="64">
                    <p style="margin: 8px 0 0; font-size: 13px; opacity: 0.7;">Matplotlib</p>
                </div>
                <div class="tech-item">
                    <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" width="64">
                    <p style="margin: 8px 0 0; font-size: 13px; opacity: 0.7;">Seaborn</p>
                </div>
                <div class="tech-item">
                    <img src="https://pandas.pydata.org/static/img/pandas_mark.svg" width="64">
                    <p style="margin: 8px 0 0; font-size: 13px; opacity: 0.7;">Pandas</p>
                </div>
                <div class="tech-item">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1200px-Scikit_learn_logo_small.svg.png" width="64">
                    <p style="margin: 8px 0 0; font-size: 13px; opacity: 0.7;">Scikit-learn</p>
                </div>
                <div class="tech-item">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/OpenCV_Logo_with_text.svg/1200px-OpenCV_Logo_with_text.svg.png" width="64">
                    <p style="margin: 8px 0 0; font-size: 13px; opacity: 0.7;">OpenCV</p>
                </div>
                <div class="tech-item">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/New_Power_BI_Logo.svg/1200px-New_Power_BI_Logo.svg.png" width="64">
                    <p style="margin: 8px 0 0; font-size: 13px; opacity: 0.7;">Power BI</p>
                </div>
                <div class="tech-item">
                    <img src="https://www.tableau.com/sites/default/files/2023-10/Tableau-Logo.png" width="64" style="filter: brightness(1.2);">
                    <p style="margin: 8px 0 0; font-size: 13px; opacity: 0.7;">Tableau</p>
                </div>
            </div>
        </div>

        <!-- COLLAB & ASK -->
        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 24px;">
            <div class="section" style="margin-bottom: 0;">
                <h3 align="center" style="color: #00ffcc;">🤝 Open to Collaborate On</h3>
                <ul style="font-size: 17px; line-height: 2; opacity: 0.9;">
                    <li>🔥 Agentic RAG &amp; LLM Applications</li>
                    <li>📊 Production-grade AI Systems</li>
                    <li>👀 Computer Vision Projects</li>
                    <li>🏆 Kaggle Competitions</li>
                    <li>🚀 AI Startup Ventures</li>
                </ul>
            </div>
            
            <div class="section" style="margin-bottom: 0;">
                <h3 align="center" style="color: #6466ff;">💬 Ask Me About</h3>
                <ul style="font-size: 17px; line-height: 2; opacity: 0.9;">
                    <li>LLMs &amp; Prompt Engineering</li>
                    <li>Agentic AI Frameworks</li>
                    <li>RAG Architectures</li>
                    <li>Computer Vision Pipelines</li>
                    <li>End-to-End ML Systems</li>
                    <li>AI Product Strategy</li>
                </ul>
            </div>
        </div>

        <!-- CONNECT -->
        <div class="section" style="text-align: center; margin-top: 40px;">
            <h2 style="font-size: 28px; margin-bottom: 24px;">Let's Build Something Legendary</h2>
            
            <div style="display: flex; justify-content: center; flex-wrap: wrap; gap: 16px;">
                <a href="https://x.com/Harbhajan2105" target="_blank" class="connect-btn" style="background: #000; color: white;">
                    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/x.svg" width="28" height="28"> X
                </a>
                <a href="https://www.linkedin.com/in/harbhajansingh21/" target="_blank" class="connect-btn">
                    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" width="28" height="28"> LinkedIn
                </a>
                <a href="https://www.kaggle.com/harbhajansingh21" target="_blank" class="connect-btn" style="background: #20a300; color: white;">
                    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/kaggle.svg" width="28" height="28"> Kaggle
                </a>
                <a href="mailto:singh.bhajji2105@gmail.com" class="connect-btn" style="background: #ea4335; color: white;">
                    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/gmail.svg" width="28" height="28"> Email
                </a>
            </div>
        </div>

        <!-- STATS -->
        <div style="display: flex; justify-content: center; flex-wrap: wrap; gap: 20px; margin-top: 40px;">
            <img src="https://github-readme-stats.vercel.app/api?username=harbhajan21&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0f0f23&title_color=00ffcc&text_color=e0e0ff" alt="GitHub Stats">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=harbhajan21&theme=tokyonight&hide_border=true&background=0f0f23&stroke=6466ff&ring=00ffcc&fire=ff00cc" alt="Streak">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=harbhajan21&layout=compact&theme=tokyonight&hide_border=true&bg_color=0f0f23&title_color=00ffcc&text_color=e0e0ff" alt="Top Languages">
        </div>

        <p align="center" style="margin-top: 60px; opacity: 0.6; font-size: 15px;">
            Thanks for stopping by ✨ • Made with ❤️ and a lot of GPUs
        </p>
        
        <p align="center">
            <img height="28" src="https://komarev.com/ghpvc/?username=harbhajan21&color=00ffcc&style=for-the-badge&label=PROFILE+VIEWS" />
        </p>
    </div>
    
    <script>
        // Simple typing animation for the hero (fallback)
        const texts = [
            "Data Scientist • GenAI Engineer • AI Entrepreneur",
            "Building Intelligent Systems That Matter",
            "Agentic RAG • LLMs • Computer Vision"
        ];
        let index = 0;
        const typingEl = document.getElementById('typing');
        
        setInterval(() => {
            index = (index + 1) % texts.length;
            typingEl.style.opacity = 0;
            setTimeout(() => {
                typingEl.textContent = texts[index];
                typingEl.style.opacity = 1;
            }, 600);
        }, 3800);
    </script>
</body>
</html>
