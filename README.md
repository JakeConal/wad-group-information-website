# Team members — Image map example

This is a minimal static HTML/CSS project demonstrating an image map that links faces in a group photo to individual member pages. It fulfills the assignment requirements:

- A group photo (illustrated in `images/group.svg`).
- Detailed group information and a list of members in `index.html`.
- An image map in `index.html` that navigates to each member's page when clicking on a face.

How to view

1. Open `index.html` in your browser (double-click or serve from a static server). On Windows, open the file with your browser (File > Open...).

Notes on updating the image-map

- If you replace `images/group.svg` with a real photo (e.g., JPEG/PNG), update the `<area>` `coords` in `index.html` to match the face positions. Coordinates are currently measured to match the example SVG (800x400).
- The `<area>` elements are: Alice (150,120,45), Bob (350,100,45), Carol (550,130,45), David (700,110,45).

That's it — pure HTML and CSS. If you'd like, I can add a simple script to help pick coordinates or add responsive image-map support.
