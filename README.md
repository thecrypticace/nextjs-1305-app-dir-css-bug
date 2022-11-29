# Next.js 13.0.5 CSS HMR bug reproduction

1. `npm install`
2. `npm run dev`
3. Open `http://localhost:3000` in your browser
4. Update `page.tsx` to change the background color
5. See the HTML update but the CSS does not, resulting in a white background.
6. Edit the comment in `global.css` to trigger a CSS update.
7. See that the CSS updates and the background color changes.
