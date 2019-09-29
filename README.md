## People Migration from US Census Data

I’ve noticed a lot of new home construction where I live. However the population has stayed constant. 
Also it is currently a sellers market, meaning there more buyers than sellers. I am wondering then how the area will sustain all this new construction, 
where the people are coming from, and where the hole is they are leaving behind, and what might happen to that hole.

### Census Data

[County to County Migration Flows](https://www.census.gov/topics/population/migration/guidance/county-to-county-migration-flows.html)

#### Data Headers for All Data.txt

The all data text file does not have headers, but see `county-to-county-2013-2017-current-residence-sort.xlsx` 
and `county-to-county-2013-2017-previous-residence-sort.xlsx`, as they are In and Out flow respectively. Or half of the all flows data text file. 
Left hand is *Current Residence*. 

For net, use the last two columns in all data text for `Movers in County-to-County Flow` so, lets say left or current is A and right or previous is B. 
Example:

```

AB = 8; // "Alabama Autauga County <- Alabama Baldwin County"
BA = 194; // "Alabama Baldwin County <- Alabama Autauga County"

// To answer the question: What direction are people moving between A and B and what velocity (Moving Vector?
// Alabama Autauga County to Alabama Baldwin County?

AB - BA = -186

// People are leaving Alabama Autauga County for Alabama Baldwin County

```


### Map Examples

 * [Census Flow Mapper](https://flowsmapper.geo.census.gov/map.html)
 * [USA Counties](https://mapchart.net/usa-counties.html)
 
#### Map Sources

 * [USA Country SVG](https://commons.wikimedia.org/wiki/File:Usa_counties_large.svg)

