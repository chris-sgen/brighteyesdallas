# Provenance

> **Unofficial copy — not the website of Bright Eyes Vision.** See `README.md`.

Where everything in this copy comes from, and what was changed to publish it. The same facts, as data, are in `PROVENANCE.json`.

## Words

Apart from the redesign's own words listed in the README, the pages' text comes from https://www.brighteyesdallas.com/, read from a crawl of 220 addresses (210 pages, and 10 addresses the live site answers with "not found") on the evening of October 19, 2026, Dallas time (October 20, between 01:29 and 01:40 UTC).

## Pictures and video made for this redesign

13 stills and 1 loop, made on the evening of October 19, 2026, Dallas time (October 20, between 01:31 and 01:40 UTC). None shows a person, the practice's office, a clinical result, lettering, a label or a named product. Every still was opened whole and then in enlarged regions at its full size (2304 × 1856 px; the still the loop was made from, 2048 × 2048), looking for lettering, numbers, marks that read as a brand, a recognisable product, a person or a hand, a malformed object and a border; the loop's poster and frames were looked at the same way. A still that failed was made again from a second or third prompt, two candidates each. The files here are re-encodings made by the private build (WebP through a browser canvas, H.264 without an audio track); each carries the AI label (README, Generated imagery) and was read for metadata before publishing (README, Verification). 3 pictures are used with a remark:

| Picture | Remark |
| --- | --- |
| still-home | At three times enlargement the inner side of the crossing temple shows a faint row of letter-like marks, and the far temple a darker row by the hinge. The still itself is not shipped: the home page shows the loop made from it, and its first frame as the poster. On the poster (1440 px) and in the loop (1080 px), enlarged four times, no character can be read. |
| still-desk | The clear temples show their metal core wire with a dotted texture near the hinges; it is texture, not lettering. |
| still-frames-b | The tortoiseshell front carries a small ridged oval stud by the hinge, a decoration with no character in it. |

| File (under assets/generated/) | Kind | What it shows | Made with | Pages that show it |
| --- | --- | --- | --- | --- |
| loop-home | loop | tortoiseshell eyeglasses on a linen tablecloth in morning light, the light moving slowly (made from one still, used as its first and last frame) | Higgsfield: kling-video/o3/first-last-frame, from the still still-home (fal.ai: nano-banana-pro) | 1 |
| still-contacts | still | a contact-lens case on a marble counter | fal.ai: nano-banana-pro | 12 |
| still-desk | still | clear eyeglasses on a wooden desk by a window, with a notebook and a potted plant | fal.ai: nano-banana-pro | 8 |
| still-desk-pen | still | a notebook and a pen on a desk by a window, with a flower in a vase | fal.ai: nano-banana-pro | 6 |
| still-drops-b | still | a glass dropper over a drop of water on stone | fal.ai: nano-banana-pro | 4 |
| still-exam-c-alt-1 | still | the rim of a round lens, close up and out of focus behind | fal.ai: nano-banana-pro | 17 |
| still-frames-b | still | three pairs of eyeglass frames lying flat on a stone surface | fal.ai: nano-banana-pro | 10 |
| still-greens | still | a bowl of leafy greens and orange peppers on linen | fal.ai: nano-banana-pro | 1 |
| still-iris | still | an abstract ring of warm light around a dark centre, made to look like the iris of an eye (it is not a photograph of one) | fal.ai: nano-banana-pro | 47 |
| still-kids | still | small blue eyeglasses on a wooden table with toy blocks and a paper plane | fal.ai: nano-banana-pro | 10 |
| still-lens-b | still | rimless eyeglasses on a white ground | fal.ai: nano-banana-pro | 8 |
| still-light | still | a thin ring of light over dark water | fal.ai: nano-banana-pro | 10 |
| still-reading | still | reading glasses on an open book, with a cup of tea and honey | fal.ai: nano-banana-pro | 17 |
| still-sun | still | sunglasses with amber lenses on sand | fal.ai: nano-banana-pro | 6 |

## Pictures from the live site

149 pictures published on the practice's site are used (162 counting the different cuts the redesign makes of some of them): the practice's logo and its bulb, a photograph of the front of its office, the stock photographs and drawings of its articles, the pictures and logos of the makers, insurers and payment cards its pages name, and the badges of two optometric associations. Most stand on the page where the live site shows them; the redesign also shows a page's picture on the cards and menus that lead to that page. The portraits of the practice's two doctors are not shown here (README, Hardening 7). 1 picture named only in the old theme's stylesheet could not be downloaded: it is on another host of the live site's web platform, which refused the request (HTTP 403).

## Typefaces

Lexend and Atkinson Hyperlegible Next, both under the SIL Open Font License 1.1, served from this site; the licence texts are beside the font files.

## Changes made for publishing

| Change | Count |
| --- | --- |
| Pages given the robots tag `noindex, nofollow, noarchive, nosnippet, noimageindex` and a `no-referrer` tag | 207 |
| JSON-LD blocks removed | 619 |
| Link-preview picture tags removed | 414 |
| Pages whose link-preview tags carry the disclosure | 207 |
| Link-card titles marked "Unofficial preview:" | 207 |
| Icon links removed | 414 |
| Page descriptions replaced by the disclosure | 4 |
| Forms of the practice made inert | 1 |
| Forms of another company for the practice's account not loaded (a note with a link to the live page in their place) | 2 |
| Settings of the review badge taken off | 621 |
| Places where one of the 2 doctors' portraits stood (an initials tile there now) | 8 |
| Notes "the words on this page are the live site's own" | 7 |
| Links that carried a referral code (now to the practice's own page) | 1 |
| Documents of the practice not shipped (the link leads to the live page; a note says so) | 1 |
| Map frames that carry `referrerpolicy="no-referrer"` | 206 (all carried it in the private build) |
| Canonical tags removed (pages the build makes itself) | 3 |
| Search-index entries reduced to their title and section | 3 |
| Comments taken out (stylesheet, script) | 181, 105 |
| Generated files given the AI label | 117 |
| Files of the private build not shipped | `llms.txt`, `sitemap.xml`, `_redirects`, and the practice's document |
| `robots.txt` | replaced by the preview's own (`Disallow: /`) |
| Files nothing in this copy names, not shipped | 16 |
