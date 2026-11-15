# For Rafif — GitHub website package

This contains the exact current website code and assets exported from the Site. No build tools, npm, or server are required. The original letter remains replaced with the “be patient hehe” placeholder.

## Upload and publish

1. Unzip this download on your computer.
2. Create a GitHub repository, or open the one you want to use.
3. Choose Add file → Upload files. Upload the extracted contents, including the letters folder. Do not upload the ZIP itself. index.html must be at the repository's top level.
4. Commit the uploaded files to main.
5. Open Settings → Pages. Select Deploy from a branch, then main and /(root), and Save.
6. When deployment finishes, return to Settings → Pages for your website link.

Keep filenames and folder names unchanged. The .nojekyll file disables Jekyll processing; if your file picker hides it, you can create that empty file directly in GitHub.

## Files

- index.html: all HTML, CSS, JavaScript, comments, animations, and ending message.
- ck-jot-regular.ttf: your uploaded handwriting font.
- cat-transparent.png: the transparent cat used on screen.
- pink-lilies.png: the watercolor lily sticker used on the final page.
- cat.jpeg and letters/: original retained assets, included for completeness.

## Preview and edit

Open index.html in your browser after extracting the whole ZIP. An internet connection loads the secondary Google Fonts (Caveat, Patrick Hand, Indie Flower); CK Jot and the images are included locally. Edit index.html with a plain-text/code editor. Search for `const lines` for the five button comments, `const frantic` for early scribbles, `const finalLines` for the final scribbles, and `not the right time yet mommy` for the ending note. Keep the surrounding JavaScript quotes and punctuation valid.

## Privacy

This package has no password or login protection. The original Sites owner-only access is hosting-level and is not included. Ordinary GitHub Pages sites are publicly accessible, including those published from private repositories. Public repositories also expose the source and assets. Keeping a link secret is not access control. GitHub Free supports Pages from public repositories; eligible paid plans support private source repositories. Do not publish here if you require the original owner-only protection.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Exported source commit: b0be319f1eb72f8f524a5bff1b331fa1ab233be7
