<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My G.I.T - Aviator Tracker</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #0e0e0e;
      color: #f1f1f1;
    }
    header {
      background: #111;
      padding: 1em;
      text-align: center;
      font-size: 1.5em;
      font-weight: bold;
      color: #ff3c3c;
    }
    .container {
      padding: 1em;
    }
    .section {
      background: #1b1b1b;
      padding: 1em;
      margin-bottom: 1em;
      border-radius: 8px;
    }
    .section h2 {
      color: #62ff62;
    }
    input, button, textarea {
      width: 100%;
      padding: 0.5em;
      margin: 0.5em 0;
      border-radius: 5px;
      border: none;
    }
    button {
      background: #ff3c3c;
      color: #fff;
      font-weight: bold;
    }
    .alert {
      background: #ffef62;
      color: #000;
      padding: 0.5em;
      margin-top: 0.5em;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <header>Welcome back, Pilot. Let’s chase these skies...</header>  <div class="container">
    <div class="section">
      <h2>Lock In Multiplier</h2>
      <input id="multiplier" placeholder="Enter last round multiplier (e.g. 2.3)" type="number" step="0.01" />
      <button onclick="lockIn()">Lock In</button>
      <div id="prediction"></div>
    </div><div class="section">
  <h2>Diagnostics</h2>
  <button onclick="checkDataSources()">Run Check</button>
  <div id="diagnostics"></div>
</div>

<div class="section">
  <h2>WhatsApp Alerts</h2>
  <p>We’ll notify you if data sources go dark:</p>
  <div class="alert">Yo, G — if data ain't loading, watch for a WhatsApp heads-up!</div>
</div>

  </div>  <script>
    const localHistory = [];

    function lockIn() {
      const val = parseFloat(document.getElementById("multiplier").value);
      if (!isNaN(val)) {
        localHistory.push(val);
        const prediction = predictNextMultiplier();
        document.getElementById("prediction").innerHTML = `Next prediction: <strong>${prediction.toFixed(2)}x</strong>`;
      }
    }

    function predictNextMultiplier() {
      const recent = localHistory.slice(-25);
      if (recent.length < 5) return 1.50 + Math.random();
      const avg = recent.reduce((a, b) => a + b, 0) / recent.length;
      return avg + (Math.random() * 0.5);
    }

    function checkDataSources() {
      const diagnostics = document.getElementById("diagnostics");
      const sources = [
        { name: "Live Aviator Feed", status: Math.random() > 0.5 },
        { name: "Bet Graph Server", status: Math.random() > 0.5 },
        { name: "Stat Repo", status: Math.random() > 0.5 },
      ];

      diagnostics.innerHTML = sources.map(source =>
        `<div>${source.name}: <strong style="color: ${source.status ? 'lime' : 'red'}">${source.status ? 'Connected' : 'Unavailable'}</strong></div>`
      ).join('');

      if (sources.some(s => !s.status)) {
        sendWhatsAppAlert();
      }
    }

    function sendWhatsAppAlert() {
      alert("Yo, G — can’t tap into the live stats. Check WhatsApp for the update.");
    }
  </script></body>
</html>
