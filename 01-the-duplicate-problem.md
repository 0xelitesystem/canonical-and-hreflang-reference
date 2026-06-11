# The duplicate problem

The same content reachable at more than one URL creates a duplicate-content problem: search engines see several pages with the same content and must guess which to rank, splitting signals between them and weakening all of them. Canonical and hreflang tags exist to tell engines which version to use.

## How duplicates happen

The same page often ends up reachable at multiple URLs without anyone intending it: with and without a trailing slash, with tracking parameters appended, over different protocols or subdomains, through different navigation paths, or in print and mobile variants. Each variation is a distinct URL to a search engine, even though the content is identical. Duplicates accumulate quietly from ordinary site behavior, not from deliberate copying.

## Why duplicates hurt

When an engine finds the same content at several URLs, it has to decide which one to index and rank, and it may not choose the one you want. Worse, the signals that should accumulate on one page, the links and authority, get split across the duplicates, so each version is weaker than a single consolidated page would be. Duplicates dilute the strength of your content by spreading it across copies that compete with one another.

## The near-duplicate case

Beyond exact duplicates, near-duplicate pages, very similar content on different URLs, cause related confusion. Pages that are mostly the same can compete for the same terms and split signals much as exact duplicates do. The canonical tag handles both cases by naming the preferred version, telling the engine to treat the others as pointing to it. The problem is the same whether the pages are identical or merely very similar: the engine needs to be told which one matters.

## The international wrinkle

A different version of the problem arises with international content: the same page translated into several languages, or adapted for several regions, is genuinely multiple pages serving different users, not duplicates to consolidate. Here the goal is not to pick one version but to show each user the right one. This is what hreflang handles, and conflating it with the duplicate problem is a common source of error. Duplicates need consolidating; language and region versions need routing. The two tags address these two distinct needs.
