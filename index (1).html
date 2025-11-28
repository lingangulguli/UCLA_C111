<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LoL Match Prediction | ML Project</title>
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Beaufort+for+LOL:wght@400;700&family=Spiegel:wght@400;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --gold: #C8AA6E;
            --gold-light: #F0E6D2;
            --gold-dark: #785A28;
            --blue: #0AC8B9;
            --blue-dark: #0A1428;
            --blue-darker: #010A13;
            --red: #E84057;
            --hextech: #0397AB;
            --magic: #C89B3C;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        html {
            scroll-behavior: smooth;
        }
        
        body {
            font-family: 'Inter', 'Spiegel', sans-serif;
            background: var(--blue-darker);
            color: var(--gold-light);
            line-height: 1.8;
            overflow-x: hidden;
        }
        
        /* Particle Canvas */
        #particles-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
            pointer-events: none;
        }
        
        /* Navigation */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            background: linear-gradient(180deg, rgba(1,10,19,0.98) 0%, rgba(1,10,19,0.9) 100%);
            border-bottom: 1px solid var(--gold-dark);
            backdrop-filter: blur(10px);
        }
        
        .nav-container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 70px;
        }
        
        .logo {
            font-family: 'Cinzel', serif;
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--gold);
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .logo i {
            color: var(--blue);
        }
        
        .nav-links {
            display: flex;
            gap: 2rem;
            list-style: none;
        }
        
        .nav-links a {
            color: var(--gold-light);
            text-decoration: none;
            font-size: 0.9rem;
            font-weight: 500;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s ease;
            position: relative;
        }
        
        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--gold);
            transition: width 0.3s ease;
        }
        
        .nav-links a:hover {
            color: var(--gold);
        }
        
        .nav-links a:hover::after {
            width: 100%;
        }
        
        /* Hero Section */
        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            overflow: hidden;
            background: linear-gradient(135deg, var(--blue-darker) 0%, var(--blue-dark) 100%);
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('https://raw.communitydragon.org/latest/plugins/rcp-fe-lol-static-assets/global/default/images/ranked-emblem/wings/wings-challenger.png') no-repeat center center;
            background-size: 800px;
            opacity: 0.03;
            animation: pulse 4s ease-in-out infinite;
        }
        
        @keyframes pulse {
            0%, 100% { transform: scale(1); opacity: 0.03; }
            50% { transform: scale(1.05); opacity: 0.05; }
        }
        
        .hero-content {
            text-align: center;
            z-index: 10;
            padding: 2rem;
            max-width: 900px;
        }
        
        .hero-badge {
            display: inline-block;
            padding: 8px 20px;
            background: linear-gradient(135deg, var(--gold-dark), var(--gold));
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 2rem;
            color: var(--blue-darker);
            animation: glow 2s ease-in-out infinite alternate;
        }
        
        @keyframes glow {
            from { box-shadow: 0 0 10px var(--gold-dark), 0 0 20px var(--gold-dark); }
            to { box-shadow: 0 0 20px var(--gold), 0 0 40px var(--gold); }
        }
        
        .hero h1 {
            font-family: 'Cinzel', serif;
            font-size: 4rem;
            font-weight: 700;
            color: var(--gold);
            margin-bottom: 1.5rem;
            text-shadow: 0 0 60px rgba(200, 170, 110, 0.3);
            line-height: 1.2;
        }
        
        .hero h1 span {
            color: var(--blue);
        }
        
        .hero-subtitle {
            font-size: 1.3rem;
            color: var(--gold-light);
            margin-bottom: 2rem;
            opacity: 0.9;
        }
        
        .hero-stats {
            display: flex;
            justify-content: center;
            gap: 3rem;
            margin: 3rem 0;
            flex-wrap: wrap;
        }
        
        .stat-item {
            text-align: center;
        }
        
        .stat-value {
            font-family: 'Cinzel', serif;
            font-size: 3rem;
            font-weight: 700;
            color: var(--gold);
            display: block;
        }
        
        .stat-label {
            font-size: 0.9rem;
            color: var(--gold-light);
            opacity: 0.8;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .cta-buttons {
            display: flex;
            gap: 1.5rem;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 2rem;
        }
        
        .btn {
            padding: 15px 35px;
            font-size: 0.95rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
            text-decoration: none;
            border-radius: 4px;
            transition: all 0.3s ease;
            display: inline-flex;
            align-items: center;
            gap: 10px;
            cursor: pointer;
            border: none;
        }
        
        .btn-primary {
            background: linear-gradient(135deg, var(--gold-dark), var(--gold));
            color: var(--blue-darker);
        }
        
        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 30px rgba(200, 170, 110, 0.4);
        }
        
        .btn-secondary {
            background: transparent;
            color: var(--gold);
            border: 2px solid var(--gold);
        }
        
        .btn-secondary:hover {
            background: var(--gold);
            color: var(--blue-darker);
            transform: translateY(-3px);
        }
        
        .scroll-indicator {
            position: absolute;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            animation: bounce 2s infinite;
        }
        
        .scroll-indicator i {
            font-size: 2rem;
            color: var(--gold);
            opacity: 0.6;
        }
        
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateX(-50%) translateY(0); }
            40% { transform: translateX(-50%) translateY(-10px); }
            60% { transform: translateX(-50%) translateY(-5px); }
        }
        
        /* Section Styles */
        section {
            padding: 100px 2rem;
            position: relative;
            z-index: 10;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .section-header {
            text-align: center;
            margin-bottom: 4rem;
        }
        
        .section-header h2 {
            font-family: 'Cinzel', serif;
            font-size: 2.5rem;
            color: var(--gold);
            margin-bottom: 1rem;
            position: relative;
            display: inline-block;
        }
        
        .section-header h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 60px;
            height: 3px;
            background: linear-gradient(90deg, transparent, var(--gold), transparent);
        }
        
        .section-header p {
            color: var(--gold-light);
            opacity: 0.8;
            max-width: 600px;
            margin: 0 auto;
        }
        
        /* About Section */
        #about {
            background: linear-gradient(180deg, var(--blue-darker) 0%, rgba(10, 20, 40, 0.95) 100%);
        }
        
        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4rem;
            align-items: center;
        }
        
        .about-text h3 {
            font-family: 'Cinzel', serif;
            font-size: 1.8rem;
            color: var(--gold);
            margin-bottom: 1.5rem;
        }
        
        .about-text p {
            margin-bottom: 1.5rem;
            color: var(--gold-light);
            opacity: 0.9;
        }
        
        .about-image {
            position: relative;
        }
        
        .about-image img {
            width: 100%;
            border-radius: 10px;
            border: 2px solid var(--gold-dark);
            box-shadow: 0 20px 60px rgba(0,0,0,0.5);
        }
        
        .about-image::before {
            content: '';
            position: absolute;
            top: -20px;
            right: -20px;
            width: 100%;
            height: 100%;
            border: 2px solid var(--gold);
            border-radius: 10px;
            z-index: -1;
            opacity: 0.3;
        }
        
        /* Key Findings */
        #findings {
            background: var(--blue-dark);
        }
        
        .findings-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
        }
        
        .finding-card {
            background: linear-gradient(135deg, rgba(10,20,40,0.9) 0%, rgba(1,10,19,0.9) 100%);
            border: 1px solid var(--gold-dark);
            border-radius: 10px;
            padding: 2rem;
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }
        
        .finding-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, var(--gold), var(--blue), var(--gold));
            transform: scaleX(0);
            transition: transform 0.4s ease;
        }
        
        .finding-card:hover::before {
            transform: scaleX(1);
        }
        
        .finding-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(200, 170, 110, 0.15);
            border-color: var(--gold);
        }
        
        .finding-icon {
            width: 60px;
            height: 60px;
            background: linear-gradient(135deg, var(--gold-dark), var(--gold));
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1.5rem;
        }
        
        .finding-icon i {
            font-size: 1.5rem;
            color: var(--blue-darker);
        }
        
        .finding-card h3 {
            font-family: 'Cinzel', serif;
            font-size: 1.3rem;
            color: var(--gold);
            margin-bottom: 1rem;
        }
        
        .finding-card p {
            color: var(--gold-light);
            opacity: 0.85;
            font-size: 0.95rem;
        }
        
        .finding-stat {
            display: inline-block;
            background: rgba(200, 170, 110, 0.1);
            padding: 5px 15px;
            border-radius: 20px;
            margin-top: 1rem;
            font-weight: 600;
            color: var(--gold);
            border: 1px solid var(--gold-dark);
        }
        
        /* Models Section */
        #models {
            background: linear-gradient(180deg, var(--blue-dark) 0%, var(--blue-darker) 100%);
        }
        
        .models-table-container {
            overflow-x: auto;
            margin-top: 2rem;
        }
        
        .models-table {
            width: 100%;
            border-collapse: collapse;
            background: rgba(10, 20, 40, 0.8);
            border-radius: 10px;
            overflow: hidden;
            border: 1px solid var(--gold-dark);
        }
        
        .models-table th,
        .models-table td {
            padding: 1.2rem 1.5rem;
            text-align: center;
        }
        
        .models-table th {
            background: linear-gradient(135deg, var(--gold-dark), var(--gold));
            color: var(--blue-darker);
            font-family: 'Cinzel', serif;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
            font-size: 0.9rem;
        }
        
        .models-table tr {
            border-bottom: 1px solid var(--gold-dark);
            transition: all 0.3s ease;
        }
        
        .models-table tr:hover {
            background: rgba(200, 170, 110, 0.05);
        }
        
        .models-table td {
            color: var(--gold-light);
        }
        
        .models-table .highlight {
            color: var(--blue);
            font-weight: 600;
        }
        
        .model-badge {
            display: inline-block;
            padding: 4px 12px;
            border-radius: 15px;
            font-size: 0.8rem;
            font-weight: 600;
        }
        
        .badge-best {
            background: linear-gradient(135deg, var(--gold-dark), var(--gold));
            color: var(--blue-darker);
        }
        
        /* Strategy Section */
        #strategy {
            background: var(--blue-darker);
        }
        
        .strategy-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
        }
        
        .strategy-card {
            background: linear-gradient(135deg, rgba(10,20,40,0.95) 0%, rgba(1,10,19,0.95) 100%);
            border: 1px solid var(--gold-dark);
            border-radius: 10px;
            padding: 2rem;
            position: relative;
        }
        
        .strategy-card .priority {
            position: absolute;
            top: -15px;
            left: 20px;
            background: linear-gradient(135deg, var(--gold), var(--magic));
            color: var(--blue-darker);
            padding: 5px 15px;
            border-radius: 20px;
            font-weight: 700;
            font-size: 0.85rem;
        }
        
        .strategy-card h3 {
            font-family: 'Cinzel', serif;
            color: var(--gold);
            margin: 1rem 0;
            font-size: 1.4rem;
        }
        
        .strategy-card .impact {
            display: flex;
            align-items: center;
            gap: 10px;
            margin: 1rem 0;
            padding: 10px 15px;
            background: rgba(200, 170, 110, 0.1);
            border-radius: 8px;
            border-left: 3px solid var(--gold);
        }
        
        .strategy-card .impact-value {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--blue);
        }
        
        .strategy-card .impact-label {
            font-size: 0.9rem;
            color: var(--gold-light);
            opacity: 0.9;
        }
        
        .strategy-card p {
            color: var(--gold-light);
            opacity: 0.85;
            font-size: 0.95rem;
            line-height: 1.7;
        }
        
        /* Resources Section */
        #resources {
            background: linear-gradient(180deg, var(--blue-darker) 0%, var(--blue-dark) 100%);
        }
        
        .resources-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .resource-card {
            background: linear-gradient(135deg, rgba(10,20,40,0.9) 0%, rgba(1,10,19,0.9) 100%);
            border: 2px solid var(--gold-dark);
            border-radius: 10px;
            padding: 2.5rem;
            text-align: center;
            transition: all 0.4s ease;
            text-decoration: none;
            display: block;
        }
        
        .resource-card:hover {
            border-color: var(--gold);
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(200, 170, 110, 0.2);
        }
        
        .resource-card i {
            font-size: 3rem;
            color: var(--gold);
            margin-bottom: 1.5rem;
            display: block;
        }
        
        .resource-card h3 {
            font-family: 'Cinzel', serif;
            font-size: 1.4rem;
            color: var(--gold);
            margin-bottom: 1rem;
        }
        
        .resource-card p {
            color: var(--gold-light);
            opacity: 0.8;
            font-size: 0.95rem;
        }
        
        /* Author Section */
        #author {
            background: var(--blue-darker);
            border-top: 1px solid var(--gold-dark);
        }
        
        .author-content {
            display: flex;
            align-items: center;
            gap: 3rem;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .author-avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid var(--gold);
            background: linear-gradient(135deg, var(--gold-dark), var(--gold));
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
        }
        
        .author-avatar i {
            font-size: 4rem;
            color: var(--blue-darker);
        }
        
        .author-info h3 {
            font-family: 'Cinzel', serif;
            font-size: 1.8rem;
            color: var(--gold);
            margin-bottom: 0.5rem;
        }
        
        .author-info .affiliation {
            color: var(--blue);
            font-size: 1rem;
            margin-bottom: 1rem;
        }
        
        .author-info p {
            color: var(--gold-light);
            opacity: 0.85;
            margin-bottom: 1rem;
        }
        
        .course-info {
            background: rgba(200, 170, 110, 0.1);
            padding: 15px 20px;
            border-radius: 8px;
            border-left: 3px solid var(--gold);
        }
        
        .course-info p {
            margin: 0;
            font-size: 0.95rem;
        }
        
        /* Footer */
        footer {
            background: var(--blue-darker);
            border-top: 1px solid var(--gold-dark);
            padding: 3rem 2rem;
            text-align: center;
        }
        
        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .footer-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-bottom: 2rem;
        }
        
        .footer-links a {
            color: var(--gold-light);
            text-decoration: none;
            transition: color 0.3s ease;
        }
        
        .footer-links a:hover {
            color: var(--gold);
        }
        
        .copyright {
            color: var(--gold-light);
            opacity: 0.6;
            font-size: 0.9rem;
        }
        
        /* Animations */
        .fade-in {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s ease;
        }
        
        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
        
        /* Mobile Menu */
        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            color: var(--gold);
            font-size: 1.5rem;
            cursor: pointer;
        }
        
        /* Responsive */
        @media (max-width: 992px) {
            .about-content {
                grid-template-columns: 1fr;
            }
            
            .author-content {
                flex-direction: column;
                text-align: center;
            }
        }
        
        @media (max-width: 768px) {
            .mobile-menu-btn {
                display: block;
            }
            
            .nav-links {
                display: none;
                position: absolute;
                top: 70px;
                left: 0;
                right: 0;
                background: var(--blue-darker);
                flex-direction: column;
                padding: 2rem;
                gap: 1.5rem;
                border-bottom: 1px solid var(--gold-dark);
            }
            
            .nav-links.active {
                display: flex;
            }
            
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .hero-stats {
                gap: 1.5rem;
            }
            
            .stat-value {
                font-size: 2rem;
            }
            
            .cta-buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .section-header h2 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <!-- Particle Canvas -->
    <canvas id="particles-canvas"></canvas>
    
    <!-- Navigation -->
    <nav>
        <div class="nav-container">
            <a href="#" class="logo">
                <i class="fas fa-chess-knight"></i>
                LoL Predictor
            </a>
            <button class="mobile-menu-btn" onclick="toggleMenu()">
                <i class="fas fa-bars"></i>
            </button>
            <ul class="nav-links" id="navLinks">
                <li><a href="#about">About</a></li>
                <li><a href="#findings">Findings</a></li>
                <li><a href="#models">Models</a></li>
                <li><a href="#strategy">Strategy</a></li>
                <li><a href="#resources">Resources</a></li>
            </ul>
        </div>
    </nav>
    
    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content">
            <span class="hero-badge">AOS C111/204 Final Project</span>
            <h1>Predicting <span>League of Legends</span> Match Outcomes</h1>
            <p class="hero-subtitle">Using Machine Learning to Analyze Early Game Statistics from 9,879 Diamond-Tier Ranked Games</p>
            
            <div class="hero-stats">
                <div class="stat-item">
                    <span class="stat-value">72%</span>
                    <span class="stat-label">Prediction Accuracy</span>
                </div>
                <div class="stat-item">
                    <span class="stat-value">9,879</span>
                    <span class="stat-label">Games Analyzed</span>
                </div>
                <div class="stat-item">
                    <span class="stat-value">5</span>
                    <span class="stat-label">ML Models</span>
                </div>
            </div>
            
            <div class="cta-buttons">
                <a href="#findings" class="btn btn-primary">
                    <i class="fas fa-chart-line"></i>
                    View Results
                </a>
                <a href="#resources" class="btn btn-secondary">
                    <i class="fas fa-download"></i>
                    Get Resources
                </a>
            </div>
        </div>
        
        <div class="scroll-indicator">
            <i class="fas fa-chevron-down"></i>
        </div>
    </section>
    
    <!-- About Section -->
    <section id="about">
        <div class="container">
            <div class="section-header fade-in">
                <h2>About This Project</h2>
                <p>Applying machine learning to competitive gaming analytics</p>
            </div>
            
            <div class="about-content">
                <div class="about-text fade-in">
                    <h3>The Challenge</h3>
                    <p>In competitive League of Legends, the first 10 minutes—known as the "laning phase"—are widely considered crucial in determining match outcomes. Players must decide whether to play aggressively for kills, farm safely for gold, or rotate to help teammates.</p>
                    <p>Coaches and analysts frequently debate which early-game factors matter most. Does First Blood (the first kill of the game) provide crucial momentum? Is maintaining high CS (Creep Score) more important? This project addresses these questions through rigorous machine learning analysis.</p>
                    <h3>The Approach</h3>
                    <p>Using a dataset of 9,879 Diamond-tier ranked games from Kaggle, I trained five different classification models to predict match winners based solely on 10-minute statistics. The models include Logistic Regression (with L1 and L2 regularization), Decision Trees, Random Forests, and Support Vector Machines.</p>
                </div>
                <div class="about-image fade-in">
                    <img src="https://cdn1.epicgames.com/offer/24b9b5e323bc40eea252a10cdd3b2f10/EGS_LeagueofLegends_RiotGames_S1_2560x1440-47eb328eac5ddd63ebd096ded7d0d5ab" alt="League of Legends">
                </div>
            </div>
        </div>
    </section>
    
    <!-- Key Findings Section -->
    <section id="findings">
        <div class="container">
            <div class="section-header fade-in">
                <h2>Key Findings</h2>
                <p>Data-driven insights from nearly 10,000 high-level games</p>
            </div>
            
            <div class="findings-grid">
                <div class="finding-card fade-in">
                    <div class="finding-icon">
                        <i class="fas fa-coins"></i>
                    </div>
                    <h3>Gold is King</h3>
                    <p>Gold difference is the strongest predictor of victory with a correlation of r = 0.51. Teams in the top gold quintile at 10 minutes win 87% of their games.</p>
                    <span class="finding-stat">87% Win Rate</span>
                </div>
                
                <div class="finding-card fade-in">
                    <div class="finding-icon">
                        <i class="fas fa-crosshairs"></i>
                    </div>
                    <h3>First Blood Impact</h3>
                    <p>Securing First Blood provides a substantial 20 percentage point increase in win rate—from 40% without it to 60% with it.</p>
                    <span class="finding-stat">+20% Advantage</span>
                </div>
                
                <div class="finding-card fade-in">
                    <div class="finding-icon">
                        <i class="fas fa-dragon"></i>
                    </div>
                    <h3>Dragon Control</h3>
                    <p>Teams securing a dragon win 64% of games compared to 42% for teams without one—a meaningful 22 percentage point advantage.</p>
                    <span class="finding-stat">64% Win Rate</span>
                </div>
                
                <div class="finding-card fade-in">
                    <div class="finding-icon">
                        <i class="fas fa-skull-crossbones"></i>
                    </div>
                    <h3>Deaths Matter</h3>
                    <p>Deaths show strong negative correlation with winning (r = -0.34). Each death transfers gold and experience to the enemy team.</p>
                    <span class="finding-stat">r = -0.34</span>
                </div>
                
                <div class="finding-card fade-in">
                    <div class="finding-icon">
                        <i class="fas fa-trophy"></i>
                    </div>
                    <h3>Combined Objectives</h3>
                    <p>Teams securing both Dragon and Herald by 10 minutes win 72% of games—demonstrating map-wide dominance.</p>
                    <span class="finding-stat">72% Win Rate</span>
                </div>
                
                <div class="finding-card fade-in">
                    <div class="finding-icon">
                        <i class="fas fa-brain"></i>
                    </div>
                    <h3>Simple Models Win</h3>
                    <p>Logistic Regression performs as well as complex models like Random Forest and SVM, suggesting the relationship is approximately linear.</p>
                    <span class="finding-stat">73.5% CV Accuracy</span>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Models Section -->
    <section id="models">
        <div class="container">
            <div class="section-header fade-in">
                <h2>Model Performance</h2>
                <p>Comparing five different machine learning approaches</p>
            </div>
            
            <div class="models-table-container fade-in">
                <table class="models-table">
                    <thead>
                        <tr>
                            <th>Model</th>
                            <th>Train Accuracy</th>
                            <th>Test Accuracy</th>
                            <th>CV Score</th>
                            <th>Status</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Logistic Regression (L2)</td>
                            <td>73.6%</td>
                            <td class="highlight">72.4%</td>
                            <td>73.4% ± 1.6%</td>
                            <td></td>
                        </tr>
                        <tr>
                            <td>Logistic Regression (L1)</td>
                            <td>73.6%</td>
                            <td class="highlight">72.4%</td>
                            <td>73.5% ± 1.5%</td>
                            <td><span class="model-badge badge-best">Best</span></td>
                        </tr>
                        <tr>
                            <td>Decision Tree</td>
                            <td>73.8%</td>
                            <td>72.0%</td>
                            <td>71.3% ± 0.8%</td>
                            <td></td>
                        </tr>
                        <tr>
                            <td>Random Forest</td>
                            <td>78.8%</td>
                            <td>72.0%</td>
                            <td>72.9% ± 1.3%</td>
                            <td></td>
                        </tr>
                        <tr>
                            <td>SVM (RBF Kernel)</td>
                            <td>74.2%</td>
                            <td>71.8%</td>
                            <td>72.7% ± 1.2%</td>
                            <td></td>
                        </tr>
                    </tbody>
                </table>
            </div>
            
            <div style="margin-top: 3rem; text-align: center;" class="fade-in">
                <p style="color: var(--gold-light); opacity: 0.9; max-width: 800px; margin: 0 auto;">
                    All models achieve approximately <strong style="color: var(--gold);">72% test accuracy</strong>, suggesting this represents an approximate ceiling for prediction using only 10-minute statistics. The remaining 28% of matches are determined by factors not captured in these early-game features, such as champion compositions, individual player skill, or strategic decisions made after the 10-minute mark.
                </p>
            </div>
        </div>
    </section>
    
    <!-- Strategy Section -->
    <section id="strategy">
        <div class="container">
            <div class="section-header fade-in">
                <h2>Strategic Recommendations</h2>
                <p>Data-driven priorities for the first 10 minutes</p>
            </div>
            
            <div class="strategy-content">
                <div class="strategy-card fade-in">
                    <span class="priority">Priority #1</span>
                    <h3>Maximize Gold Income</h3>
                    <div class="impact">
                        <span class="impact-value">73.4%</span>
                        <span class="impact-label">Win rate swing between top and bottom gold quintiles</span>
                    </div>
                    <p>Focus on consistent farming—aim for 7-8 CS per minute. Gold is the foundation of all other advantages. A 1,500 gold lead translates to roughly four long swords worth of combat statistics, creating a compounding advantage.</p>
                </div>
                
                <div class="strategy-card fade-in">
                    <span class="priority">Priority #2</span>
                    <h3>Secure First Blood</h3>
                    <div class="impact">
                        <span class="impact-value">+20%</span>
                        <span class="impact-label">Win rate increase from 40% to 60%</span>
                    </div>
                    <p>First Blood grants 400 gold (vs normal 300), creates level advantage, and provides psychological momentum. Look for level 1 invades or level 2 all-ins if your composition supports early aggression.</p>
                </div>
                
                <div class="strategy-card fade-in">
                    <span class="priority">Priority #3</span>
                    <h3>Contest Dragon</h3>
                    <div class="impact">
                        <span class="impact-value">+22%</span>
                        <span class="impact-label">Win rate advantage with dragon control</span>
                    </div>
                    <p>Dragon spawns at 5:00 and provides permanent team-wide buffs. Establish bot lane priority before it spawns and use this advantage to contest or take the objective.</p>
                </div>
                
                <div class="strategy-card fade-in">
                    <span class="priority">Priority #4</span>
                    <h3>Minimize Deaths</h3>
                    <div class="impact">
                        <span class="impact-value">r = -0.34</span>
                        <span class="impact-label">Strong negative correlation with winning</span>
                    </div>
                    <p>Deaths transfer approximately 300+ gold to enemies. Ward properly to avoid ganks, don't tower dive unless certain to succeed, and avoid chasing into unwarded territory.</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Resources Section -->
    <section id="resources">
        <div class="container">
            <div class="section-header fade-in">
                <h2>Resources</h2>
                <p>Access the full report, code, and dataset</p>
            </div>
            
            <div class="resources-grid">
                <a href="LoL_Final_Report_v2.ipynb" class="resource-card fade-in" target="_blank">
                    <i class="fas fa-file-alt"></i>
                    <h3>Full Report</h3>
                    <p>Complete Jupyter Notebook with detailed analysis, code, visualizations, and discussion</p>
                </a>
                
                <a href="https://www.kaggle.com/datasets/bobbyscience/league-of-legends-diamond-ranked-games-10-min" class="resource-card fade-in" target="_blank">
                    <i class="fas fa-database"></i>
                    <h3>Dataset</h3>
                    <p>9,879 Diamond-tier ranked games from Kaggle with 40 features captured at 10 minutes</p>
                </a>
                
                <a href="https://github.com/YOUR_USERNAME/YOUR_REPO" class="resource-card fade-in" target="_blank">
                    <i class="fab fa-github"></i>
                    <h3>Source Code</h3>
                    <p>GitHub repository containing all Python code, analysis scripts, and this website</p>
                </a>
            </div>
        </div>
    </section>
    
    <!-- Author Section -->
    <section id="author">
        <div class="container">
            <div class="section-header fade-in">
                <h2>About the Author</h2>
            </div>
            
            <div class="author-content fade-in">
                <div class="author-avatar">
                    <i class="fas fa-user-graduate"></i>
                </div>
                <div class="author-info">
                    <h3>Aaron Wen</h3>
                    <p class="affiliation">UCLA Department of Atmospheric and Oceanic Sciences</p>
                    <p>This project was completed as part of the AOS C111/204 Machine Learning course, applying classification techniques to predict competitive gaming outcomes.</p>
                    <div class="course-info">
                        <p><strong>Course:</strong> AOS C111/204 - Introduction to Machine Learning for Physical Sciences</p>
                        <p><strong>Instructor:</strong> Dr. Alexander Lozinski</p>
                        <p><strong>Date:</strong> December 2024</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-links">
                <a href="#about">About</a>
                <a href="#findings">Findings</a>
                <a href="#models">Models</a>
                <a href="#strategy">Strategy</a>
                <a href="#resources">Resources</a>
            </div>
            <p class="copyright">
                © 2024 League of Legends Match Prediction Project | UCLA AOS C111/204
            </p>
        </div>
    </footer>
    
    <script>
        // Mobile Menu Toggle
        function toggleMenu() {
            document.getElementById('navLinks').classList.toggle('active');
        }
        
        // Scroll Animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, observerOptions);
        
        document.querySelectorAll('.fade-in').forEach(el => {
            observer.observe(el);
        });
        
        // Particle Animation
        const canvas = document.getElementById('particles-canvas');
        const ctx = canvas.getContext('2d');
        
        canvas.width = window.innerWidth;
        canvas.height = window.innerHeight;
        
        const particles = [];
        const particleCount = 80;
        
        class Particle {
            constructor() {
                this.x = Math.random() * canvas.width;
                this.y = Math.random() * canvas.height;
                this.size = Math.random() * 2 + 0.5;
                this.speedX = Math.random() * 0.5 - 0.25;
                this.speedY = Math.random() * 0.5 - 0.25;
                this.opacity = Math.random() * 0.5 + 0.2;
                this.color = Math.random() > 0.5 ? '#C8AA6E' : '#0AC8B9';
            }
            
            update() {
                this.x += this.speedX;
                this.y += this.speedY;
                
                if (this.x > canvas.width) this.x = 0;
                if (this.x < 0) this.x = canvas.width;
                if (this.y > canvas.height) this.y = 0;
                if (this.y < 0) this.y = canvas.height;
            }
            
            draw() {
                ctx.fillStyle = this.color;
                ctx.globalAlpha = this.opacity;
                ctx.beginPath();
                ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
                ctx.fill();
            }
        }
        
        function init() {
            for (let i = 0; i < particleCount; i++) {
                particles.push(new Particle());
            }
        }
        
        function animate() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            
            particles.forEach(particle => {
                particle.update();
                particle.draw();
            });
            
            // Draw connections
            particles.forEach((a, index) => {
                particles.slice(index + 1).forEach(b => {
                    const dx = a.x - b.x;
                    const dy = a.y - b.y;
                    const distance = Math.sqrt(dx * dx + dy * dy);
                    
                    if (distance < 150) {
                        ctx.strokeStyle = '#C8AA6E';
                        ctx.globalAlpha = 0.1 * (1 - distance / 150);
                        ctx.lineWidth = 0.5;
                        ctx.beginPath();
                        ctx.moveTo(a.x, a.y);
                        ctx.lineTo(b.x, b.y);
                        ctx.stroke();
                    }
                });
            });
            
            requestAnimationFrame(animate);
        }
        
        init();
        animate();
        
        // Resize handler
        window.addEventListener('resize', () => {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        });
        
        // Smooth scroll for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                    // Close mobile menu if open
                    document.getElementById('navLinks').classList.remove('active');
                }
            });
        });
    </script>
</body>
</html>
