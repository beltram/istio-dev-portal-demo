## Model | ApiProduct
* [ApiProduct](https://docs.solo.io/dev-portal/latest/concepts/api_products/#api-products)
& [Spec](https://docs.solo.io/dev-portal/latest/reference/api/apiproduct/#apiproductspec)
* aggregation of 'ApiDoc'
* granularity: pick only operations (endpoints) required
* e.g. for banking offers
    * `PSD2` product with (GET /api/accounts), (POST /api/payments) endpoints
    * `IPCE` product with (POST /api/payments) endpoints
* creates Istio ingress routes for those endpoints only
* integration (or R&D) offer definition