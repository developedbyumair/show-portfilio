# show-portfilio

show-portfilio is an experimental link-in-bio tool, where the data lives in the URL.

> **Note**
> Since the URL can become very long, it's better to use a link shortener like https://dub.co

Here's a demo page
https://show-portfilio.vercel.app/1?data=eyJuIjoiVW1haXIgQWxpIiwiZCI6Iknwn5GLIEknbSBhIFNvZnR3YXJlIEVuZ2luZWVyLiIsImkiOiJodHRwczovL2RldmVsb3BlZGJ5dW1haXIubWUvYXNzZXRzL2ltZy9CYW5uZXIuanBnIiwiZiI6IiIsInQiOiJodHRwczovL3R3aXR0ZXIuY29tL0RldkJ5VW1haXIiLCJpZyI6Imh0dHBzOi8vd3d3Lmluc3RhZ3JhbS5jb20vZGV2ZWxvcGVkYnl1bWFpci8iLCJlIjoiZGV2ZWxvcGVkYnl1bWFpckBnbWFpbC5jb20iLCJnaCI6Imh0dHBzOi8vZ2l0aHViLmNvbS9kZXZlbG9wZWRieXVtYWlyIiwidGciOiIiLCJ3IjoiIiwieSI6IiIsImwiOiIiLCJscyI6W3sibCI6Ik15IFdlYnNpdGUiLCJpIjoicGg6Z2xvYmUtZHVvdG9uZSIsInUiOiJodHRwczovL2RldmVsb3BlZGJ5dW1haXIubWUvIn0seyJsIjoiRG93bmxvYWQgbXkgcmVzdW1lIiwiaSI6InBoOmZpbGUtcGRmIiwidSI6Imh0dHBzOi8vZ29vZ2xlLmNvbSJ9XX0=

The data is converted to a base 64 string which we show-portfilio uses as a query parameter. I have tried to reduce the json keys to be as small as possible

Roadmap.

1. Templates - make different templates, the `/1` after the host is basically a template here.
2. Refactor code - a lot of repeated boilerplate code is added here - refactor it properly.

## Setup locally

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Checkout the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.
