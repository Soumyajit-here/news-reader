# 📰 Personalized News Reader

A beautiful, AI-powered news curation web application that provides personalized news articles based on your interests. Features a modern glassmorphic design with smooth animations and intelligent content ranking.

## ✨ Features

### Core Functionality
- **Interest-Based Curation**: Select from 8 different news categories
- **Smart Relevance Scoring**: Articles are scored based on your interests and recency
- **Multiple Sorting Options**: Sort by relevance, date, or priority
- **Priority Levels**: Articles are categorized as high, medium, or low priority
- **Bookmark System**: Save your favorite articles for later reading
- **Reading Time Estimates**: Know how long each article will take to read

### Analytics Dashboard
- Total articles found
- Average relevance score
- Top category distribution
- Average reading time
- Priority distribution
- Sentiment analysis (positive/neutral/negative)

### User Experience
- Beautiful glassmorphic UI with gradient backgrounds
- Smooth animations and transitions
- Responsive design (mobile-friendly)
- Real-time notifications
- Loading states with spinners
- Interactive hover effects

## 🎨 Design Highlights

- **Modern Glassmorphism**: Translucent cards with backdrop blur effects
- **Vibrant Gradients**: Eye-catching purple-pink color scheme
- **Micro-interactions**: Smooth hover animations and transitions
- **Responsive Grid Layout**: Adapts to different screen sizes
- **Accessibility**: Proper contrast and semantic markup

## 📋 Available Categories

1. **Technology** - AI, software, hardware, cybersecurity
2. **Business** - Markets, investments, corporate news
3. **Science** - Research, discoveries, space exploration
4. **Health** - Medical breakthroughs, wellness, mental health
5. **Sports** - Championships, athletics, training innovations
6. **Entertainment** - Movies, streaming, music industry
7. **Politics** - Legislation, policies, elections
8. **World News** - International events, climate, trade

## 🚀 Getting Started

### Installation

1. **Download the HTML file** or copy the code
2. **Open in a browser** - Simply double-click the HTML file or open it in any modern web browser
3. **No dependencies required** - Everything runs in the browser

### Usage

1. **Select Your Interests**
   - Click on one or more interest tags
   - Tags will highlight when selected
   - You can select multiple categories

2. **Fetch News**
   - Click the "Fetch News" button
   - Wait for articles to load (simulated 2-second delay)
   - Articles will appear with smooth animations

3. **Sort & Filter**
   - Use the dropdown to sort by:
     - Relevance (default)
     - Date (newest first)
     - Priority (high to low)

4. **Interact with Articles**
   - Click article titles or "Read Full Article" to view (demo URLs)
   - Click the star icon to bookmark articles
   - View relevance scores, keywords, and reading times

5. **Clear News**
   - Click "Clear" to remove all articles
   - Select different interests and fetch again

## 🔧 Technical Details

### Technologies Used
- **HTML5** - Structure and semantic markup
- **CSS3** - Styling with modern features (gradients, backdrop-filter, animations)
- **Vanilla JavaScript** - No frameworks or libraries required

### Key Components

#### PersonalizedNewsReader Class
Main application class that handles:
- Interest selection and tracking
- News fetching and generation
- Article processing and scoring
- Sorting and display logic
- Analytics generation
- User preferences (bookmarks)

#### Mock Data System
- Generates realistic news articles for demonstration
- 3 articles per selected category
- Includes titles, content, sources, and timestamps

#### Relevance Algorithm
```javascript
- Base score: 50 points
- Category match: +20 points per match
- Recent articles (<24h): +10 points
- Maximum score: 100 points
```

#### Priority Calculation
- **High Priority**: Relevance > 80%
- **Medium Priority**: Relevance 60-80%
- **Low Priority**: Relevance < 60%

## 📱 Browser Compatibility

- ✅ Chrome/Edge (v90+)
- ✅ Firefox (v88+)
- ✅ Safari (v14+)
- ✅ Opera (v76+)

**Note**: Requires support for CSS `backdrop-filter` for best visual effects.

## 🎯 Use Cases

- **Personal News Dashboard**: Create your own customized news feed
- **Demo/Portfolio Project**: Showcase frontend development skills
- **Learning Tool**: Study modern CSS and JavaScript techniques
- **Prototype**: Base for a real news aggregation application

## 🔮 Future Enhancements

Potential features for real-world implementation:

### Integration
- Connect to real news APIs (NewsAPI, Google News, etc.)
- Backend server for user authentication
- Database for persistent bookmarks and preferences

### Features
- Search functionality within articles
- Category filtering after fetch
- Export bookmarks to PDF/JSON
- Email digest of top articles
- Social sharing buttons
- Dark/light theme toggle
- Multi-language support

### Advanced Analytics
- Reading history tracking
- Interest trend analysis
- Personalized recommendations using ML
- Topic clustering and visualization

### Performance
- Infinite scroll/pagination
- Lazy loading of images
- Service worker for offline access
- Progressive Web App (PWA) capabilities

## 🛠️ Customization

### Changing Colors
Edit the CSS gradient values:
```css
/* Main background gradient */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Adjust to your preferred colors */
background: linear-gradient(135deg, #YOUR_COLOR1 0%, #YOUR_COLOR2 100%);
```

### Adding New Categories
Add to the `mockNewsTemplates` object in JavaScript:
```javascript
your_category: [
    {
        title: "Your Article Title",
        content: "Article content...",
        source: "Source Name"
    }
]
```

Then add a tag in HTML:
```html
<div class="tag" data-interest="your_category">Your Category</div>
```

### Adjusting Animation Speed
Modify transition durations in CSS:
```css
transition: all 0.3s ease; /* Change 0.3s to your preference */
```

## 📄 License

This project is open source and free to use for personal and commercial projects.

## 🤝 Contributing

Feel free to:
- Report bugs or issues
- Suggest new features
- Submit improvements
- Fork and customize for your needs

## 📧 Support

For questions or support, please open an issue or contact the developer.

## 🙏 Acknowledgments

- Inspired by modern news aggregation platforms
- Design influenced by glassmorphism trends
- Built with attention to user experience and accessibility

---

**Made with ❤️ for news enthusiasts and developers**

*Version 1.0 - December 2025*
