# Tatiana Munoz digital business card
Static site, no build step. Live at https://digitalcard.tatianamunoz.com

Deploy: push to GitHub, Vercel (framework preset: Other) redeploys on every push.
Edit contact details in index.html and tatiana-munoz.vcf. The QR (assets/qr.png) encodes name, phone, email and website; regenerate it if those change.

Availability pill: shows "Available now" 8am-9pm US Eastern (Pembroke Pines), otherwise "Away right now". Change FROM / TO / TZ in the script at the bottom of index.html.
Cache note: if you replace an image, give it a new file name so phones don't show the old one.
