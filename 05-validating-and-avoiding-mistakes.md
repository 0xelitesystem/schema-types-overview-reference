# Validating and avoiding mistakes

Structured data is markup, and markup can be wrong: invalid syntax, missing required properties, or, most seriously, claims that do not match the page. Validating it before relying on it catches the technical errors, and a few discipline rules avoid the substantive mistakes that get sites penalized. The two together, validate the form and keep the content honest, are what make structured data an asset rather than a liability.

## Validate before you trust it

Before relying on any structured data, run it through the validators that engines provide, which check that the markup is syntactically correct, uses the vocabulary properly, and includes the required properties for any feature you are targeting. These tools report errors and warnings, errors being problems that break the markup or block a feature, warnings being recommended properties you are missing. Fixing the errors is essential; addressing the warnings improves the result. Validating catches the technical mistakes that would otherwise make your markup silently fail, and it is quick, so there is no reason to skip it before deploy.

## The cardinal rule: mark up only what is on the page

The most important discipline is that structured data must reflect the actual visible content of the page. Marking up information that is not present, claiming a rating the page does not show, a price that is not there, properties that describe content the user cannot see, is a violation that engines actively penalize. The markup is supposed to describe the page, not embellish it. If the page shows a rating, you may mark up that rating; if it does not, you may not invent one. This single rule prevents most of the serious structured-data mistakes, because nearly all of them are some form of claiming more than the page actually contains.

## Never fabricate ratings and reviews

A specific and common abuse worth calling out is fabricating or inflating ratings and reviews in product or business markup, because review stars in search are attractive and tempting to fake. Marking up ratings that are not real, or that do not correspond to genuine reviews shown on the page, is exactly the kind of misrepresentation engines penalize, and it can lead to the markup being ignored or the site being demoted. Only mark up ratings and reviews that genuinely exist and are visible on the page. The pull toward fake stars is strong precisely because they work in search, which is why the rule against them is firm.

## Keep the markup in sync with the page

A subtler mistake is letting the structured data drift out of sync with the page as the page changes. A price that is updated on the page but not in the markup, hours that change in reality but not in the local business data, an article whose markup still shows the old author, these mismatches misrepresent the current page even though they were accurate once. Treating the markup as something that updates whenever the underlying content does, rather than as a set-once block, keeps it honest over time. Stale markup is a slow version of the same problem as fabricated markup: it describes something other than the real page.

## Validate, stay honest, and keep it current

The whole discipline of structured data comes down to three habits. Choose the accurate, specific type for what the page genuinely is. Fill it with complete, true properties and validate that the markup is technically correct. And keep it honest and in sync with the page over time, never claiming what is not there and never letting it drift stale. Done this way, structured data reliably helps engines and AI systems understand, represent, and cite your content. Done carelessly, with invented properties or stale claims, it ranges from useless to actively harmful. The payoff is real, and it depends entirely on accuracy.
