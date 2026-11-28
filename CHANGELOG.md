# Changelog

## 1.6.0
- **Hanging guide page** (`page.hanging-guide`, the Hanging guide section): Art Cellar's Atelier hanging tips in Claret's look. Each tip draws the mistake beside the right way with the store's own paintings in Claret's frames (too high, too small, wider than the sofa, not centred, uneven set, empty wall). Under them, a size finder: type the furniture's width and see the sizes that fill about two thirds of it, as one painting or a set of 2 or 3, drawn to scale. English and Arabic.
- **Language selector easier to see.** On computers, a button with a globe; with two languages it names the other language and switches in one click. On phones, a globe and the language code beside the menu button (new setting **Show language selector on phones**). The phone menu's selector has a globe and an outline.
- **Announcement bar** is white with a line under it.
- **Homepage:** Reviews, Before and after and the Reels videos are off the homepage (still under Add section).
- **Product page:** Reviews, Reels and the stock line are off the page; Questions and answers is on white; the name, artist line, price and stars are centred; the price is thinner (weight 200) and smaller (85%, 65% on phones); new **Space under the wall on phones** setting, 20px (it was about 58px).
- **Fixed:** the phone menu showed the text logo with its stars (Art \*Cellar\*) instead of the italic word.
- Setup guide: the homepage now opens with Shop by colour (the guide still said Full painting hero).

## 1.5.0
- **Shop by colour is the homepage hero again.** The Full painting hero stays in the theme, hidden on the homepage, for a video or photo hero.
- **Size guide page** (`page.size-guide`, the Size guide section): the same tool as Art Cellar's Atelier size guide, in Claret's look. Wall and furniture sizes, shape, number of pieces, sizes, a custom size, artworks and Claret's five frames, drawn to scale. Opened with `?product=<handle>`, it shows that painting's own sizes and photo. All words in English and Arabic; the number fields fit narrow phones.
- **Bulk orders page** (`page.bulk-orders`, the Bulk orders section): the same page and quote form as Art Cellar's Atelier one, in Claret's look, with the store's paintings hung on the wall at the top. Every word is a setting, the form labels are in English and Arabic, and WhatsApp falls back to the number in Theme settings.

## 1.4.0
- **New hero: Full painting.** One painting fills the first screen and drifts slowly, with the headline and two buttons at the bottom where the thumb is and the painting's name at the top, linking to it. A new painting fades in every five seconds; shoppers tap the right side for the next, the left side to go back, swipe, pick one from the lines above the headline, or pause. Paintings come from a collection (all paintings by default) or from **Slide** blocks with your own photo, phone photo, second photo or video. Settings for motion, speed, drift, text color, shade, height on computers and phones (fill the screen by default), sizes, padding and text alignment.
- It opens the homepage. **Shop by colour** is hidden (still in the section list, ready to show again), and the hidden Painting hero placeholder was removed, since the new hero takes a video, one photo or two photos.

