https://github.com/user-attachments/assets/94f13a9a-d21a-4fbb-84e0-4be685bf47db

# AI Recipe Generator

AI Recipe Generator is a web application that uses artificial intelligence to create unique recipes based on ingredients provided by the user. Built with React, TypeScript, Vite, and AWS Amplify, this application leverages Anthropic's Claude 3 Sonnet model via AWS Bedrock to generate creative recipe suggestions.

## Features

- Input ingredients in a comma-separated format
- Generates unique recipes using AI
- User authentication via AWS Amplify
- Responsive design with a clean, modern UI
- Loading states and error handling

## Prerequisites

- Node.js (v18 or later)
- npm (v9 or later)
- AWS account with Amplify CLI configured
- Access to AWS Bedrock service

## Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/hritik-6918/ai-recipe-generator.git
cd ai-recipe-generator
```

2. Install dependencies:
```bash
npm install
```

3. Initialize Amplify:
```bash
amplify init
```

4. Deploy backend resources:
```bash
amplify push
```

### Running the Application

1. Start the development server:
```bash
npm run dev
```

2. Open your browser and visit:
```
http://localhost:5173
```

### Building for Production

```bash
npm run build
```

### Linting

```bash
npm run lint
```

## Technology Stack

- **Frontend**: React 19, TypeScript, Vite
- **Styling**: CSS with responsive design
- **Backend**: AWS Amplify
- **AI**: AWS Bedrock (Anthropic Claude 3 Sonnet)
- **Authentication**: AWS Amplify Auth
- **Linting**: ESLint with TypeScript support

## Configuration

### ESLint
The project includes a robust ESLint configuration with TypeScript support. To extend it further, see the ESLint configuration section in the original template documentation.

### TypeScript
Multiple tsconfig files are used:
- `tsconfig.app.json`: For the React application
- `tsconfig.node.json`: For Node.js-specific files (like Vite config)
- `amplify/tsconfig.json`: For Amplify backend

### AWS Amplify
- Authentication is configured with email verification
- Data layer uses GraphQL with Bedrock integration
- Default authorization mode is API Key (30-day expiration)

## Usage

1. Sign up or log in using the authentication interface
2. Enter ingredients in the format: `ingredient1, ingredient2, ingredient3`
3. Click "Generate" to receive an AI-generated recipe
4. View the recipe in the result section

## Acknowledgments

- Built with ❤️ by Hritik
- Powered by AWS Amplify and Anthropic's Claude 3 Sonnet
