# Sabaduri Hills — HTML reconstruction

Production-style static website prototype: HTML, CSS, and vanilla JavaScript; no build system required. Open `index.html` in a browser or upload the folder to a web server.

## Publishing a shareable demo (Netlify Drop)
1. Go to https://app.netlify.com/drop and sign in if required.
2. Drag and drop the extracted `sabaduri_hills_site` folder (the folder containing `index.html`, `style.css`, `script.js`, and `assets/`).
3. Netlify gives you a public `*.netlify.app` URL. Share the generated address.

Alternatively, upload all files into `/var/www/html/` or another HTTPS virtual host, or deploy via GitHub Pages.

## Photos
Images in `assets/` are captured photo previews of Sabaduri Hills appearing on publicly accessible booking/travel services, used for this authorized prototype following the user's statement that hotel photos are theirs. Some are low-resolution preview derivatives and should be replaced with original high-resolution assets before production. These are actual hotel reference photos, not generic stock photos. `hero-illustration.jpg` is **an AI-created illustrative forest image extracted from a reconstruction mockup**, not a verified historical original photograph. The design is a reconstruction, not original source code.

Photo source pages: Expedia https://www.expedia.com/Mtskheta-Hotels-Sabaduri-Hills.h111049017.Hotel-Information ; Booking https://www.booking.com/hotel/ge/sabaduri-hills-resort.html ; Web Features https://webfeatures.ge/en/projects/sabaduri-hills/ ; Jetstar https://www.jetstar.com/au/en/hotels/properties/1175249-sabaduri-hills

## Important: Booking inquiries
The booking form is a **demo**, it validates dates and composes an email request addressed to an email entered by the tester; it is NOT a hotel reservation engine and does not confirm availability. Connect the actual booking engine or set the hotel's verified reservations email before public launch.

## Notes for production
- Verify hotel contact phone/email and social media before populating (none are invented).
- Confirm room taxonomy/prices/photos and legal/privacy information.
- Replace preview images with high-resolution originals, especially `hero-illustration.jpg`.
- Optional multilingual content and CMS can be added later.
- Google Fonts are loaded over the internet; host locally if offline font support is essential.
