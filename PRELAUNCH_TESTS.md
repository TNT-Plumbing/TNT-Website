# Prelaunch Tests

Run from the project root:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080/
```

## Route Checks

- [ ] Homepage loads: `/`
- [ ] Water heater page loads: `/water-heater-repair-atlanta/`
- [ ] Leak repair page loads: `/leak-repair-atlanta/`
- [ ] Drain cleaning page loads: `/drain-cleaning-atlanta/`
- [ ] Toilet repair page loads: `/toilet-repair-atlanta/`
- [ ] Water pressure page loads: `/water-pressure-repair-atlanta/`
- [ ] Emergency plumber page loads: `/emergency-plumber-atlanta/`
- [ ] Residential plumbing page loads: `/residential-plumbing-atlanta/`
- [ ] About page loads: `/about/`

## Conversion Checks

- [ ] Quick Problem Finder buttons work
- [ ] Header nav works
- [ ] Footer links work
- [ ] Mobile sticky call button works
- [ ] Phone links use `tel:+14705088904`
- [ ] Email links use `mailto:tntplumbing25@gmail.com`

## SEO/Technical Checks

- [ ] Sitemap is valid XML
- [ ] `robots.txt` points to sitemap
- [ ] No public placeholder/internal notes remain
- [ ] Logo displays naturally on desktop/mobile
- [ ] Review section is present

## Sandbox Note

The Codex sandbox blocked binding a local web server with `PermissionError: [Errno 1] Operation not permitted`. Static route resolution was checked by mapping each `/route/` to its matching `route/index.html`.
