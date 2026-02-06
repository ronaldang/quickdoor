# QuickDoor 🚪

**The delivery address problem, solved with a simple iOS Shortcut.**

## 🎯 Problem
Every time you order delivery in Saudi Arabia, the driver calls asking for your address. It's annoying to explain the same location over and over.

## 💡 Solution
QuickDoor is a downloadable iOS Shortcut that automatically sends your location + building photos via WhatsApp when unknown numbers call.

## 🚀 Features
- 📞 Triggers on unknown incoming calls (likely delivery)
- 📍 Sends your current GPS location
- 🏠 Includes pre-selected building photos
- 📝 Custom text with floor/apartment details
- 🔒 100% private - everything stays on your phone
- 💰 Completely FREE - no servers, no costs

## 📱 Requirements
- iPhone with iOS 14+
- WhatsApp installed
- Shortcuts app (built-in)

## 🛠️ Quick Setup (3 minutes)
1. Download `QuickDoor.shortcut`
2. Add your building photos to "Delivery Photos" album
3. Configure your floor/apartment number once
4. Enable automation for unknown calls
5. Done! 🎉

## 🌐 Live Demo
Visit: [quickdoor.github.io](https://quickdoor.github.io)

## 📂 Project Structure
```
quickdoor/
├── index.html          # Landing page
├── setup.html          # Setup guide
└── shortcuts/
    └── QuickDoor.shortcut  # iOS automation
```

## 🚢 Deploy Your Own

### GitHub Pages (Free)
1. Fork this repository
2. Go to Settings → Pages
3. Select Source: Deploy from branch
4. Select Branch: main, folder: / (root)
5. Save and wait 2 minutes
6. Your site is live at `https://[username].github.io/quickdoor`

### Custom Domain
1. Add a `CNAME` file with your domain
2. Configure DNS:
   - A Record: `185.199.108.153`
   - CNAME: `[username].github.io`

## 🔨 Building the Shortcut

Since `.shortcut` files must be created on iOS:

1. Open Shortcuts app on iPhone
2. Create new shortcut with these actions:
   - Get current location
   - Get photos from "Delivery Photos" album
   - Compose WhatsApp message
   - Open WhatsApp URL scheme
3. Export as `QuickDoor.shortcut`
4. Replace placeholder file in `/shortcuts`

See [shortcuts/shortcut-instructions.md](shortcuts/shortcut-instructions.md) for detailed steps.

## 🤝 Contributing

Improvements welcome! Especially:
- Android version (using Tasker/Automate)
- More messaging apps (Telegram, SMS)
- Better Arabic translations
- Video tutorials

## 📄 License

MIT - Use freely!

## 🙏 Credits

Built with ❤️ to solve a real problem for delivery in Saudi Arabia.

---

**Not affiliated with Apple, WhatsApp, or any delivery company.**