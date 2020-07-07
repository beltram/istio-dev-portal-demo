## Model | ApiProduct
* [ApiProduct](https://docs.solo.io/dev-portal/latest/concepts/api_products/#api-products)
& [Spec](https://docs.solo.io/dev-portal/latest/reference/api/apiproduct/#apiproductspec)
* aggregation of 'ApiDoc'
* pick only required operations (endpoints) required
* e.g. banking clients
    * `PSD2` (GET /api/accounts), (POST /api/payments)
    * `IPCE` (POST /api/payments)
* creates Istio ingress routes for those endpoints only
* integration (or R&D) offer definition