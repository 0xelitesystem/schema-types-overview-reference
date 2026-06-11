# Common types and when to use them

Most sites need only a handful of schema types, matched to the kinds of pages they have. Rather than surveying the entire vocabulary, it is more useful to know the common types and the page each one fits, so you can mark up a typical site correctly. These are the types that cover the great majority of real pages.

## Organization and person

Organization describes a company or brand and is commonly applied site-wide, carrying the name, logo, and links to the brand's official profiles. Person describes an individual, used for an author, a founder, or a personal brand, with their name, role, and links to their profiles. These identity types matter for establishing who is behind a site, which feeds the trust signals that search and AI systems weigh. A personal brand site is primarily about a person; a company site carries an organization. The links to other official profiles are especially valuable, because they connect the entity across the web.

## Article and blog posting

Article, and its more specific variants for blog posts and news, describes a written piece of content, carrying the headline, author, publication date, and publisher. This is the type for any page that is fundamentally an article: a blog post, a news story, a guide. The author tied to a person, the publication and modification dates, and the publisher tied to an organization are the properties that matter, because they establish authorship and freshness, which both search and AI systems use to judge and cite content. Any content site lives largely on this type.

## Product and offer

Product describes a single item for sale, carrying its name, description, image, and an offer with the price and availability. This is the type for a product page, and it is what can produce rich results showing price and availability directly in search. The offer, holding the actual price and whether the item is available, is the part that does the work. Only mark up ratings and reviews if they are genuinely present on the page, a point the later page on mistakes returns to, because invented ratings are a common and penalized abuse of this type.

## Local business

Local business describes a business with a physical location, carrying the name, address, geographic coordinates, phone, opening hours, and price range. It is the type for a business serving a local area, and for directory listings of such businesses. The address, hours, and location are what let engines represent the business in local results and answer location-based queries accurately. A directory of local businesses applies this type to each listing. It is one of the higher-value types, because location-based search relies heavily on it and many sites omit it.

## Supporting types: breadcrumb, FAQ, and others

Beyond the primary types, a few supporting types appear across many sites. Breadcrumb markup describes a page's position in the site's navigation hierarchy and helps engines show the path. FAQ markup, used on pages that genuinely contain questions and answers, can present those directly in search. There are others for specific content, events, recipes, courses, videos, each fitting its particular kind of page. The pattern is to apply the primary type for what the page is, then add the supporting types for the specific components the page actually contains, never inventing components that are not there.
