# The Royal Covenant — Wedding Invitation

A responsive, static wedding invitation website for **Dr. Davuluri Ratna Deepika & Merugu Easter Aaron**, hosted with GitHub Pages.

## Website
- Custom domain: https://wedding.growwithanthony.com
- Repository: https://github.com/divineblessedrhythmsanthony-ops/Davuluri

## Features
- Royal navy and antique-gold responsive design
- Invitation cover, family introductions, and couple sections
- Ceremony and reception schedule
- Live countdown to 18 December 2026 at 4:00 PM IST
- Google Maps direction links
- Downloadable calendar event (.ics)
- WhatsApp RSVP and guestbook message handoff
- Optional background music

## Publish with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Choose **Deploy from a branch**.
3. Select branch **main** and folder **/ (root)**, then Save.
4. Set the custom domain to `wedding.growwithanthony.com`.
5. Enable **Enforce HTTPS** once GitHub makes it available.

## GoDaddy DNS
Create this record in GoDaddy DNS:

| Type | Host | Points to | TTL |
|---|---|---|---|
| CNAME | wedding | divineblessedrhythmsanthony-ops.github.io | 1 hour |

The repository includes a `CNAME` file containing `wedding.growwithanthony.com`. Remove conflicting records for host `wedding`; do not change root-domain records used by other services. DNS propagation and certificate issuance may take time.

## Update the invitation
Edit `index.html`. The date, names, and RSVP WhatsApp number are configured in the `WEDDING` object near the bottom. Search the file for venue, family, and schedule text.

## Event details
- Friday, 18 December 2026
- Ceremony welcome: 3:30 PM
- Wedding ceremony: 4:00 PM, CSI Wesley Church, Clock Tower, Secunderabad
- Reception welcome: 6:45 PM
- Reception: 7:00 PM, Sri Raja Rajeshwari Convention, Sy.No.26, Sikh Road, Diamond Point, Sikh Village, Bowenpally, Secunderabad, Telangana 500009
- RSVP / guestbook WhatsApp: +91 9063219894

## Music
Upload an MP3 you have permission to use, named exactly `wedding-music.mp3`, to the repository root. Visitors must tap the floating music button before audio can play.

## Guestbook
The form opens WhatsApp with the visitor's name and wish pre-filled; the visitor must press Send in WhatsApp. This static GitHub Pages site does not store or publish a shared public guestbook. That requires a database/backend integration.

## Photographs
No couple photographs are bundled. The invitation uses a typography-led royal design and works without image uploads.
