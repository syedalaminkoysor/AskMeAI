<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Our AI Architecture Services | AskMeAI</title>  
    <link rel="preconnect" href="https://googleapis.com">  
    <link rel="preconnect" href="https://gstatic.com" crossorigin>  
    <link href="https://googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">  
    <style>  
        :root {  
            --bg-main: #060913;  
            --bg-card: #0f1526;  
            --border-color: #1e293b;  
            --text-primary: #ffffff;  
            --text-secondary: #94a3b8;  
            --accent-blue: #3b82f6;  
            --font-stack: 'Plus Jakarta Sans', sans-serif;  
        }  
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: var(--font-stack); }  
        body { background-color: var(--bg-main); color: var(--text-primary); padding: 20px; display: flex; flex-direction: column; align-items: center; min-height: 100vh; }  
        .header-bar { max-width: 720px; width: 100%; display: flex; justify-content: space-between; align-items: center; padding: 15px 0; margin-bottom: 20px; position: relative; }  
        .logo-area { display: flex; align-items: center; gap: 8px; font-weight: 800; font-size: 1.2rem; color: var(--text-primary); text-decoration: none; }  
        .logo-dot { width: 8px; height: 8px; background: var(--accent-blue); border-radius: 50%; }  
        .menu-trigger { background: none; border: none; color: var(--text-secondary); font-size: 1.3rem; cursor: pointer; padding: 8px; }  
        .dropdown-panel { position: absolute; top: 65px; right: 0; width: 220px; background: var(--bg-card); border: 1px solid var(--border-color); border-radius: 12px; padding: 8px; display: none; z-index: 100; }  
        .dropdown-panel.active { display: block; }  
        .dropdown-panel a { display: block; padding: 12px 14px; color: var(--text-secondary); text-decoration: none; font-size: 0.95rem; }  
        .dropdown-panel a:hover { background: #1e293b; color: var(--text-primary); }  
        .container { max-width: 720px; width: 100%; background: var(--bg-card); border: 1px solid var(--border-color); border-radius: 16px; padding: 40px 24px; }  
        .nav-back { color: var(--accent-blue); font-size: 0.9rem; text-decoration: none; display: block; margin-bottom: 20px; }  
        h1 { font-size: 2rem; margin-bottom: 12px; font-weight: 800; letter-spacing: -0.03em; }  
        .subtitle { font-size: 1.05rem; color: var(--text-secondary); margin-bottom: 30px; }  
        .service-block { border-bottom: 1px solid var(--border-color); padding-bottom: 20px; margin-bottom: 20px; }  
        .service-block:last-of-type { border-bottom: none; }  
        .service-meta { background: rgba(59, 130, 246, 0.1); color: var(--accent-blue); font-size: 0.7rem; font-weight: 700; padding: 2px 8px; border-radius: 4px; text-transform: uppercase; }  
        .service-title { font-size: 1.25rem; font-weight: 700; margin: 8px 0; }  
        .service-desc { color: var(--text-secondary); font-size: 0.95rem; margin-bottom: 12px; }  
        .spec-item { font-size: 0.85rem; color: #cbd5e1; margin-bottom: 6px; display: flex; align-items: center; }  
        .spec-item::before { content: "▪"; color: #10b981; margin-right: 8px; }  
        .email-cta-box { background: rgba(59, 130, 246, 0.06); border: 1px solid rgba(59, 130, 246, 0.2); padding: 20px; border-radius: 8px; text-align: center; margin-top: 20px; }  
        .cta-label { font-size: 0.75rem; text-transform: uppercase; color: var(--text-secondary); font-weight: 600; margin-bottom: 6px; }  
        .cta-email-link { font-size: 1.25rem; color: var(--accent-blue); text-decoration: none; font-weight: 700; }  
        .footer { font-size: 0.8rem; color: #64748b; border-top: 1px solid var(--border-color); padding-top: 20px; text-align: center; margin-top: 30px; }  
    </style>  
</head>  
<body>  
    <header class="header-bar">  
        <a href="index.html" class="logo-area"><span class="logo-dot"></span>AskMeAI</a>  
        <button class="menu-trigger" id="menuBtn">☰</button>  
        <div class="dropdown-panel" id="menuDropdown">  
            <a href="index.html">🏠 Home Overview</a>  
            <a href="services.html">🛠️ System Architecture</a>  
            <a href="mailto:hello@askmeai.co.uk">📧 Direct Support Inbox</a>  
        </div>  
    </header>  
    <main class="container">  
        <a href="index.html" class="nav-back">← Back to Overview</a>  
        <h1>Enterprise AI Capabilities</h1>  
        <p class="subtitle">Secure integration models engineered to connect natural language models directly with your custom system databases.</p>  
        <div class="service-block">  
            <span class="service-meta">Core Matrix 01</span>  
            <div class="service-title">Secure Transactional Automation</div>  
            <p class="service-desc">We build authenticated communication lines that pull directly from your CRM or data storehouses to fulfill routine customer lookups instantly.</p>  
            <div class="spec-item">Real-time order tracking status mapping</div>  
            <div class="spec-item">Custom webhook payload sanitization</div>  
        </div>  
        <div class="service-block">  
            <span class="service-meta">Core Matrix 02</span>  
            <div class="service-title">Two-Factor Identity Engineering</div>  
            <p class="service-desc">Protecting confidential client information is an absolute operational requirement behind verification triggers.</p>  
            <div class="spec-item">Instant One-Time Password (OTP) validation routing</div>  
            <div class="spec-item">UK GDPR compliant data sandbox handling</div>  
        </div>  
        <div class="email-cta-box">  
            <div class="cta-label">Request Bespoke System Integration Statement</div>  
            <a href="mailto:hello@askmeai.co.uk" class="cta-email-link">hello@askmeai.co.uk</a>  
        </div>  
        <footer class="footer"><p>© 2026 AskMeAI. All architecture operates behind TLS 1.3 encryption.</p></footer>  
    </main>  
    <script>  
        const menuBtn = document.getElementById('menuBtn');  
        const menuDropdown = document.getElementById('menuDropdown');  
        menuBtn.addEventListener('click', (e) => { e.stopPropagation(); menuDropdown.classList.toggle('active'); });  
        document.addEventListener('click', () => { menuDropdown.classList.remove('active'); });  
    </script>  
  
    <!-- Voiceflow Webchat Integration Widget -->  
    <script type="text/javascript">  
      (function(d, t) {  
          var v = d.createElement(t), s = d.getElementsByTagName(t);  
          v.onload = function() {  
            window.voiceflow.chat.load({  
              verify: { projectID: '6a64b39235227746506e25f0' },  
              url: 'https://voiceflow.com',  
              versionID: 'production'  
            });  
          }  
          v.src = "https://voiceflow.com"; v.type = "text/javascript"; s.parentNode.insertBefore(v, s);  
      })(document, 'script');  
    </script>  
</body>  
</html>  
