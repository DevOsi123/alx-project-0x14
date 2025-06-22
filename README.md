# alx-project-0x14

## MoviesDatabase API Integration

This project demonstrates how to consume the MoviesDatabase RESTful API using TypeScript. It provides a structured overview of the API’s features, endpoints, request/response formats, authentication, error handling, and best practices.

---

## API Overview

The MoviesDatabase API allows developers to **search for movies**, **retrieve movie details** (including genres, release info, images), and **browse trending data**. Key features include:
- Keyword-based movie search
- Detailed metadata per movie (title, genres, rating, release date)
- High-resolution images (posters, backdrops)
- Access to popular/trending movie lists

---

## Version

API Version: **v3** :contentReference[oaicite:1]{index=1}

---

## Available Endpoints

| Endpoint                             | Method | Description                                        |
|--------------------------------------|:------:|----------------------------------------------------|
| `/search/movie?query=...`           | GET    | Search movies by keyword                           |
| `/movie/{movie_id}`                 | GET    | Get detailed info about a specific movie          |
| `/genre/movie/list`                 | GET    | Retrieve list of available genres                 |
| `/movie/popular`                    | GET    | List currently popular movies                     |
| `/movie/{movie_id}/credits`         | GET    | Get cast and crew for a movie                     |

---

## Request and Response Format

### Example Request