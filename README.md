<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta http-equiv="X-UA-Compatible" content="ie=edge" />
  <title>Mehmet</title>
  <style>
    body {
      font-family: "Space Grotesk", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #000000;
      color: #e6f1f5;
      font-size: 22px;
      text-align: left;
    }

    .date {
      position: absolute;
      top: 10px;
      right: 20px;
      font-size: 22px;
      color: #cfcfcf;
    }

    .container {
      width: 90%;
      max-width: 800px;
      margin: 0 auto;
      padding: 10px;
    }

    .section {
      margin-bottom: 30px;
      padding-left: 10px;
    }

    .section h2 {
      font-size: 22px;
      margin-bottom: 10px;
    }

    .info {
      font-size: 22px;
      line-height: 1.5;
      margin-left: 10px;
    }

    .info a {
      color: #8ab4ff;
      text-decoration: none;
    }

    .info a:hover {
      text-decoration: underline;
    }

    .contribution-container {
      margin-top: 30px;
      padding-top: 20px;
      text-align: center;
    }

    .contribution-title {
      font-size: 22px;
      margin-bottom: 10px;
    }

    .contribution-grid {
      display: grid;
      grid-template-columns: repeat(6, 10px);
      grid-template-rows: repeat(7, 10px);
      gap: 4px;
      justify-content: center;
      margin-top: 20px;
    }

    .square {
      width: 10px;
      height: 10px;
      background-color: #2d2d2d;
      border-radius: 2px;
    }

    .square[data-level="1"] { background-color: #9be9a8; }
    .square[data-level="2"] { background-color: #40c463; }
    .square[data-level="3"] { background-color: #30a14e; }
    .square[data-level="4"] { background-color: #216e39; }

    footer {
      text-align: center;
      margin-top: 30px;
      font-size: 22px;
      color: #888;
    }
  </style>
</head>

<body>
  <div class="date" id="current-date"></div>

  <div class="container">
    <div class="section" id="about">
      <h2>Mehmet / Researcher & Technical Writer</h2>
      <div class="info"></div>
    </div>

    <div class="section" id="about-me">
      <h2>About Me</h2>
      <div class="info">
        <p>I am Mehmet from Istanbul. I started investing in crypto 5 years ago and have been conducting research for the last 4 years. I have shared some of my content on my Medium account. Additionally, I am a senior mechanical engineering student. My final project is related to physical AI. Nowadays, I research blockchain, data, ML, and AI, improving my Python and SQL skills. You can contact me via:</p>
        <p><strong>Telegram:</strong> <a href="https://t.me/emkey0x" target="_blank">@emkey0x</a></p>
        <p><strong>X:</strong> <a href="https://x.com/0xemkey" target="_blank">@0xemkey</a></p>
      </div>
    </div>

    <div class="section" id="data-analysis">
      <h2>Data Analysis</h2>
      <div class="info">
        <ul>
          <li><p><a href="https://dune.com/emkey/bio-ecosystem" target="_blank" style="font-style: italic">Bio Protocol Dashboard on Dune</a></p></li>
          <li><p><a href="https://dune.com/emkey/fuel-analytics" target="_blank" style="font-style: italic">Fuel Network Dashboard on Dune</a></p></li>
          <li><p><a href="https://dune.com/emkey/xan-token-analytics" target="_blank" style="font-style: italic">XAN Token Analysis Dashboard on Dune</a></p></li>
        </ul>
      </div>
    </div>

    <div class="section" id="hackathons">
      <h2>Hackathons</h2>
      <div class="info">
        <ul>
          <li><p><a href="https://ethglobal.com/showcase/domino-wallet-gb28e" target="_blank" style="font-style: italic">ETHOnline 2024: Domino Wallet</a></p></li>
          <li><p><a href="https://ethglobal.com/showcase/witnessbase-gc864" target="_blank" style="font-style: italic">Scaling Ethereum 2024: WitnessBase</a></p></li>
          <li><p><a href="https://ethglobal.com/showcase/paigent-obai3" target="_blank" style="font-style: italic">Agentic Ethereum: Paigent</a></p></li>
        </ul>
      </div>
    </div>

    <!-- NEW: Live as its own top-level section -->
    <div class="section" id="live">
      <h2>Live</h2>
      <div class="info">
        <ul>
          <li><p><a href="https://youtu.be/5jt40feF41I?si=N7luonN_oA-oZCOz" target="_blank" style="font-style: italic">Otopsi #8 - Bybit ve Safe{Wallet} Saldırısı</a></p></li>
        </ul>
      </div>
    </div>

    <div class="section" id="articles">
      <h2>Articles</h2>

      <h3>[EN] Technical Articles</h3>
      <div class="info">
        <ul>
          <li><p><a href="https://medium.com/@0xemkey/from-barter-to-stablecoin-8edf4a1023c5" target="_blank" style="font-style: italic">From Barter to Stablecoin</a></p></li>
          <li><p><a href="https://medium.com/@0xemkey/erc-7281-aka-xerc20-vs-erc-7683-aka-cross-chain-intents-06de500959fa" target="_blank" style="font-style: italic">ERC-7281 vs ERC-7683</a></p></li>
          <li><p><a href="https://medium.com/@0xemkey/how-to-get-liquidated-online-fast-c4cd54a0f52c" target="_blank" style="font-style: italic">How to Get Liquidated Online Fast</a></p></li>
        </ul>
      </div>

      <h3>[EN] Project Explanations</h3>
      <div class="info">
        <ul>
          <li><p><a href="https://medium.com/@0xemkey/off-chain-computation-in-mina-and-ethereum-4f243d38c606" target="_blank" style="font-style: italic">Off Chain Computation and Mina</a></p></li>
          <li><p><a href="https://medium.com/@0xemkey/web-1-2-3-and-mina-88e4b8661200" target="_blank" style="font-style: italic">Web3.0 and Mina</a></p></li>
        </ul>
      </div>

      <h3>[TR] Project Explanations</h3>
      <div class="info">
        <ul>
          <li><p><a href="https://medium.com/@0xemkey/monad-18e6b27648dc" target="_blank" style="font-style: italic">Monad</a></p></li>
          <li><p><a href="https://medium.com/@0xemkey/berachain-0b8fb5edeffe" target="_blank" style="font-style: italic">Berachain</a></p></li>
          <li><p><a href="https://medium.com/@0xemkey/bankless-podcastinden-%C3%A7%C4%B1kard%C4%B1%C4%9F%C4%B1m-virtuals-notlar%C4%B1-70fc36346018" target="_blank" style="font-style: italic">Virtuals</a></p></li>
        </ul>
      </div>

      <h3>[TR] Technical Articles</h3>
      <div class="info">
        <ul>
          <li><p><a href="https://blog.itublockchain.com/hibrit-katman-2-6ea585a10ce5" target="_blank" style="font-style: italic">Hibrit Katman-2’ler</a></p></li>
          <li><p><a href="https://fintables.com/arastirma/yazilar/kripto-varliklar/linea-fiyati-ne-olur" target="_blank" style="font-style: italic">Linea Fiyatı Ne Olur</a></p></li>
          <li><p><a href="https://fintables.com/arastirma/yazilar/kripto-varliklar/yapay-zeka-paranizdan-para-kazanmanizi-saglayabilir-mi" target="_blank" style="font-style: italic">Yapay Zeka Paranızdan Para Kazanmanızı Sağlayabilir mi?</a></p></li>
          <li><p><a href="https://fintables.com/arastirma/yazilar/kripto-varliklar/kripto-odeme-sistemlerinde-son-surat-yaris" target="_blank" style="font-style: italic">Kripto Ödemelerinde Son Sürat Yarış</a></p></li>
          <li><p><a href="https://fintables.com/arastirma/yazilar/kripto-varliklar/bitcoin-katman-2-c%C3%B6z%C3%BCmleri" target="_blank" style="font-style: italic">Bitcoin Katman-2’leri</a></p></li>
          <li><p><a href="https://x.com/FintablesKripto/status/1953889209321664643" target="_blank" style="font-style: italic">Pendle Boros</a></p></li>
          <li><p><a href="https://x.com/FintablesKripto/status/1929584173636796669" target="_blank" style="font-style: italic">Pendle Strategy</a></p></li>
          <li><p><a href="https://x.com/FintablesKripto/status/1932806724127277057" target="_blank" style="font-style: italic">Onchain Adaptation</a></p></li>
        </ul>
      </div>
    </div>

  </div>

  <script>
    const currentDateElement = document.getElementById("current-date");
    const now = new Date();
    currentDateElement.innerText = now.toLocaleDateString("en-US", {
      weekday: "short",
      year: "numeric",
      month: "short",
      day: "numeric"
    });
  </script>
</body>

</html>
