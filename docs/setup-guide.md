# Claret setup guide

Claret is a shop for framed art prints that reads like a fine art book: big italic titles, plates on white paper, and every painting hung on a softly lit wall in a floating frame. This guide takes you from install to a store that's ready to sell. Setting names are written as they appear in the theme editor.

## 1. Install

- **From GitHub**: go to **Online Store → Themes → Add theme → Connect from GitHub** and pick the repository and the `main` branch. Changes pushed to `main` show up automatically.
- **From a zip**: go to **Online Store → Themes → Add theme → Upload zip file**.

If a change doesn't show up on a GitHub-connected theme, open the theme card, click **View logs**, then **Actions → Reset to last commit**.

## 2. Pick a style

Go to **Customize → Theme settings → Theme styles**. You can change anything afterwards.

| Style | Look |
| --- | --- |
| Claret | White pages, black type and lines, paintings on a nearly white wall |
| Gallery | Soft grey pages and a slightly deeper wall |
| Slate | Cool grey walls and blue-black ink |

## 3. Colors and the wall

**Theme settings → Colors** has six color schemes. In the Claret style:

| Scheme | Color | Used for |
| --- | --- | --- |
| 1 | White | The page |
| 2 | The wall | The footer and quiet bands |
| 3 | Ink | The announcement bar and the hero text |
| 4 | Soft white | Free to use |
| 5 | White | Free to use |
| 6 | Ink | Free to use |

**Theme settings → Claret** sets:

- **Wall**: the color behind the paintings on cards, in Shop by style, Spotlight and the product page. It is lit softly from the front, so it looks brighter in the middle.
- **Frame on cards**: a different wood for each card (the default: espresso, oak, black and umber in turn), or one wood for all of them (oak, umber, espresso or black), or no frame.
- **Show frame dots on cards**: four small dots beside the price for the frame woods.
- **Frame option names**: product option names that show as frame tiles, for example `Frame`.

## 4. Fonts

**Theme settings → Typography**:

- **Heading font**: Newsreader (the default, as in Atelier), bundled with the theme. Red Hat Text, Instrument Serif, Inter Tight or any font from Shopify's library can replace it.
- **Body font**: Red Hat Text (the default, as in Atelier), bundled with the theme.
- **Arabic**: Noto Naskh Arabic for headings and Noto Sans Arabic for text. They only load when a page shows Arabic.
- **Accent words**: wrap words in *asterisks*, for example `The great paintings, *framed for your walls.*`. **Accent words in headings → Italic** sets them in italics.

## 5. Paintings and frames

Claret draws a frame around each product's photo, so **one clean photo of the artwork per product is enough**: the painting itself, straight on, with no frame and no background.

- **Sizes**: add a product option named **Size** (or a name listed in **Theme settings → Product cards → Size option names**) with values written like `30 x 40 cm`. The theme reads the width and height from each value. The frame keeps the painting's own shape, and the size sets how large it hangs: the longer side of the size becomes the painting's longer side, so a wide painting stays wide. The size dropdown shows a small outline of each size.
- **Frames as a product option**: add an option named **Frame** with values such as `Oak`, `Umber`, `Espresso`, `Black` and `No frame`. They show as frame tiles, and picking one changes the frame on the wall.
- **Frames from a product options app** (for example Easify): keep **Show frame tiles when frames come from an app** on in the **Frame and size** block. The tiles change the frame on the wall and pick the same frame in the app. The theme also follows the app's own swatches when shoppers click them.
- **Extra photos** (for example the painting in a room) show as thumbnails under the wall, without a frame.

## 6. Announcement bar

The announcement bar moves as a ticker in ink. Edit the messages in **Customize → Announcement bar**. **Speed** is in pixels per second, and **Mode** switches it to rotating or static.

## 7. Header

**Customize → Header** uses the **Claret header**:

- The store name as an italic serif wordmark (or your logo) at the start, the menu beside it, and Search, Account and Bag written as words at the end. **Search, account and bag** can switch to icons.
- Menu links get a fine ink underline that draws in on hover.
- **Dropdown style → Mega menu** (the default) opens each menu item with sub-links as a white panel, one column per sub-menu. A thin ink line draws across its top as it opens, and the columns rise into place. Create the menu in **Online Store → Navigation**, for example Paintings, Artists, Styles and Sizes.
- **Show language selector on desktop** is on. It appears once you add a second language in **Settings → Languages**.

## Padding

Every section has **Padding** with **Top** and **Bottom** sliders in pixels, including the header, the announcement bar, the footer and the product page (which also has **Space between blocks**). Phones use 60% of each.

