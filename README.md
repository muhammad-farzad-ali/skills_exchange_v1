# Student Digital Skills Exchange

A static website (hosted on GitHub Pages) that promotes the Student Digital Skills Exchange community.

## Project Structure
```
├─ index.html            # Landing page
├─ students.html         # Student information & sign‑up form
├─ businesses.html       # Business request form
├─ faq.html              # Frequently asked questions
├─ testimonials.html     # Testimonials placeholder
├─ about.html            # Mission & contact
├─ resources.html        # Free tools & guides
├─ impressum.html        # German legal imprint (placeholder)
├─ datenschutz.html      # German privacy policy (placeholder)
├─ style.css (optional) # Minimal custom CSS (Tailwind handles most)
└─ .github/workflows/gh-pages.yml  # GitHub Actions deployment
```

## Development
- Uses plain HTML + Tailwind CSS (via CDN).
- Forms point to placeholder Google Form URLs which can be replaced later.
- CI workflow automatically deploys to GitHub Pages on every push to `main`.

## License
MIT (or any license you prefer)
