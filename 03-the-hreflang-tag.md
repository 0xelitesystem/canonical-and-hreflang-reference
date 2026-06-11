# The hreflang tag

The hreflang tag tells search engines that a page has versions for different languages or regions, and which version is meant for which audience, so the engine shows each user the version in their language and region. It is used when you have the same content adapted for multiple languages or locales.

## What it does

Hreflang annotations declare the set of language and region versions of a page and label each with the language, and optionally the region, it targets. This lets the engine show a user the version matching their language and location rather than an arbitrary one. For a site serving multiple languages or regions, hreflang is what ensures a French-speaking user sees the French version and a user in one region sees the version meant for it. It routes users to their version.

## Language and region

Hreflang can target by language alone, or by language plus region, depending on how specific your versions are. A site with one version per language uses language targeting; a site that also adapts content for specific regions within a language uses language-and-region targeting. The granularity of the hreflang annotations should match the granularity of your actual versions. Targeting more specifically than your content warrants, or less specifically than it needs, both cause mismatches.

## Reciprocal annotations

Hreflang must be reciprocal: every version in the set links to every other version, including itself, with consistent annotations. If page A lists page B as its French version, page B must list page A as its version too, and both must list themselves. This mutual, complete set of annotations is what lets the engine understand the group as a coordinated set of alternatives. Missing or one-sided annotations break the relationship, which is the most common hreflang error.

## It is not for duplicates

Hreflang routes users among genuinely different language or region versions; it does not consolidate duplicates the way canonical does. The versions in an hreflang set are all valid pages meant for different audiences, not copies to collapse into one. Confusing the two, using hreflang where you mean canonical or vice versa, causes problems. Hreflang says these are alternatives for different users; canonical says these are the same and here is the one to use. Keep the purposes distinct.
