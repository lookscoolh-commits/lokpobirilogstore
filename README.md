# lokpobirilogstore
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lokpobirilogstore - Your Trusted Source for Social Media Accounts</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0a0a0a;
            color: #ffffff;
            line-height: 1.6;
        }

        /* Header / Logo Section */
        .logo-section {
            background-color: #f5f5f5;
            padding: 60px 20px;
            text-align: center;
        }

        .logo-container {
            max-width: 600px;
            margin: 0 auto;
        }

        .logo-icon {
            width: 200px;
            height: 200px;
            margin: 0 auto 20px;
            background: linear-gradient(135deg, #001a4d 0%, #003d99 100%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            box-shadow: 0 10px 40px rgba(0, 61, 153, 0.3);
        }

        .logo-icon::before {
            content: "L";
            font-size: 80px;
            font-weight: 900;
            color: #ffffff;
            font-family: 'Arial Black', sans-serif;
        }

        .logo-icon::after {
            content: "";
            position: absolute;
            width: 60px;
            height: 60px;
            background: #ffffff;
            border-radius: 50%;
            right: 40px;
            top: 50%;
            transform: translateY(-50%);
            box-shadow: inset -5px -5px 10px rgba(0,0,0,0.1);
        }

        .brand-name {
            font-size: 48px;
            font-weight: 900;
            color: #001a4d;
            letter-spacing: 4px;
            text-transform: uppercase;
            margin-top: 20px;
        }

        .brand-sub {
            font-size: 18px;
            color: #333;
            letter-spacing: 12px;
            text-transform: uppercase;
            margin-top: 5px;
        }

        /* About Section */
        .about-section {
            background-color: #ffffff;
            color: #333;
            padding: 80px 20px;
            text-align: center;
        }

        .about-container {
            max-width: 900px;
            margin: 0 auto;
        }

        .about-section h2 {
            font-size: 16px;
            text-transform: uppercase;
            letter-spacing: 3px;
            color: #666;
            margin-bottom: 10px;
        }

        .about-section h1 {
            font-size: 36px;
            color: #001a4d;
            margin-bottom: 30px;
            font-weight: 700;
        }

        .about-section p {
            font-size: 18px;
            color: #555;
            line-height: 1.8;
            margin-bottom: 20px;
        }

        /* Features Grid */
        .features-section {
            background-color: #0a0a0a;
            padding: 60px 20px;
        }

        .features-grid {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .feature-card {
            background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
            border-radius: 15px;
            padding: 40px 30px;
            text-align: center;
            border: 1px solid rgba(255,255,255,0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0, 61, 153, 0.2);
        }

        .feature-icon {
            width: 60px;
            height: 60px;
            background: linear-gradient(135deg, #003d99 0%, #0066cc 100%);
            border-radius: 50%;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
        }

        .feature-card h3 {
            font-size: 20px;
            margin-bottom: 10px;
            color: #fff;
        }

        .feature-card p {
            color: #aaa;
            font-size: 14px;
        }

        /* Services Banner */
        .services-banner {
            background: linear-gradient(135deg, #001a4d 0%, #003d99 50%, #0066cc 100%);
            padding: 80px 20px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .services-banner::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><circle cx="50" cy="50" r="40" fill="none" stroke="rgba(255,255,255,0.1)" stroke-width="0.5"/></svg>');
            background-size: 50px 50px;
            opacity: 0.3;
        }

        .services-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
            margin: 0 auto;
        }

        .services-banner h2 {
            font-size: 42px;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .services-banner p {
            font-size: 20px;
            opacity: 0.9;
        }

        /* Platform Icons */
        .platforms-section {
            background-color: #0f0f0f;
            padding: 60px 20px;
            text-align: center;
        }

        .platforms-grid {
            max-width: 1000px;
            margin: 0 auto;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 40px;
        }

        .platform-item {
            width: 80px;
            height: 80px;
            background: #1a1a1a;
            border-radius: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 36px;
            transition: all 0.3s ease;
            border: 2px solid transparent;
        }

        .platform-item:hover {
            transform: scale(1.1);
            border-color: #0066cc;
            background: #1a1a2e;
        }

        /* Contact Section */
        .contact-section {
            background-color: #ffffff;
            color: #333;
            padding: 80px 20px;
            text-align: center;
        }

        .contact-container {
            max-width: 600px;
            margin: 0 auto;
        }

        .contact-section h2 {
            font-size: 36px;
            color: #001a4d;
            margin-bottom: 20px;
        }

        .contact-section p {
            font-size: 18px;
            color: #666;
            margin-bottom: 30px;
        }

        .contact-btn {
            display: inline-block;
            padding: 15px 40px;
            background: linear-gradient(135deg, #001a4d 0%, #003d99 100%);
            color: #fff;
            text-decoration: none;
            border-radius: 50px;
            font-size: 18px;
            font-weight: 600;
            transition: all 0.3s ease;
            box-shadow: 0 10px 30px rgba(0, 61, 153, 0.3);
        }

        .contact-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(0, 61, 153, 0.4);
        }

        /* Footer */
        footer {
            background-color: #000;
            color: #666;
            text-align: center;
            padding: 30px 20px;
            font-size: 14px;
        }

        footer span {
            color: #0066cc;
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .animate {
            animation: fadeInUp 0.8s ease forwards;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .brand-name {
                font-size: 32px;
            }
            
            .about-section h1 {
                font-size: 28px;
            }
            
            .services-banner h2 {
                font-size: 32px;
            }
        }
    </style>
</head>
<body>

    <!-- Logo / Hero Section -->
    <section class="logo-section">
        <div class="logo-container">
            <div class="logo-icon"></div>
            <div class="brand-name">LOKPOBIRILOG</div>
            <div class="brand-sub">STORE</div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about-section">
        <div class="about-container">
            <h2>About Us</h2>
            <h1>Providing You with Secure, Authentic Logins.</h1>
            <p>
                With <strong>Lokpobirilogstore</strong>, users can browse through a wide range of social media accounts for sale, 
                including accounts on popular platforms such as Instagram, Facebook, Twitter, and YouTube. The platform ensures 
                that all accounts are verified and authentic, giving buyers peace of mind that they are getting a quality account.
            </p>
            <p>
                At <strong>Lokpobirilogstore</strong>, our mission is to help you grow your social media influence easily and securely. 
                No matter your goal, we're here to provide you with the tools you need to succeed.
            </p>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features-section">
        <div class="features-grid">
            <div class="feature-card">
                <div class="feature-icon">🔐</div>
                <h3>Expert in Account Logs</h3>
                <p>Premium quality accounts with full access and credentials</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">🛡️</div>
                <h3>Secure Transactions</h3>
                <p>Encrypted and safe payment processing guaranteed</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">⚡</div>
                <h3>Fast Delivery</h3>
                <p>Instant delivery of account details after purchase</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">📊</div>
                <h3>Diverse Options</h3>
                <p>Wide variety of accounts across all major platforms</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">💰</div>
                <h3>Affordable Pricing</h3>
                <p>Competitive rates for every budget and need</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">🎧</div>
                <h3>Exceptional Support</h3>
                <p>24/7 customer support for all your inquiries</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">📱</div>
                <h3>SMS Verification Site</h3>
                <p>Reliable SMS verification services available</p>
            </div>
            <div class="feature-card">
                <div class="feature-icon">✉️</div>
                <h3>SMS Services</h3>
                <p>Virtual number services for verification needs</p>
            </div>
        </div>
    </section>

    <!-- Services Banner -->
    <section class="services-banner">
        <div class="services-content">
            <h2>Social Media Management</h2>
            <p>Boost your online presence with our premium account solutions and strategic social media growth services.</p>
        </div>
    </section>

    <!-- Platforms Section -->
    <section class="platforms-section">
        <div class="platforms-grid">
            <div class="platform-item" title="Instagram">📷</div>
            <div class="platform-item" title="Facebook">👍</div>
            <div class="platform-item" title="Twitter/X">🐦</div>
            <div class="platform-item" title="YouTube">▶️</div>
            <div class="platform-item" title="TikTok">🎵</div>
            <div class="platform-item" title="LinkedIn">💼</div>
            <div class="platform-item" title="Pinterest">📌</div>
            <div class="platform-item" title="Snapchat">👻</div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact-section">
        <div class="contact-container">
            <h2>Get In Touch</h2>
            <p>Ready to grow your social media presence? Contact us today and let's get started.</p>
            <a href="#" class="contact-btn">Contact Us</a>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2024 <span>Lokpobirilogstore</span>. All rights reserved. Your Trusted Source for Social Media Accounts.</p>
    </footer>

    <script>
        // Simple scroll animation
        const observerOptions = {
            threshold: 0.1,
            rootMargin: "0px 0px -50px 0px"
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('animate');
                }
            });
        }, observerOptions);

        document.querySelectorAll('.feature-card, .platform-item').forEach(el => {
            el.style.opacity = '0';
            observer.observe(el);
        });
    </script>

</body>
</html>
