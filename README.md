# EntermediaDB JSON API Documentation

Unfortunately, there isn't much documentation for the EntermediaDB API, here is a way of getting a list of endpoints and some description of the API

    curl -H'Content-type: application/json' -H'Cookie: entermedia.key=adminmd5421c0af185908a6c0c40d50fd5e3f16760d5580bc' -X POST 'http://demo.entermediasoftware.com/mediadb/services/lists/search/endpoint'  -d '{"page": "1","hitsperpage": "100","query": {"terms": [{"field": "id","operator": "matches","value": "*"}]}}'
