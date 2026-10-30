# **Asahi**

A glassmorphic music web app built around the Spotify API that features track, album and artist search, as well as full-track streaming for premium users. It uses the Deezer API for song previews. 
To protect user credentials, the OAuth 2.0 protocol is handled on the server-side with Node.js and Express.

## Development Setup

1. Clone the source locally:

```bash
git clone https://github.com/GustavoLimaDaSilva/Asahi.git
```
2. Install the dependencies:
```bash
npm install
```
## To Contribute

1. In your clone, create a feature/refactor branch, e.g.:
```bash
git checkout -b feature/foo
```
2. Run an instance of your branch in a local development environment:
```bash
npm run dev
```
3. Commit your changes:
```bash
git commit -m "feat: added a new foo"
```
4. Push to the branch:
```bash
git push origin feature/foo
```
5. Create a new Pull Request.

## Challenges

As of February 11th, 2026, Spotify restricted Development Mode to premium users. Since I don't have a premium account, all Spotify-related features no longer work due to the company's new policy.

If you would like to see a demo of the app working fully, please watch [this demo](https://youtu.be/EF_-aVFSSLU) (it's in Portuguese).

Future development will focus on refactoring Spotify-related features to consume the Deezer API instead.

## Built With

- React

- JavaScript

- React Router

- Node.js

- Express

### Additional Dependencies

- Lodash

- React Icons

## License
MIT © Gustavo Lima da Silva
