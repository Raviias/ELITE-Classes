<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ELITE CLASSES | An Exclusive Mission For Futuristic Education</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,600;0,700;1,400&family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --primary: #2563eb;
            --primary-dark: #1d4ed8;
            --secondary: #0f172a;
            --accent: #f59e0b;
            --bg-light: #f8fafc;
            --text-main: #334155;
            --text-muted: #64748b;
            --border-color: #e2e8f0;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Plus Jakarta Sans', sans-serif;
            scroll-behavior: smooth;
        }

        body {
            background-color: var(--bg-light);
            color: var(--text-main);
            line-height: 1.6;
        }

        /* Navbar */
        nav {
            position: sticky;
            top: 0;
            background: #ffffff;
            border-bottom: 1px solid var(--border-color);
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 5%;
            z-index: 1000;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.02);
        }

        .nav-brand {
            display: flex;
            flex-direction: column;
        }

        .nav-logo {
            font-size: 1.4rem;
            font-weight: 800;
            color: var(--secondary);
            letter-spacing: 0.5px;
        }

        .nav-subtitle {
            font-size: 0.72rem;
            font-weight: 600;
            color: var(--primary);
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .nav-cta {
            background: var(--primary);
            color: #ffffff;
            padding: 10px 22px;
            border-radius: 50px;
            font-weight: 600;
            font-size: 0.9rem;
            border: none;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 12px rgba(37, 99, 235, 0.2);
            text-decoration: none;
        }

        .nav-cta:hover {
            background: var(--primary-dark);
            transform: translateY(-2px);
        }

        /* Hero Section */
        .hero {
            padding: 70px 5%;
            background: linear-gradient(135deg, #f0f4ff 0%, #ffffff 100%);
            text-align: center;
            border-bottom: 1px solid var(--border-color);
        }

        .hero h1 {
            font-size: 2.5rem;
            font-weight: 800;
            color: var(--secondary);
            margin-bottom: 15px;
            line-height: 1.3;
        }

        .hero h1 span {
            color: var(--primary);
        }

        .hero p {
            font-size: 1.1rem;
            color: var(--text-muted);
            max-width: 700px;
            margin: 0 auto 30px auto;
        }

        /* Mentor Message Section (Updated with your custom design) */
        .elite-mentor-wrapper {
            padding: 60px 5%;
        }

        .elite-mentor-card {
            background: #ffffff;
            border-radius: 24px;
            padding: 40px;
            max-width: 1000px;
            margin: 0 auto;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.06);
            border: 1px solid var(--border-color);
        }

        .elite-mentor-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 30px;
            flex-wrap: wrap;
            gap: 15px;
            border-bottom: 2px solid var(--bg-light);
            padding-bottom: 20px;
        }

        .elite-badge {
            background: #eff6ff;
            color: var(--primary);
            font-size: 11px;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 2px;
            padding: 6px 16px;
            border-radius: 30px;
            border: 1px solid #bfdbfe;
        }

        .elite-mentor-switcher {
            display: flex;
            background: var(--bg-light);
            padding: 4px;
            border-radius: 12px;
        }

        .elite-lang-btn {
            background: transparent;
            border: none;
            padding: 6px 16px;
            font-size: 13px;
            font-weight: 600;
            color: var(--text-muted);
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .elite-lang-btn.active {
            background: var(--primary);
            color: #ffffff;
            box-shadow: 0 4px 12px rgba(37, 99, 235, 0.2);
        }

        .elite-mentor-grid {
            display: flex;
            gap: 40px;
            align-items: center;
        }

        .elite-mentor-content {
            flex: 1;
            text-align: left;
        }

        .elite-main-quote {
            font-family: 'Playfair Display', serif;
            font-size: 1.65rem;
            font-weight: 700;
            color: #1e3a8a;
            line-height: 1.4;
            margin-bottom: 20px;
            font-style: italic;
        }

        .elite-body-text {
            font-size: 1.02rem;
            color: var(--text-muted);
            line-height: 1.8;
        }

        .elite-mentor-profile {
            text-align: center;
            min-width: 240px;
            display: flex;
            flex-direction: column;
            align-items: center;
            background: var(--bg-light);
            padding: 30px 20px;
            border-radius: 20px;
            border: 1px solid var(--border-color);
        }

        .elite-mentor-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #ffffff;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
            margin-bottom: 15px;
        }

        .elite-mentor-name {
            font-size: 1.2rem;
            font-weight: 700;
            color: var(--secondary);
            margin-bottom: 4px;
        }

        .elite-mentor-title {
            font-size: 0.85rem;
            color: var(--text-muted);
            font-weight: 600;
            line-height: 1.4;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .lang-pane {
            display: none;
        }
        .lang-pane.active {
            display: block;
            animation: fadeIn 0.4s ease-in-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(5px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Features Section */
        .features {
            padding: 60px 5%;
            background: #ffffff;
            text-align: center;
        }

        .section-title {
            font-size: 2rem;
            font-weight: 800;
            color: var(--secondary);
            margin-bottom: 10px;
        }

        .section-desc {
            color: var(--text-muted);
            margin-bottom: 40px;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            max-width: 1100px;
            margin: 0 auto;
        }

        .feature-card {
            background: var(--bg-light);
            padding: 30px 20px;
            border-radius: 16px;
            border: 1px solid var(--border-color);
            transition: transform 0.3s ease;
        }

        .feature-card:hover {
            transform: translateY(-5px);
            border-color: var(--primary);
        }

        .feature-icon {
            font-size: 2rem;
            color: var(--primary);
            margin-bottom: 15px;
        }

        .feature-card h3 {
            font-size: 1.15rem;
            color: var(--secondary);
            margin-bottom: 10px;
        }

        .feature-card p {
            font-size: 0.9rem;
            color: var(--text-muted);
        }

        /* Footer */
        footer {
            background: var(--secondary);
            color: #ffffff;
            text-align: center;
            padding: 30px 5%;
            font-size: 0.9rem;
        }

        footer span {
            color: var(--primary);
            font-weight: 600;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .elite-mentor-grid {
                flex-direction: column-reverse;
                gap: 25px;
            }
            .elite-mentor-card {
                padding: 20px;
            }
            .elite-main-quote {
                font-size: 1.35rem;
            }
            .elite-mentor-profile {
                width: 100%;
            }
            .hero h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
        <div class="nav-brand">
            <span class="nav-logo">ELITE CLASSES</span>
            <span class="nav-subtitle">An Exclusive Mission For Futuristic Education</span>
        </div>
        <a href="#demo" class="nav-cta">Book Free Demo</a>
    </nav>

    <!-- Hero Section -->
    <header class="hero">
        <h1>Empowering Minds, Shaping <span>Future Success</span></h1>
        <p>Expert home tuition & coaching for primary and secondary students across all core subjects in Noida with personalized guidance.</p>
        <a href="#demo" class="nav-cta" style="font-size: 1rem; padding: 12px 30px;">Get Started Today</a>
    </header>

    <!-- Mentor Message Section with Language Switcher & Photo -->
    <section class="elite-mentor-wrapper" id="mentor">
        <div class="elite-mentor-card">
            
            <div class="elite-mentor-header">
                <span class="elite-badge">A Message From The Mentor</span>
                <div class="elite-mentor-switcher">
                    <button class="elite-lang-btn active" onclick="switchLanguage('en')">English</button>
                    <button class="elite-lang-btn" onclick="switchLanguage('hi')">हिंदी</button>
                </div>
            </div>

            <div class="elite-mentor-grid">
                
                <!-- Content Area -->
                <div class="elite-mentor-content">
                    
                    <!-- English Pane -->
                    <div id="pane-en" class="lang-pane active">
                        <h2 class="elite-main-quote">"Education Is Not Just About Rote Learning; It Is About Building the Power to Think."</h2>
                        <p class="elite-body-text">
                            "Right from the beginning, my vision has been to provide an education that instills genuine confidence in a child. Today, many parents in Noida are concerned about their children's low academic performance or weak foundational concepts. At <strong>ELITE CLASSES</strong>, we don’t just teach; we identify every weak link and transform it into a strength. Regular assessments, custom revision notes, and a disciplined environment are the true keys to lasting success."
                        </p>
                    </div>

                    <!-- Hindi Pane -->
                    <div id="pane-hi" class="lang-pane">
                        <h2 class="elite-main-quote">"पढ़ाई सिर्फ रट्टा मारना नहीं, सोचने की ताकत बनाना है।"</h2>
                        <p class="elite-body-text">
                            "बचपन से ही मेरा मकसद रहा है कि शिक्षा ऐसी हो जो बच्चे के अंदर आत्मविश्वास जगाए। आज नोएडा के कई पेरेंट्स अपने बच्चों के कमजोर प्रदर्शन या कमजोर कॉन्सेप्ट्स को लेकर परेशान रहते हैं। <strong>ELITE CLASSES</strong> में हम सिर्फ पढ़ाते नहीं, बल्कि बच्चे की हर एक कमजोर कड़ी को पहचानकर उसे मजबूत बनाते हैं। रेगुलर टेस्ट, कस्टम रिवीजन नोट्स और डिसिप्लिन माहौल ही सफलता की असली कुंजी हैं।"
                        </p>
                    </div>

                </div>

                <!-- Right Side Profile & Photo -->
                <div class="elite-mentor-profile">
                    <!-- Yahan apni photo ka naam update kar dein jaise: src="ravi-yadav.jpg" -->
                    <img src="1000001536.jpg" alt="Ravi Yadav" class="elite-mentor-img">
                    <div class="elite-mentor-name">Ravi Yadav</div>
                    <div class="elite-mentor-title">Founder &amp; Lead Educator<br><span style="color: var(--primary);">ELITE CLASSES</span></div>
                </div>

            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features" id="features">
        <h2 class="section-title">Why Choose ELITE CLASSES?</h2>
        <p class="section-desc">We provide structured academic solutions for comprehensive student growth.</p>
        
        <div class="features-grid">
            <div class="feature-card">
                <div class="feature-icon"><i class="fa-solid fa-bullseye"></i></div>
                <h3>Concept Clarity</h3>
                <p>Focusing on strong foundations rather than rote memorization to master complex topics easily.</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon"><i class="fa-solid fa-file-lines"></i></div>
                <h3>Custom Revision Notes</h3>
                <p>Programmatically designed PDF worksheets, assignments, and test papers tailored for each student.</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon"><i class="fa-solid fa-chart-line"></i></div>
                <h3>Regular Assessments</h3>
                <p>Frequent testing and diagnostic academic progress tracking to monitor continuous improvement.</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon"><i class="fa-solid fa-user-graduate"></i></div>
                <h3>Disciplined Environment</h3>
                <p>Creating a focused, inspiring, and professional learning culture for primary and secondary levels.</p>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer id="demo">
        <p>&copy; 2026 <span>ELITE CLASSES</span> (An Exclusive Mission For Futuristic Education). All Rights Reserved.</p>
        <p style="margin-top: 8px; font-size: 0.8rem; color: #94a3b8;">Contact: 9675732501 | Noida, Uttar Pradesh</p>
    </footer>

    <!-- JavaScript for Language Switcher -->
    <script>
        function switchLanguage(lang) {
            const buttons = document.querySelectorAll('.elite-lang-btn');
            buttons.forEach(btn => btn.classList.remove('active'));
            
            if(lang === 'en') {
                document.querySelector('.elite-lang-btn:nth-child(1)').classList.add('active');
                document.getElementById('pane-en').classList.add('active');
                document.getElementById('pane-hi').classList.remove('active');
            } else {
                document.querySelector('.elite-lang-btn:nth-child(2)').classList.add('active');
                document.getElementById('pane-hi').classList.add('active');
                document.getElementById('pane-en').classList.remove('active');
            }
        }
    </script>
</body>
</html>
