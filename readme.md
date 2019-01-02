## About the Data

 * used `cd-hit` to reduce those with > 300 records in a country, with `-i 1`. Final: 10,821 tips
 * Tree computed with `fasttree v2.1.8`

## Local Build

Uses `http-server` for a local server. To install:

```
npm install http-server -g
```

To run:

```
http-server
```

## To Do

* A chloropleth (i.e. "map") visualization about the persistence patterns of dengue. If dengue is animal-borne, and has rate of mutation within a certain range, is this reasonable explanation for geographic clustering (as opposed to flu B, which is just everywhere)?
* A `treetime` computed tree. Unlike certain phylogenetic models (SIR, if I'm not wrong), though, the internal nodes in this case are *not* the unsampled individuals. As such, I'm still not comfortable with interpreting the vanilla phylogenetic tree as anything more than a dendrogram - I see phrases like "ancestral structure and relationships" all the time, but this (a) doesn't actually mean anything and (b) suffers from [Cubist Chicken syndrome](https://books.google.com.au/books?id=gjwlDwAAQBAJ&pg=PA317&lpg=PA317&dq=cubist+chicken&source=bl&ots=K0PBwn2ftd&sig=APZYpADnyXy4v3Cjs-IhwJGJC8s&hl=en&sa=X&ved=2ahUKEwj5vdv3kc7fAhXJb1AKHcJkDTcQ6AEwD3oECAkQAQ#v=onepage&q=cubist%20chicken&f=false).
