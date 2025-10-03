# AI Synopsis Setup Instructions

## Setting up Google AI for Character Synopsis Generation

### 1. Get Google AI API Key
1. Visit [Google AI Studio](https://aistudio.google.com/apikey)
2. Sign in with your Google account
3. Create a new API key
4. Copy the API key

### 2. Configure Environment Variables
1. Create a `.env.local` file in your project root (if it doesn't exist)
2. Add your API key:
```
GOOGLE_API_KEY=your_actual_api_key_here
```

### 3. Alternative Environment Variable Names
Genkit supports multiple environment variable names:
- `GOOGLE_API_KEY`
- `GEMINI_API_KEY`

### 4. Restart Development Server
After adding the environment variable, restart your development server:
```bash
npm run dev
```

## How It Works

### With API Key (AI-Generated)
- Uses Google's Gemini 2.5 Flash model
- Generates creative, contextual character synopses
- Provides engaging 50-75 word descriptions

### Without API Key (Template-Based)
- Falls back to template-based synopsis generation
- Uses character data to create informative descriptions
- Still provides useful character information

## Troubleshooting

### Common Issues
1. **"FAILED_PRECONDITION" Error**: API key is missing or invalid
2. **Empty Synopsis**: Check network connection and API key validity
3. **Template Fallback**: AI generation failed, using backup system

### Testing
Visit any character detail page to see the synopsis in action. The component will automatically detect whether AI or template generation was used.

## Features
- ✅ Automatic fallback system
- ✅ User-friendly error messages  
- ✅ Visual indicators for AI vs template content
- ✅ Graceful degradation without API key