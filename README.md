# sparql

SPARQL `queries`
Check out the queries on [WikiData Query Endpoint](https://query.wikidata.org/)

- `wikidata_*.txt` [Tutorial](https://www.youtube.com/watch?v=b3ft3CzkLYk&ab_channel=WikimedianinResidence-UniversityofEdinburgh),
- population `population_world_subqueries.txt`, study of subqueries,
- study on italian politicians `politicians.txt`,
- Italian poets' family structure `all_relatives.txt`,
- spanish poets with max number of children `spanish_poet_with_max_number_of_children.txt`,
- spanish poets with max number of children (using `HAVING` keyword) `spanish_poet_with_max_number_of_children2.txt`,
- search for the same parent but implicit parent `implicit_parent.txt`;
- siblings of Bach [source](https://en.wikibooks.org/wiki/SPARQL/Property_paths#:~:text=of%20this%20element-,Inverse,-link%5Bedit) at `siblings.txt`,
- implicit vs. explicit siblings of italian politicians as `politicians_implicit_siblings.txt`. By implicit sibling I mean a subject that has the same parent, but it is not explicitely represented on Wiki. I compare lists of implicit and explicit siblings,
- `politicians_subclasses.txt` the SPARQL statement queries for items that have a "subclass of" relationship (direct or indirect) with the occupation or profession represented by wd:Q82955 (politician). In other words, it retrieves all the items that are either instances of Q82955 or instances of its subclasses based on the "subclass of" relationships defined in Wikidata,
- we can use BIND function for better query reading `bind_for_better_reading.txt` [source](https://en.wikibooks.org/wiki/SPARQL/Expressions_and_Functions#:~:text=For%20example%2C%20a%20query%20that%20finds%20all%20female%20priests),
- `railways_lists.txt`, studying IN clause, displayin railway stations in London and Paris;

Jupyter `notebooks`

- `biggest_cities_population.ipynb` following the [tutorial](https://max-coding.medium.com/extract-structured-data-from-wikidata-using-python-and-sparql-query-987c3bff97be),

Using mkwikidata and pandas, we extract and plot the most significant cities by population,

- `politicians.ipynb`: the same code as above, using `queries/politicians.txt` query.
