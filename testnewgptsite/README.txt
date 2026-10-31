BUSINESS VIDEO PRODUCTION GUIDE — STATIC SITE EXPORT

HOSTING
1. Extract this ZIP on your computer. Do not upload the ZIP itself as the website.
2. Upload every extracted file, including styles.css and all HTML pages, to the same folder or bucket location.
3. Configure your host's default/home document as index.html.
4. Serve .html files as text/html and styles.css as text/css. On AWS S3, enable Static website hosting and open the S3 website endpoint (or a CloudFront distribution), not the raw object URL.

The HTML pages link to ./styles.css and to the other pages in this archive, so their names and shared folder location must be preserved exactly. Object storage URLs are case-sensitive.

FILES
index.html is the homepage. Five separate article pages, styles.css, robots.txt, and sitemap.xml are included.
