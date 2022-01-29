
This folder contains the usage results of 20047 web APIs, including 18866 web APIs from ProgrammableWeb (PW) and 1347 web APIs from APIs.guru.

1. pweb: the processed web API names from PW
	-- apinames_pwurls.txt: the API name with the PW URL of 18958 web APIs after filtering out 1217 non-web APIs by architectural styles.
	-- apinames_ori2ref.txt: the original API name -> refined API name of 18957 web APIs (excluding one web API created for testing purposes).
	-- apinames_ref2oris.txt: the (18866) refined API name -> original API names.

2. apis.guru: the processed web API names/titles from APIs.guru (OpenAPI & GraphQL)
	-- openapi_apititles_ori2ref.txt: the original API title -> refined API title of 1310 web APIs from OpenAPI, after filtering out 4 web APIs created for testing purposes and 2 meaningless API names, i.e., "API v1" and "REST API Version 2".
	-- graphql_apititles_ori2ref.txt: the original API title -> refined API title of 69 web APIs from GraphQL.
	-- apititles_ref2oris.txt: the (1347) refined API title -> original API titles collected for APIs.guru.
	
3. lucene: the merged API names/titles from PW and APIs.guru for SO question retrieval using Lucene
	-- apinames_ref2oris.txt: the union set of 20047 refined API titles.
	-- id2apiname.txt: the indexed API names/titles to facilitate the question retrieval.
	-- apinames_contain.txt: the containing relationship between API names/titles, which will be used to obtain the correct set of SO questions retrieved for each web API. For example, for two web APIs with names "a" and "a b", then the set of questions retrieved for "a" should exclude the questions retrieved for "a b".

4. apiusage.xlsx: the usage results of 20047 web APIs, as listed in Table 6 of the paper.
	