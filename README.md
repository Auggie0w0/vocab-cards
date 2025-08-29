# Vocab Cards

A simple but effective platform for studying, reviewing, and memorizing vocabulary with a clean, Notion-like interface.

## Features

- Create and manage vocabulary cards with words, meanings, examples, and context notes
- Organize cards into folders/collections
- Clean, minimal UI inspired by Notion
- Easy to use for personal learning
- Data persists in your browser's localStorage
- Vercel deployment for easy hosting

## Development

This project is a single-page application built with vanilla HTML, CSS, and JavaScript.

## Local Development

To run the application locally:

1. Clone this repository
2. Start a local server (any of these options):

```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have it installed)
npx serve
```

3. Access the application at http://localhost:8000 (or the port shown in your terminal)

## Vercel Deployment

This project is configured for easy deployment on Vercel.

### Deploying to Vercel

1. Push your code to a GitHub repository
2. Go to [Vercel](https://vercel.com) and sign up/login
3. Click "New Project" and import your GitHub repository
4. Keep the default settings (Vercel will automatically detect the static HTML project)
5. Click "Deploy"

### Using Vercel CLI

If you prefer using the command line:

1. Install Vercel CLI:

```bash
npm install -g vercel
```

2. Navigate to your project directory and run:

```bash
vercel
```

3. Follow the prompts to deploy your project

### Configuration

The included `vercel.json` file configures Vercel to properly serve your static site. No additional configuration is needed.