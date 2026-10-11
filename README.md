# Art Music Group — Website concept

Web design concept for **Art Music Group**, a complex in Bassano del Grappa (Veneto, Italy) that combines a pro-audio and instrument distribution business with recording studios, under one roof.

> *Concepto de sitio web para Art Music Group: un solo sitio que unifica distribución, estudio de grabación y alojamiento. Estado: borrador de diseño, aún no publicado.*
>
> URL: https://mildreyruiz-ai.github.io/artmusic-group-web/

**Status:** design concept (v10), not live.

## The idea

The group's current online presence is spread across several separate sites. This concept proposes **one umbrella site** that unifies and modernizes them, while keeping each part's own identity: distribution and brands on one side, the recording studio on the other.

## Sections

| Section | Purpose |
|---|---|
| Top | Brand statement and group figures |
| The Complex | One address, one building: how the businesses connect |
| Distribution and brands | The five in-house brands and the markets served |
| Studio | Recording studios, rooms and equipment |
| Stay | On-site accommodation |
| Contact | Address and links |

## Design

- Dark interface with a red and cyan accent palette, set in Space Grotesk, IBM Plex Sans and IBM Plex Mono.
- Scroll-reveal animations built with the `IntersectionObserver` API.
- Inline SVG icons.
- Real photographs of the studio and accommodation, embedded in the page.
- Illustrated placeholders where product photography was not yet available.

## Tech stack

- HTML5, CSS3 and vanilla JavaScript, no framework and no build step.
- Google Fonts.
- Images embedded as base64, so the page is a single self-contained file of about 2.7 MB.

## Project structure

```
artmusic-group-web/
├── index.html
└── README.md
```

## Credits

- Design and front-end development: Mildrey Ruiz.
- Photographs and logo: Art Music, used with the company's permission.

## Roadmap

- Replace the illustrated placeholders with real product photography.
- Move images out of the HTML into optimized, lazy-loaded files.
- Add an Italian version of the site.
- Choose the final platform and publish.

## Development notes

Built with an AI-assisted workflow (Claude) for drafting and review. Structure, content selection, design decisions and checks are mine.

## License

© Mildrey Ruiz. All rights reserved. The code is published for reference as a portfolio piece. Photographs, logos and brand names belong to Art Music and its brands.
