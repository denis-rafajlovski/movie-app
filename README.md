# Movie App

A movie search app that shows popular movies and lets you search by title.

**Live demo:**

## Features

- Popular movies on load, color-coded ratings
- Search by title
- Overview on hover
- Loading, empty and error states

## Built with

HTML, CSS and vanilla JavaScript (fetch, async/await, DOM manipulation), with The Movie Database (TMDB) API.

## Known limitation

The TMDB API key is visible in the frontend code. For a production app I would move API calls behind a small backend so the key stays private.

## What I learned

- How to fetch data with async/await and handle failures (checking `res.ok`, try/catch)
- The API Key is visible in the frontend so i learned that in production that should be moved in a small backend to stay private.
- How to debug an API by logging the full response before assuming its structure
