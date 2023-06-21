# sparql

SPARQL `queries`.
Check out the queries on [WikiData Query Endpoint](https://query.wikidata.org/):

- `parentela` folder:

  - `all_relatives.txt`: This query retrieves information about a person's familial relationships. It includes the person's label, their fathers, mothers, brothers, sisters, spouses, uncles, children, stepfathers, stepmothers, grandparents, and aunts,
  - `implicit_father.txt`: This query retrieves pairs of politicians from Italy who have the same father,
  - `siblings.txt`: This SPARQL query retrieves the siblings of Johann Sebastian Bach, who are the father's siblings,
  - `spanish_poet_with_max_number_of_children.txt`: This query retrieves a list of Spanish poets with the maximum number of children among all Spanish poets,
  - `spanish_poet_with_max_number_of_children2.txt`: same topic, another syntax;

- `politics` folder:

  - `politicians.txt`: This query retrieves information about Italian politicians and their children who are also involved in politics. It includes the politician's name, the parties they belong to, the number of children in politics, the names of their children, and the parties their children belong to, sorted by the descending order of the number of children involved in politics,
  - `politicians_implicit_siblings.txt`: This query retrieves information about Italian politicians' explicit siblings,
  - `politicians_subclasses.txt`: The SPARQL queries for items that have a "subclass of" relationship (direct or indirect) with the occupation or profession represented by wd:Q82955 (politician). In other words, it retrieves all the items that are either instances of Q82955 or instances of its subclasses based on the "subclass of" relationships defined in Wikidata;

- `sandbox` folder contains various SPARQL query examples.

Jupyter `notebooks`:

- `biggest_cities_population.ipynb` following the [tutorial](https://max-coding.medium.com/extract-structured-data-from-wikidata-using-python-and-sparql-query-987c3bff97be), Using `mkwikidata` and pandas, we extract and plot the most significant cities by population,

- `politicians.ipynb`: the same code as above, using `politicians.txt` query.
