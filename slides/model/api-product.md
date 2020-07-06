## Model | ApiProduct
* [ApiProduct](https://docs.solo.io/dev-portal/latest/concepts/api_products/#api-products)
& [Spec](https://docs.solo.io/dev-portal/latest/reference/api/apiproduct/#apiproductspec)
* aggregation of 'ApiDoc'
* pick only required operations (endpoints) required
* e.g. for PDS2
    * `TppProduct` (GET /api/accounts)
    * `BankerProduct` (GET /api/accounts), (POST /api/accounts)
* creates Istio ingress routes for those endpoints only
* integration offer definition