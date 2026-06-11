# Common mistakes

The common mistakes are canonical tags pointing to the wrong or broken URLs, canonicals that contradict other signals, hreflang sets that are incomplete or not reciprocal, wrong language or region codes, and confusing the two tags' purposes. Most break quietly, so they go unnoticed until rankings suffer.

## Wrong canonical target

A canonical pointing to the wrong URL, a redirect, a broken page, or a different page entirely, sends the engine the wrong signal about which version to use. This can cause the engine to drop the page you wanted or consolidate signals onto the wrong one. The canonical target must be the correct, accessible, preferred URL. A mistyped or mistargeted canonical is worse than none, because it actively misdirects rather than just leaving the choice open.

## Contradicting signals

A canonical that disagrees with your internal links, sitemap, or redirects creates conflicting signals that the engine must resolve, possibly against your intent. When the canonical names one URL but everything else points to another, the engine may follow the majority and ignore the canonical. The fix is alignment: make every signal name the same preferred URL. Contradiction is a frequent and avoidable cause of canonicals not being honored.

## Broken hreflang sets

Incomplete or non-reciprocal hreflang, where versions do not all reference each other and themselves, is the most common hreflang failure. The set only works as a complete, mutual group, so a missing or one-sided annotation breaks the routing. Because hreflang fails silently, a broken set can sit unnoticed while users get the wrong language version. Validating the set's completeness and reciprocity is the way to catch this, since the symptoms are subtle.

## Confusing the two

Using canonical where hreflang is needed, or hreflang where canonical is needed, is a conceptual error with real consequences. Pointing language versions' canonicals at a single version collapses them into one, hiding the others; treating duplicates as hreflang alternatives fails to consolidate them. The two tags serve opposite purposes, consolidating versus routing, and applying the wrong one mishandles the content. Keeping straight which problem you have, duplicates to consolidate or versions to route, is what tells you which tag to reach for.
