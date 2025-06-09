# 中文学习平台 (Chinese Learning Platform)

A comprehensive online Chinese language learning platform built with Next.js, featuring interactive courses, AI-powered learning tools, and professional instruction for learners of all levels.

## 🌟 Features

- **系统化课程 (Systematic Courses)**: From beginner to advanced level, progressive course system
- **AI智能学习 (AI-Powered Learning)**: Personalized learning paths with AI assistant for real-time Q&A
- **专业师资 (Professional Teachers)**: Experienced Chinese language teaching team
- **权威认证 (Official Certification)**: Official certification upon course completion

## 🚀 Tech Stack

- **Framework**: Next.js 15+ with App Router
- **UI Components**: Shadcn/ui + Radix UI
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Package Manager**: Bun
- **Code Quality**: Biome (ESLint + Prettier alternative)
- **TypeScript**: Full type safety

## 📚 Course Offerings

- **汉语拼音基础入门 (Pinyin Basics)**: Learn pronunciation rules and fundamentals
- **基础汉字认读 (Character Recognition)**: Master common Chinese characters and stroke order
- **日常对话实践 (Daily Conversation)**: Practical dialogues for everyday communication

## 🎯 Key Statistics

- 50,000+ registered students
- 200+ premium courses
- 98% student satisfaction rate
- 24/7 online support

## 🛠️ Getting Started

### Prerequisites

- Node.js 18+ or Bun
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/johnjyang/chinese-learning-platform.git
cd chinese-learning-platform
```

2. Install dependencies:
```bash
bun install
```

3. Run the development server:
```bash
bun dev
```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 📁 Project Structure

```
chinese-learning-platform/
├── src/
│   ├── app/                 # Next.js app router pages
│   │   ├── courses/         # Courses page
│   │   ├── tools/           # Learning tools page
│   │   └── globals.css      # Global styles
│   ├── components/          # Reusable components
│   │   ├── ui/              # shadcn/ui components
│   │   ├── navbar.tsx       # Navigation component
│   │   ├── course-card.tsx  # Course card component
│   │   └── footer.tsx       # Footer component
│   └── lib/                 # Utility functions
├── public/                  # Static assets
├── package.json            # Dependencies and scripts
├── tailwind.config.ts      # Tailwind configuration
├── tsconfig.json           # TypeScript configuration
└── biome.json              # Biome configuration
```

## 🎨 Components

The platform uses modern UI components built with:

- **Radix UI**: Accessible, unstyled components
- **Tailwind CSS**: Utility-first CSS framework
- **Lucide React**: Beautiful & consistent icons
- **Custom Components**: Course cards, navigation, and more

## 📱 Features Overview

### Home Page
- Hero section with engaging call-to-action
- Feature highlights and statistics
- Popular course recommendations
- Responsive design for all devices

### Course System
- Progressive learning paths
- Interactive course cards with ratings and progress tracking
- Detailed course descriptions and prerequisites

### Learning Tools
- Interactive exercises and practice sessions
- Progress tracking and analytics
- AI-powered assistance

## 🚀 Deployment

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## 📄 Scripts

- `bun dev` - Start development server
- `bun build` - Build for production
- `bun start` - Start production server
- `bun lint` - Run linting and type checking
- `bun format` - Format code with Biome

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

For support and questions, please contact our 24/7 support team or visit our help center.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

**Start your Chinese learning journey today! 🇨🇳✨**