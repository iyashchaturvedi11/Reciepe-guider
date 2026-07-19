# Recipe Guider 🥘

**An AI-powered React application that helps you create delicious recipes based on ingredients you have at home.** Reduce food waste and discover new meal ideas with intelligent recipe suggestions!

![Recipe Guider Demo](https://github.com/user/recipe-guider/raw/main/public/demo-video.mp4)

> **Demo Video** (Screen Recording)

<video width="100%" controls>
  <source src="https://github.com/user/recipe-guider/raw/main/public/demo-video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

## ✨ Features

- **Smart Ingredient Management**: Add and remove ingredients with an intuitive interface
- **AI Recipe Generation**: Get personalized recipe suggestions powered by OpenAI GPT-4
- **Beautiful Modern UI**: Responsive design with TailwindCSS and smooth animations
- **Fallback Recipes**: Basic recipe suggestions even when AI service is unavailable
- **Real-time Updates**: Instant recipe generation with loading states
- **Mobile Friendly**: Fully responsive design that works on all devices

## 🚀 Tech Stack

- **Frontend**: React 19, TypeScript, Next.js 15
- **Styling**: TailwindCSS v4
- **Icons**: Heroicons, Lucide React
- **AI Integration**: OpenAI API with structured output using Zod
- **Development**: Turbopack for blazing-fast development
- **Type Safety**: Full TypeScript support throughout

## 🛠️ Setup & Installation

### Prerequisites

- Node.js (v18 or higher)
- OpenAI API Key — [Get yours from OpenAI Platform](https://platform.openai.com/)

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone <your-repo-url>
   cd recipe-guider

   Install dependencies:Bashnpm install
Set up environment variables:Bash# Create .env.local file
echo "OPENAI_API_KEY=your_actual_api_key_here" > .env.local
Start the development server:Bashnpm run dev
Open the app in your browser: http://localhost:3000

🎯 How to Use

Add Ingredients — Type ingredients you have in your fridge and click the + Add button (or select from suggestions)
Generate Recipes — Click "Find Recipes" to get AI-powered suggestions
Browse Results — View detailed recipes with ingredients lists and step-by-step instructions
Cook & Enjoy — Follow the instructions to create delicious meals!

📝 Available Scripts
Bashnpm run dev      # Start development server with Turbopack
npm run build    # Build for production
npm run start    # Start production server
npm run lint     # Run ESLint
🔧 Configuration
The app uses OpenAI's GPT-4 model for recipe generation. You can modify the AI prompt and model settings in src/app/api/recipes/route.ts.
🤝 Contributing
Feel free to submit issues and enhancement requests! This project is perfect for:

UI/UX improvements
Additional recipe features
Performance optimizations
New ingredient categorization features

📄 License
This project is open source and available under the MIT License.

Happy Cooking! 👨‍🍳👩‍🍳
Built with ❤️ by Yash Chaturvedi
text**Next Steps:**

1. Copy the above content into a new `README.md` file in your project root.
2. Add your actual GitHub repo URL.
3. Place the demo video in `/public/demo-video.mp4` (or update the video source path).
4. Commit and push!

Would you like me to create the actual `README.md` file in the workspace using tools, or make an
