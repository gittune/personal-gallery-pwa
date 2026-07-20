# Personal Gallery PWA

## Project status

This project is currently in the planning and initial development stage.
No production access to the Reddit Data API has been implemented yet.

## Purpose

This is a private, non-commercial Progressive Web App for personal use.

The application will display public image and video posts from selected
subreddits in a multi-column thumbnail gallery on mobile and desktop devices.

Initial communities:

- r/Models
- r/Celebs
- r/NewYorkNine

## Planned functionality

- Read-only browsing of public posts
- Multi-column thumbnail gallery
- Larger media viewer
- Links to the original Reddit posts
- User-selected subreddit feeds
- Temporary caching to reduce API requests

## API usage

The application will use Reddit OAuth and the Reddit Data API.

It will only retrieve the public information required to display posts,
including titles, subreddit names, author attribution where available,
thumbnail and media preview URLs, timestamps, and post permalinks.

The application will not:

- Submit posts or comments
- Cast votes
- Send messages
- Perform moderation actions
- Access private messages or private communities
- Store a permanent archive of Reddit content
- Use Reddit data for AI training, advertising, profiling, resale, or research

OAuth credentials and access tokens will be stored securely on the server
side and will not be exposed to the browser.

## Distribution

The application is intended for use only by its developer.
It will not be publicly distributed or monetized.
