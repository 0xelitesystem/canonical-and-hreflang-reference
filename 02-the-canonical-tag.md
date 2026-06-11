# The canonical tag

The canonical tag tells search engines which URL is the preferred version of a page, so they consolidate indexing and ranking signals onto that version rather than splitting them across duplicates. You place it in the page's head, pointing to the canonical URL.

## What it does

A canonical tag declares, for a given page, the single URL that should be treated as the authoritative version. When duplicates or near-duplicates exist, each one can carry a canonical tag pointing to the preferred URL, telling the engine to consolidate signals there and index that version. The engine treats the canonical as a strong hint about which URL to use, resolving the ambiguity that duplicates create. It is how you nominate the page that should represent the content.

## Self-referencing canonicals

The preferred version itself carries a canonical tag pointing to its own URL, called a self-referencing canonical. This confirms to the engine that this URL is the canonical one and guards against the page being treated as a duplicate of something else, especially when parameters or variations could create accidental copies. Having every page point to its own clean URL as canonical is a common baseline practice that prevents a range of duplicate problems.

## Where it goes

The canonical tag goes in the head section of the page's HTML, specifying the full preferred URL. It must point to a valid, accessible URL that returns the content, not to a redirect or a broken page. The tag is read by the engine when it processes the page, so it has to be present in the page as the engine sees it. Placement and a correct target URL are what make the tag function.

## A hint, not a command

The canonical tag is a strong signal but not an absolute instruction; engines generally respect it but can override it if other signals strongly contradict it. This means the canonical works best when it agrees with the rest of your signals, the internal links, the sitemap, the redirects, all pointing at the same preferred version. When everything is consistent, the engine follows the canonical reliably. When signals conflict, the engine may pick differently, which is why consistency across signals matters as much as the tag itself.
