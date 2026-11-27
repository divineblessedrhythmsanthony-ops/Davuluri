# The Royal Covenant — Wedding Invitation

An editable, responsive wedding invitation website for Ratna Deepika & Easter Aaron.

## Publish with GitHub Pages
1. Open the repository **Settings**.
2. Select **Pages** in the sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then Save.
5. After GitHub finishes publishing, the site URL will appear in the Pages section. It will normally be `https://divineblessedrhythmsanthony-ops.github.io/Davuluri/`.

## Edit the invitation
Open `index.html` and edit the `INVITATION` object near the bottom:
- `bride`, `groom`: displayed names and RSVP message
- `weddingDate`: local India time in ISO format, e.g. `2026-12-18T16:00:00+05:30`
- `rsvpNumber`: WhatsApp number with country code and digits only

For venue names, addresses, map links, headings, and other visible wording, use GitHub's pencil (Edit this file) on `index.html`, make changes, and commit.

## Add photos
Upload your chosen image files to the repository, then add image elements in `index.html` where you want them. Use relative paths such as `images/bride.jpg`. No personal photos were supplied, so this version uses elegant initials instead of invented portraits.

## Add music
Upload an audio file named `wedding-music.mp3` to the repository root. The music button is already included; playback begins only after a visitor taps it.

## Details currently included
- Wedding: Friday, 18 December 2026, 4:00 PM
- Ceremony: CSI Wesley Church, Clock Tower, Secunderabad
- Reception: Sri Raja Rajeshwari Convention, Bowenpally, Secunderabad
- Reception time: intentionally marked "Time to be announced" because no time was supplied
- RSVP: WhatsApp +91 9063219894

The site uses plain HTML, CSS and JavaScript; no build tools or paid hosting are required for GitHub Pages.
