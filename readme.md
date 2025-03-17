# PicChatter

A web application for image-based conversations and interactions. This application provides a simple interface for uploading and managing images with interactive features.

## Features

- Image upload functionality
- Web-based interface using EJS templates
- Express.js backend server
- Environment variable configuration
- Static file serving

## Prerequisites

- Node.js (v12 or higher)
- npm (Node Package Manager)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/PicChatter.git
cd PicChatter
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your configuration:
```env
PORT=3000
API_ENDPOINT=your_api_endpoint
API_KEY=your_api_key
```

## Usage

To start the server:

```bash
npm start
```

The application will be available at `http://localhost:3000` (or the port specified in your `.env` file).

## Project Structure

- `/views` - EJS template files
- `/uploads` - Directory for uploaded files
- `server.js` - Main application server
- `.env` - Environment configuration

## Dependencies

- express - Web application framework
- ejs - Templating engine
- dotenv - Environment variable management
- multer - File upload handling

## License

ISC

## Contributing

Feel free to submit issues and pull requests to improve the application.
