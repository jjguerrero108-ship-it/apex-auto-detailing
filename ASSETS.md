# External visual assets

The site currently references hosted visual assets instead of local image files:

- Automotive photography: Unsplash image URLs defined in the `photos` object in `src/main.jsx`.
- Typography: DM Sans and Manrope from Google Fonts, referenced in `index.html`.

The images and fonts load when the site is run with an internet connection. Replace these references with licensed local files if the project needs to work offline or use business-owned photography.
