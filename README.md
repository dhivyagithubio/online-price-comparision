PriceWise - AI-Powered Price Comparison Website
A modern, multilingual price comparison platform that helps users find the best deals across major Indian e-commerce platforms including Amazon, Flipkart, Meesho, Myntra, Ajio, and Shopsy.

🌟 Features
🤖 AI Chatbot Assistant
Interactive chatbot for natural language product queries
Intelligent product extraction from user messages
Contextual responses and recommendations
Minimizable chat interface with typing indicators
🌐 Multi-Language Support
5 Languages: English, Hindi, Kannada, Telugu, Tamil
Complete UI translation including chatbot responses
Language-specific user preferences
💰 Smart Price Comparison
Real-time price comparison across 6 major platforms
Intelligent product matching and filtering
Price range filtering based on expected budget
Cheapest price and best quality recommendations
📱 Mobile App Integration
Direct deep linking to shopping apps
Android intent URLs for seamless app opening
iOS app scheme handling with web fallbacks
Automatic mobile app detection
🎯 Advanced Search Features
60+ product categories and subcategories
Recent searches and popular searches
Auto-suggestions in search form
Expected price filtering
💾 User Data Management
Search history storage (localStorage simulation)
User preferences tracking
Popular searches analytics
Query storage for backend simulation
🚀 Live Demo
Deployed Site: https://price-comparison-web-buq2.bolt.host

🛠️ Tech Stack
Frontend: React 18 + TypeScript
Styling: Tailwind CSS
Icons: Lucide React
Build Tool: Vite
Deployment: Netlify
State Management: React Hooks
Storage: LocalStorage (Backend Simulation)
📦 Installation
Prerequisites
Node.js 18+
npm or yarn
Setup Instructions
Clone the repository
git clone <repository-url>
cd price-comparison-website
Install dependencies
npm install
Start development server
npm run dev
Build for production
npm run build
Preview production build
npm run preview
🏗️ Project Structure
src/
├── components/           # React components
│   ├── Header.tsx       # Top navigation with features
│   ├── SearchForm.tsx   # Product search form
│   ├── PriceResults.tsx # Price comparison results
│   ├── ChatBot.tsx      # AI chatbot interface
│   ├── LanguageSelector.tsx # Language switcher
│   ├── OffersSection.tsx    # Live offers display
│   └── RecentSearches.tsx   # Search history
├── utils/               # Utility functions
│   ├── translations.ts  # Multi-language translations
│   ├── mockData.ts     # Sample product data
│   ├── deepLinkGenerator.ts # App deep linking
│   ├── platformConfig.ts    # Platform configurations
│   └── userStorage.ts  # User data management
├── types/              # TypeScript type definitions
│   └── index.ts
├── App.tsx            # Main application component
├── main.tsx          # Application entry point
└── index.css         # Global styles
🎨 Supported Platforms
Platform	Web Support	App Deep Link	Categories
Amazon	✅	✅	All
Flipkart	✅	✅	All
Meesho	✅	✅	Fashion, Home
Myntra	✅	✅	Fashion
Ajio	✅	✅	Fashion
Shopsy	✅	✅	All
🌍 Supported Languages
English (en) - Default
Hindi (hi) - हिंदी
Kannada (kn) - ಕನ್ನಡ
Telugu (te) - తెలుగు
Tamil (ta) - தமிழ்
📱 Mobile App Integration
Android Deep Links
Uses Android Intent URLs
Automatic fallback to web browser
Package-specific app opening
iOS Deep Links
Custom URL schemes for each platform
Graceful fallback handling
Safari integration
🔧 Configuration
Environment Variables
No environment variables required for basic functionality. All data is currently mocked for demonstration.

Netlify Configuration
The project includes a netlify.toml file with:

Build settings
Redirect rules for SPA
Security headers
Caching configuration
🚀 Deployment
Netlify (Recommended)
Connect your repository to Netlify
Build command: npm run build
Publish directory: dist
Deploy automatically on push
Manual Deployment
npm run build
# Upload dist/ folder to your hosting provider
🤖 AI Chatbot Features
Natural Language Processing
Product name extraction from queries
Price range detection
Context-aware responses
Supported Query Types
"Find iPhone under 50000"
"Show me running shoes"
"Compare laptop prices"
"What's the cheapest headphones?"
Response Types
Product search results
Price comparisons
Platform recommendations
Help and guidance
📊 Analytics & Storage
User Data Tracking
Search queries with timestamps
Language preferences
Popular search analytics
Recent search history
Data Storage
Currently uses localStorage for:

User preferences
Search history
Popular searches
Query analytics
🎯 Future Enhancements
 Real API integration with e-commerce platforms
 User authentication and profiles
 Price alerts and notifications
 Advanced filtering options
 Product reviews integration
 Wishlist functionality
 Social sharing features
🐛 Known Issues
Mock data is used for demonstration
Real-time pricing requires API integration
Some deep links may not work on all devices
🤝 Contributing
Fork the repository
Create a feature branch
Make your changes
Test thoroughly
Submit a pull request
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
React and TypeScript communities
Tailwind CSS for styling
Lucide React for icons
Netlify for hosting
📞 Support
For support and questions:

Create an issue in the repository
Check the documentation
Review the code comments
Built with ❤️ for smart shopping decisions
