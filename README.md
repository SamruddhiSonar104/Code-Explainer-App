# Code-Explainer-App

# CodeCompanion - AI-Powered Code Analysis Tool

CodeCompanion is an advanced AI-powered code companion that provides intelligent code analysis, explanation, debugging assistance, documentation generation, and more.

## Features

- **Multiple Analysis Modes**:
  - **Explain**: Get clear explanations of code functionality with step-by-step breakdowns
  - **Debug**: Identify potential bugs, logic errors, and performance issues
  - **Document**: Generate comprehensive documentation for your code
  - **Interview**: Receive practice interview questions based on your code
  - **Improve**: Get suggestions for improving code quality and performance

- **Language Support**:
  - Supports 16 popular programming languages including JavaScript, Python, Java, C++, and more

- **Smart Code Handling**:
  - Intelligent code truncation for large inputs that preserves code structure
  - Visual length indicators showing how close you are to recommended limits
  - Detailed warnings when code might be too long for effective analysis

- **Clean, Modern UI**:
  - Beautiful syntax highlighting
  - Light and dark mode support
  - Responsive design for all screen sizes

- **Database Storage**:
  - Save and revisit previous analysis sessions
  - Store code snippets and analysis results

## Getting Started

### Demo Mode

CodeCompanion includes a demo mode that works without requiring an API key. This allows you to explore the app's features with pre-generated responses for example code.

### API Key Setup (Optional)

For full functionality with real AI-powered analysis:

1. Obtain an OpenAI API key from [https://platform.openai.com/signup](https://platform.openai.com/signup)
2. Add your API key when prompted in the application

## How to Use

1. **Enter your code**: Paste or type your code in the left panel
2. **Select the language**: Choose your programming language from the dropdown
3. **Choose analysis mode**: Select from Explain, Debug, Document, Interview, or Improve
4. **Generate analysis**: Click the "Generate AI Response" button
5. **View results**: Read the detailed analysis in the right panel
6. **Copy results**: Use the copy button to save the analysis to your clipboard

## Technical Details

CodeCompanion is built using:

- **Frontend**: React, TypeScript, TailwindCSS
- **Backend**: Node.js, Express
- **Database**: PostgreSQL
- **AI**: OpenAI GPT-4o (in full mode) or pre-generated responses (in demo mode)

## Features in Development

- Support for more programming languages
- Code execution and testing
- Multi-file analysis capabilities
- Collaborative sharing features
- Mobile applications

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
