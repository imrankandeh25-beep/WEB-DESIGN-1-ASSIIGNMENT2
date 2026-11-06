# TalentRise Foundation Website

A static, multi-page website for **TalentRise Foundation**, an NGO in Freetown, Sierra Leone that supports young athletes and music artists through sponsorship, training, equipment, studio time and events.

## Features

- 10 responsive pages: Home, About, Sports, Music, Talents, Sponsorship, Events, Stories, Contact and Apply
- Mobile menu, talent and story filters, and event tabs, all built with pure CSS (no JavaScript)
- 4-step sponsorship application form with step validation
- Contact form and sponsorship call-to-action buttons
- Consistent navy and orange branding using CSS variables
- Basic accessibility: alt text, ARIA labels, visible focus outlines

## Tech Stack

- HTML5
- CSS3 (Grid, Flexbox, `:has()`, `:target`)
- No frameworks, no database, no backend

## Project Structure

```
talentrise_Imran/
├── .vscode/settings.json    # Live Server port (5501)
└── talentrise/
    ├── index.html           # Home
    ├── about.html           # Mission, vision, team, partners
    ├── sports.html          # Sports programs and athletes
    ├── music.html           # Music programs and artists
    ├── talent.html          # All talents with filter
    ├── sponsorship.html     # How sponsoring works, donate
    ├── event.html           # Upcoming and past events
    ├── stories.html         # Success stories with filter
    ├── contact.html         # Contact details and message form
    ├── apply.html           # 4-step application form
    ├── CSS/main.css         # All styling
    └── images/              # Photos and banners
```

## Getting Started

1. Unzip the project and open the `talentrise_Imran` folder in **VS Code**.
2. Install the **Live Server** extension.
3. Right-click `talentrise/index.html` and choose **Open with Live Server**.
4. The site opens at `http://127.0.0.1:5501`.

You can also double-click `index.html` to open it directly in a browser.

## Customizing

- **Colors:** edit the variables at the top of `CSS/main.css` (`--navy`, `--or`, etc.).
- **Content:** edit the text directly in each HTML file.
- **Images:** replace files in `images/`, keeping the same filenames or updating the `src` paths.
- **Menu:** the header and footer are copied into every page, so update all 10 files when changing navigation.

## Known Issues / To Do

- [ ] `index.html` references `images/hero.jpg`, which does not exist (use `images/home.jpg` or add the file)
- [ ] Some team and talent photos are reused for different people; add unique photos
- [ ] Forms use `mailto:`; connect them to a service such as Formspree or Netlify Forms
- [ ] "Read Full Story", "View Profile" and "Donate" links need real destinations
- [ ] Add a real donation method (mobile money, bank details or payment link)
- [ ] Replace placeholder content (stats, partners, phone, address, testimonials) with real information
- [ ] Add years to event dates and update past/upcoming events
- [ ] Compress large images (one is about 3.3 MB) and remove unused ones
- [ ] Embed a real map on the Contact page and link the social media icons
- [ ] Add meta descriptions, a favicon and social share tags

## Deployment

Because the site is fully static, it can be hosted for free on:

- [Netlify](https://www.netlify.com/) (drag and drop the `talentrise` folder)
- [GitHub Pages](https://pages.github.com/)
- [Vercel](https://vercel.com/)

## Contact

TalentRise Foundation
12 Independence Drive, Freetown, Sierra Leone
Email: info@talentrisefoundation.org
Phone: +232 76 123 456

*(Contact details are sample data from the site and should be confirmed before launch.)*

## License

© 2026 TalentRise Foundation. All rights reserved.
