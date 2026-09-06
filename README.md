💰 Gold & Dollar — Apple Shortcuts

A simple and fast way to check the latest USD and 18K gold prices directly from Apple Shortcuts.

This repository provides two versions of the same Shortcut:

* ⚡ Standard — fixed, consistent output with no AI processing
* 🤖 Siri AI — uses on-device Siri AI to generate the response dynamically

Both versions retrieve the latest prices from a personal API and process the remaining steps locally on the device.

⸻

✨ Features

* 💵 Latest USD price
* 🪙 Latest 18K gold price
* ⚡ Fast execution
* 📱 Designed for Apple Shortcuts
* 🌐 Internet is only required to retrieve the latest prices
* 🔒 No account or additional app required
* 📦 Ready-to-install .shortcut files
* 🤖 Optional on-device Siri AI version

⸻

📦 Available Shortcuts

⚡ Standard Version

File: USDT&GOLDprice.shortcut

This version uses a predefined text template, so the output is always consistent.

It is recommended for devices that:

* Don’t have iOS 27
* Don’t have Siri AI / Apple Intelligence enabled
* Don’t support Siri AI
* Prefer a predictable and lightweight output

Example output

💰 قیمت بازار
💵 دلار: 225,400 تومان
🪙 طلای ۱۸ عیار: 23,464,906 تومان
🕐 آخرین بروزرسانی: همین الان

The prices are retrieved from the API and inserted directly into the predefined template.

No Siri AI processing is required.

⸻

🤖 Siri AI Version

File: USDT&GOLDprice(SiriAI).shortcut

This version is designed for devices that support the required Siri AI / on-device intelligence capabilities.

Instead of using a fixed response template, the received price data is passed to the on-device Siri AI model, which generates the final response.

This allows the response format to be more dynamic while keeping the processing responsive by using the on-device model.

⸻

⚖️ Standard vs Siri AI

Feature	Standard	Siri AI
Fixed output format	✅	❌
Dynamic AI-generated output	❌	✅
Requires Siri AI	❌	✅
On-device AI processing	❌	✅
Works without iOS 27 / Siri AI	✅	❌
Internet required	API only	API only
Local processing	✅	✅
Additional app required	❌	❌

Which one should I use?

Use the Standard version if your device doesn’t support Siri AI, Siri AI isn’t available on your device, or you simply want a consistent result every time.

Use the Siri AI version if your device supports the required on-device Siri AI capabilities and you want a more dynamic response.

⸻

🚀 Installation

Installation is intentionally simple.

1. Download the .shortcut file you want.
2. Tap the downloaded file on your Apple device.
3. The file will open in the Shortcuts app.
4. Add the Shortcut.
5. Run it whenever you want to check the latest prices.

That’s it. 🎉

No separate application or account is required.

⸻

🌐 How It Works

The Shortcut uses a personal price API to retrieve the latest market data.

The API returns data in the following structure:

{
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
}

The Shortcut extracts:

* data.usd → USD price
* data.gold_18k → 18K gold price

The API uses Iranian Toman (IRT) for the returned prices.

Data sources

* USD → alanchand.com
* 18K gold → saatchico.com

After the data is retrieved, the remaining Shortcut processing happens locally on the device.

⸻

🔌 Internet Requirements

An internet connection is required only for fetching the latest prices from the API.

Once the API response is received:

* The Standard version performs the remaining processing locally.
* The Siri AI version performs its AI processing on the device.

No cloud AI processing is required for the Siri AI Shortcut.

⸻

📱 Compatibility

The Shortcuts are intended for Apple devices that have the Shortcuts app available.

Standard

The Standard version is the most compatible option and does not depend on Siri AI availability.

Siri AI

The Siri AI version requires a compatible Apple device and the required Siri AI / on-device intelligence features to be available and enabled.

Availability of these capabilities may depend on the device, operating system, language, and region.

⸻

📁 Repository Structure

gold-dollar-apple-shortcuts/
│
├── USDT&GOLDprice.shortcut
├── USDT&GOLDprice(SiriAI).shortcut
├── README.md
└── LICENSE

⸻

📄 License

This project is provided for personal and educational use.

See LICENSE for details.
