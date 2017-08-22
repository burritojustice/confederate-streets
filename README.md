# Confederate Streets

https://burritojustice.github.io/confederate-streets/index.html

Uses Mapzen Search to find the extent of street names and points of interest (POIs) named after Robert E. Lee. These serve as a signal for other streets named after confederates. (These first appear at zoom 14.) 

Red dots are streets, blue are POIs. Green circles indicate data from the [Southern Poverty Law Center](https://splcenter.carto.com/datasets).

Red and blue dots are from OpenStreetMap, via Mapzen Search. While Mapzen Search returns a maximum of 40 results per query, this gave a good impression of distribution (through the southern U.S.) but it was obviously not exhaustive. I ran a second set of queries for streets and venues for each southern state for more detailed coverage.

The confidence scores from Mapzen Search were very helpful. In general, results above `0.67` were meaningful.

If a street is named after Robert E. Lee, there is a significant chance that nearby streets names are also named after confederates.

- [Southgate Estates, Lafayette, Louisiana](https://burritojustice.github.io/confederate-streets/index.html#lat=32.4613&lng=-93.6509&z=15.7011)

- [Pine Valley Estates, Wilmington, NC](https://burritojustice.github.io/confederate-streets/index.html#lat=34.1881&lng=-77.8959&z=15.2750)

- [Stanley, NC](https://burritojustice.github.io/confederate-streets/index.html#lat=35.34578&lng=-81.08881&z=16.0844)

- [Alexandria, VA](https://burritojustice.github.io/confederate-streets/index.html#lat=38.8271&lng=-77.0651&z=12.0386)

- [Erlanger, KY](https://burritojustice.github.io/confederate-streets/index.html#lat=39.05277&lng=-84.61434&z=16.0677) (across the river from Cincinnati, OH)

- [Forest Hills, TN](https://burritojustice.github.io/confederate-streets/index.html#lat=36.0652&lng=-86.8140&z=15.1927)

Sometimes streets are named for both Confederate and Union generals.

- [Battlefied, MO](https://burritojustice.github.io/confederate-streets/index.html#lat=37.11232&lng=-93.37270&z=16.9219)


- [Catoosca County, GA] features Grant and Lee in a subdivision-sized battle. (https://burritojustice.github.io/confederate-streets/index.html#lat=34.92622&lng=-85.16206&z=17.0927)

- (A few miles away in [Fort Oglethrope, GA](https://burritojustice.github.io/confederate-streets/index.html#lat=34.9471&lng=-85.2507&z=15.6594), it's a confederate namespace.)

There are some surprising outliers.

- [Santa Clarita, CA](https://burritojustice.github.io/confederate-streets/index.html#lat=34.39948&lng=-118.48957&z=16.9219) (north of Los Angeles)
- [Brooklyn](https://burritojustice.github.io/confederate-streets/index.html#lat=40.6091&lng=-74.0310&z=15.9715)

regex logic and map styling is here:

https://mapzen.com/tangram/play/?api=22/663#13.6708/32.4467/-93.6457

