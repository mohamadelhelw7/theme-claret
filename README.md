# Claret, a Shopify theme

A premium Online Store 2.0 theme for shops that sell framed art prints. Light pages, a fine light serif with uppercase labels, black accents and every painting on a softly lit wall in a floating frame drawn around one photo: a thin wooden face, a warm shadow gap and the canvas floating inside. Shoppers can find paintings by colour. It has Arabic and right to left support, Egyptian delivery features, and selling tools that usually need apps.

- **Setup guide:** [docs/setup-guide.md](docs/setup-guide.md)
- **دليل الإعداد بالعربية:** [docs/setup-guide.ar.md](docs/setup-guide.ar.md)
- **Changes:** [CHANGELOG.md](CHANGELOG.md)

## Install

- **GitHub (recommended):** Online Store → Themes → Add theme → Connect from GitHub → this repo, `main` branch.
- **Zip:** `shopify theme package` in this folder, then Online Store → Themes → Add theme → Upload zip.
- **Local preview:** `shopify theme dev --store your-store.myshopify.com`

## What's included

**Three style presets:**
- **Claret:** white pages, black type and lines, paintings on a nearly white wall.
- **Gallery:** soft grey pages and a slightly deeper wall.
- **Slate:** cool grey walls and blue-black ink.

**The frame**
- Oak, umber and espresso faces made from real frame photos, a matte black face, a warm shadow gap, a soft shadow on the wall and a gentle gallery light. No frame shows the canvas alone.
- One photo of the artwork per product is enough. Frames can come from a product option called Frame or from a product options app such as Easify: the theme changes the frame when the app's choice changes, and its own frame tiles pick the same frame in the app.
- The frame always takes the painting's own shape. Sizes written like `30 x 40 cm` set how large it hangs: the longer side of the size becomes the painting's longer side.

**Claret sections**
- **Claret header:** the store's name in the light serif with one word in italics (or your logo), the menu in small capitals beside it, and a black line under it.
- **Shop by colour:** a spectrum made of every painting's own colours. Move along it and the painting that carries the colour comes onto the wall, with its five colours, its name and a button. A marker sweeps along on its own until a shopper takes over. Colours are read from each painting's photo, or from the product's `custom.colours` metafield when you fill it.
- **Shop by style:** your style collections as rooms, each a lit wall with one of its paintings in a frame. Pick the collections in one Collections setting.
- **Spotlight:** the section stays in place while the page scrolls, and paintings slide onto a lit wall one at a time.
- **Promise band:** seven sizes, five frames and ready to hang, with line icons, on the wall colour.
- **Collection grid:** a collection's paintings as wall cards under a large heading with a View all link.
- **Claret footer:** the store's name, an email signup, menu columns and a fine line with the copyright and policies, on the wall colour under a black line.
- **Sizes everywhere:** an Overall size in Theme settings, and size sliders in every section and product block.
- Folio's sections come too: the painting hero with its art strip, Shop by style as big names, Turn of the page and the footer with recently viewed paintings.

**The product page hangs the painting.**
- The painting in its floating frame on a lit wall, beside a column that stays in view: the title in the light serif, the artist, the price and rating.
- **Frame and size:** frame tiles showing a corner of each real frame, a size dropdown with every price and a little shape to scale, and an underlined Size guide link that opens a popup with centimetres, inches and prices.
- **Add to bag** with the price and **Buy it now** in black.
- **Hanging kit:** a simple upsell for hanging material, one quiet line with an Add button.
- **Promises** with line icons, **About the painting**, accordion rows and a **delivery progress** bar whose dots radiate softly.

**Product cards** hang each painting in its frame on a piece of wall, at the same eye level, with the title in small capitals, the artist and the price in the light serif. Frame dots can be switched on.

**Motion**
- **Spectrum sweep:** in Shop by colour a marker moves along the colours until a shopper takes over, and each painting fades onto the wall.
- **Rooms:** in Shop by style the painting lifts toward you when you point at it.
- **Spotlight:** paintings slide onto the wall one at a time as the page scrolls.
- **Radiating dots:** the delivery steps send out soft rings.
- **Fade:** sections fade in gently as the page scrolls (Unveil, fade up and zoom are also in Theme settings → Motion).

**Also included:**
- **Merchandising:** the moving announcement bar, the before and after slider and the delivery timeline.
- **Upsells:** the Upsell block, Pair it with, Product add-ons, an Offer banner, Free shipping progress and the Bundle builder.
- **Customer care:** a Customer support section and the Reels video section.
- **Cart:** a cart upsell and an optional free shipping bar, in the drawer and on the cart page.
- **Shared engine:** every section from the shared engine, plus quick view and frequently bought together.
- **Store tools:** predictive search, saved items, back in stock alerts and WhatsApp.
- **Egypt and Arabic:** full Arabic with right-to-left layout, and price formats for EGP.

**Technical:**
- Theme blocks everywhere, with no external libraries or remote assets.
- Bundled fonts: Instrument Serif and Inter Tight, with Noto Naskh Arabic and Noto Sans Arabic.
- Effects only run on screen and turn off for visitors who prefer reduced motion.

## Versioning

`theme_version` in `config/settings_schema.json` goes up with every change, and `shopify theme package` names the zip after it.
