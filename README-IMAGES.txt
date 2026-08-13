This zip contains all the site's code files (HTML + CSS), fully updated
with the hero-image fit fix, the team-photo crop fix, and corrected names.

It does NOT contain the actual image files (ord-logo.png, img-home-hero.jpg,
img-about-hero.jpg, img-platform-hero.jpg, img-footer.jpg, img-team-01.jpg,
img-team-02.jpg, img-team-03.jpg, img-team-04.jpg). Those already live in
your GitHub repo exactly as you uploaded them, nothing about them needs to
change, only the code that displays them.

To finish the update:
1. Upload these 5 files to the repo (index.html, about.html, platform.html,
   case-studies.html, styles.css), overwriting the existing ones.
2. Leave the 9 image files alone, they're already correctly named and in place.
3. Commit, wait a minute for GitHub Pages to rebuild, and refresh.

What changed this round:
- Hero image containers now have a fixed height instead of a flexible
  minimum, which was the actual cause of the visible gap under some photos.
- Team photos now crop from higher in the frame instead of dead-center,
  so faces stay in view instead of getting cut off.
- Leadership Team names corrected to match how each photo actually reads:
  Chidi Okafor (CEO), Desmond Ashworth (CTO, unchanged), Arjun Vellingiri
  (Head of Sustainability Practice), Elena Reyes (VP of Customer Success).
