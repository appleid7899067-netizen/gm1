<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI-Мастерская | Воркшоп будущего</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800;900&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #07071a;
            --text-color: #e0e0f0;
            --accent-color: #00e5ff;
            --accent-secondary: #7c4dff;
            --secondary-bg: #0e0e28;
            --card-bg: rgba(22, 22, 50, 0.7);
            --glow-cyan: 0 0 30px rgba(0, 229, 255, 0.3);
            --glow-purple: 0 0 30px rgba(124, 77, 255, 0.3);
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
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.7;
            overflow-x: hidden;
        }

        /* ===== NAVBAR ===== */
        .navbar {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 1000;
            padding: 15px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: rgba(7, 7, 26, 0.85);
            backdrop-filter: blur(20px);
            border-bottom: 1px solid rgba(0, 229, 255, 0.1);
            transition: all 0.3s ease;
        }

        .navbar.scrolled {
            padding: 10px 40px;
            background: rgba(7, 7, 26, 0.95);
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.5);
        }

        .nav-logo {
            font-size: 1.4rem;
            font-weight: 800;
            color: var(--accent-color);
            text-decoration: none;
            letter-spacing: 1px;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .nav-logo svg {
            width: 28px;
            height: 28px;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 30px;
            align-items: center;
        }

        .nav-links a {
            color: var(--text-color);
            text-decoration: none;
            font-size: 0.9rem;
            font-weight: 500;
            position: relative;
            padding: 5px 0;
            transition: color 0.3s;
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--accent-color);
            transition: width 0.3s ease;
        }

        .nav-links a:hover {
            color: var(--accent-color);
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        .nav-cta {
            background: var(--accent-color) !important;
            color: var(--bg-color) !important;
            padding: 8px 20px !important;
            border-radius: 25px !important;
            font-weight: 700 !important;
            transition: all 0.3s ease !important;
        }

        .nav-cta:hover {
            box-shadow: var(--glow-cyan);
            transform: translateY(-2px);
        }

        .nav-cta::after {
            display: none !important;
        }

        .hamburger {
            display: none;
            flex-direction: column;
            cursor: pointer;
            gap: 5px;
            z-index: 1001;
        }

        .hamburger span {
            width: 28px;
            height: 2px;
            background: var(--accent-color);
            transition: all 0.3s ease;
        }

        .hamburger.active span:nth-child(1) {
            transform: rotate(45deg) translate(5px, 5px);
        }

        .hamburger.active span:nth-child(2) {
            opacity: 0;
        }

        .hamburger.active span:nth-child(3) {
            transform: rotate(-45deg) translate(5px, -5px);
        }

        /* ===== HERO ===== */
        .hero {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 120px 20px 80px;
            position: relative;
            overflow: hidden;
        }

        .hero-canvas {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
        }

        .hero-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(ellipse at center, rgba(7, 7, 26, 0.3) 0%, rgba(7, 7, 26, 0.9) 70%);
            z-index: 1;
        }

        .hero-content {
            position: relative;
            z-index: 2;
            max-width: 850px;
        }

        .hero-badge {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: rgba(0, 229, 255, 0.1);
            border: 1px solid rgba(0, 229, 255, 0.3);
            padding: 8px 20px;
            border-radius: 50px;
            font-size: 0.85rem;
            color: var(--accent-color);
            margin-bottom: 30px;
            font-weight: 600;
            letter-spacing: 1px;
            text-transform: uppercase;
            animation: fadeInDown 0.8s ease forwards;
        }

        .hero-badge .pulse-dot {
            width: 8px;
            height: 8px;
            background: var(--accent-color);
            border-radius: 50%;
            animation: pulse 2s infinite;
        }

        .hero h1 {
            font-size: clamp(2.5rem, 7vw, 5rem);
            font-weight: 900;
            margin-bottom: 10px;
            background: linear-gradient(135deg, var(--accent-color), var(--accent-secondary), #ff6b9d);
            background-size: 200% 200%;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            animation: gradientShift 5s ease infinite, fadeInUp 0.8s ease 0.2s both;
            line-height: 1.1;
        }

        .hero-subtitle {
            font-size: clamp(1rem, 2.5vw, 1.5rem);
            font-weight: 300;
            margin-bottom: 20px;
            opacity: 0.85;
            animation: fadeInUp 0.8s ease 0.4s both;
        }

        .hero-date {
            font-size: 1.1rem;
            color: var(--accent-color);
            font-weight: 600;
            margin-bottom: 40px;
            font-family: 'JetBrains Mono', monospace;
            animation: fadeInUp 0.8s ease 0.5s both;
        }

        .hero-buttons {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
            animation: fadeInUp 0.8s ease 0.6s both;
        }

        .btn-primary {
            display: inline-flex;
            align-items: center;
            gap: 10px;
            background: linear-gradient(135deg, var(--accent-color), var(--accent-secondary));
            color: var(--bg-color);
            padding: 16px 36px;
            text-decoration: none;
            font-weight: 800;
            border-radius: 50px;
            font-size: 1rem;
            border: none;
            cursor: pointer;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .btn-primary::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
            transition: left 0.5s ease;
        }

        .btn-primary:hover::before {
            left: 100%;
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: var(--glow-cyan);
        }

        .btn-secondary {
            display: inline-flex;
            align-items: center;
            gap: 10px;
            background: transparent;
            color: var(--text-color);
            padding: 16px 36px;
            text-decoration: none;
            font-weight: 600;
            border-radius: 50px;
            font-size: 1rem;
            border: 2px solid rgba(255,255,255,0.2);
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .btn-secondary:hover {
            border-color: var(--accent-color);
            color: var(--accent-color);
            transform: translateY(-3px);
        }

        .scroll-indicator {
            position: absolute;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            z-index: 2;
            animation: bounce 2s infinite;
        }

        .scroll-indicator svg {
            width: 30px;
            height: 30px;
            opacity: 0.5;
        }

        /* ===== COUNTDOWN ===== */
        .countdown-section {
            padding: 40px 20px;
            background: var(--secondary-bg);
            border-top: 1px solid rgba(0, 229, 255, 0.1);
            border-bottom: 1px solid rgba(0, 229, 255, 0.1);
        }

        .countdown {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
            max-width: 600px;
            margin: 0 auto;
        }

        .countdown-item {
            text-align: center;
        }

        .countdown-value {
            font-size: clamp(2rem, 5vw, 3.5rem);
            font-weight: 900;
            font-family: 'JetBrains Mono', monospace;
            color: var(--accent-color);
            line-height: 1;
            text-shadow: 0 0 20px rgba(0, 229, 255, 0.3);
        }

        .countdown-label {
            font-size: 0.8rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            opacity: 0.6;
            margin-top: 5px;
        }

        .countdown-sep {
            font-size: 3rem;
            color: var(--accent-secondary);
            align-self: flex-start;
            padding-top: 5px;
        }

        /* ===== SECTIONS ===== */
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .section {
            padding: 100px 20px;
            position: relative;
        }

        .section-header {
            text-align: center;
            margin-bottom: 60px;
        }

        .section-header h2 {
            font-size: clamp(2rem, 4vw, 3rem);
            font-weight: 800;
            margin-bottom: 15px;
            color: #fff;
        }

        .section-header h2 span {
            color: var(--accent-color);
        }

        .section-header p {
            font-size: 1.1rem;
            opacity: 0.7;
            max-width: 600px;
            margin: 0 auto;
        }

        .section-divider {
            width: 60px;
            height: 4px;
            background: linear-gradient(90deg, var(--accent-color), var(--accent-secondary));
            margin: 15px auto;
            border-radius: 2px;
        }

        /* ===== ABOUT ===== */
        .about-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            align-items: center;
        }

        .about-text p {
            margin-bottom: 20px;
            font-size: 1.05rem;
            opacity: 0.85;
        }

        .about-image {
            position: relative;
            border-radius: 20px;
            overflow: hidden;
            aspect-ratio: 4/3;
            background: var(--card-bg);
            border: 1px solid rgba(0, 229, 255, 0.15);
        }

        .about-image-inner {
            width: 100%;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            overflow: hidden;
        }

        .about-visual {
            position: absolute;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, rgba(0, 229, 255, 0.05), rgba(124, 77, 255, 0.05));
        }

        .about-visual::before {
            content: '';
            position: absolute;
            width: 200px;
            height: 200px;
            background: radial-gradient(circle, rgba(0, 229, 255, 0.15), transparent 70%);
            top: 20%;
            left: 30%;
            animation: float 6s ease-in-out infinite;
        }

        .about-visual::after {
            content: '';
            position: absolute;
            width: 150px;
            height: 150px;
            background: radial-gradient(circle, rgba(124, 77, 255, 0.15), transparent 70%);
            bottom: 20%;
            right: 30%;
            animation: float 6s ease-in-out infinite reverse;
        }

        .about-icon-center {
            position: relative;
            z-index: 1;
            width: 120px;
            height: 120px;
        }

        .about-icon-center svg {
            width: 100%;
            height: 100%;
        }

        .about-stats {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            margin-top: 40px;
        }

        .stat-item {
            text-align: center;
            padding: 20px;
            background: var(--card-bg);
            border-radius: 15px;
            border: 1px solid rgba(0, 229, 255, 0.1);
        }

        .stat-number {
            font-size: 2rem;
            font-weight: 900;
            color: var(--accent-color);
            font-family: 'JetBrains Mono', monospace;
        }

        .stat-label {
            font-size: 0.85rem;
            opacity: 0.7;
            margin-top: 5px;
        }

        /* ===== PROGRAM ===== */
        .program-section {
            background: var(--secondary-bg);
        }

        .timeline {
            position: relative;
            max-width: 700px;
            margin: 0 auto;
        }

        .timeline::before {
            content: '';
            position: absolute;
            left: 30px;
            top: 0;
            bottom: 0;
            width: 3px;
            background: linear-gradient(to bottom, var(--accent-color), var(--accent-secondary));
            border-radius: 2px;
        }

        .timeline-item {
            display: flex;
            gap: 25px;
            margin-bottom: 40px;
            position: relative;
            opacity: 0;
            transform: translateX(-30px);
            transition: all 0.6s ease;
        }

        .timeline-item.visible {
            opacity: 1;
            transform: translateX(0);
        }

        .timeline-dot {
            width: 20px;
            height: 20px;
            min-width: 20px;
            background: var(--accent-color);
            border-radius: 50%;
            margin-top: 5px;
            margin-left: 21px;
            position: relative;
            z-index: 1;
            box-shadow: 0 0 15px rgba(0, 229, 255, 0.4);
            transition: all 0.3s ease;
        }

        .timeline-item:hover .timeline-dot {
            transform: scale(1.3);
            box-shadow: 0 0 25px rgba(0, 229, 255, 0.6);
        }

        .timeline-content {
            background: var(--card-bg);
            padding: 25px;
            border-radius: 15px;
            border: 1px solid rgba(0, 229, 255, 0.1);
            flex: 1;
            transition: all 0.3s ease;
        }

        .timeline-item:hover .timeline-content {
            border-color: rgba(0, 229, 255, 0.3);
            transform: translateX(5px);
        }

        .timeline-time {
            font-family: 'JetBrains Mono', monospace;
            color: var(--accent-color);
            font-weight: 700;
            font-size: 0.9rem;
            margin-bottom: 8px;
        }

        .timeline-title {
            font-size: 1.2rem;
            font-weight: 700;
            margin-bottom: 8px;
            color: #fff;
        }

        .timeline-desc {
            font-size: 0.95rem;
            opacity: 0.7;
        }

        /* ===== SKILLS ===== */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .skill-card {
            background: var(--card-bg);
            padding: 35px 25px;
            border-radius: 20px;
            border: 1px solid rgba(0, 229, 255, 0.08);
            transition: all 0.4s ease;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .skill-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, rgba(0, 229, 255, 0.05), rgba(124, 77, 255, 0.05));
            opacity: 0;
            transition: opacity 0.4s ease;
        }

        .skill-card:hover::before {
            opacity: 1;
        }

        .skill-card:hover {
            transform: translateY(-8px);
            border-color: rgba(0, 229, 255, 0.2);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
        }

        .skill-icon {
            width: 60px;
            height: 60px;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, rgba(0, 229, 255, 0.15), rgba(124, 77, 255, 0.15));
            border-radius: 15px;
            position: relative;
            z-index: 1;
        }

        .skill-icon svg {
            width: 30px;
            height: 30px;
        }

        .skill-card h3 {
            font-size: 1.15rem;
            font-weight: 700;
            margin-bottom: 12px;
            color: #fff;
            position: relative;
            z-index: 1;
        }

        .skill-card p {
            font-size: 0.9rem;
            opacity: 0.7;
            position: relative;
            z-index: 1;
        }

        /* ===== SPEAKERS ===== */
        .speakers-section {
            background: var(--secondary-bg);
        }

        .speakers-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            max-width: 900px;
            margin: 0 auto;
        }

        .speaker-card {
            background: var(--card-bg);
            border-radius: 20px;
            overflow: hidden;
            border: 1px solid rgba(0, 229, 255, 0.08);
            transition: all 0.4s ease;
        }

        .speaker-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
            border-color: rgba(0, 229, 255, 0.2);
        }

        .speaker-avatar {
            width: 100%;
            aspect-ratio: 1;
            position: relative;
            overflow: hidden;
        }

        .speaker-avatar img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .speaker-avatar-placeholder {
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, rgba(0, 229, 255, 0.1), rgba(124, 77, 255, 0.1));
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .speaker-avatar-placeholder svg {
            width: 80px;
            height: 80px;
            opacity: 0.5;
        }

        .speaker-info {
            padding: 25px;
        }

        .speaker-name {
            font-size: 1.2rem;
            font-weight: 700;
            margin-bottom: 5px;
        }

        .speaker-role {
            color: var(--accent-color);
            font-size: 0.9rem;
            font-weight: 600;
            margin-bottom: 10px;
        }

        .speaker-bio {
            font-size: 0.9rem;
            opacity: 0.7;
        }

        /* ===== FAQ ===== */
        .faq-list {
            max-width: 700px;
            margin: 0 auto;
        }

        .faq-item {
            background: var(--card-bg);
            border-radius: 15px;
            margin-bottom: 15px;
            border: 1px solid rgba(0, 229, 255, 0.08);
            overflow: hidden;
            transition: all 0.3s ease;
        }

        .faq-item:hover {
            border-color: rgba(0, 229, 255, 0.2);
        }

        .faq-question {
            padding: 20px 25px;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-weight: 600;
            font-size: 1.05rem;
            transition: color 0.3s;
        }

        .faq-question:hover {
            color: var(--accent-color);
        }

        .faq-icon {
            font-size: 1.5rem;
            transition: transform 0.3s ease;
            color: var(--accent-color);
        }

        .faq-item.active .faq-icon {
            transform: rotate(45deg);
        }

        .faq-answer {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.4s ease, padding 0.4s ease;
        }

        .faq-answer-inner {
            padding: 0 25px 20px;
            font-size: 0.95rem;
            opacity: 0.7;
            line-height: 1.7;
        }

        .faq-item.active .faq-answer {
            max-height: 300px;
        }

        /* ===== REGISTER ===== */
        .register-section {
            background: var(--secondary-bg);
            position: relative;
            overflow: hidden;
        }

        .register-section::before {
            content: '';
            position: absolute;
            width: 500px;
            height: 500px;
            background: radial-gradient(circle, rgba(0, 229, 255, 0.05), transparent 70%);
            top: -200px;
            right: -200px;
        }

        .register-section::after {
            content: '';
            position: absolute;
            width: 500px;
            height: 500px;
            background: radial-gradient(circle, rgba(124, 77, 255, 0.05), transparent 70%);
            bottom: -200px;
            left: -200px;
        }

        .register-container {
            max-width: 550px;
            margin: 0 auto;
            position: relative;
            z-index: 1;
        }

        .register-card {
            background: var(--card-bg);
            border-radius: 25px;
            padding: 40px;
            border: 1px solid rgba(0, 229, 255, 0.1);
            backdrop-filter: blur(10px);
        }

        .register-info {
            display: flex;
            flex-direction: column;
            gap: 12px;
            margin-bottom: 30px;
        }

        .register-info-item {
            display: flex;
            align-items: center;
            gap: 12px;
            font-size: 0.95rem;
        }

        .register-info-item svg {
            width: 20px;
            height: 20px;
            color: var(--accent-color);
            flex-shrink: 0;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            font-size: 0.9rem;
            color: rgba(255, 255, 255, 0.8);
        }

        .form-group input,
        .form-group select {
            width: 100%;
            padding: 14px 18px;
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 12px;
            color: #fff;
            font-size: 1rem;
            font-family: 'Inter', sans-serif;
            transition: all 0.3s ease;
            outline: none;
        }

        .form-group input::placeholder {
            color: rgba(255, 255, 255, 0.3);
        }

        .form-group input:focus,
        .form-group select:focus {
            border-color: var(--accent-color);
            box-shadow: 0 0 0 3px rgba(0, 229, 255, 0.1);
        }

        .form-group select {
            appearance: none;
            cursor: pointer;
            background-image: url("image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='12' fill='%2300e5ff' viewBox='0 0 16 16'%3E%3Cpath d='M8 11L3 6h10z'/%3E%3C/svg%3E");
            background-repeat: no-repeat;
            background-position: right 15px center;
        }

        .form-group select option {
            background: var(--bg-color);
            color: #fff;
        }

        .form-submit {
            width: 100%;
            padding: 16px;
            background: linear-gradient(135deg, var(--accent-color), var(--accent-secondary));
            color: var(--bg-color);
            border: none;
            border-radius: 12px;
            font-size: 1.05rem;
            font-weight: 800;
            font-family: 'Inter', sans-serif;
            cursor: pointer;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .form-submit::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
            transition: left 0.5s ease;
        }

        .form-submit:hover::before {
            left: 100%;
        }

        .form-submit:hover {
            transform: translateY(-2px);
            box-shadow: var(--glow-cyan);
        }

        .form-submit:disabled {
            opacity: 0.5;
            cursor: not-allowed;
            transform: none;
        }

        .form-message {
            text-align: center;
            margin-top: 15px;
            font-size: 0.9rem;
            font-weight: 600;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .form-message.show {
            opacity: 1;
        }

        .form-message.success {
            color: #00e676;
        }

        .form-message.error {
            color: #ff5252;
        }

        /* ===== FOOTER ===== */
        footer {
            padding: 40px 20px;
            text-align: center;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            background: #050510;
        }

        .footer-logo {
            font-size: 1.3rem;
            font-weight: 800;
            color: var(--accent-color);
            margin-bottom: 10px;
        }

        .footer-text {
            font-size: 0.85rem;
            opacity: 0.5;
        }

        .footer-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 15px 0;
        }

        .footer-links a {
            color: var(--text-color);
            opacity: 0.5;
            text-decoration: none;
            font-size: 0.85rem;
            transition: all 0.3s;
        }

        .footer-links a:hover {
            color: var(--accent-color);
            opacity: 1;
        }

        /* ===== MODAL ===== */
        .modal-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
            backdrop-filter: blur(10px);
            z-index: 2000;
            display: none;
            align-items: center;
            justify-content: center;
            padding: 20px;
            animation: fadeIn 0.3s ease;
        }

        .modal-overlay.active {
            display: flex;
        }

        .modal-content {
            background: var(--secondary-bg);
            border-radius: 25px;
            padding: 50px;
            text-align: center;
            border: 1px solid rgba(0, 229, 255, 0.2);
            max-width: 450px;
            width: 100%;
            position: relative;
            animation: scaleIn 0.4s ease;
        }

        .modal-close {
            position: absolute;
            top: 15px;
            right: 20px;
            background: none;
            border: none;
            color: var(--text-color);
            font-size: 1.5rem;
            cursor: pointer;
            opacity: 0.5;
            transition: opacity 0.3s;
        }

        .modal-close:hover {
            opacity: 1;
        }

        .modal-icon {
            width: 80px;
            height: 80px;
            margin: 0 auto 20px;
            background: linear-gradient(135deg, rgba(0, 230, 118, 0.15), rgba(0, 230, 118, 0.05));
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .modal-icon svg {
            width: 40px;
            height: 40px;
            color: #00e676;
        }

        .modal-content h3 {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }

        .modal-content p {
            opacity: 0.7;
        }

        /* ===== ANIMATIONS ===== */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes fadeInDown {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes scaleIn {
            from { opacity: 0; transform: scale(0.8); }
            to { opacity: 1; transform: scale(1); }
        }

        @keyframes gradientShift {
            0%, 100% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; transform: scale(1); }
            50% { opacity: 0.5; transform: scale(1.5); }
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateX(-50%) translateY(0); }
            40% { transform: translateX(-50%) translateY(-15px); }
            60% { transform: translateX(-50%) translateY(-7px); }
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }

        /* ===== SCROLL REVEAL ===== */
        .reveal {
            opacity: 0;
            transform: translateY(40px);
            transition: all 0.8s ease;
        }

        .reveal.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .reveal-delay-1 { transition-delay: 0.1s; }
        .reveal-delay-2 { transition-delay: 0.2s; }
        .reveal-delay-3 { transition-delay: 0.3s; }
        .reveal-delay-4 { transition-delay: 0.4s; }

        /* ===== RESPONSIVE ===== */
        @media (max-width: 768px) {
            .navbar {
                padding: 12px 20px;
            }

            .nav-links {
                position: fixed;
                top: 0;
                right: -100%;
                width: 70%;
                height: 100vh;
                background: rgba(7, 7, 26, 0.98);
                backdrop-filter: blur(20px);
                flex-direction: column;
                justify-content: center;
                align-items: center;
                transition: right 0.4s ease;
                z-index: 999;
                border-left: 1px solid rgba(0, 229, 255, 0.1);
            }

            .nav-links.open {
                right: 0;
            }

            .hamburger {
                display: flex;
            }

            .about-grid {
                grid-template-columns: 1fr;
            }

            .about-image {
                order: -1;
            }

            .about-stats {
                grid-template-columns: repeat(3, 1fr);
            }

            .countdown {
                gap: 15px;
            }

            .countdown-sep {
                display: none;
            }

            .register-card {
                padding: 30px 20px;
            }

            .modal-content {
                padding: 35px 25px;
            }

            .timeline::before {
                left: 20px;
            }

            .timeline-dot {
                margin-left: 11px;
            }
        }

        @media (max-width: 480px) {
            .about-stats {
                grid-template-columns: 1fr;
            }

            .skills-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <!-- NAVBAR -->
    <nav class="navbar" id="navbar">
        <a href="#" class="nav-logo">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2"></polygon>
            </svg>
            AI-Мастерская
        </a>
        <ul class="nav-links" id="navLinks">
            <li><a href="#about" onclick="closeMenu()">О мероприятии</a></li>
            <li><a href="#program" onclick="closeMenu()">Программа</a></li>
            <li><a href="#skills" onclick="closeMenu()">Навыки</a></li>
            <li><a href="#speakers" onclick="closeMenu()">Спикеры</a></li>
            <li><a href="#faq" onclick="closeMenu()">FAQ</a></li>
            <li><a href="#register" class="nav-cta" onclick="closeMenu()">Регистрация</a></li>
        </ul>
        <div class="hamburger" id="hamburger" onclick="toggleMenu()">
            <span></span>
            <span></span>
            <span></span>
        </div>
    </nav>

    <!-- HERO -->
    <section class="hero" id="hero">
        <canvas class="hero-canvas" id="particleCanvas"></canvas>
        <div class="hero-overlay"></div>
        <div class="hero-content">
            <div class="hero-badge">
                <span class="pulse-dot"></span>
                Воркшоп 2026
            </div>
            <h1>AI-Мастерская</h1>
            <p class="hero-subtitle">Создай своё первое ИИ-мероприятие за один день</p>
            <p class="hero-date">📅 20 апреля 2026 • 📍 Главный корпус, ауд. 305</p>
            <div class="hero-buttons">
                <a href="#register" class="btn-primary">
                    Зарегистрироваться
                    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"></line><polyline points="12 5 19 12 12 19"></polyline></svg>
                </a>
                <a href="#program" class="btn-secondary">
                    Программа
                    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="6 9 12 15 18 9"></polyline></svg>
                </a>
            </div>
        </div>
        <div class="scroll-indicator">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="6 9 12 15 18 9"></polyline></svg>
        </div>
    </section>

    <!-- COUNTDOWN -->
    <div class="countdown-section">
        <div class="countdown" id="countdown">
            <div class="countdown-item">
                <div class="countdown-value" id="countDays">00</div>
                <div class="countdown-label">дней</div>
            </div>
            <div class="countdown-sep">:</div>
            <div class="countdown-item">
                <div class="countdown-value" id="countHours">00</div>
                <div class="countdown-label">часов</div>
            </div>
            <div class="countdown-sep">:</div>
            <div class="countdown-item">
                <div class="countdown-value" id="countMinutes">00</div>
                <div class="countdown-label">минут</div>
            </div>
            <div class="countdown-sep">:</div>
            <div class="countdown-item">
                <div class="countdown-value" id="countSeconds">00</div>
                <div class="countdown-label">секунд</div>
            </div>
        </div>
    </div>

    <!-- ABOUT -->
    <section class="section" id="about">
        <div class="container">
            <div class="section-header reveal">
                <h2>О <span>мероприятии</span></h2>
                <div class="section-divider"></div>
                <p>Четыре часа интенсивной практики с нейросетями</p>
            </div>
            <div class="about-grid">
                <div class="about-text reveal">
                    <p>Ты когда-нибудь хотел создать крутую афишу, написать идеальный текст для проекта или даже сверстать сайт, но не знал, с чего начать? Пришло время разрушить мифы!</p>
                    <p>За четыре часа ты не просто услышишь теорию, а своими руками создашь готовые продукты: от визуального контента до работающего веб-макета. Не важно, гуманитарий ты или технарь — ИИ говорит на языке идей.</p>
                    <p>Мы верим, что каждый может использовать искусственный интеллект для творчества. Приходи и убедись сам!</p>
                </div>
                <div class="about-image reveal reveal-delay-2">
                    <div class="about-image-inner">
                        <div class="about-visual"></div>
                        <div class="about-icon-center">
                            <svg viewBox="0 0 120 120" fill="none">
                                <defs>
                                    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%">
                                        <stop offset="0%" style="stop-color:#00e5ff;stop-opacity:1" />
                                        <stop offset="100%" style="stop-color:#7c4dff;stop-opacity:1" />
                                    </linearGradient>
                                </defs>
                                <circle cx="60" cy="60" r="50" stroke="url(#grad1)" stroke-width="2" fill="none" opacity="0.3"/>
                                <circle cx="60" cy="60" r="35" stroke="url(#grad1)" stroke-width="1.5" fill="none" opacity="0.5"/>
                                <circle cx="60" cy="60" r="20" stroke="url(#grad1)" stroke-width="1" fill="none" opacity="0.7"/>
                                <path d="M45 60 L60 45 L75 60 L60 75 Z" fill="url(#grad1)" opacity="0.6"/>
                                <circle cx="60" cy="60" r="5" fill="#00e5ff"/>
                                <line x1="60" y1="20" x2="60" y2="35" stroke="#00e5ff" stroke-width="1.5" opacity="0.5"/>
                                <line x1="60" y1="85" x2="60" y2="100" stroke="#00e5ff" stroke-width="1.5" opacity="0.5"/>
                                <line x1="20" y1="60" x2="35" y2="60" stroke="#7c4dff" stroke-width="1.5" opacity="0.5"/>
                                <line x1="85" y1="60" x2="100" y2="60" stroke="#7c4dff" stroke-width="1.5" opacity="0.5"/>
                            </svg>
                        </div>
                    </div>
                </div>
            </div>
            <div class="about-stats reveal reveal-delay-3">
                <div class="stat-item">
                    <div class="stat-number">4</div>
                    <div class="stat-label">часа практики</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">4</div>
                    <div class="stat-label">тематических блока</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">∞</div>
                    <div class="stat-label">возможностей</div>
                </div>
            </div>
        </div>
    </section>

    <!-- PROGRAM -->
    <section class="section program-section" id="program">
        <div class="container">
            <div class="section-header reveal">
                <h2>Программа <span>дня</span></h2>
                <div class="section-divider"></div>
                <p>Четыре насыщенных блока от теории к практике</p>
            </div>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <div class="timeline-time">10:00 – 10:45</div>
                        <div class="timeline-title">Блок 1. ИИ без магии</div>
                        <div class="timeline-desc">Ликбез по нейросетям: как они работают, что умеют и где их границы. Разберёмся с этикой и ответственностью при использовании ИИ.</div>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <div class="timeline-time">10:45 – 11:45</div>
                        <div class="timeline-title">Блок 2. Магия слов</div>
                        <div class="timeline-desc">Основы промпт-инжиниринга: Zero-shot, Few-shot, Chain of Thought. Научимся писать запросы, которые ИИ понимает с полуслова.</div>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <div class="timeline-time">12:00 – 13:00</div>
                        <div class="timeline-title">Блок 3. Визуализация</div>
                        <div class="timeline-desc">Генерация изображений в Kandinsky и Midjourney. Создадим афишу мероприятия, логотип и иллюстрации — всё с помощью ИИ.</div>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <div class="timeline-time">13:00 – 13:45</div>
                        <div class="timeline-title">Блок 4. ИИ-разработчик</div>
                        <div class="timeline-desc">Создаём простой лендинг кодом из ИИ. Даже если вы никогда не видели код — к концу блока у вас будет работающий веб-макет.</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SKILLS -->
    <section class="section" id="skills">
        <div class="container">
            <div class="section-header reveal">
                <h2>Чему вы <span>научитесь</span></h2>
                <div class="section-divider"></div>
                <p>Навыки, которые останутся с вами надолго</p>
            </div>
            <div class="skills-grid">
                <div class="skill-card reveal reveal-delay-1">
                    <div class="skill-icon">
                        <svg viewBox="0 0 24 24" fill="none" stroke="#00e5ff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"></path></svg>
                    </div>
                    <h3>Промпт-инжиниринг</h3>
                    <p>Писать промпты, которые понимают с полуслова. Освоите техники Zero-shot и Few-shot.</p>
                </div>
                <div class="skill-card reveal reveal-delay-2">
                    <div class="skill-icon">
                        <svg viewBox="0 0 24 24" fill="none" stroke="#7c4dff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="2" ry="2"></rect><circle cx="8.5" cy="8.5" r="1.5"></circle><polyline points="21 15 16 10 5 21"></polyline></svg>
                    </div>
                    <h3>Генерация изображений</h3>
                    <p>Создавать профессиональные изображения без навыков дизайна. Kandinsky, Midjourney и другие.</p>
                </div>
                <div class="skill-card reveal reveal-delay-3">
                    <div class="skill-icon">
                        <svg viewBox="0 0 24 24" fill="none" stroke="#00e5ff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="16 18 22 12 16 6"></polyline><polyline points="8 6 2 12 8 18"></polyline></svg>
                    </div>
                    <h3>ИИ-разработка</h3>
                    <p>Верстать простые сайты, даже если никогда не видели код. ИИ станет вашим помощником-программистом.</p>
                </div>
                <div class="skill-card reveal reveal-delay-4">
                    <div class="skill-icon">
                        <svg viewBox="0 0 24 24" fill="none" stroke="#7c4dff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path></svg>
                    </div>
                    <h3>Этичное использование</h3>
                    <p>Использовать ИИ этично и эффективно в учёбе и проектах. Понимать ограничения и риски.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- SPEAKERS -->
    <section class="section speakers-section" id="speakers">
        <div class="container">
            <div class="section-header reveal">
                <h2>Ваши <span>спикеры</span></h2>
                <div class="section-divider"></div>
                <p>Эксперты, которые проведут вас через мир ИИ</p>
            </div>
            <div class="speakers-grid">
                <div class="speaker-card reveal reveal-delay-1">
                    <div class="speaker-avatar">
                        <div class="speaker-avatar-placeholder">
                            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                        </div>
                    </div>
                    <div class="speaker-info">
                        <div class="speaker-name">Алексей Нейронов</div>
                        <div class="speaker-role">ML-инженер</div>
                        <div class="speaker-bio">5+ лет в машинном обучении. Ведёт блок «ИИ без магии» и «Магия слов».</div>
                    </div>
                </div>
                <div class="speaker-card reveal reveal-delay-2">
                    <div class="speaker-avatar">
                        <div class="speaker-avatar-placeholder">
                            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                        </div>
                    </div>
                    <div class="speaker-info">
                        <div class="speaker-name">Мария Визуалова</div>
                        <div class="speaker-role">AI-художник</div>
                        <div class="speaker-bio">Профессиональный генеративный дизайнер. Проведёт блок «Визуализация».</div>
                    </div>
                </div>
                <div class="speaker-card reveal reveal-delay-3">
                    <div class="speaker-avatar">
                        <div class="speaker-avatar-placeholder">
                            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                        </div>
                    </div>
                    <div class="speaker-info">
                        <div class="speaker-name">Дмитрий Кодофф</div>
                        <div class="speaker-role">Fullstack-разработчик</div>
                        <div class="speaker-bio">Фуллстек с опытом в AI-интеграциях. Научит создавать сайты через ИИ.</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section class="section" id="faq">
        <div class="container">
            <div class="section-header reveal">
                <h2>Частые <span>вопросы</span></h2>
                <div class="section-divider"></div>
            </div>
            <div class="faq-list reveal">
                <div class="faq-item">
                    <div class="faq-question" onclick="toggleFaq(this)">
                        Нужны ли знания программирования?
                        <span class="faq-icon">+</span>
                    </div>
                    <div class="faq-answer">
                        <div class="faq-answer-inner">Нет! Воркшоп подходит для всех уровней. Мы начинаем с самых основ и постепенно переходим к практике. Даже если вы никогда не видели код, к концу воркшопа у вас будет готовый лендинг.</div>
                    </div>
                </div>
                <div class="faq-item">
                    <div class="faq-question" onclick="toggleFaq(this)">
                        Нужно ли приносить свой ноутбук?
                        <span class="faq-icon">+</span>
                    </div>
                    <div class="faq-answer">
                        <div class="faq-answer-inner">Желательно, но не обязательно. Все используемые сервисы работают в браузере. Если ноутбука нет — сообщите при регистрации, мы предоставим оборудование.</div>
                    </div>
                </div>
                <div class="faq-item">
                    <div class="faq-question" onclick="toggleFaq(this)">
                        Будет ли сертификат об участии?
                        <span class="faq-icon">+</span>
                    </div>
                    <div class="faq-answer">
                        <div class="faq-answer-inner">Да! Все участники получат электронный сертификат с указанием пройденной программы. Его можно добавить в портфолио или CV.</div>
                    </div>
                </div>
                <div class="faq-item">
                    <div class="faq-question" onclick="toggleFaq(this)">
                        Воркшоп бесплатный?
                        <span class="faq-icon">+</span>
                    </div>
                    <div class="faq-answer">
                        <div class="faq-answer-inner">Да, участие полностью бесплатное! Мы хотим сделать ИИ-грамотность доступной для всех. Количество мест ограничено, поэтому рекомендуем зарегистрироваться заранее.</div>
                    </div>
                </div>
                <div class="faq-item">
                    <div class="faq-question" onclick="toggleFaq(this)">
                        Запишут ли воркшоп?
                        <span class="faq-icon">+</span>
                    </div>
                    <div class="faq-answer">
                        <div class="faq-answer-inner">Да, мы ведём видеозапись. Все материалы и записи будут доступны зарегистрированным участникам в течение 7 дней после мероприятия.</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- REGISTER -->
    <section class="section register-section" id="register">
        <div class="container">
            <div class="section-header reveal">
                <h2>Регистрация <span>на воркшоп</span></h2>
                <div class="section-divider"></div>
                <p>Количество мест ограничено — успейте записаться!</p>
            </div>
            <div class="register-container reveal">
                <div class="register-card">
                    <div class="register-info">
                        <div class="register-info-item">
                            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg>
                            20 апреля 2026, 10:00 – 13:45
                        </div>
                        <div class="register-info-item">
                            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"></path><circle cx="12" cy="10" r="3"></circle></svg>
                            Главный корпус, ауд. 305
                        </div>
                        <div class="register-info-item">
                            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>
                            4 часа интенсивной практики
                        </div>
                    </div>
                    <form id="registerForm" onsubmit="handleSubmit(event)">
                        <div class="form-group">
                            <label for="name">Имя и фамилия</label>
                            <input type="text" id="name" name="name" placeholder="Иван Иванов" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="email" id="email" name="email" placeholder="ivan@example.com" required>
                        </div>
                        <div class="form-group">
                            <label for="phone">Телефон</label>
                            <input type="tel" id="phone" name="phone" placeholder="+7 (999) 123-45-67">
                        </div>
                        <div class="form-group">
                            <label for="experience">Уровень подготовки</label>
                            <select id="experience" name="experience">
                                <option value="beginner">Новичок — ничего не знаю про ИИ</option>
                                <option value="basic">Базовый — пробовал(а) ChatGPT</option>
                                <option value="intermediate">Средний — работаю с ИИ регулярно</option>
                            </select>
                        </div>
                        <button type="submit" class="form-submit" id="submitBtn">
                            Подать заявку
                        </button>
                        <div class="form-message" id="formMessage"></div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer>
        <div class="footer-logo">AI-Мастерская</div>
        <div class="footer-links">
            <a href="#about">О мероприятии</a>
            <a href="#program">Программа</a>
            <a href="#register">Регистрация</a>
        </div>
        <p class="footer-text">© 2026 AI-Мастерская. Проект создан студентами Школы 21.</p>
    </footer>

    <!-- SUCCESS MODAL -->
    <div class="modal-overlay" id="successModal">
        <div class="modal-content">
            <button class="modal-close" onclick="closeModal()">&times;</button>
            <div class="modal-icon">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg>
            </div>
            <h3>Заявка отправлена! 🎉</h3>
            <p>Мы свяжемся с вами по email для подтверждения. До встречи на воркшопе!</p>
        </div>
    </div>

    <script>
        // ===== PARTICLE CANVAS =====
        const canvas = document.getElementById('particleCanvas');
        const ctx = canvas.getContext('2d');
        let particles = [];
        let animationId;

        function resizeCanvas() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        }

        resizeCanvas();
        window.addEventListener('resize', resizeCanvas);

        class Particle {
            constructor() {
                this.reset();
            }

            reset() {
                this.x = Math.random() * canvas.width;
                this.y = Math.random() * canvas.height;
                this.size = Math.random() * 2 + 0.5;
                this.speedX = (Math.random() - 0.5) * 0.5;
                this.speedY = (Math.random() - 0.5) * 0.5;
                this.opacity = Math.random() * 0.5 + 0.1;
                this.hue = Math.random() > 0.5 ? 185 : 270;
            }

            update() {
                this.x += this.speedX;
                this.y += this.speedY;

                if (this.x < 0 || this.x > canvas.width) this.speedX *= -1;
                if (this.y < 0 || this.y > canvas.height) this.speedY *= -1;
            }

            draw() {
                ctx.beginPath();
                ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
                ctx.fillStyle = `hsla(${this.hue}, 100%, 70%, ${this.opacity})`;
                ctx.fill();
            }
        }

        function initParticles() {
            const count = Math.min(Math.floor((canvas.width * canvas.height) / 12000), 120);
            particles = [];
            for (let i = 0; i < count; i++) {
                particles.push(new Particle());
            }
        }

        function drawConnections() {
            for (let i = 0; i < particles.length; i++) {
                for (let j = i + 1; j < particles.length; j++) {
                    const dx = particles[i].x - particles[j].x;
                    const dy = particles[i].y - particles[j].y;
                    const dist = Math.sqrt(dx * dx + dy * dy);

                    if (dist < 150) {
                        const opacity = (1 - dist / 150) * 0.15;
                        ctx.beginPath();
                        ctx.moveTo(particles[i].x, particles[i].y);
                        ctx.lineTo(particles[j].x, particles[j].y);
                        ctx.strokeStyle = `rgba(0, 229, 255, ${opacity})`;
                        ctx.lineWidth = 0.5;
                        ctx.stroke();
                    }
                }
            }
        }

        function animateParticles() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            particles.forEach(p => {
                p.update();
                p.draw();
            });
            drawConnections();
            animationId = requestAnimationFrame(animateParticles);
        }

        initParticles();
        animateParticles();

        // ===== NAVBAR SCROLL =====
        window.addEventListener('scroll', () => {
            const navbar = document.getElementById('navbar');
            if (window.scrollY > 50) {
                navbar.classList.add('scrolled');
            } else {
                navbar.classList.remove('scrolled');
            }
        });

        // ===== MOBILE MENU =====
        function toggleMenu() {
            document.getElementById('hamburger').classList.toggle('active');
            document.getElementById('navLinks').classList.toggle('open');
        }

        function closeMenu() {
            document.getElementById('hamburger').classList.remove('active');
            document.getElementById('navLinks').classList.remove('open');
        }

        // ===== COUNTDOWN =====
        function updateCountdown() {
            const target = new Date('2026-04-20T10:00:00').getTime();
            const now = new Date().getTime();
            const diff = target - now;

            if (diff <= 0) {
                document.getElementById('countDays').textContent = '00';
                document.getElementById('countHours').textContent = '00';
                document.getElementById('countMinutes').textContent = '00';
                document.getElementById('countSeconds').textContent = '00';
                return;
            }

            const days = Math.floor(diff / (1000 * 60 * 60 * 24));
            const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((diff % (1000 * 60)) / 1000);

            document.getElementById('countDays').textContent = String(days).padStart(2, '0');
            document.getElementById('countHours').textContent = String(hours).padStart(2, '0');
            document.getElementById('countMinutes').textContent = String(minutes).padStart(2, '0');
            document.getElementById('countSeconds').textContent = String(seconds).padStart(2, '0');
        }

        updateCountdown();
        setInterval(updateCountdown, 1000);

        // ===== SCROLL REVEAL =====
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

        document.querySelectorAll('.reveal, .timeline-item').forEach(el => {
            observer.observe(el);
        });

        // ===== FAQ =====
        function toggleFaq(element) {
            const item = element.parentElement;
            const isActive = item.classList.contains('active');

            document.querySelectorAll('.faq-item').forEach(i => i.classList.remove('active'));

            if (!isActive) {
                item.classList.add('active');
            }
        }

        // ===== FORM =====
        function handleSubmit(e) {
            e.preventDefault();
            const btn = document.getElementById('submitBtn');
            const msg = document.getElementById('formMessage');
            const name = document.getElementById('name').value.trim();
            const email = document.getElementById('email').value.trim();

            if (!name || !email) {
                msg.textContent = 'Пожалуйста, заполните все обязательные поля.';
                msg.className = 'form-message show error';
                return;
            }

            btn.disabled = true;
            btn.textContent = 'Отправка...';

            setTimeout(() => {
                btn.disabled = false;
                btn.textContent = 'Подать заявку';
                document.getElementById('successModal').classList.add('active');
                document.getElementById('registerForm').reset();
                msg.className = 'form-message';
            }, 1500);
        }

        // ===== MODAL =====
        function closeModal() {
            document.getElementById('successModal').classList.remove('active');
        }

        document.getElementById('successModal').addEventListener('click', (e) => {
            if (e.target === document.getElementById('successModal')) {
                closeModal();
            }
        });

        // ===== SMOOTH SCROLL FOR ANCHORS =====
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    e.preventDefault();
                    const offset = 80;
                    const top = target.getBoundingClientRect().top + window.pageYOffset - offset;
                    window.scrollTo({ top, behavior: 'smooth' });
                }
            });
        });
    </script>

</body>
</html>
