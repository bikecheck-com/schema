# Bicycle

_A Schema.org Type_

[Thing]([./bicycle/README.md](https://schema.org/Thing)) / [Product](https://schema.org/Product) / [Vehicle](https://schema.org/Vehicle) / Bicycle

- Canonical URL: https://schema.bikecheck.cc/Bicycle
- [Check for open issues](https://github.com/bikecheck-com/schema/issues)

A bicycle is a vehicle consisting of two wheels held in a frame one behind the other, propelled by pedals and steered with handlebars attached to the front wheel.

|Property|Expected Type|Description|
|---|---|---|
|cargoVolume|[QuantitativeValue](https://schema.org/QuantitativeValue)|The available volume for cargo or luggage. For automobiles, this is usually the trunk volume. Typical unit code(s): LTR for liters, FTQ for cubic foot/feet Note: You can use [minValue](https://schema.org/minValue) and [maxValue](https://schema.org/maxValue) to indicate ranges.|
|modelDate|[Date](https://schema.org/Date)|The release date of a vehicle model (often used to differentiate versions of the same make and model).|
|numberOfForwardGears|[Number](https://schema.org/Number) or [QuantitativeValue](https://schema.org/QuantitativeValue)|The total number of forward gears available for the transmission system of the vehicle.|
|numberOfPreviousOwners|[Number](https://schema.org/Number) or [QuantitativeValue](https://schema.org/QuantitativeValue)|The number of owners of the vehicle, including the current one.|
|payload|[QuantitativeValue](https://schema.org/QuantitativeValue)|The permitted weight of passengers and cargo, EXCLUDING the weight of the empty vehicle. Typical unit code(s): KGM for kilogram, LBR for pound|
|productionDate|[Date](https://schema.org/Date)|The date of production of the item, e.g. vehicle.|
|purchaseDate|[Date](https://schema.org/Date)|The date the item, e.g. vehicle, was purchased by the current owner.|
|speed|[QuantitativeValue](https://schema.org/QuantitativeValue)|The speed range of the vehicle. If the vehicle is powered by an engine, the upper limit of the speed range (indicated by maxValue) should be the maximum speed achievable under regular conditions. Typical unit code(s): KMH for km/h, HM for mile per hour (0.447 04 m/s), KNT for knot|
|Properties from [Thing](https://schema.org/Thing)||
|additionalType|Text or URL|An additional type for the item, typically used for adding more specific types from external vocabularies in microdata syntax. This is a relationship between something and a class that the thing is in. Typically the value is a URI-identified RDF class, and in this case corresponds to the use of rdf:type in RDF. Text values can be used sparingly, for cases where useful information can be added without their being an appropriate schema to reference. In the case of text values, the class label should follow the schema.org style guide.|
|[alternateName](https://schema.org/alternateName)|[Text](https://schema.org/Text)|An alias for the item.|
|[description](https://schema.org/description)|[Text](https://schema.org/Text) or [TextObject](https://schema.org/TextObject)|A description of the item.|
|[disambiguatingDescription](https://schema.org/Text)||A sub property of description. A short description of the item used to disambiguate from other, similar items. Information from other properties (in particular, name) may be necessary for the description to be useful for disambiguation.|
|identifier|[PropertyValue](https://schema.org/PropertyValue) or [Text](https://schema.org/Text) or [URL](https://schema.org/URL)|The identifier property represents any kind of identifier for any kind of Thing, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See background notes for more details.|
|image|[ImageObject](https://schema.org/ImageObject) or [URL](https://schema.org/URL)|An image of the item. This can be a URL or a fully described ImageObject.|
|mainEntityOfPage|[CreativeWork](https://schema.org/CreativeWork) or [URL](https://schema.org/URL)|Indicates a page (or other CreativeWork) for which this thing is the main entity being described. See background notes for details. Inverse property: mainEntity|
|name|[Text](https://schema.org/Text)|The name of the item.
|sameAs|[URL](https://schema.org/URL)|URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website.|
|url|[URL](https://schema.org/URL)|URL of the item.|