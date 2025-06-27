<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coindemograph - Crypto Resources</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #1a1a1a;
            color: #ffffff;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .card {
            background: #2d2d2d;
            border-radius: 10px;
            padding: 20px;
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        h2 {
            color: #4CAF50;
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 10px;
        }

        a {
            color: #4CAF50;
            text-decoration: none;
        }

        .referral-code {
            background: #333;
            padding: 5px 10px;
            border-radius: 5px;
            margin: 10px 0;
            font-family: monospace;
        }

        .section-title {
            font-size: 24px;
            margin: 40px 0 20px;
        }

        .accordion {
            margin-bottom: 10px;
        }

        .accordion-summary {
            background: #333;
            padding: 15px;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Coindemograph Crypto Resources</h1>

        <h2 class="section-title">Featured Projects</h2>
        <div class="project-grid">
            <div class="card">
                <h3>GPU Network</h3>
                <a href="https://token.gpu.net?ref=QTVPJB" target="_blank">Visit GPU Network</a>
                <div class="referral-code">Referral: QTVPJB</div>
            </div>

            <div class="card">
                <h3>Gata</h3>
                <a href="https://app.gata.xyz?invite_code=8ypenp68" target="_blank">Visit Gata</a>
                <div class="referral-code">Invite Code: 8ypenp68</div>
            </div>

            <!-- Add other projects in similar card format -->
        </div>

        <h2 class="section-title">Monad Testnet Guide</h2>
        <div class="accordion">
            <details open>
                <summary class="accordion-summary">1. Bridge Sepolia ETH</summary>
                <div class="card">
                    <a href="https://testnet.orbiter.finance/bridge/Sepolia/Monad%20Testnet?token=ETH" target="_blank">Bridge ETH</a>
                </div>
            </details>

            <details>
                <summary class="accordion-summary">2. Swap Tokens</summary>
                <div class="card">
                    <a href="https://monad.ambient.finance/swap/chain=0x279f&tokenA=0x836047a99e11F376522B447bffb6e3495Dd0637c&tokenB=0x0000000000000000000000000000000000000000" target="_blank">Swap ETH to Monad</a>
                </div>
            </details>

            <!-- Add other steps in similar accordion format -->
        </div>

        <h2 class="section-title">DeFi & Trading Platforms</h2>
        <div class="project-grid">
            <div class="card">
                <h3>KiloEx</h3>
                <a href="https://app.kiloex.io/trade?chain=MON" target="_blank">Trade Futures</a>
                <p>Mint test USDT and trade</p>
            </div>

            <div class="card">
                <h3>Nitro Finance</h3>
                <a href="https://testapp.nitrofinance.xyz/trade" target="_blank">Provide LP</a>
                <div class="referral-code">Get NIT tokens</div>
            </div>

            <!-- Add other platforms similarly -->
        </div>
    </div>
</body>
</html>