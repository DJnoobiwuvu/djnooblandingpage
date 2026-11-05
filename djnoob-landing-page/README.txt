DJ NOOB STREAMING LANDING PAGE

HOW TO PREVIEW
1. Unzip the folder.
2. Open the folder in VS Code.
3. Open index.html in your browser, or use the VS Code "Live Server" extension.

CUSTOMIZE THE THREE COLORS
Open style.css and edit the first three variables under :root:
  --main      = page background
  --secondary = buttons and cards
  --accent    = highlights, borders, icons

EDIT YOUR LINKS AND CONTENT
Open index.html:
- Replace the example Spotify, Apple Music, YouTube Music and Amazon Music URLs.
- SoundCloud is prefilled with djnoobiwuvu; change it if needed.
- Replace the announcement text inside #announcementText.
- Replace "YOUR LATEST SONG" with your song title.
- Replace the YouTube video URL in the latest-card href.
- Replace the social links at the bottom.

ADD YOUR LATEST SONG ARTWORK
1. Put your square cover image in the images folder.
2. Name it latest-release.jpg (or change the image src in index.html).
3. A placeholder appears automatically if the image is missing.

PUBLISHING
For your existing GitHub Pages site, put the whole djnoob folder inside the repository's
published root. The page should then be available at:
https://cherrypuffstudios.com/djnoob/

This is a static HTML/CSS/JS page. It does not require a framework, build step, or database.
