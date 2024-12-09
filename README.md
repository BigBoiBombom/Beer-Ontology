# Beer-Ontology

### Purpose

The Beer-Ontology project aims to create a structured and reusable ontology to represent the domain of beers, their styles, breweries, characteristics, and related concepts such as tasting notes, food pairings, and regions. This ontology can serve as a foundation for applications in beer recommendation systems, educational tools, and brewery management systems.

## Classes:

**Beer:** Represents individual beers.

**BeerStyle:** Represents styles of beer (e.g., PaleAle, IPA, Stout).

**TastingNote:** Represents sensory characteristics like flavor, aroma, and appearance.

**Brewery:** Represents beer producers, including attributes such as location and year of establishment.

**FoodPairing:** Represents foods that complement specific beer styles.

**Region:** Represents geographical origins of beer styles or breweries.

**Ingredient:** Represents beer ingredients like malt, hops, yeast, and water.

**AlcoholContent:** Represents alcohol by volume (ABV).


## Properties:

**hasAlcoholContent:** Specifies the alcohol content by volume (ABV).

**hasBrewery:** Indicates the brewery responsible for producing the beer.

**hasIngredient:** Identifies the ingredients used in crafting the beer.

**hasPairing:** Suggests foods or dishes that pair well with the beer.

**hasRegion:** Specifies the geographic region or location associated with the beer's production.

**hasStyle:** Describes the beer's style or category (e.g., IPA, stout, lager).

**hasTastingNote:** Captures sensory characteristics or flavors experienced while tasting the beer.

**producesBeer:** Defines a relationship between a brewery and the beers it produces.
