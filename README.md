# Lede Press

Lede Press is a daily public edition of product stories at [ledepress.com](https://ledepress.com). Each story is a page a reader can open: what the product is, who it is for, and why it might matter. The homepage is that day’s index. The story keeps its own URL after the day moves on.

A reader uses the edition to discover a product with enough context to decide whether to look further. A maker uses it to put a clear, permanent introduction on the public web, filed by category, instead of a logo in a catalog.

## What is a Lede Press story?

A Lede Press story is one product, one page, written so a stranger can retell it. The title names the product and the job. The opening says who it is for. The body is something a person can finish. The page lives at a stable address on ledepress.com, in a category a reader would browse later.

It is not a directory row. A directory stores a name, a mark, and a link. An edition page stores sentences. If there is nothing to understand, it does not belong in the day’s index.

## Who it is for

**Readers** who want a finished daily index of products, not an endless logo wall. They can open one story, learn the job it does, and leave — or follow the product if it fits.

**Makers** who need a public write-up that still makes sense next month. The day’s homepage announces the story. The URL, title, and category are what keep it findable after that announcement scrolls off.

**Editors and answer systems** that need a specific page to point at. A story that names the product, the person, and the job in the first paragraph can be quoted. A tagline cannot.

## What a reader gets

- A dated index. Today’s stories are labeled as today’s stories. Yesterday stays yesterday.
- A page per product, with a title and a short deck that say who it is for.
- A category to browse when they come back looking for a kind of product, not a day.
- Writing that can be repeated: name, job, person, and a limit. Not “powerful platform for modern teams.”

The edition is meant to be finished. Five to twenty real stories beat a hundred captions. If a story is not ready, it waits for a later day instead of shipping as a placeholder.

## What a maker gets

A project for the product, then a publication: a readable page on Lede Press, listed on the homepage the day it goes live, and left up at its own URL afterward.

The page is the record. Anyone can open it and see what was published. Corrections update that same URL. The story does not vanish when the next edition starts.

Plans — what is included, how a day fills up, and what the full editorial package adds — are on the [pricing page](https://ledepress.com/pricing). The [submit page](https://ledepress.com/submit) is how a product enters the edition. This README is the public description of the press, not the rate card.

## How an edition day works

The homepage is an index, not a reprint of every article. Each row needs a title, a deck, the day, and a way into the story. Free stories in a day go live together at 08:00 UTC, so the page has an edge a reader can plan around. A paid story can join the day it is ready and does not take a free slot.

Older stories leave the day’s index and stay on their category, tag, and project pages. A story that only exists for 24 hours was never a publication.

## How this is different from a product directory

| A directory | Lede Press |
| --- | --- |
| A grid of logos | A day of stories you can finish |
| A name and a URL | Sentences: what it is, who it is for |
| Sort and filter a pile | Publish a set, then file it |
| The row is the product | The page is the product; the homepage points at it |

Search and answer systems need a URL, a name, and sentences. The edition page has those. The index tells a person what was published today. The category tells them where to look next week.

## What we will not publish

- A logo with a link and nothing to read.
- A page that misstates what the product does.
- A draft that points the reader somewhere other than the product.
- A second story that adds nothing to one already live.
- Copy that is not the maker’s to publish.

The working rules are on the [editorial page](https://ledepress.com/editorial). Corrections and takedowns go to [hi@ledepress.com](mailto:hi@ledepress.com) with the page URL.

## How to read a page before you trust it

Open the URL. Check that the product is named, that the first paragraph says who it is for, and that the page is still the one you were sent. Category and title should agree with the body. If a fact changed, the correction belongs on that URL, not in a new post that orphans the old one.

Lede Press does not promise a ranking, a traffic number, or a citation. It promises a public page a person can read and a stranger can find later.

## Guides and tools

Notes from the desk:

- [How to write the first paragraph of a product story](https://ledepress.com/blog/how-to-write-a-product-story-opening)
- [What a daily product edition should include](https://ledepress.com/blog/what-a-daily-product-edition-should-include)
- [How to file a product story so readers can find it later](https://ledepress.com/blog/how-to-file-a-product-story)

Free tools, in the browser, no account:

- [Lede grader](https://ledepress.com/tools/lede-grader) — does the opening name the product, the job, and the reader?
- [Deck fitter](https://ledepress.com/tools/deck-fitter) — will the title and deck survive a short preview?
- [Edition clock](https://ledepress.com/tools/edition-clock) — the next 08:00 UTC edition in your local time.

More notes live on the [blog](https://ledepress.com/blog). More utilities live on [tools](https://ledepress.com/tools).

## The sister presses

The same desk publishes four different reading styles. Use the one that matches the piece.

- [Hed Press](https://hedpress.com) — opener-first stories. Who, what, and for whom in the first lines.
- [Listed Press](https://listedpress.com) — criteria-led shortlists for people comparing options.
- [Piece Press](https://piecepress.com) — longer explainers around one buyer question.

Lede is the daily index: one product story per page, listed the day it publishes.

Launch-platform sites from the same desk, for a different job: [Best Launch Platforms](https://bestlaunchplatforms.com) and [Product Hunt Alternatives](https://producthunt-alternatives.com).

## Questions

### What is today’s edition?

The homepage index for that day. Each item is a product story with its own URL. The index points at the story. It does not replace it.

### How is a story different from a project?

A project is the product record: name, site, summary, category. A publication is the edition page written about that product. Readers meet the publication. The project is the file it belongs to.

### Does a story stay up after the day ends?

Yes. It leaves the day’s index and stays at its URL, in its category. The day was the announcement. The URL is the publication.

### Where do I see plans?

On [ledepress.com/pricing](https://ledepress.com/pricing). Submit from [ledepress.com/submit](https://ledepress.com/submit).

### Who do I write about a correction?

[hi@ledepress.com](mailto:hi@ledepress.com). Include the page URL.

## Run the app

Next.js, React, TypeScript, Tailwind, Postgres, Drizzle, Auth.js.

```bash
npm install
cp .env.example .env.local
npm run dev
```

Set `AUTH_SECRET` and `DATABASE_URL`. Add `EMAIL_FROM` and `AUTOSEND_API_KEY` for magic links. Without an email key, development prints the link in the server log. Google and GitHub buttons need their client id and secret.

The public site is [ledepress.com](https://ledepress.com).
