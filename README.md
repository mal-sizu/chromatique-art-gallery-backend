# Chromatique Art Gallery Backend

This repository contains the backend code for the Chromatique Art Gallery application. It provides APIs and services to manage art pieces, artists, exhibitions, and user interactions.

## Features

- **Artist Management**: Add, update, and manage artist profiles.
- **Art Pieces**: CRUD operations for artworks.
- **Exhibitions**: Manage gallery exhibitions and schedules.
- **User Authentication**: Secure login and registration.
- **Search and Filter**: Search for artworks and filter by artist, category, or exhibition.
- **RESTful APIs**: Well-structured APIs for frontend integration.

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [MongoDB](https://www.mongodb.com/) (or any other database you plan to use)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/chromatique-art-gallery-backend.git
    cd chromatique-art-gallery-backend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and configure the following variables:

    ```env
    PORT=5000
    DATABASE_URL=mongodb://localhost:27017/chromatique
    JWT_SECRET=your_secret_key
    ```

4. Start the development server:

    ```bash
    npm run dev
    ```

    The server will run at `http://localhost:5000`.

## Scripts

- `npm run dev`: Start the development server with hot-reloading.
- `npm start`: Start the production server.
- `npm test`: Run tests.

## API Endpoints

### Authentication

- `POST /api/auth/register`: Register a new user.
- `POST /api/auth/login`: Login a user.

### Artists

- `GET /api/artists`: Get all artists.
- `POST /api/artists`: Add a new artist.
- `PUT /api/artists/:id`: Update an artist.
- `DELETE /api/artists/:id`: Delete an artist.

### Art Pieces

- `GET /api/artworks`: Get all artworks.
- `POST /api/artworks`: Add a new artwork.
- `PUT /api/artworks/:id`: Update an artwork.
- `DELETE /api/artworks/:id`: Delete an artwork.

### Exhibitions

- `GET /api/exhibitions`: Get all exhibitions.
- `POST /api/exhibitions`: Add a new exhibition.
- `PUT /api/exhibitions/:id`: Update an exhibition.
- `DELETE /api/exhibitions/:id`: Delete an exhibition.

## Folder Structure

```
chromatique-art-gallery-backend/
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── utils/
│   └── app.js
├── tests/
├── .env
├── .gitignore
├── package.json
└── README.md
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or support, please contact [your-email@example.com].