1. Put your compiled game at game/game.jar (it needs a Main-Class in its manifest).
2. Edit index.html and projects.html: replace the placeholder text and the e-mail address.
3. Java in the browser needs http(s), so file:// will not work.
   Test locally:  python -m http.server 8000   then open http://localhost:8000
   Host free: GitHub Pages, Netlify or Cloudflare Pages (upload this folder).
4. Works best for Swing/AWT games. JavaFX and heavy 3D (LWJGL) games are not supported.
