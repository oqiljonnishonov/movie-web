<h1>movie-web</h1>


movie-web is a web app for watching movies easily.

This service works by displaying video files from third-party providers inside an intuitive and aesthetic user interface.

Features include:

- 🕑 Saving of your progress so you can come back to a video at any time!
- 🔖 Bookmarks to keep track of videos you would like to watch.
- 🎞️ Easy switching between seasons and episodes for a TV series; binge away!
- ✖️ Supports multiple types of content including movies, TV shows and Anime (coming soon™️)

## Goals of movie-web

- No ads
- No BS: just a search bar and a video player
- No responsibility on the hoster, no databases or api's hosted by us, just a static site

## Self-hosting

A simple guide has been written to assist in hosting your own instance of movie-web.

Check it out here: [https://github.com/oqiljonnishonov/movie-web/blob/main/SELFHOSTING.md](https://github.com/oqiljonnishonov/movie-web/blob/main/SELFHOSTING.md)

## Running locally for development

To run this project locally for contributing or testing, run the following commands:
<h5><b>note: must use yarn to install packages and run NodeJS 16</b></h5>

```bash
git clone https://github.com/oqiljonnishonov/movie-web.git
cd movie-web
yarn install
yarn dev
```

To build production files, simply run `yarn build`.

You'll need to deploy a cloudflare service worker as well. Check the [selfhosting guide](https://github.com/oqiljonnishonov/movie-web/blob/main/SELFHOSTING.md) on how to run the service worker. Afterwards you can make a `.env` file and put in the URL. (see `example.env` for an example)
