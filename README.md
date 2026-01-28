# AutoApply AI - Free Job Application Automation

🚀 **100% FREE** AI-powered job application automation. No credit card required!

**Live Demo:** https://3xo5lbco6adqg.ok.kimi.link

---

## ✨ Features

- 🤖 **Real AI Resume Tailoring** - Uses Google Gemini API (free tier)
- 🔍 **Job Search** - Searches real jobs from multiple sources
- 📝 **Auto-Fill Extension** - Chrome extension for LinkedIn, Indeed, etc.
- 💾 **Local Storage** - All data stays in your browser
- 🆓 **100% Free** - No credit card, no subscriptions

---

## 🚀 Quick Start (3 Steps)

### Step 1: Get Your Free Gemini API Key (30 seconds)

1. Go to **[aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)**
2. Sign in with your Google account
3. Click **"Create API Key"**
4. Copy the key

**Free Tier Limits:**
- 1,500 requests per day
- 30 requests per minute
- 1 million token context window

### Step 2: Open the App

Go to: **https://3xo5lbco6adqg.ok.kimi.link**

### Step 3: Configure

1. Click **Settings** tab
2. Paste your Gemini API key
3. Click **Save Settings**

That's it! You're ready to use AI-powered job automation.

---

## 📋 How to Use

### Upload Your Resume

1. Go to **Resume** tab
2. Click **Upload Resume**
3. Select your PDF or TXT resume
4. AI will automatically detect your skills

### Search for Jobs

1. Go to **Jobs** tab
2. Enter search terms (e.g., "React developer")
3. Click **Search**
4. Browse jobs from multiple sources

### AI Tailor Your Resume

1. Select a resume
2. Click **"AI Tailor for Jobs"**
3. AI will optimize your resume with relevant keywords
4. View the tailored version and match score

### Apply to Jobs

1. Click on any job card
2. Review job details
3. Click **"Auto-Apply with AI"**
4. Application is tracked automatically

---

## 🔌 Chrome Extension (Optional)

The Chrome Extension helps auto-fill job applications on popular sites.

### Installation

1. Download the `extension` folder from this project
2. Open Chrome and go to `chrome://extensions/`
3. Enable **"Developer mode"** (toggle in top right)
4. Click **"Load unpacked"**
5. Select the `extension` folder

### Supported Sites

- ✅ LinkedIn Jobs
- ✅ Indeed
- ✅ Glassdoor
- ✅ Greenhouse
- ✅ Lever
- ✅ Workday
- ✅ USAJobs
- ✅ ZipRecruiter
- ✅ Monster

### How to Use Extension

1. Go to any job application page
2. Click the AutoApply AI extension icon
3. Click **"Auto-Fill Application"**
4. Review and submit!

---

## 🔑 Optional: Adzuna Job API

For more job results, you can add a free Adzuna API key.

### Get Adzuna API Key

1. Go to **[developer.adzuna.com](https://developer.adzuna.com/)**
2. Create a free account
3. Get your **App ID** and **API Key**
4. Paste them in Settings → Adzuna Job API

**Free Tier:** 100 requests/day

---

## 🛠️ Development

### Local Setup

```bash
# Clone the repository
git clone <repo-url>
cd autoapply-ai

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

### Project Structure

```
├── src/
│   ├── App.tsx           # Main application
│   ├── services/
│   │   ├── gemini.ts     # Gemini AI integration
│   │   └── jobs.ts       # Job search APIs
│   ├── types/
│   │   └── index.ts      # TypeScript types
│   └── hooks/
│       └── useLocalStorage.ts
├── extension/            # Chrome Extension
│   ├── manifest.json
│   ├── popup.html
│   ├── popup.js
│   ├── content.js
│   └── background.js
└── dist/                 # Production build
```

---

## 🔒 Privacy & Security

- ✅ **All data stored locally** in your browser
- ✅ **No server or database** - completely client-side
- ✅ **API keys never leave** your device
- ✅ **No tracking or analytics**

---

## 📊 Free Tier Limits

| Service | Free Tier |
|---------|-----------|
| Gemini AI | 1,500 requests/day |
| Adzuna Jobs | 100 requests/day |
| RemoteOK | Unlimited |
| USAJobs | Unlimited |

---

## 🐛 Troubleshooting

### "Rate limit exceeded" error

- Wait a minute and try again
- Gemini free tier: 30 requests/minute
- Check your usage at [aistudio.google.com](https://aistudio.google.com)

### Jobs not loading

- Check your internet connection
- Try refreshing the page
- The app falls back to sample jobs if APIs fail

### Extension not working

- Make sure you're on a supported job site
- Check that Developer mode is enabled
- Try reloading the extension

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

## 📄 License

MIT License - Free for personal and commercial use.

---

## 🙏 Credits

- **Google Gemini API** - AI-powered resume tailoring
- **Adzuna API** - Job search data
- **RemoteOK** - Remote job listings
- **USAJobs** - Government jobs

---

Made with ❤️ for job seekers everywhere.
