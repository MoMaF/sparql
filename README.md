# sparql
SPARQL scripts. Samples and also scripts used for updating actual data in triple store

## `wikidata_person.rq`

Script used to update person data. This script places the imported
data to a graph named <http://momaf-data.utu.fi/input> which should be
created before running this script. After everything seems to be ok,
move this graph to <http://momaf-data.utu.fi/wikidata_person> which is
the designated name for person data derived from Wikidata.
