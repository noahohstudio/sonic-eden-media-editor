# Sonic Eden media editor

The studio for Sonic Eden's covers, profile picture and clips for Reels, Shorts and X.

The site is password protected. Everything it runs on (the page, its code and its images) is in `site.bin`, encrypted with AES-256-GCM; the key comes from the password (PBKDF2-SHA256, 600,000 rounds), and the password isn't stored anywhere in this repo. `index.html` asks for it and opens the studio in the browser.

All rights reserved.