## 1.3.0
- **Product page: every part is its own block.** The name, the artist line, the price and the star rating were fixed parts of the section; they are now the blocks **Painting name**, **Artist line**, **Painting price** and **Star rating**, so each can be moved, hidden or set on its own. The name and price blocks carry their own **Size** and **Size on phones** (these left the section's settings).
- **Every product page block has its own Text and Padding:** Alignment (as the section, Left, Center or Right), Font, and Padding Top and Bottom. Changing one block never changes another.
- The blocks sit in a flex column, so the name and artist, and the price and stars, keep their close spacing exactly (a grid stretched short blocks and added 4px).

## 1.2.0
- **Text alignment on every section with text** (72 sections, under Text): As designed, Left, Center or Right. Headings, text, labels, lists, button rows, icons, links and section heads all move together; product cards keep their own card settings. Checked on Claret's homepage, footer and product page in all three positions on computers and phones.
- **Heading font and Text font on every section with text:** As designed, the theme's heading or body font, Newsreader, Red Hat Text, Instrument Serif or Inter Tight. The Arabic font stays in each choice.

## 1.1.4
Shop by colour on phones:
- The colour strip sits right under the painting instead of below the words, so the painting and the colours are on screen together.
- Five colour buttons (Reds, Golds, Greens, Blues, Neutrals) under the strip: a tap brings a painting in that colour onto the wall, another tap moves to the next painting in that colour.
- Swipe the painting left or right to step to the next or previous painting.
- Computers are unchanged.

## 1.1.3
Product page on phones:
- New **Sizes on phones** settings in the Product on the wall section: **Wall height on phones** (120%), **Painting size on the wall on phones** (114%), **Title size on phones** (75%) and **Price size on phones** (75%). Phones no longer follow the computer sizes, so the painting hangs larger on a taller wall and the title and price are smaller. The painting also keeps less empty wall around it on phones (24px instead of 64px).
- The sticky Add to bag bar looks like the rest of Claret: a fine ink line on top instead of a shadow, the painting as a tiny framed print, the name in small capitals, the price in the light serif and a slimmer black button.

## 1.1.2
- Infinite scroll: no more "Showing X of Y", progress line or Load more button while paintings load. A row of empty wall cards holds the place of the next paintings until they arrive (one row; two cards on phones). The Load more button style keeps its count and button.
- Phones: paintings hang larger on the card walls. New setting **Theme settings → Claret → Painting size on cards on phones**, 125% by default.

## 1.1.1
- Product cards: names, artists and prices sit on the same lines across a row, whatever the length of the name. Each name keeps room for the number of lines set in Theme settings → Product cards → Title lines (2 by default), so a one-line name no longer lifts its price above the others.

## 1.1.0
Everything on the theme checklist is now in Claret.
- **Padding on every section:** a Padding heading with Top and Bottom sliders in pixels, on every section, including the header and announcement bar (which had one slider for both before), the footer, the product page, the page templates (collection, cart, search, blog, article, page, 404, password) and the heroes. The old None, Small, Medium and Large spacing became pixels (0, 24, 40 and 80). Phones use 60% of each.
- **Sizes on every section:** sections without their own size sliders get Heading size and Text size. Claret's own sections keep their sliders, and Overall size in Theme settings still scales everything.
- **Homepage:** Reviews, Before and after, a video section (Seen on the wall), an email signup and Customer support follow the existing sections, which are unchanged. A Painting hero for a video, one photo or two photos (new Second photo setting) is placed first but hidden, ready to switch on.
- **Product page:** Stock status above the buttons, and a sticky Add to bag bar that slides up once a shopper scrolls past the buttons (phones and computers by default; phones only or off in the section).
- **Footer:** payment icons and the real language selector are on. The "Language" text column is gone, so the menus sit in three columns.

## 1.0.9
- Recently viewed in the footer: the paintings hang level and their names start on the same line, even when a name runs to two lines. A long name used to push its painting up.

## 1.0.8
Phones:
- Product page rows: About the painting and Sizes and frames are the same height again. On phones the space between blocks shrinks to 60%, but the rows were still pulled together by the full space, so the second row covered part of the first. The hanging kit line no longer touches Buy it now.
- Delivery bar a size smaller, as in the design.
- Recently viewed in the footer: painting names show at most two lines, a size smaller, and the small note moves under the heading when there is no room beside it.
- Header: Search shows as an icon on phones and tablets, so only Bag stays in words beside the logo.

## 1.0.7
- Every frame colour on the collection pages and product grids: Frame on cards has a new default, A different wood for each card, which hangs the paintings in espresso, oak, black and umber in turn. Pick one wood under Theme settings → Claret → Frame on cards to use it for all cards.
- Recently viewed now sits in the footer where the store name was, beside the email signup, smaller and tighter. The store name shows there until a shopper has looked at a painting. Paintings a shopper has not framed yet take the card frames too.

## 1.0.6
- Infinite scroll on collection pages: more paintings load as shoppers scroll down. Load more button and Page numbers are still in the collection page settings.

## 1.0.5
- Recently viewed in the footer: the paintings a shopper looked at last hang in a row in the frames they chose, above the name and the email signup. It stays hidden until they have looked at one (or shows a collection you pick). Settings for the heading, note, number of paintings and painting size.

## 1.0.4
- Padding sliders in pixels: Padding above and below on Shop by colour, Shop by style, Spotlight, the Promise band (plus the padding inside it), the Collection grid and the footer; Padding above, below and Space between the blocks on the product page; Padding above and below on the header (in place of Compact, Standard and Tall) and on the announcement bar. Phones use 60% of each.
- Hanging kit: pick any product under Product to offer. Its name, photo and price show in the line; the Name and Short note fields are optional and empty by default.

## 1.0.3
- Newsreader and Red Hat Text are now bundled with the theme and are the default fonts. The menu, labels and text no longer fall back to a serif when the font library font does not load.
- Logo in the middle: the menu sits in the column beside the logo when it fits; when it does not, it moves to its own centred row under the logo instead of wrapping. The logo is in the middle by default.
- The announcement bar moves again: three messages scroll past in small capitals with a dash between them.

## 1.0.2
- The store name in the header sits on the same centre line as the menu and the Search and Bag links. Newsreader leaves room for descenders under its letters, which made the name sit about 5px higher.

## 1.0.1
- The line under the header is thinner: 2px instead of 3px.

## 1.0.0
- First release of Claret, a theme for framed art prints, built on Folio's engine and product page.
- Atelier's type: Newsreader at its lightest weight for names and headings, Red Hat Text for text, small capitals for labels and buttons.
- Black accents on light pages, and Folio's softly lit wall behind every painting.
- New sections: Shop by colour (a spectrum of every painting's colours, read from their photos or from the custom.colours metafield), Shop by style as rooms, Promise band, Collection grid and the Claret footer.
- Folio's Spotlight, in Claret's type.
- Product page: Folio's structure with the light serif title and price, frame tiles, the size dropdown and Size guide, Add to bag and Buy it now, the hanging kit, promises, rows and the delivery bar. The size menu and the size guide list only the sizes each painting has.
