# D8A blogs

Blog content for [d8a.pro](https://d8a.pro): the series **Specs are the new code**. It has one pillar page and sixteen posts that link to each other. The series is written for Heads of Data, CDOs, CIOs and data engineering leads in Belgium and the Netherlands.

Start with the [series index](./blog/index.md). It lists every post, its primary keyword, buyer stage, the link map, the title options considered and the editorial choices behind the copy.

## The series

| # | Post |
|---|---|
| 0 | [What is D8A? The spec-driven data platform, explained](./blog/what-is-d8a.md) (pillar) |
| 1 | [Sovereign data stack](./blog/sovereign-data-stack.md) |
| 2 | [Specs are the new code](./blog/specs-are-the-new-code.md) |
| 3 | [AI is your next compiler](./blog/ai-is-your-next-compiler.md) |
| 4 | [Impact on your data team](./blog/data-team-capacity.md) |
| 5 | [Bronze is the new gold](./blog/bronze-is-the-new-gold.md) |
| 6 | [Impact on your technology stack](./blog/data-stack-storage-compute.md) |
| 7 | [Impact on your business](./blog/business-owned-data.md) |
| 8 | [D8A versus a data catalogue](./blog/data-catalogue-alternative.md) |
| 9 | [Context owner](./blog/context-owner.md) |
| 10 | [Strategy grounded in your own data](./blog/strategy-grounded-in-data.md) |
| 11 | [Data Mesh without the mess](./blog/data-mesh-without-the-mess.md) |
| 12 | [D8A vs Microsoft Fabric](./blog/d8a-vs-microsoft-fabric.md) |
| 13 | [D8A vs Databricks](./blog/d8a-vs-databricks.md) |
| 14 | [D8A vs Snowflake](./blog/d8a-vs-snowflake.md) |
| 15 | [D8A vs Palantir Foundry](./blog/d8a-vs-palantir.md) |
| 16 | [D8A vs dbt](./blog/d8a-vs-dbt.md) |

## Structure

```
README.md            this file
blog/
  index.md           posts, keywords, buyer stage, link map, title options, open items
  what-is-d8a.md     pillar page
  <slug>.md          one file per post
images/
  <slug>/hero.png    1600x900, top of the post
  <slug>/social.png  1200x627, LinkedIn share image
  <slug>/*.png       inline schematics, 1600x900
```

## How to use

- **Frontmatter.** Every post carries `title`, `meta_description`, `slug`, `canonical_url` (`https://d8a.pro/blog/<slug>`), keywords, buyer stage, series, image paths and related posts. The D8a-website repo has no blog yet. The format follows the series brief, so a future blog template can read it directly.
- **Links.** Internal links and image paths are relative (`./<slug>.md`, `../images/<slug>/...`), so they work on GitHub. When the posts move to the website, rewrite `./<slug>.md` to `/blog/<slug>`.
- **Diagrams.** Every flow or architecture diagram also has a Mermaid version below the image, so GitHub can render it without the PNG.
- **Image prompts.** Each image has an `<!-- IMAGE PROMPT: ... -->` comment above its embed, so a designer or image model can redo it.
- **Images.** All images were rendered in the D8A Brand Kit v5.0 style: Geist and Geist Mono, canvas `#F7F7F7`, ink `#262626`, body blue `#2D6FA8`, chrome dots, color frames, medallion chips only for bronze, silver and gold. They contain no stock photos or people.
- **Status.** Every post is `published: draft` and ready to publish. There are no open items.
- **Demo CTA.** "Book a D8A demo" opens an email to hello@d8a.pro, with the waitlist link next to it. When a booking page exists, swap the `mailto:` link.

## Sources

- Product facts come from `PlainsightPro/D8a-application`: CONTEXT.md, ADRs, product specs, prompts and the marketplace. Features that could not be confirmed there are not claimed.
- Voice, positioning, colours and type come from `PlainsightPro/D8a-Brand-Kit` v5.0.
- Site structure, pricing and CTA come from `PlainsightPro/D8a-website`.
- Competitor facts link to each vendor's official documentation.
