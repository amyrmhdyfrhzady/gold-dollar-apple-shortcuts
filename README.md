<h1>💰 Gold &amp; Dollar — Apple Shortcuts</h1>

<p>🇮🇷 Get the latest USD and 18K gold prices instantly using Apple Shortcuts.</p>

<p>
Two ready-to-use Apple Shortcuts for checking Iranian market prices —
one with a fixed output format, and one powered by on-device Siri AI
for a more dynamic response.
</p>

<hr>

<h2>✨ Features</h2>

<ul>
  <li>💵 USD price</li>
  <li>🪙 18K gold price</li>
  <li>⚡ Fast and lightweight</li>
  <li>📱 Works with Apple Shortcuts</li>
  <li>🌐 Internet required only for fetching prices</li>
  <li>🔒 No account required</li>
  <li>📦 Ready-to-install <code>.shortcut</code> files</li>
  <li>🤖 Optional on-device Siri AI version</li>
  <li>📴 Remaining processing is performed locally on the device</li>
</ul>

<hr>

<h2>📦 Shortcuts</h2>

<h3>⚡ Standard</h3>

<p><strong>File:</strong> <code>USDT&amp;GOLDprice.shortcut</code></p>

<p>
The Standard version uses a predefined text template.
</p>

<p>
The API prices are inserted directly into the template, so the output
remains fast, predictable, and consistent every time.
</p>

<h4>Example output</h4>

<pre>
💰 قیمت بازار
💵 دلار: 225,400 تومان
🪙 طلای ۱۸ عیار: 23,464,906 تومان
🕐 آخرین بروزرسانی: همین الان
</pre>

<h4>Recommended for:</h4>

<ul>
  <li>Devices without iOS 27</li>
  <li>Devices without Siri AI / Apple Intelligence</li>
  <li>Devices that don’t support the required on-device AI features</li>
  <li>Anyone who prefers a consistent output</li>
</ul>

<p><strong>No Siri AI processing is required.</strong></p>

<hr>

<h3>🤖 Siri AI</h3>

<p><strong>File:</strong> <code>USDT&amp;GOLDprice(SiriAI).shortcut</code></p>

<p>
This version uses the on-device Siri AI model to generate the final response.
</p>

<p>
Instead of relying on a predefined output template, the received price data
is passed to the on-device model, which generates the response dynamically.
</p>

<p>
This version is intended for compatible devices where the required Siri AI /
on-device intelligence features are available.
</p>

<h4>Recommended for:</h4>

<ul>
  <li>Compatible iOS 27 devices</li>
  <li>Devices with the required Siri AI features enabled</li>
  <li>Users who prefer a more dynamic response</li>
</ul>

<p>
The AI processing is performed on-device, keeping the response responsive
without requiring cloud AI processing.
</p>

<hr>

<h2>⚖️ Standard vs Siri AI</h2>

<table>
  <thead>
    <tr>
      <th>Feature</th>
      <th>Standard</th>
      <th>Siri AI</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Fixed output format</td><td>✅</td><td>❌</td></tr>
    <tr><td>Dynamic AI-generated output</td><td>❌</td><td>✅</td></tr>
    <tr><td>Requires Siri AI</td><td>❌</td><td>✅</td></tr>
    <tr><td>On-device AI processing</td><td>❌</td><td>✅</td></tr>
    <tr><td>Works without Siri AI</td><td>✅</td><td>❌</td></tr>
    <tr><td>Works without iOS 27</td><td>✅</td><td>❌</td></tr>
    <tr><td>Internet required for API</td><td>✅</td><td>✅</td></tr>
    <tr><td>Local processing</td><td>✅</td><td>✅</td></tr>
    <tr><td>Additional app required</td><td>❌</td><td>❌</td></tr>
  </tbody>
</table>

<h3>Which version should I use?</h3>

<p>
Use <strong>Standard</strong> if your device doesn’t support Siri AI,
Siri AI isn’t available for you, or you simply want the fastest and most
predictable result.
</p>

