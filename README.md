# Podcast Summary API

This API provides summaries of podcast episodes using OpenAI's GPT-3 language model.

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- An OpenAI API key

## Installation

1. Clone the repository
2. Install dependencies with `npm install`
3. Create a `.env` file with the following contents:
OPENAI_API_KEY=<your_openai_api_key_here>
4. Start the server with `npm start`

## Endpoints

### `GET /shows`

Returns a list of the 10 most popular shows.

### `GET /shows/:id`

Returns information about a specific show.

### `GET /episodes/:id`

Returns information about a specific episode.

### `GET /episodes/:id/summary`

Returns a summary of a specific episode generated by OpenAI's GPT-3 language model.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.