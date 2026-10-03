# Elmberg Properties

Single-page marketing site for [elmbergproperties.com](https://elmbergproperties.com), built with Astro.

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # static output in ./dist
```

## Editing content

Phone, email, nav links, stats, testimonials, and the comparison tables live in `src/data/site.ts`.
Each page section is a component in `src/components/`; brand colors and type are tokens at the top of `src/styles/global.css`.

## Contact form

By default the inquiry form opens the visitor's email app with a pre-filled message to `david@elmbergproperties.com`.
To receive submissions directly instead, create a form endpoint (e.g. [Formspree](https://formspree.io) or [Web3Forms](https://web3forms.com)) and set it at build time:

```sh
PUBLIC_FORM_ENDPOINT=https://formspree.io/f/xxxxxxx npm run build
```

## Photo credits

Stock photos are from [Unsplash](https://unsplash.com) under the free [Unsplash License](https://unsplash.com/license).

| File | Photographer |
| --- | --- |
| `hero-field.jpg` | [Benjamin Davies](https://unsplash.com/photos/Zm2n2O7Fph4) |
| `about-fence.jpg` | [Low Angle](https://unsplash.com/photos/QKSdzldhnoQ) |
| `handshake.jpg` | [Erika Fletcher](https://unsplash.com/photos/GJwgw_XqooQ) |
| `signing.jpg` | [Annika Wischnewsky](https://unsplash.com/photos/wNxbeoNUg_4) |
| `land-residential.jpg` | [Paul Hanaoka](https://unsplash.com/photos/5Za2sS955yg) |
| `land-acreage.jpg` | [Phil Hearing](https://unsplash.com/photos/rQwsx3S288U) |
| `land-wooded.jpg` | [Declan Sun](https://unsplash.com/photos/UsSkZWuKc5k) |
| `land-vacant.jpg` | [Qang Jaka](https://unsplash.com/photos/oqy-em7_ifM) |
| `contact-development.jpg` | [Alex Reynolds](https://unsplash.com/photos/XWVofaQ50UY) |

`team-david.webp` is the client's own photo from the original site.
