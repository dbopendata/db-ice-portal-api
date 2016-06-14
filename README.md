# DB ICE Portal API

Dieses Repository enthält [Swagger](http://swagger.io/specification/)/[OpenAPI](https://github.com/OAI/OpenAPI-Specification) Spezifikation für die [Deutsche Bahn ICE Portal API](http://data.deutschebahn.com/apis/iceportal/):

* [db-ice-portal-api-specification.yaml](https://github.com/dbopendata/db-ice-portal-api/blob/master/db-ice-portal-api-specification.yaml), see also in  [Swagger Editor](http://editor.swagger.io/#/?import=https://raw.githubusercontent.com/dbopendata/db-ice-portal-api/master/db-ice-portal-api-specification.yaml)

Des weiteren, es dient auch dazu, die [Issues](https://github.com/dbopendata/db-ice-portal-api/issues) und [Pull Requests](https://github.com/dbopendata/db-ice-portal-api/pulls) für die [Deutsche Bahn ICE Portal API](http://data.deutschebahn.com/apis/iceportal/) zu tracken.

# Beispiele

Siehe [examples](https://github.com/dbopendata/db-ice-portal-api/blob/master/examples).

## status

URL: `http://ice.portal1/jetty/api/v1/status`

Ergebnis:

```json
{  
   "connection":true,
   "servicelevel":"SERVICE",
   "speed":185.8000030517578,
   "longitude":10.924448,
   "latitude":52.432009,
   "serverTime":1445351850874
}
```
# Lizenz

Work in progress, noch nicht freigegeben.