<p>
Use <strong>Siri AI</strong> if your device supports the required on-device
Siri AI features and you want the response to be generated dynamically.
</p>

<hr>

<h2>🚀 Installation</h2>

<p>Installing a Shortcut takes only a few seconds.</p>

<ol>
  <li>Download the <code>.shortcut</code> file you want.</li>
  <li>Tap the downloaded file on your Apple device.</li>
  <li>It will open in the Shortcuts app.</li>
  <li>Add the Shortcut.</li>
  <li>Run it.</li>
</ol>

<p>That’s it. 🎉</p>

<p>No additional application or account is required.</p>

<hr>

<h2>🌐 How It Works</h2>

<p>
Both Shortcuts use a personal API to retrieve the latest price data.
</p>

<p>The API returns data in this format:</p>

<pre><code>{
  "success": true,
  "data": {
    "usd": 225400,
    "gold_18k": 23464906
  },
  "currency": "IRT",
  "gold_unit": "IRT_per_gram",
  "sources": {
    "usd": "alanchand.com",
    "gold_18k": "saatchico.com"
  },
  "updated_at": "2026-09-06T14:12:37.455Z"
}</code></pre>

<p>The Shortcuts use:</p>

<ul>
  <li><code>data.usd</code> → USD price</li>
  <li><code>data.gold_18k</code> → 18K gold price</li>
</ul>

<p>Prices are returned in <strong>IRT (Iranian Toman)</strong>.</p>

<h3>Data Sources</h3>

<ul>
  <li>💵 USD: <code>alanchand.com</code></li>
  <li>🪙 18K Gold: <code>saatchico.com</code></li>
</ul>

<hr>

<h2>🔌 Internet &amp; Privacy</h2>

<p>
An internet connection is required to retrieve the latest prices from the API.
</p>

<h3>Standard</h3>

<p>
The price values are inserted into the predefined template locally on the device.
</p>

<h3>Siri AI</h3>

<p>
The received data is processed using the compatible on-device Siri AI model.
</p>

<p>
No cloud AI processing is required for generating the Siri AI response.
</p>

<hr>

<h2>📱 Compatibility</h2>

<p>
The Shortcuts are designed for Apple devices that have the Shortcuts app available.
</p>

<h3>Standard</h3>

<p>
The Standard version does not depend on Siri AI and is therefore the recommended
option for devices without the required Siri AI capabilities.
</p>

<h3>Siri AI</h3>

<p>The Siri AI version requires:</p>

<ul>
  <li>A compatible Apple device</li>
  <li>The required operating system version</li>
  <li>Siri AI / on-device intelligence availability</li>
  <li>The required features enabled on the device</li>
</ul>

<p>
Availability of these features may vary depending on device, operating system,
language, and region.
</p>

<hr>

<h2>📁 Repository Structure</h2>

<pre>
gold-dollar-apple-shortcuts/
│
├── USDT&amp;GOLDprice.shortcut
├── USDT&amp;GOLDprice(SiriAI).shortcut
├── README.md
└── LICENSE
</pre>

<hr>

<h2>🛠️ Requirements</h2>

<h3>Standard</h3>

<ul>
  <li>Apple device</li>
  <li>Shortcuts app</li>
  <li>Internet connection when fetching prices</li>
</ul>

<h3>Siri AI</h3>

<p>Everything required by the Standard version, plus:</p>

<ul>
  <li>Compatible Apple device</li>
  <li>Compatible operating system</li>
  <li>Supported on-device Siri AI features</li>
</ul>

<hr>

<h2>📌 Notes</h2>

<ul>
  <li>Price data is provided by the project’s personal API.</li>
  <li>The displayed prices depend on the availability and freshness of the API data.</li>
  <li>Internet access is required to retrieve updated prices.</li>
  <li>Siri AI functionality depends on Apple’s device, OS, language, and regional availability.</li>
  <li>This project does not provide or modify Apple’s Siri AI technology.</li>
</ul>

<hr>

<h2>📄 License</h2>

<p>See <code>LICENSE</code> for license information.</p>
