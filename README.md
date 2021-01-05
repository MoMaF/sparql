# sparql
SPARQL scripts. Samples and also scripts used for updating actual data in triple store


# Update scripts

These scripts update the datasets in the database. They should be run only by the triple store admin, and are placed here only for documentation.

## `wikidata_person.rq`

Script used to update person data. This script places the imported
data to a graph named <http://momaf-data.utu.fi/input> which should be
created before running this script. After everything seems to be ok,
move this graph to <http://momaf-data.utu.fi/wikidata_person> which is
the designated name for person data derived from Wikidata.

## `wikidata_movie.rq`

Script used for enriching movie data from Wikidata. This script places
the imported data to a graph named <http://momaf-data.utu.fi/input>
which should be created before running this script. After everything
seems to be ok, move this graph to
<http://momaf-data.utu.fi/wikidata_movie> which is the designated name
for movie data derived from Wikidata.
