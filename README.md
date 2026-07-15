# Darshan A Portfolio

Personal portfolio site for Darshan A, an AI/ML Engineer.

## Live Preview

- Local development: `npm start`
- Production build: `npm run build`

## Highlights

- Animated hero, about, projects, contact, and footer sections
- Custom project showcase for a Sentiment Analysis Web App
- Custom sentiment-analysis dashboard artwork in `src/assets/`
- Responsive layout with reduced-motion support
- Clean footer with LinkedIn and GitHub links

## Project Structure

- `src/index.html` - page markup and content
- `src/index.js` - browser behavior and animation hooks
- `src/styles.scss` - main SCSS entry point
- `src/sass/sections/` - section-specific styling
- `src/sass/layout/` - layout styling
- `src/assets/` - images, resume, and project artwork

## Run Locally

1. Install dependencies:

```bash
npm install
```

2. Start the development server:

```bash
npm start
```

3. Open the local URL shown by Parcel, usually:

```bash
http://localhost:1234/
```

## Build For Production

```bash
npm run  build
```

## Deployment

The simplest deployment path is Vercel:

1. Push the repository to GitHub.
2. Import the repo into Vercel.
3. Use `npm run build` as the build command.
4. Set the output directory to `dist`.
5. Deploy.

## Customization Notes

- Update your personal details in `src/index.html`.
- Replace or add project visuals inside `src/assets/`.
- Adjust section animations and styling in `src/sass/sections/`.
- Keep your resume PDF in `src/assets/` and point the About button to it.

## License

This project is MIT licensed. Keep the `LICENSE.md` file to preserve the reuse terms for the code in this repository.
