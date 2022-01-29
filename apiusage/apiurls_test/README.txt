
This folder contains the accessibility test results of 27,211 URLs of the web APIs collected from ProgrammableWeb and APIs.guru.
The test is conducted from three countries, i.e., China, the United States, and Australia, by requesting each URL three times using the requests module in Python.

1. apiurl_status(china).json: the accessibility test results of the URLs from China.
2. apiurl_status(usa).json: the accessibility test results of the URLs from the United States.
3. apiurl_status(australia).json: the accessibility test results of the URLs from Australia.
4. apiurls(200).json: the three sets of accessible URLs (with status code 200) obtained from different countries, the union set of the three sets (which will be used to determine the set of active web APIs), and the different sets of accessible URLs between any two of the three countries.