# elasticsearch-micropython
A simple elasticsearch opensearch micropython requests library with tls support 


## Usage

### Make a POST request

```Python

import opensearch

authtoken = "YOUR AUTH TOKEN"

requests.post("search.blackhole.consulting",9200,"\ncontent-type: application/json\nAuthorization: Bearer "+authtoken,'{"signatures": ["'+r+'","'+v+'"],"compression": true,"packed_context_free_data": "'+memo+'","packed_trx": '+json.dumps(trx)+'}')


```
