# Navigating The Green Book

A set of experimental interfaces by the [Brian Foo](http://brianfoo.com/) of [NYPL Labs](http://labs.nypl.org/) that explore the [Green Book](http://digitalcollections.nypl.org/collections/the-green-book), a travel guide published between 1936 and 1966 that listed hotels, restaurants, bars, gas stations, etc. where black travelers would be welcome.

View the website here: [http://publicdomain.nypl.org/greenbook-map/](http://publicdomain.nypl.org/greenbook-map/)

## The Data

The [NYPL Labs](http://labs.nypl.org/) has [extracted the text and coordinate data](https://github.com/NYPL-publicdomain/greenbooks) (via OCR) from the high-resolution images of [The Negro Motorist Green Book: 1947](http://digitalcollections.nypl.org/items/29219280-892b-0132-4271-58d385a7bbd0). The [Scribe](http://scribeproject.github.io/) framework was then used to correct and normalize the data generated from the OCR processing.

The data from [The Negro Travelers' Green Book: Spring 1956](http://digital.tcl.sc.edu/cdm/compoundobject/collection/greenbook/id/88) was provided by the [Green Book map](http://library.sc.edu/digital/collections/greenbookmap.html) created by the [SC Digital Academy](http://library.sc.edu/blogs/academy/) and the [Digital Collections](http://library.sc.edu/digital/index.php) and [African American Studies](http://www.cas.sc.edu/afra/) departments of the University of South Carolina.

## The Technology Used

- [Mapbox](https://www.mapbox.com/) - map tiles, routing directions
- [Leaflet](http://leafletjs.com/) - interactive map UI
- [Open Street Map Nominatim](http://wiki.openstreetmap.org/wiki/Nominatim) - reverse geocoding

## About the NYPL Public Domain Release

On January 6, 2016, The New York Public Library enhanced access to public domain items in Digital Collections so that everyone has the freedom to enjoy and reuse these materials in almost limitless ways. For all such items the Library now makes it possible to download the highest resolution images available directly from the Digital Collections website.

That means more than 187,000 items free to use without restriction! But we know that 180K of anything is a lot to get your head around — so as a way to introduce you to these collections and inspire new works, NYPL Labs developed a suite of projects and tools to help you explore the vast collections and dive deep into specific ones.

Go forth & re-use; apply for our Remix Residency; and let us know what you made with the #nyplpd hashtag. For more info, links to our projects and more, visit:

- [More about our public domain release](http://publicdomain.nypl.org)
- Remix Residency (coming soon)
- [Data & Tools](https://github.com/NYPL-publicdomain/data-and-utilities)
