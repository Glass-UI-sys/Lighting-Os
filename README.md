<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nebula OS V18 Security</title>
    <style>
        body { background-color: #0b0914; color: #ffffff; font-family: Arial, sans-serif; margin: 0; padding: 20px; display: flex; justify-content: center; }
        .container { width: 100%; max-width: 450px; display: flex; flex-direction: column; gap: 15px; }
        .system-header { background-color: #ffffff; color: #000000; padding: 12px; border-radius: 8px; text-align: center; font-weight: bold; font-size: 14px; }
        .shield-console { background-color: #121026; border: 1px solid #231d45; border-radius: 12px; padding: 20px; text-align: center; position: relative; }
        .shield-badge { background-color: #1b4d22; color: #4af26e; padding: 4px 10px; border-radius: 20px; font-size: 12px; display: inline-block; margin-bottom: 15px; }
        .status-circle { width: 70px; height: 70px; border: 3px solid #4af26e; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: #4af26e; font-size: 32px; margin: 0 auto 15px auto; }
        h2 { color: #4af26e; margin: 0 0 10px 0; }
        .scan-details { font-size: 12px; color: #a09cb0; line-height: 1.5; }
        .status-switches { text-align: left; margin: 20px 0; font-size: 14px; }
        .status-on { color: #4af26e; font-weight: bold; }
        .action-btn { background-color: #4af26e; color: #000000; border: none; padding: 10px 20px; border-radius: 6px; font-weight: bold; cursor: pointer; width: 100%; }
    </style>
</head>
<body>
    <div class="container">
        <header class="system-header">
            🛡️ Nebula OS V18 Security — FIXED — No X11 — No Localhost
        </header>
        <main class="shield-console">
            <div class="shield-badge">Protected</div>
            <div class="status-circle">✓</div>
            <h2>No threats found</h2>
            <p class="scan-details">Last scan: 10:15 AM • 24GB RAM • 512GB NVMe 7100MB/s<br>2.1s scan • 19% battery OK</p>
            <div class="status-switches">
                <p>Virus protection: <span class="status-on">ON</span></p>
                <p>Firewall: <span class="status-on">ON</span></p>
                <p>Web: <span class="status-on">ON</span></p>
                <p>Ransomware: <span class="status-on">ON</span></p>
            </div>
            <button onclick="alert('Nebula Engine Scan Successfully Running on Host Device!')" class="action-btn">Run Engine Scan</button>
        </main>
    </div>
</body>
</html>