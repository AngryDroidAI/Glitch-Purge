<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Glitch Purge Viewer</title>
  <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&family=Orbitron:wght@400;700;900&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      background: 
        radial-gradient(ellipse at center, rgba(0,20,30,0.8) 0%, rgba(0,5,10,1) 100%),
        repeating-linear-gradient(0deg, rgba(0,30,40,0.3), rgba(0,30,40,0.3) 1px, transparent 1px, transparent 2px);
      font-family: 'Share Tech Mono', monospace;
      color: #00ffcc;
      min-height: 100vh;
      padding: 20px;
      position: relative;
      overflow-x: hidden;
    }
    
    body::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: 
        linear-gradient(rgba(0, 255, 204, 0.05) 1px, transparent 1px),
        linear-gradient(90deg, rgba(0, 255, 204, 0.05) 1px, transparent 1px);
      background-size: 30px 30px;
      pointer-events: none;
      z-index: -1;
    }
    
    .scan-line {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 2px;
      background: rgba(0, 255, 204, 0.3);
      box-shadow: 0 0 10px rgba(0, 255, 204, 0.5);
      animation: scan 8s linear infinite;
      z-index: 100;
    }
    
    @keyframes scan {
      0% { top: 0; }
      100% { top: 100%; }
    }
    
    .crt-container {
      border: 2px solid #00ffcc;
      padding: 25px;
      margin: 40px auto;
      max-width: 800px;
      background: 
        repeating-linear-gradient(0deg, rgba(0, 10, 20, 0.9), rgba(0, 10, 20, 0.9) 2px, rgba(0, 20, 30, 0.9) 2px, rgba(0, 20, 30, 0.9) 4px),
        linear-gradient(135deg, rgba(0, 30, 40, 0.9), rgba(0, 10, 20, 0.9));
      box-shadow: 
        0 0 15px rgba(0, 255, 204, 0.7),
        inset 0 0 20px rgba(0, 0, 0, 0.8);
      position: relative;
      border-radius: 4px;
      overflow: hidden;
    }
    
    .crt-container::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(rgba(0, 255, 204, 0.03) 50%, transparent 50%);
      background-size: 100% 4px;
      pointer-events: none;
      animation: flicker 0.1s infinite;
    }
    
    .glitch-title {
      text-align: center;
      font-family: 'Orbitron', sans-serif;
      font-weight: 900;
      font-size: 2.5rem;
      text-shadow: 
        0 0 5px #00ffcc, 
        0 0 10px #00ffcc, 
        0 0 20px #00ffcc,
        0 0 40px #ff00cc,
        0 0 80px #ff00cc;
      animation: glitch 5s infinite;
      margin-bottom: 25px;
      letter-spacing: 3px;
      position: relative;
      text-transform: uppercase;
    }
    
    @keyframes glitch {
      0%, 100% { transform: translate(0); }
      20% { transform: translate(-3px, 3px); }
      40% { transform: translate(-3px, -3px); }
      60% { transform: translate(3px, 3px); }
      80% { transform: translate(3px, -3px); }
    }
    
    @keyframes flicker {
      0%, 100% { opacity: 1; }
      50% { opacity: 0.8; }
    }
    
    .crt-output {
      margin-top: 25px;
      white-space: pre-wrap;
      background: rgba(0, 15, 25, 0.7);
      padding: 15px;
      border: 1px solid #00ffcc;
      box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.5);
      min-height: 200px;
      position: relative;
      overflow: hidden;
    }
    
    .crt-output::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(transparent 50%, rgba(0, 255, 204, 0.05) 50%);
      background-size: 100% 3px;
      pointer-events: none;
      animation: scanline 6s linear infinite;
    }
    
    @keyframes scanline {
      0% { background-position: 0 0; }
      100% { background-position: 0 100%; }
    }
    
    .input-group {
      display: flex;
      gap: 10px;
      margin-bottom: 20px;
    }
    
    input, button {
      background: rgba(0, 10, 20, 0.8);
      color: #00ffcc;
      border: 1px solid #00ffcc;
      padding: 12px 15px;
      font-family: 'Share Tech Mono', monospace;
      font-size: 1rem;
      box-shadow: 0 0 5px rgba(0, 255, 204, 0.5);
      transition: all 0.3s ease;
    }
    
    input {
      flex: 1;
      border-radius: 3px 0 0 3px;
    }
    
    input:focus {
      outline: none;
      box-shadow: 0 0 10px rgba(0, 255, 204, 0.8);
      border-color: #00ffcc;
    }
    
    button {
      background: linear-gradient(to bottom, rgba(0, 40, 60, 0.8), rgba(0, 20, 30, 0.8));
      border-radius: 0 3px 3px 0;
      cursor: pointer;
      font-weight: bold;
      letter-spacing: 1px;
      text-transform: uppercase;
    }
    
    button:hover {
      background: linear-gradient(to bottom, rgba(0, 60, 90, 0.9), rgba(0, 30, 50, 0.9));
      box-shadow: 0 0 15px rgba(0, 255, 204, 0.8);
      transform: translateY(-2px);
    }
    
    button:active {
      transform: translateY(1px);
    }
    
    .broker-entry {
      margin-top: 15px;
      padding: 12px;
      border: 1px solid rgba(0, 255, 204, 0.3);
      background: rgba(0, 20, 30, 0.4);
      border-radius: 3px;
      transition: all 0.3s ease;
      position: relative;
      overflow: hidden;
    }
    
    .broker-entry::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(90deg, transparent, rgba(0, 255, 204, 0.1), transparent);
      transform: translateX(-100%);
    }
    
    .broker-entry:hover::before {
      animation: shine 1.5s;
    }
    
    @keyframes shine {
      100% { transform: translateX(100%); }
    }
    
    .broker-entry.purged {
      border-color: #ff00cc;
      background: rgba(30, 0, 20, 0.4);
    }
    
    .broker-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 10px;
    }
    
    .broker-name {
      font-weight: bold;
      font-size: 1.2rem;
      color: #00ffcc;
    }
    
    .purged .broker-name {
      color: #ff00cc;
      text-decoration: line-through;
    }
    
    .broker-links {
      display: flex;
      gap: 15px;
      margin: 10px 0;
    }
    
    .broker-link {
      display: inline-flex;
      align-items: center;
      gap: 5px;
      color: #00ffcc;
      text-decoration: none;
      padding: 5px 10px;
      border: 1px solid rgba(0, 255, 204, 0.3);
      border-radius: 3px;
      transition: all 0.3s ease;
    }
    
    .broker-link:hover {
      background: rgba(0, 255, 204, 0.1);
      box-shadow: 0 0 8px rgba(0, 255, 204, 0.5);
    }
    
    .purged .broker-link {
      color: #ff00cc;
      border-color: rgba(255, 0, 204, 0.3);
    }
    
    .purge-button {
      background: linear-gradient(to bottom, rgba(0, 40, 60, 0.8), rgba(0, 20, 30, 0.8));
      color: #00ffcc;
      border: 1px solid #00ffcc;
      padding: 8px 15px;
      font-family: 'Share Tech Mono', monospace;
      cursor: pointer;
      border-radius: 3px;
      transition: all 0.3s ease;
      margin-top: 10px;
    }
    
    .purge-button:hover {
      background: linear-gradient(to bottom, rgba(0, 60, 90, 0.9), rgba(0, 30, 50, 0.9));
      box-shadow: 0 0 10px rgba(0, 255, 204, 0.8);
    }
    
    .purged .purge-button {
      background: linear-gradient(to bottom, rgba(40, 0, 30, 0.8), rgba(20, 0, 15, 0.8));
      color: #ff00cc;
      border-color: #ff00cc;
      cursor: not-allowed;
    }
    
    .purge-button:disabled {
      opacity: 0.7;
    }
    
    .log-entry {
      margin-top: 10px;
      padding: 8px;
      background: rgba(0, 15, 25, 0.6);
      border-left: 3px solid #00ffcc;
      font-size: 0.9rem;
    }
    
    .purged .log-entry {
      border-left-color: #ff00cc;
    }
    
    .status-indicator {
      display: inline-block;
      width: 12px;
      height: 12px;
      border-radius: 50%;
      margin-right: 8px;
    }
    
    .status-active {
      background: #00ffcc;
      box-shadow: 0 0 8px #00ffcc;
    }
    
    .status-purged {
      background: #ff00cc;
      box-shadow: 0 0 8px #ff00cc;
    }
    
    .stats-bar {
      display: flex;
      justify-content: space-between;
      margin-top: 20px;
      padding: 10px;
      background: rgba(0, 20, 30, 0.6);
      border: 1px solid rgba(0, 255, 204, 0.3);
      border-radius: 3px;
      font-size: 0.9rem;
    }
    
    .glitch-effect {
      position: relative;
      display: inline-block;
    }
    
    .glitch-effect::before,
    .glitch-effect::after {
      content: attr(data-text);
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }
    
    .glitch-effect::before {
      left: 2px;
      text-shadow: -2px 0 #ff00cc;
      clip: rect(44px, 450px, 56px, 0);
      animation: glitch-anim 5s infinite linear alternate-reverse;
    }
    
    .glitch-effect::after {
      left: -2px;
      text-shadow: -2px 0 #00ffcc;
      clip: rect(44px, 450px, 56px, 0);
      animation: glitch-anim2 5s infinite linear alternate-reverse;
    }
    
    @keyframes glitch-anim {
      0% { clip: rect(42px, 9999px, 44px, 0); }
      5% { clip: rect(12px, 9999px, 59px, 0); }
      10% { clip: rect(48px, 9999px, 29px, 0); }
      15% { clip: rect(42px, 9999px, 73px, 0); }
      20% { clip: rect(63px, 9999px, 27px, 0); }
      25% { clip: rect(34px, 9999px, 55px, 0); }
      30% { clip: rect(86px, 9999px, 73px, 0); }
      35% { clip: rect(20px, 9999px, 20px, 0); }
      40% { clip: rect(26px, 9999px, 60px, 0); }
      45% { clip: rect(25px, 9999px, 66px, 0); }
      50% { clip: rect(57px, 9999px, 98px, 0); }
      55% { clip: rect(5px, 9999px, 46px, 0); }
      60% { clip: rect(82px, 9999px, 31px, 0); }
      65% { clip: rect(54px, 9999px, 27px, 0); }
      70% { clip: rect(28px, 9999px, 99px, 0); }
      75% { clip: rect(45px, 9999px, 69px, 0); }
      80% { clip: rect(23px, 9999px, 85px, 0); }
      85% { clip: rect(1px, 9999px, 83px, 0); }
      90% { clip: rect(71px, 9999px, 14px, 0); }
      95% { clip: rect(60px, 9999px, 89px, 0); }
      100% { clip: rect(100px, 9999px, 100px, 0); }
    }
    
    @keyframes glitch-anim2 {
      0% { clip: rect(65px, 9999px, 100px, 0); }
      5% { clip: rect(52px, 9999px, 74px, 0); }
      10% { clip: rect(79px, 9999px, 85px, 0); }
      15% { clip: rect(75px, 9999px, 5px, 0); }
      20% { clip: rect(67px, 9999px, 61px, 0); }
      25% { clip: rect(14px, 9999px, 79px, 0); }
      30% { clip: rect(1px, 9999px, 66px, 0); }
      35% { clip: rect(86px, 9999px, 30px, 0); }
      40% { clip: rect(23px, 9999px, 98px, 0); }
      45% { clip: rect(85px, 9999px, 72px, 0); }
      50% { clip: rect(71px, 9999px, 75px, 0); }
      55% { clip: rect(2px, 9999px, 48px, 0); }
      60% { clip: rect(30px, 9999px, 16px, 0); }
      65% { clip: rect(59px, 9999px, 50px, 0); }
      70% { clip: rect(41px, 9999px, 62px, 0); }
      75% { clip: rect(2px, 9999px, 82px, 0); }
      80% { clip: rect(47px, 9999px, 73px, 0); }
      85% { clip: rect(3px, 9999px, 27px, 0); }
      90% { clip: rect(26px, 9999px, 55px, 0); }
      95% { clip: rect(42px, 9999px, 97px, 0); }
      100% { clip: rect(38px, 9999px, 49px, 0); }
    }
    
    .pulse {
      animation: pulse 2s infinite;
    }
    
    @keyframes pulse {
      0% { box-shadow: 0 0 0 0 rgba(0, 255, 204, 0.7); }
      70% { box-shadow: 0 0 0 10px rgba(0, 255, 204, 0); }
      100% { box-shadow: 0 0 0 0 rgba(0, 255, 204, 0); }
    }
    
    .terminal-header {
      display: flex;
      justify-content: space-between;
      padding: 5px 10px;
      background: rgba(0, 20, 30, 0.8);
      border-bottom: 1px solid #00ffcc;
      font-size: 0.8rem;
    }
    
    .terminal-buttons {
      display: flex;
      gap: 5px;
    }
    
    .terminal-button {
      width: 12px;
      height: 12px;
      border-radius: 50%;
    }
    
    .close { background: #ff5f56; }
    .minimize { background: #ffbd2e; }
    .maximize { background: #27c93f; }
    
    @media (max-width: 768px) {
      .crt-container {
        width: 95%;
        padding: 15px;
      }
      
      .glitch-title {
        font-size: 1.8rem;
      }
      
      .input-group {
        flex-direction: column;
      }
      
      button {
        border-radius: 3px;
      }
    }
  </style>
</head>
<body>
  <div class="scan-line"></div>
  
  <div class="crt-container">
    <div class="terminal-header">
      <div>glitch-purge-viewer.exe</div>
      <div class="terminal-buttons">
        <div class="terminal-button close"></div>
        <div class="terminal-button minimize"></div>
        <div class="terminal-button maximize"></div>
      </div>
    </div>
    
    <h1 class="glitch-title">
      <span class="glitch-effect" data-text="🛡 GLITCH PURGE VIEWER">🛡 GLITCH PURGE VIEWER</span>
    </h1>
    
    <div class="input-group">
      <input type="text" id="searchInput" placeholder="Enter name or email to scan...">
      <button onclick="scanBrokers()" class="pulse">SCAN BROKERS</button>
    </div>
    
    <div id="resultsViewer" class="crt-output">
      <div style="text-align: center; padding: 40px 0; color: rgba(0, 255, 204, 0.5);">
        🔍 Enter a name or email to begin scanning...
      </div>
    </div>
    
    <div class="stats-bar">
      <div>Total Brokers: <span id="totalBrokers">3</span></div>
      <div>Purged: <span id="purgedCount">0</span></div>
      <div>Status: <span id="systemStatus">READY</span></div>
    </div>
  </div>

  <script>
    const brokers = [
      { 
        name: 'Whitepages', 
        search: 'https://www.whitepages.com/', 
        optOut: 'https://www.whitepages.com/suppress/remove',
        description: 'People search and background check service'
      },
      { 
        name: 'Spokeo', 
        search: 'https://www.spokeo.com/', 
        optOut: 'https://www.spokeo.com/opt_out/new',
        description: 'People search and social media directory'
      },
      { 
        name: 'Intelius', 
        search: 'https://www.intelius.com/', 
        optOut: 'https://www.intelius.com/opt-out',
        description: 'People search and background check service'
      },
      { 
        name: 'BeenVerified', 
        search: 'https://www.beenverified.com/', 
        optOut: 'https://www.beenverified.com/f/optout/search',
        description: 'Background checks and people search'
      },
      { 
        name: 'Instant Checkmate', 
        search: 'https://www.instantcheckmate.com/', 
        optOut: 'https://www.instantcheckmate.com/opt-out/',
        description: 'Criminal records and background checks'
      }
    ];

    let purgedCount = 0;

    function scanBrokers() {
      const query = document.getElementById('searchInput').value.trim();
      const viewer = document.getElementById('resultsViewer');
      
      if (!query) {
        viewer.innerHTML = `<div style="text-align: center; padding: 40px 0; color: #ff00cc;">
          ⚠ Please enter a name or email to scan
        </div>`;
        return;
      }
      
      viewer.innerHTML = `<div class="log-entry">🔍 Scanning for: <strong>${query}</strong> | ${new Date().toLocaleTimeString()}</div>`;
      
      // Reset purged count for new scan
      purgedCount = 0;
      updateStats();
      
      brokers.forEach((broker, index) => {
        const div = document.createElement('div');
        div.className = 'broker-entry';
        div.id = `broker-${index}`;
        div.innerHTML = `
          <div class="broker-header">
            <div>
              <span class="status-indicator status-active"></span>
              <span class="broker-name">${broker.name}</span>
            </div>
            <div style="font-size: 0.8rem; opacity: 0.7;">${broker.description}</div>
          </div>
          <div class="broker-links">
            <a href="${broker.search}" target="_blank" class="broker-link">🔗 Search Site</a>
            <a href="${broker.optOut}" target="_blank" class="broker-link">🧼 Opt-Out Page</a>
          </div>
          <button onclick="markPurged(this, '${broker.name}', ${index})" class="purge-button">Mark as Purged</button>
          <div id="log-${index}" class="log-entry" style="display: none;"></div>
        `;
        viewer.appendChild(div);
      });
      
      // Update system status
      document.getElementById('systemStatus').textContent = 'SCANNING';
      document.getElementById('systemStatus').style.color = '#00ffcc';
    }

    function markPurged(button, site, index) {
      button.disabled = true;
      button.textContent = 'Purged';
      button.parentElement.classList.add('purged');
      
      const log = document.getElementById(`log-${index}`);
      log.style.display = 'block';
      log.innerHTML = `🔮 ${new Date().toLocaleString()} | ${site} → Purged | Badge unlocked`;
      
      // Update status indicator
      const statusIndicator = button.parentElement.querySelector('.status-indicator');
      statusIndicator.classList.remove('status-active');
      statusIndicator.classList.add('status-purged');
      
      // Update stats
      purgedCount++;
      updateStats();
      
      // Check if all are purged
      if (purgedCount === brokers.length) {
        document.getElementById('systemStatus').textContent = 'ALL PURGED';
        document.getElementById('systemStatus').style.color = '#ff00cc';
      }
    }
    
    function updateStats() {
      document.getElementById('purgedCount').textContent = purgedCount;
      document.getElementById('totalBrokers').textContent = brokers.length;
    }
    
    // Initialize stats
    updateStats();
    
    // Add some random glitches for effect
    setInterval(() => {
      const glitchElements = document.querySelectorAll('.glitch-effect');
      glitchElements.forEach(el => {
        if (Math.random() > 0.7) {
          el.style.animation = 'glitch 0.1s';
          setTimeout(() => {
            el.style.animation = '';
          }, 100);
        }
      });
    }, 3000);
  </script>
</body>
</html>
