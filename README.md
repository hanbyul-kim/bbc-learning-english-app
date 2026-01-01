# BBC Learning English Study App

A web application for systematic learning with BBC Learning English's "6 Minute English" podcasts.

## 🌐 Live Demo

Once GitHub Pages is configured, the podcast list will be available at:
`https://[your-username].github.io/bbc-learning-english-app/`

## 🚀 Quick Start - Enable GitHub Pages

### Method 1: Using GitHub Web Interface (Recommended)

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section in the left sidebar
4. Under **Source**, select:
   - **Branch**: `claude/bbc-english-learning-d5alT` (or merge to `main` first)
   - **Folder**: `/ (root)`
5. Click **Save**
6. Wait a few minutes for deployment
7. Your site will be available at the URL shown

### Method 2: Merge to Main Branch

If you prefer to use the main branch for GitHub Pages:

```bash
# Create a pull request to merge claude/bbc-english-learning-d5alT to main
# Then configure GitHub Pages to use main branch
```

## 📁 Project Structure

```
bbc-learning-english-app/
├── index.html          # Main podcast list page with RSS feed integration
├── CLAUDE.md          # Detailed project specification and requirements
└── README.md          # This file
```

## ✨ Current Features

### Podcast List Page (`index.html`)

- **RSS Feed Integration**: Automatically fetches latest episodes from BBC Learning English
- **Real-time Search**: Filter episodes by title or description
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful gradient design with smooth animations
- **Episode Information**: Displays title, date, description, and direct links
- **Statistics**: Shows total episode count and latest year

## 🎯 Planned Features (from CLAUDE.md)

### 5-Stage Learning Methodology

1. **Stage 1: First Listening** - Listen 2-3 times without script
2. **Stage 2: Sentence Analysis** - Analyze each sentence with AI assistance
3. **Stage 3: Complete Listening** - Listen without subtitles until fully understood
4. **Stage 4: Expression Mastery** - Create example sentences and flashcards
5. **Stage 5: Speaking & Writing** - Practice with recording and essay writing

### Key Features to Implement

- [ ] Audio player with sentence-by-sentence playback
- [ ] AI-powered grammar analysis
- [ ] Expression collection and flashcard system
- [ ] Speaking practice with recording
- [ ] Writing practice with AI feedback
- [ ] Progress tracking and statistics
- [ ] Spaced repetition review system

## 🛠 Technology Stack

- **Frontend**: Pure HTML/CSS/JavaScript (no build process needed)
- **RSS Parsing**: rss2json.com API for CORS proxy
- **Hosting**: GitHub Pages
- **Future**: React + Next.js + TypeScript (see CLAUDE.md)

## 📊 Data Source

Episodes are loaded from the official BBC Learning English RSS feed:
- **Feed URL**: https://feeds.bbci.co.uk/learningenglish/english/features/6-minute-english/rss
- **Updates**: Weekly with new episodes

## 🎨 Design Philosophy

- **Minimal but Effective**: 6 minutes of content for comprehensive learning
- **Deep Learning**: One episode per week, studied thoroughly
- **Four Skills**: Listening, Speaking, Writing, and Vocabulary in one package
- **Sustainable**: Light learning load for consistent habit formation

## 📝 Learning Philosophy

> "English learning is a marathon, not a sprint. Consistency is more important than speed."

This app is designed to help learners:
- Focus deeply on one episode per week
- Build lasting habits with manageable content
- Improve all four English skills simultaneously
- Enjoy the learning process

## 🔗 Related Links

- [BBC Learning English Official Website](https://www.bbc.co.uk/learningenglish)
- [6 Minute English Podcast Page](https://www.bbc.co.uk/learningenglish/english/features/6-minute-english)
- [Project Specification](./CLAUDE.md)

## 📄 License

This is an educational project. BBC Learning English content is copyright of the BBC.
Please refer to [BBC's Terms of Use](https://www.bbc.co.uk/usingthebbc/terms/) for content usage guidelines.

## 🤝 Contributing

This project is in early development. See [CLAUDE.md](./CLAUDE.md) for the full roadmap and feature specifications.
