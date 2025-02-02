# Beer-Ontology

### Purpose

The Beer-Ontology project aims to create a structured and reusable ontology to represent the domain of beers, their styles, breweries, characteristics, and related concepts such as tasting notes, food pairings, and regions. This ontology can serve as a foundation for applications in beer recommendation systems.

## Classes:

**BeerStyle:** Represents styles of beer (e.g., PaleAle, IPA, Stout).
- https://www.wineenthusiast.com/basics/most-popular-style-beer-guide
- https://www.tastingtable.com/1705830/types-of-beer-explained/

**TastingNote:** Represents sensory characteristics like flavor, aroma, and appearance.
- https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgk6GzCJZb7z5RlgYYkbsI_ydzPHpToMWl_2DZgKNnab7R4xOgSpe6gdmcQx8VurxCeKkGN1CYL5hdvupxSWuJE4WqrE_lm8s_dADrVGzF8NLtt9gtS2oVSVOa4uKQ2BQa4DDaBzu9amLYr/s1600/beer-flavor-wheel.jpg

**Brewery:** Represents beer producers, including attributes such as location and year of establishment.

**FoodPairing:** Represents foods that complement specific beer styles.
- https://www.brewersassociation.org/attachments/0000/2095/Beer_and_Food_Flyer_MDC.pdf
- https://www.webstaurantstore.com/article/96/beer-and-food-pairings.html?srsltid=AfmBOopsjI7v4dnyX5IbS5jKh87guIQfwSv7jYdRXb2qrVmUl2YHA6Mq
- https://www.craftbeer.com/beer-styles  =  *contains food pairings to every beer style*

**Region:** Represents geographical origins of beer styles or breweries.
- https://www.statista.com/statistics/270269/leading-10-countries-in-worldwide-beer-production/ = Selected top 5 + Czechia and Slovakia

**Ingredient:** Represents beer ingredients like malt, hops, yeast, and water. 
- General structure: https://www.homebrewersassociation.org/how-to-brew/homebrew-ingredients/
- Malt:
- https://www.baladin.it/en/blog/what-are-the-ingredients-of-beer/
- https://beercrush.eu/en/blogs/articles/malt-dans-la-biere?srsltid=AfmBOook9H_nc_xyF6MwCukgzVVWTD7FSFsSzmnY0qJXjm8V4gjHWaf6
- Yeast: https://beermaverick.com/yeasts/
- Hops: https://www.brewgem.com/what-types-of-hops-are-used-in-beer-brewing/
- Adjuncts: https://www.thespruceeats.com/beer-adjuncts-guide-353147

**AlcoholContent:** Represents alcohol by volume (ABV).
- https://www.unknownbrewing.com/how-much-alcohol-is-in-beer/


## Properties:

**hasAlcoholContent:** Specifies the alcohol content by volume (ABV).

**hasBrewery:** Indicates the brewery responsible for producing the beer.

**hasIngredient:** Identifies the ingredients used in crafting the beer.

**hasPairing:** Suggests foods or dishes that pair well with the beer.

**hasRegion:** Specifies the geographic region or location associated with the beer's production.

**hasStyle:** Describes the beer's style or category (e.g., IPA, stout, lager).

**hasTastingNote:** Captures sensory characteristics or flavors experienced while tasting the beer.

**producesBeer:** Defines a relationship between a brewery and the beers it produces.


## Instances:
https://alkypal.com.au/beer/ale/sour-ale.html

https://www.nachmelenaopice.cz/en/

https://pivo.beerstation.sk/

https://www.barthhaas.com/hops-and-products/hops


## Work Distribution:
Lukas:
- Defined comments to each class
- Defined proper naming conventions and QA

Johanka:
- Defined object properties
- Created final presentation

Martin:
- Defined beer ontology classes
- Gathered sources for the classes and other ontologies
- Defined individuals

## Sources:
...

## Other Ontologies:
**https://rdf.ag/o/beer-en.html** - 1. Beer ontology = The scope of this ontology is to help provide beer and beer ingredient traceability, process control and style identification in a language neutral way. __
**https://www.cs.umd.edu/projects/plus/SHOE/onts/beer1.0.html** - 2. Draft of a beer ontology __
**https://rdfs.co/bevon/latest/html** - 3. Beverage ontology