Every section also has **Sizes**. Claret's own sections have a slider for each part (headings, text, paintings); the other sections have **Heading size** and **Text size**. **Theme settings → Claret → Overall size** scales everything at once. The space at the sides of the page is in **Theme settings → Layout**.

Every section with text also has **Text**:
- **Text alignment**: As designed, Left, Center or Right. Headings, text, labels, buttons, icons and links all follow it, and it mirrors on Arabic pages.
- **Heading font** and **Text font**: As designed, the theme's heading or body font (**Theme settings → Typography**), or one of the fonts that come with Claret: Newsreader, Red Hat Text, Instrument Serif or Inter Tight.

Product cards keep their own settings in **Theme settings → Product cards**.

## 8. Homepage

The homepage opens with the **Full painting hero**, then Shop by style, Spotlight, the Promise band, the Collection grid, Reviews, Before and after, videos (**Seen on the wall**), the email signup and Customer support. **Shop by colour** is still in the list but hidden: click the eye icon beside it to show it again. Each section can be moved, hidden or removed, and more sections are under **Add section**.

### Full painting hero

- One painting fills the first screen and drifts slowly, with the headline and two buttons at the bottom and the painting's name at the top, linking to it. A new painting fades in every few seconds. Shoppers tap the right side for the next painting and the left side to go back, swipe, pick one from the lines above the headline, or pause.
- **Paintings**: without blocks, the hero shows the paintings from **Paintings from** (all your paintings when it is empty), up to **Number of paintings**. Add **Slide** blocks to use your own photos instead: each slide takes a photo, a phone photo, a second photo beside it on computers, or a video, plus a credit and its link.
- **Motion**: **Move to the next painting on its own**, **Seconds per painting** and **Slow drift**. It stays still for shoppers who turn off motion on their phone.
- **Height**: on computers Fill the screen, Large, Medium, the first painting's own shape or an aspect ratio; on phones Fill the screen, Tall, the painting's shape or an aspect ratio. Fill the screen ends the hero at the bottom of the screen, under the header.
- **Look**: text color, the shade behind the text, sizes (heading on computers and on phones, text), padding and text alignment.
- Tall paintings are cropped to fill a wide computer screen. For computers, wide paintings or your own photos in Slide blocks work best; set each photo's focal point in the image picker.

### Shop by colour

- A spectrum made of every painting's own colours, grouped into reds, golds, greens, blues and neutrals. Moving along it brings the painting that carries the colour onto the wall, with its five colours under it, and shows its name, the colour code and a **Shop this painting** button.
- **Paintings from**: the collection to read colours from (up to 40 paintings).
- **The colours**: the theme reads five colours from a small copy of each painting's photo in the shopper's browser and remembers them. To set a painting's colours yourself, create a product metafield **custom.colours** of type **List of colors** and fill it; those colours are used instead.
- **Move along the colours until a shopper takes over** keeps a marker sweeping along on its own.
- **On phones** the colour strip sits right under the painting, with five colour buttons under it: a tap on Reds, Golds, Greens, Blues or Neutrals brings a painting in that colour onto the wall, and another tap moves to the next one. Shoppers can also swipe the painting left or right to step through the paintings, or tap and drag along the strip.

### Shop by style

Your style collections as rooms: a softly lit wall with one painting from the collection in its frame, the collection's name under it and a **Shop the room** link.

- Pick the collections under **Collections** (up to 8). Each room uses the collection's image, or its first painting. **Frames** sets one wood for all, or a different wood for each.

### Sizes

Everything has a size setting:

- **Theme settings → Claret → Overall size** scales Claret's text and spacing everywhere. 100% is the design. **Painting size on cards**, **Painting size on cards on phones** (125% by default, because cards are narrow on phones), **Title size on cards** and **Price size on cards** set the product cards.
- Each section has a **Sizes** group: the header (logo height and width, text logo, menu text), the announcement bar (text), the hero (height, heading, link and credit, strip paintings), Shop by style (small title, style names, painting), Spotlight (titles, text, wall, painting), Turn of the page (book, painting, titles, text), the footer (headings, recently viewed paintings, text, store name width) and the product page (wall height, painting on the wall, title, price, text).
- Product blocks: frame tile size and text size (Frame and size), button height and text size (Buy buttons), and a size for the hanging kit, the promises (icon and text) and the delivery bar.

### Spotlight

The section stays in place while the page scrolls, and paintings from a collection slide up onto a lit wall one at a time, each in its frame. Beside the wall, the painting's title, artist and price change with it, with a counter and a thin progress line.

### Promise band

Up to four promises on the wall colour, each with a line icon, a title and a short note. Claret starts with Seven sizes, Five frames and Ready to hang. Change the words to match your shop.

### Collection grid

A collection's paintings as wall cards under a large heading, with a **View all** link. Pick the **Collection**, how many paintings and the columns.

