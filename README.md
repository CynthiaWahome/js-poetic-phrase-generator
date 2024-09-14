# Poetic Phrase & Background Generator

## Overview

The **Poetic Phrase & Background Generator** is a web application designed to produce imaginative and engaging poetic phrases about your favorite activities and destinations. By utilizing OpenAI and Unsplash APIs, the application combines witty, satirical poetry with beautiful, relevant background images.

## Features

- **AI-Generated Poetry**: Leverages OpenAI's GPT model to generate creative and humorous poetic phrases.
- **High-Quality Imagery**: Integrates with the Unsplash API to provide visually appealing background images.
- **Interactive Experience**: Customize the input to generate phrases and images based on your preferences.

## Technologies

- **JavaScript**: Core scripting language for application logic.
- **OpenAI API**: For generating poetic content.
- **Unsplash API**: For fetching high-resolution images.

## Getting Started

To set up and run the Poetic Phrase & Background Image Generator locally, follow these steps:

### Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (includes npm)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/poetic-phrase-background-generator.git
   cd poetic-phrase-background-generator
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Configure API Keys**

   Create a `.env` file in the root directory of the project and add your API keys:

   ```plaintext
   OPENAI_API_KEY=your_openai_api_key
   UNSPLASH_ACCESS_KEY=your_unsplash_access_key
   ```

4. **Run the Application**

   Start the application with:

   ```bash
   npm start
   ```

   Navigate to `http://localhost:3000` in your browser to view the application.

## Usage

1. **Input**: Enter your favorite activity or place in the provided field.
2. **Generate Content**: Click the generate button to receive a poetic phrase and a corresponding background image.
3. **Refresh**: Use the refresh button to generate new content.

## API Keys

To use the application, you need API keys from OpenAI and Unsplash:

- **OpenAI API Key**: Sign up at [OpenAI](https://beta.openai.com/signup/) to obtain your key.
- **Unsplash Access Key**: Register at [Unsplash Developers](https://unsplash.com/developers) to get your access key.

## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for more details.


