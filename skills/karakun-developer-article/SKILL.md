---
name: karakun-developer-article
description: Package technical articles for the Karakun Developer Hub. Use the repository's Jekyll conventions and the established article structure and metadata conventions.
---

# Karakun Developer Article

## Audience and purpose

Write for software developers interested in practical, technically substantive engineering topics. The article should stand on its own and should not read like company marketing or release notes.

## Front matter

Use the Karakun Jekyll post conventions:

- `layout: post`
- `title`: visible article heading
- `seo_title`: browser/SEO title; may be shorter and keyword-oriented
- `description`: concise article description
- `authors`: author identifiers used by the site
- `featuredImage`: image basename under `assets/featuredImages/`
- `excerpt`: overview/card text
- `permalink`: explicit publication URL when required
- `categories`: relevant topical categories
- `header.text`: large page-header text
- `header.image: 'post'`

The visible article title and header text do not have to be identical to the SEO title.

## Article style

Apply the `technical-article-writing` skill as the default writing style. In particular:

- Start with a concrete problem or example.
- Introduce Groovy features because the example needs them.
- Explain the semantic or engineering consequence of each feature.
- Avoid turning the article into a Groovy 6 feature catalogue.
- Keep the prose technically precise, professional, and non-promotional.
- Assume a competent JVM developer who may not know every Groovy 6 feature.
- Use Java comparisons where they clarify a mechanism or trade-off.
- When discussing AI, focus on explicit program semantics and concrete engineering consequences rather than generic AI claims.

## Formatting

- Use Markdown naturally.
- Use headings to support the narrative, not as a rigid template.
- Avoid a table of contents unless the article is long enough to genuinely need one.
- Prefer complete prose around code examples.
- Keep code snippets focused and runnable or close to runnable when practical.