### More sections

Claret's sections are also included: the **Painting hero** with its art strip, **Turn of the page** (a collection as an open art book) and the **Recently viewed footer**.

### Before and after

Two photos to compare, for example a bare wall and the same wall with the painting. Shoppers drag the line between them.

### Reviews, videos and customer support

- **Reviews**: paste real reviews only, one per block.
- **On your walls**: the **Reels** section, short vertical videos of the paintings in customers' homes. Upload each video under **Content → Files** (9:16 works best).
- **Customer support**: each **Contact option** block opens a WhatsApp chat, a phone call, an email or a link.

There is an email signup on the homepage (**Newsletter**) and one in the footer on every page.

## 9. Product cards

**Theme settings → Product cards → Card layout → On the wall** (the default) hangs each painting in its frame on a piece of softly lit wall, at the same eye level, with:

- the title in italics and the artist (the product's vendor) underneath;
- the price and the four frame dots.

The painting lifts a little when shoppers point at the card. Quick view and saved items work too.

## 10. Product page

The product template has five sections.

### 1. Product on the wall

- **The wall**: the painting hangs in its floating frame under a soft gallery light (**Gallery light on the painting**). Picking a frame changes the wood; picking a size changes how large it hangs. The frame always keeps the painting's shape.
- **The details** sit in a column that stays in view. Every part is its own block, so you can move it, hide it or set it on its own. Each block has **Text** (**Alignment**: as the section, Left, Center or Right, and **Font**) and **Padding** (**Top** and **Bottom**), and changing one never changes the others:
  - **Painting name**: with its own **Size** and **Size on phones**.
  - **Artist line**: the artist (the product's vendor, hidden when it is the store's name) and the note from the metafield **custom.artist_note**.
  - **Painting price**: with its own **Size** and **Size on phones**.
  - **Star rating**: shows once your review app saves a rating on the product.
  - **Frame and size**: the frame tiles, the size dropdown with every price, and an underlined **Size guide** link that opens a popup with every size in centimetres and inches, and your tips.
  - **Stock status**.
  - **Buy buttons**: **Add to bag** with the price, and **Buy it now** in black, which goes straight to checkout.
  - **Hanging kit**: one quiet line with a small **Add** button. Pick your hanging kit product in the block. Once added, it goes to the bag with the painting and its price is added to Add to bag.
  - **Promises**: three short promises with line icons. An offer such as buy 2, get 1 free needs a matching automatic discount in **Discounts**.
  - **About the painting**: the product's description, folded.
  - **Accordion** rows, for example sizes and frames, and delivery and returns.
  - **Delivery progress**: order today, we ship it and delivered, with dates counted from today. Set the days to your real times, and switch off the days you don't ship.
- **Sticky Add to bag bar**: once a shopper scrolls past the buttons, a bar with the painting, its price and Add to bag slides up at the bottom. Choose phones and computers, phones only, or off under **Sticky Add to bag bar** in the section.
- **Sizes on phones**: phones have their own **Wall height** and **Painting size on the wall** in the section, and the **Painting name** and **Painting price** blocks have their own **Size on phones**, so you can set the product page for phones without changing it on computers.

### 2–5. The other sections

**Reviews**, **On your walls** (videos), **You may also like** and, at the end, **Questions and answers**.

## 11. Cart

- **Theme settings → Cart**: after adding to the cart, open the drawer, the cart page or checkout.
- **Free shipping bar**: turn on **Show a free shipping bar in the cart** and enter **Free shipping from** in your store currency. It's only a message: set the real rate in **Settings → Shipping and delivery**.
- **Cart upsells**: the cart drawer and the cart page suggest products under the cart.

## 12. Collection page

**Main collection** shows the collection name, description and the wall cards with filters. Set up filters (artist, style, size, price) with the **Search & Discovery** app.

More paintings load as shoppers scroll (**Load as shoppers scroll**, the default). While they load, a row of empty cards holds their place. **Load more button** and **Page numbers** are the other choices.

## 13. Footer

The **Claret footer**, on the wall color under a black line:

- **Recently viewed**: the paintings a shopper looked at last hang in the frames they chose, in the store name's place beside the email signup. Until they have looked at one, the store name shows there, unless you pick a collection to show before then.
- The store's name in the light serif (wrap a word in *asterisks* to set it in italics), or a logo image.
- **Email signup**: **Join the list**. Signups are saved in **Customers** with the `newsletter` tag.
- **Menus** in columns, and a fine line with the copyright, policy links, payment icons and the language selector. The selector shows once your store has a second language in **Settings → Languages**. Social links can be switched on under **Bottom line** too.

## 14. Motion

**Theme settings → Motion**:

- **Scroll reveal → Fade** (the default): sections fade in gently as they come into view. Unveil, Fade up and Zoom are also there.
- Claret's named movements have their settings in their own sections: the **spectrum sweep** in Shop by colour, the **rooms** in Shop by style, **Spotlight**, and the **radiating delivery dots**.
- Visitors who turn on reduced motion in their device settings see every page without movement.

## 15. Before you add photos

**Theme settings → Layout → Frames without a photo** shows simple drawn paintings (a landscape, a portrait, a branch, an abstract) until you add photos. **Drawing color 1–4** set their colors.

## 16. WhatsApp, Arabic and EGP

- **Theme settings → WhatsApp**: turn on the floating button and enter your number with the country code, digits only (for example `201001234567`).
- Add Arabic in **Settings → Languages**. The theme switches to right-to-left automatically, and the book turns its pages the other way. Translate products with **Translate & Adapt**.
- The currency format comes from **Settings → General → Store currency**. **Theme settings → Language and currency** can hide `.00`.

## 17. Store setup checklist

- **Menus**: `main-menu` (the header and the footer's first menu) and `footer`.
- **Products**: one photo of the artwork, a **Size** option written like `30 x 40 cm`, and a **Frame** option or your product options app.
- **The artist**: put the artist in the product's **Vendor**. An optional product metafield `custom.artist_note` (single line text) shows beside it, for example `Danish, 1863–1935`.
- **Collections**: one per style and one per artist. Add the styles to **Shop by style**.
- **Hanging kit**: create it as a product and pick it in the **Hanging kit** block.
- **Shipping**: set rates in **Settings → Shipping and delivery**, then match the delivery progress and the free shipping bar to them.
- **Reviews**: install a reviews app. The stars read the `reviews.rating` metafield.

## 18. Pages to create

| Page | Template |
| --- | --- |
| About | `about`: your page content, a statement, Shop by style and customer support |
| Contact | `contact` |
| Reviews | `reviews` |
| Shipping | `shipping`: the delivery areas with time and fee |
| Build your bundle | `bundle`: the Bundle builder |

## 19. Speed and accessibility

- Fonts are bundled and only the ones in use load. Images are sized responsively and lazy loaded. The frames are drawn with CSS around one photo.
- Effects only run while on screen. Visitors who turn on reduced motion see every painting still.
- The menu, search, drawers, the art strip (arrow keys), the frame tiles, the size dropdown, the size guide, the book (arrow keys) and the accordion rows work with the keyboard and screen readers.

## 20. Upsells and bundles

Five upsell types are included. Add the first four as blocks on the product page (**Customize → Products → Add block → Upsells**), and the Bundle builder as a section on any page.

- **Pair it with**: products that go with this one, each with its own add button, so they go to the cart on their own.
  - **Style**: rows, a spotlight box, a slider of cards, or rows with a Quick view button (best for products with many options).
  - **Products**: related (chosen by Shopify), complementary (set in the Search & Discovery app) or picked by you.
  - **Note under each product**: a short line, such as a real discount you set up in **Discounts**. Leave it empty if there is none.
- **Product add-ons**: extras that go to the cart together with this product when ticked, shown as checkbox rows, tiles that show a check, or cards with a switch. **Badge on each add-on** adds a short label. Use it only for something true.
- **Offer banner**: a small banner with an image or icon, a heading and a line of text, in a dashed, filled or outlined frame. It can link to a page. Set up the offer itself in **Discounts** first.
- **Free shipping progress**: shows how far the cart is from free shipping, with a "You" marker on the bar, and updates when something is added. Enter **Free shipping from** in your store currency, matching **Settings → Shipping and delivery**. Left empty, it uses **Theme settings → Cart → Free shipping from**.
- **Bundle builder** (a section): shoppers fill a set number of slots and add the whole bundle to the cart at once.
  - Add a **Tab** block for each collection, or pick one **Collection** for a single list.
  - **Pieces in a bundle** sets the number of slots, from 2 to 8. **Let shoppers add the bundle before it's full** allows smaller bundles.
  - The bundle doesn't change prices by itself. For a bundle discount, create an automatic discount in **Discounts** (for example an amount off when buying 3 items from these collections) and describe it in **Offer line**.
  - To make a bundle page, go to **Online Store → Pages → Add page** and pick the **bundle** template.

Products already in the cart are left out of the suggestions, and sold out products are not shown.

**In a new store** Shopify has no suggestions yet, so these upsells, Frequently bought together, the product recommendations and the cart suggestions show other products from the same collection, or from the whole store, until it does. Products you pick in a block are always shown first. Frequently bought together uses **Heading before Shopify has suggestions** meanwhile, so it doesn't claim the products are bought together.
