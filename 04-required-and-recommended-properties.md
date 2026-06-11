# Required and recommended properties

Choosing the right type is half the work; filling in its properties accurately is the other half. Each type has properties that describe it, some essential for the markup to be useful and some that add detail, and engines distinguish between properties they require for a feature and ones they merely recommend. Marking up a type with too few properties leaves it nearly useless; marking it with accurate, complete properties is what makes it work.

## The essentials every type needs

A few properties are fundamental across most types: a name or title identifying the thing, a description, and usually a URL and an image. These are the baseline that lets an engine know what the entity is and represent it. An image given as an absolute URL at a reasonable size matters because it is used in rich results and previews. Without these basics, the markup describes an entity the engine cannot really do anything with. Getting the essentials right and accurate is the first priority before adding more specialized properties.

## Required versus recommended for features

When a type can produce a rich result, engines typically specify which properties are required for that result and which are recommended. The required ones must be present and valid, or the rich result will not appear, however good the rest of the markup is. The recommended ones improve the result or its chances but are not strictly necessary. Knowing this distinction for a type you care about tells you what you must include, a product needs its offer and price for a price-showing result, an article needs its headline and dates, against what merely helps. Meeting the required set is the threshold; the recommended set is the improvement.

## Identity properties and connecting the entity

For identity types, person and organization, the properties that link the entity to its other official presences are especially valuable. Listing the official profiles and pages associated with the entity connects it across the web, which helps engines and AI systems recognize it as a known entity and attribute content to it confidently. This connection is one of the stronger signals for entity recognition, so it is worth completing fully and accurately with the real, owned profiles. Identity markup that names the entity but does not connect it to its broader presence misses much of its value.

## Dates, authorship, and freshness

For content types, the properties establishing who wrote the page and when carry particular weight. The author, the original publication date, and the last modified date together tell engines who is responsible for the content and how current it is, both of which feed how content is judged and cited. These should be accurate: the modified date should genuinely reflect a meaningful update, not be bumped to fake freshness, which is a known manipulation. Honest, complete authorship and date properties support the trust and freshness signals that matter for being found and cited.

## Complete the properties, but only the true ones

The guiding rule for properties mirrors the rule for types: include the properties that accurately describe what is on the page, as completely as you reasonably can, and never include properties that are not true of the page. Complete, accurate properties make the markup genuinely useful; sparse markup underdelivers, and false properties, especially invented ratings, prices, or dates, misrepresent the page and are penalized. The work is to fill in what is real and present, thoroughly, while leaving out anything the page does not actually contain. Accuracy and completeness together are what turn correctly chosen types into structured data that helps.
