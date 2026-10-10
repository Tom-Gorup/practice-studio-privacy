# Practice Studio privacy and support pages

Static GitHub Pages site for Practice Studio. The app source is separate. The public URLs are:

- Privacy: https://practice.cybrpulse.com/
- Support: https://practice.cybrpulse.com/support.html

GitHub Pages deploys the root of the main branch. CNAME points to practice.cybrpulse.com. The existing Cloudflare DNS-only CNAME points to tom-gorup.github.io; GitHub Pages manages HTTPS. The approved privacy@cybrpulse.com and support@cybrpulse.com aliases are routed through Cloudflare Email Routing to Tom's verified mailbox.

Edit index.html and Privacy-Policy.md together for policy changes; support.html contains contact and troubleshooting instructions. home.html is the optional landing page. Check actual app behavior and the live Apple seller before changing ownership language. Practice Studio is developed by Thomas Gorup, but its current App Store seller is CHAPPIE LLC until a transfer is completed.

To preview locally, run python3 -m http.server 8080 from this directory. Publishing is a push to main; verify HTTPS, links, and mobile layout afterward.
