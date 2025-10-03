# 🚀 Rick and Morty Character Explorer

A modern web application for exploring Rick and Morty characters with AI-powered features and responsive design.

[![Next.js](https://img.shields.io/badge/Next.js-15.3.3-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-18.3.1-blue?style=flat-square&logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.1-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)

## ✨ Features

- 🔍 **Browse & Search** - Explore characters with advanced filtering (name, status, gender, species)
- 📱 **Character Details** - View detailed character info and episode appearances
- 🤖 **AI Synopsis** - AI-generated character biographies using Google Gemini
- 💾 **Favorites** - Save favorite characters (localStorage)
- 🎨 **Rick & Morty Theme** - Custom Creepster font and sci-fi design
- 📲 **Responsive** - Optimized for desktop, tablet, and mobile

## 🌟 Novelty & Unique Features

What makes this Rick and Morty Character Explorer truly special:

### 🎨 **Immersive Space-Themed Design**
- **Custom Portal Logo**: Designed Rick and Morty portal logo integrated throughout the site
- **Space Background**: Dynamic starfield animations with nebula effects
- **Dark Gradient Cards**: Consistent space-navy gradients across all components
- **Typography Excellence**: Custom Creepster font for Rick and Morty authenticity
- **Text Outlining**: Character names with crisp black outlines for enhanced readability

### 🤖 **Advanced AI Integration**
- **Dual Synopsis System**: AI-powered character descriptions with intelligent fallback templates
- **Google Gemini Integration**: Context-aware character biographies (50-75 words)
- **Smart Fallback**: Template-based descriptions when AI is unavailable
- **User Feedback**: Visual indicators showing AI vs template-generated content

### 🎯 **Enhanced User Experience**
- **Equal Height Cards**: Perfectly aligned Synopsis and Episode sections
- **Smooth Animations**: Portal-inspired hover effects and transitions
- **Status Responsive Filtering**: Real-time character filtering with immediate updates
- **Smart Pagination**: Next/Previous navigation replacing infinite scroll
- **Responsive Grid**: Adaptive layouts for all screen sizes (mobile-first)

### 🔧 **Technical Innovation**
- **Next.js 15 Compatibility**: Latest framework features with async searchParams
- **Modern Architecture**: Server components with client-side interactivity
- **Type Safety**: Full TypeScript implementation with proper type definitions
- **Performance Optimized**: Turbopack for fast development, optimized images
- **API Error Handling**: Graceful degradation with meaningful user feedback

### 🌌 **Thematic Consistency**
- **Color Palette**: Custom Rick and Morty colors (rick-green, portal-blue, space-navy)
- **Visual Hierarchy**: Consistent dark gradients maintaining readability
- **Icon Integration**: Thoughtful use of Lucide icons matching the sci-fi theme
- **Loading States**: Themed skeleton components and loading indicators

### 📱 **Accessibility & Usability**
- **Screen Reader Support**: Proper ARIA labels and semantic HTML structure
- **Keyboard Navigation**: Full keyboard accessibility throughout the application
- **Color Contrast**: High contrast ratios with starlight text on dark backgrounds
- **Progressive Enhancement**: Works without JavaScript, enhanced with it

### 🎪 **Interactive Features**
- **Character Status Indicators**: Color-coded status badges (alive, dead, unknown)
- **Episode Integration**: Direct links to episode information and character appearances
- **Favorites System**: Local storage-based character bookmarking
- **Filter Persistence**: URL-based filter state for shareable searches

## 🛠 Tech Stack

- **Frontend**: Next.js 15, React 18, TypeScript
- **Styling**: Tailwind CSS, Shadcn/ui, Radix UI
- **AI**: Firebase Genkit, Google AI (Gemini)
- **API**: Rick and Morty REST API
- **Tools**: ESLint, Turbopack

## 🚀 Quick Start

1. **Clone & Install**
   ```bash
   git clone https://github.com/ttt122w/RickAndMortyCharAPI.git
   cd RickAndMortyCharAPI
   npm install
   ```

2. **Environment Setup**
   Create `.env.local`:
   ```env
   GOOGLE_AI_API_KEY=your_google_ai_api_key_here
   ```

3. **Run Development Server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:9002](http://localhost:9002)

## 📝 Available Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run start        # Start production server
npm run lint         # Run ESLint
npm run genkit:dev   # Start AI development server
```

## 📁 Project Structure

```
src/
├── app/                 # Next.js pages & layouts
├── components/          # React components
│   ├── ui/             # Shadcn/ui components
│   ├── character-*     # Character-related components
│   └── filters.tsx     # Search & filter controls
├── ai/                 # AI flows & Genkit config
├── hooks/              # Custom React hooks
└── lib/                # Utilities & API client
```

## 🔌 API Integration

Built with the official [Rick and Morty API](https://rickandmortyapi.com/):
- Character data with pagination
- Episode information
- Real-time filtering by status, gender, species

## 🎨 Design Features

- **Theme**: Muted purple (#9D7CBF) with blue-violet accents
- **Fonts**: Creepster for headings, Inter for body text
- **Components**: Accessible UI with Radix primitives
- **Responsive**: Mobile-first design with Tailwind CSS

## 🤖 AI Features

- **Character Synopsis**: Auto-generated biographies using Google Gemini
- **Firebase Genkit**: AI workflow management
- **Contextual Info**: Rich descriptions without spoilers

## 🤝 Contributing

1. Fork the repository
2. Create feature branch: `git checkout -b feature/new-feature`
3. Commit changes: `git commit -m 'Add new feature'`
4. Push branch: `git push origin feature/new-feature`
5. Open Pull Request

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🙏 Credits

- [Rick and Morty API](https://rickandmortyapi.com/) for character data
- [Shadcn/ui](https://ui.shadcn.com/) for UI components
- [Google AI](https://ai.google.dev/) for Gemini integration

---
