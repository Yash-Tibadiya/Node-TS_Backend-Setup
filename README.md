# 🧠 Node.js + TypeScript + Cloudinary Backend Setup

This repository provides a simple backend setup using Node.js, TypeScript, and Cloudinary for image and file uploads.

## Requirements

- Node.js
- npm
- Cloudinary account (for image/file hosting)
- TypeScript
- dotenv (for environment variable management)

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/Yash-Tibadiya/Node-TS_Backend-Setup.git
    cd Node-TS_Backend-Setup
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file at the root of the project and add your Cloudinary credentials:
    ```bash
    PORT=8000
    MONGO_URI=

    CORS_ORIGIN=*

    ACCESS_TOKEN_SECRET=
    ACCESS_TOKEN_EXPIRY=1d

    REFRESH_TOKEN_SECRET=
    REFRESH_TOKEN_EXPIRY=7d

    CLOUDINARY_CLOUD_NAME=
    CLOUDINARY_API_KEY=
    CLOUDINARY_API_SECRET=
    ```

## Running the Project

1. Start the backend server:
    ```bash
    npm start
    ```

   The server will be running on `http://localhost:8000`.

## TypeScript Configuration

The TypeScript configuration is defined in the `tsconfig.json` file. It includes options for module resolution, compiler options, and paths.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
