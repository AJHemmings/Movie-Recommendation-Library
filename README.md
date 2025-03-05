# 🎬 Movie Recommendations Library

A Movie Recommendations Library built with Next.js, Pinecone, and OpenAI embeddings that provides personalized movie suggestions based on user input.

## Table of Contents

- [Features](#features)
- [Tech](#tech)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)

## Features

- Input a movie title or description to receive similar movie recommendations.
- Store new movie descriptions as embeddings for future searches.
- Powered by OpenAI for embedding generation and Pinecone for fast similarity search.
- User-friendly interface for easy interaction.

## Tech

- Next.js
- Pinecone
- OpenAI
- OMDb API
- React

## Installation

Clone the repository:

```bash
git clone <repository-url>
cd <repository-folder>
npm install
```

## Usage

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## API Endpoints

- `POST /api/recommend` - Get movie recommendations based on input.
- `POST /api/store` - Store a new movie description as an embedding.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Submit a pull request.

## License

This project is licensed under the MIT License.
