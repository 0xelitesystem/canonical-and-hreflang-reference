# Getting them right

Get canonical and hreflang right by being consistent: canonical tags should point to clean, accessible, preferred URLs that agree with your other signals, and hreflang sets should be complete, reciprocal, and use correct language and region codes. Consistency across all signals is what makes both tags work.

## Consistent canonical signals

A canonical tag works best when the rest of your site agrees with it. The preferred URL named in the canonical should be the one your internal links point to, the one in your sitemap, and the destination of any redirects. When the canonical, the links, the sitemap, and the redirects all name the same preferred URL, the engine follows it reliably. Contradictory signals, a canonical pointing one way while links point another, undermine the tag. Alignment is the goal.

## Clean canonical targets

Canonical tags should point to clean, final URLs: the actual preferred page, accessible and returning content, not a redirect, an error, or a parameter-laden variant. A canonical pointing to a URL that redirects elsewhere or does not resolve confuses the engine. The target should be the real, stable, preferred address of the content. Getting the target URL clean and correct is half of using canonicals properly.

## Complete, reciprocal hreflang

Hreflang sets must be complete and reciprocal: every version lists every version including itself, with matching annotations across all of them. An incomplete or one-sided set breaks the relationship and the engine cannot route users correctly. Building the full reciprocal set, and keeping it in sync as you add or change versions, is the core discipline of hreflang. The tags only function as a coordinated group, so completeness is not optional.

## Correct codes

Hreflang relies on correct language and region codes; an invalid or wrong code means the annotation is ignored or misapplied. Use the standard codes for the languages and regions you target, and verify them, since a small error in a code silently breaks the targeting for that version. Because hreflang errors fail quietly rather than loudly, checking the codes and the reciprocity with a validation tool is worth doing. The tags are unforgiving of small mistakes, so precision in the codes matters.
