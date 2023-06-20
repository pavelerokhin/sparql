# sparql

SPARQL `queries`
Check out the queries on [WikiData Query Endpoint](https://query.wikidata.org/)

- `wikidata_*.txt` [Tutorial](https://www.youtube.com/watch?v=b3ft3CzkLYk&ab_channel=WikimedianinResidence-UniversityofEdinburgh),
- population `population_world_subqueries.txt`, study of subqueries,
- study on italian politicians `politicians.txt`,
- Italian poets' family structure `all_relatives.txt`,
- spanish poets with max number of children `spanish_poet_with_max_number_of_children.txt`,
- spanish poets with max numb[README.md](README.md)er of children (using `HAVING` keyword) `spanish_poet_with_max_number_of_children2.txt`;
- search for the same parent but implicit parent `implicit_parent.txt`;
- siblings of Bach in `siblings.txt` [source](https://en.wikibooks.org/wiki/SPARQL/Property_paths#:~:text=of%20this%20element-,Inverse,-link%5Bedit)


Jupyter `notebooks`

- `biggest_cities_population.ipynb` following the [tutorial](https://max-coding.medium.com/extract-structured-data-from-wikidata-using-python-and-sparql-query-987c3bff97be),

Using mkwikidata and pandas, we extract and plot the most significant cities by population,

- `politicians.ipynb`: the same code as above, using `queries/politicians.txt` query.
