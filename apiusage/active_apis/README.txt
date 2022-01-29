
This folder contains the usage results of 13,235 active web APIs, including 12166 web APIs from ProgrammableWeb (PW) and 1203 web APIs from APIs.guru.

NOTE: The active web APIs are determined based on the accessibility test results of the URLs of web APIs from three countries, as shown in folder "apiurls_test". It is worthy to point out that the active web APIs may not be reliable as the accessibility test results from different countries can be different due to network or permission problems.


1. pweb: the processed web API names from PW
	-- apinames_pwurls.txt: the API name with the PW URL of 12242 active web APIs.
	-- apinames_ori2ref.txt: the original API name -> refined API name of 12241 web APIs (excluding one web API created for testing purposes).
	-- apinames_ref2oris.txt: the (12166) refined API name -> original API names.

2. apis.guru: the processed web API names/titles from APIs.guru (OpenAPI & GraphQL)
	-- openapi_apititles_ori2ref.txt: the original API title -> refined API title of 1167 active web APIs from OpenAPI.
	-- graphql_apititles_ori2ref.txt: the original API title -> refined API title of 54 web APIs from GraphQL.
	-- apititles_ref2oris.txt: the (1203) refined API title -> original API titles collected for APIs.guru.
	
3. lucene: the merged API names/titles from PW and APIs.guru for SO question retrieval using Lucene
	-- apinames_ref2oris.txt: the union set of 13235 refined API titles.
	-- id2apiname.txt: the indexed API names/titles to facilitate the question retrieval.
	-- apinames_contain.txt: the containing relationship between API names/titles, which will be used to obtain the correct set of SO questions retrieved for each web API. For example, for two web APIs with names "a" and "a b", then the set of questions retrieved for "a" should exclude the questions retrieved for "a b".

4. apiusage.xlsx: the usage results of 13235 active web APIs.
	