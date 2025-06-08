<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🔐 NEXUS PRIME™ - Secret Key Vault</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Courier New', monospace;
            background: linear-gradient(135deg, #0c0c0c 0%, #1a1a2e 50%, #16213e 100%);
            min-height: 100vh;
            color: #00ff00;
            overflow-x: hidden;
        }
        
        .vault-container {
            position: relative;
            z-index: 2;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .vault-header {
            text-align: center;
            padding: 40px 0;
            border: 2px solid #00ff00;
            border-radius: 10px;
            margin-bottom: 30px;
            background: rgba(0, 255, 0, 0.05);
        }
        
        .vault-title {
            font-size: 2.5em;
            color: #00ff00;
            text-shadow: 0 0 10px #00ff00;
            margin-bottom: 10px;
            animation: glow 2s ease-in-out infinite alternate;
        }
        
        @keyframes glow {
            0% { text-shadow: 0 0 10px #00ff00; }
            100% { text-shadow: 0 0 20px #00ff00, 0 0 30px #00ff00; }
        }
        
        .vault-section {
            background: rgba(0, 255, 0, 0.05);
            border: 2px solid #00ff00;
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 30px;
        }
        
        .section-title {
            color: #4ecdc4;
            font-size: 1.5em;
            margin-bottom: 20px;
            text-align: center;
        }
        
        .key-item {
            background: rgba(0, 0, 0, 0.7);
            border: 1px solid #333;
            border-radius: 5px;
            padding: 15px;
            margin-bottom: 15px;
        }
        
        .key-label {
            color: #f9ca24;
            font-weight: bold;
            margin-bottom: 8px;
        }
        
        .key-value {
            color: #00ff00;
            font-family: 'Courier New', monospace;
            background: rgba(0, 0, 0, 0.8);
            padding: 8px;
            border-radius: 3px;
            word-break: break-all;
        }
        
        .footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            border-top: 2px solid #00ff00;
            color: #4ecdc4;
        }
    </style>
</head>
<body>
    <div class="vault-container">
        <div class="vault-header">
            <div class="vault-title">🔐 SECRET KEY VAULT SYSTEM 🔐</div>
            <div style="color: #4ecdc4; font-size: 1.2em; margin: 10px 0;">
                NEXUS PRIME™ • AICENTRALHUBPLAZA LLC™
            </div>
            <div style="color: #ff6b6b; font-size: 1.1em;">
                ⚠️ MAXIMUM SECURITY LEVEL ⚠️
            </div>
        </div>
        
        <div class="vault-section">
            <div class="section-title">🔑 API KEYS</div>
            <div class="key-item">
                <div class="key-label">🌐 Main API Key:</div>
                <div class="key-value">NEXUS_API_A7K9M2X8Q5R3N6P1</div>
            </div>
            <div class="key-item">
                <div class="key-label">🔒 Admin API Key:</div>
                <div class="key-value">ADMIN_B8L2N5X9Q7S4M1P6</div>
            </div>
        </div>
        
        <div class="vault-section">
            <div class="section-title">💳 SQUARE PAYMENT KEYS</div>
            <div class="key-item">
                <div class="key-label">💰 Square Application ID:</div>
                <div class="key-value">sq0idp-NEXUS_PRIME_APP_2025</div>
            </div>
            <div class="key-item">
                <div class="key-label">🏪 Square Location ID:</div>
                <div class="key-value">AICENTRALHUBPLAZA_LOC_001</div>
            </div>
        </div>
        
        <div class="vault-section">
            <div class="section-title">🗄️ DATABASE SECRETS</div>
            <div class="key-item">
                <div class="key-label">🔐 Master DB Key:</div>
                <div class="key-value">DB_MASTER_C9M4N7X2Q8R5P3K6</div>
            </div>
        </div>
        
        <div class="footer">
            <p>🏢 <strong>AICENTRALHUBPLAZA LLC™</strong></p>
            <p>Secret Key Vault System • Maximum Security Protocol</p>
            <p>📧 Security Contact: emailzapbo777@aicentralhubplaza.com</p>
        </div>
    </div>
</body>
</html>
