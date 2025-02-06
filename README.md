# VisionFlow-FinalProjectTypeScript

🚀 VisionFlow 🎥
VisionFlow is a dynamic web application designed to provide personalized YouTube video recommendations based on the user's mood. Built using TypeScript, Vite, HTML, and CSS, the app integrates seamlessly with the YouTube API to deliver curated content for relaxation, motivation, focus, and more. 🌟

🎯 Features
🎭 Mood-Based Recommendations: Select your mood and get video suggestions tailored to uplift, relax, or motivate you.
🔍 Auto-Complete Search: Instantly search for videos with suggestions auto-filled based on your mood.
🔄 Load More Videos: Easily browse more content with the "Load More" button for endless discovery.
🎙️ Voice Command Integration: Search for videos or change moods using voice commands for hands-free navigation.
👤 User Profiles: Customize your profile with an avatar and track your video preferences.
🌗 Dark Mode Toggle: Switch between light and dark themes effortlessly.


🛠️ Tech Stack
Frontend: TypeScript, HTML, CSS
Build Tool: Vite
API: YouTube Data API



📂 Project Structure
css

VisionFlow/
├── src/
│   ├── components/
│   │   ├── Dashboard.ts
│   │   ├── Header.ts
│   │   ├── MoodSelector.ts
│   │   ├── UserProfile.ts
│   │   ├── DarkModeToggle.ts
│   │   └── VideoPlayer.ts
│   ├── services/
│   │   └── YouTubeAPI.ts
│   ├── styles/
│   │   └── styles.css
│   └── main.ts
├── index.html
├── package.json
└── vite.config.ts



🚀 Getting Started
Clone the repository:

bash
git clone https://github.com/your-username/VisionFlow.git
cd VisionFlow
Install dependencies:

bash
npm install
Run the application:

bash
npm run dev
Build for production:

bash

npm run build
🔑 API Configuration
Obtain a YouTube Data API key from Google Developers Console.
Replace 'YOUR_YOUTUBE_API_KEY' in YouTubeAPI.ts with your API key.
🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

📄 License
This project is licensed under the MIT License.
