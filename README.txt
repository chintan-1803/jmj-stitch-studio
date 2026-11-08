JMJ STITCH STUDIO — EXPERIMENTAL V8

Website files:
- index.html: formatted HTML, CSS and JavaScript with section comments
- data/creations.json: 15 creation records (id, title, image, alt)
- assets/creations/: 15 original blouse photos
- data/feedback.json: 5 feedback records
- assets/feedback/: 5 original customer feedback images

PUBLISH TO GITHUB PAGES
Upload the CONTENTS of this folder to the repository root, not the enclosing folder or ZIP.
Keep index.html, data/ and assets/ at the repository root.

LOCAL TEST
Do not double-click index.html: browsers block local file:// JSON fetches.
From this folder run: python -m http.server 8000
Then open http://localhost:8000/

ADD A CREATION
1. Upload assets/creations/creation-16.jpg
2. Add an object to data/creations.json using the existing entries as a guide.
3. Use id 16, title Creation 16, image assets/creations/creation-16.jpg and meaningful alt text.
4. Keep previous IDs stable so old #creation-XX links still work.

JSON does not allow comments. Documentation is in this README and index.html.
