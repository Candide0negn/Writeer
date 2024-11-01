# AI Writing Tutor

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

**AI Writing Tutor** is a user-friendly web application designed for individuals who aspire to enhance their writing skills using Artificial Intelligence. Whether you're a student, professional, or an enthusiast looking to improve your craft, this app provides a seamless interface to interact with AI-driven writing coaches inspired by renowned literary figures.

## Features

- **Interactive Chat Interface:** Engage in real-time conversations with the AI to receive personalized writing guidance.
- **Predefined Prompts:** Start your learning journey quickly with common prompts tailored to different writing aspects.
- **Custom Prompts:** Input your own queries and receive targeted feedback and suggestions.
- **Attachment Support:** Upload files and images to provide context or examples for the AI to assist you better.
- **Chat History Management:** Save, search, and manage your past conversations for easy reference.
- **Responsive Design:** Enjoy a consistent experience across desktops, tablets, and mobile devices.
- **Accessibility Optimized:** Built with accessibility in mind to ensure an inclusive experience for all users.

## Demo

![AI Writing Tutor Screenshot](path-to-your-screenshot.png)

*Illustration of the AI Writing Tutor interface.*

## Technologies Used

- **Frontend:**
  - [React](https://reactjs.org/) - A JavaScript library for building user interfaces.
  - [React Markdown](https://github.com/remarkjs/react-markdown) - Render Markdown content.
  - [Prism Syntax Highlighter](https://prismjs.com/) - Syntax highlighting for code snippets.
  - [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) - Styling with modern design principles.

- **AI Integration:**
  - [Google Generative AI SDK](https://developers.google.com/generative-ai) - Powering the AI-driven writing assistance.

- **Other Tools:**
  - [ESLint](https://eslint.org/) - Code linting to maintain code quality.
  - [Webpack](https://webpack.js.org/) - Module bundler for JavaScript applications.

## Installation

Follow these steps to set up the project locally:

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/ai-writing-tutor.git
   cd ai-writing-tutor
   ```

2. **Install Dependencies**

   Using npm:

   ```bash
   npm install
   ```

   Or using Yarn:

   ```bash
   yarn install
   ```

3. **Configure Environment Variables**

   Create a `.env` file in the root directory and add the following:

   ```env
   REACT_APP_GEMINI_API=your_google_generative_ai_api_key
   REACT_APP_IMGUR_CLIENT_ID=your_imgur_client_id
   ```

   - **REACT_APP_GEMINI_API:** Your Google Generative AI API key.
   - **REACT_APP_IMGUR_CLIENT_ID:** Your Imgur Client ID for image uploads.

4. **Start the Development Server**

   Using npm:

   ```bash
   npm start
   ```

   Or using Yarn:

   ```bash
   yarn start
   ```

   The app will be available at `http://localhost:3000`.

## Usage

1. **Launch the App**

   Open your browser and navigate to `http://localhost:3000`.

2. **Start a New Chat**

   - Click on the **New Chat** button in the sidebar to initiate a new conversation.
   - Alternatively, use one of the predefined prompts to get started quickly.

3. **Interact with the AI**

   - Type your questions or prompts in the input area.
   - Attach files or images if you want the AI to consider specific content.
   - Press **Enter** or click the **Send** button to submit your message.

4. **Manage Chat History**

   - View all your saved chats in the right sidebar.
   - Use the search bar to find specific conversations.
   - Click on a chat to revisit it or delete unwanted chats using the **Delete** button.

## Contributing

Contributions are welcome! Follow these steps to contribute to the project:

1. **Fork the Repository**

   Click the **Fork** button at the top right corner of the repository page.

2. **Clone Your Fork**

   ```bash
   git clone https://github.com/yourusername/ai-writing-tutor.git
   cd ai-writing-tutor
   ```

3. **Create a New Branch**

   ```bash
   git checkout -b feature/YourFeatureName
   ```

4. **Make Your Changes**

   Implement your feature or fix bugs.

5. **Commit Your Changes**

   ```bash
   git commit -m "Add your descriptive commit message"
   ```

6. **Push to Your Fork**

   ```bash
   git push origin feature/YourFeatureName
   ```

7. **Create a Pull Request**

   Go to the original repository and create a pull request from your fork.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this software as per the license terms.

## Contact

If you have any questions, suggestions, or feedback, feel free to reach out:

- **Email:** chrismloki@gmail.com
- **GitHub:** Candide0negn

---

*Happy Writing! ✍️*