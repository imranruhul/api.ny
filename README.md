# api.ny
curl \
  'https://api.nytimes.com/svc/search/v2/articlesearch.json?facet=true&facet_fields=document_type&facet_filter=true&page=1&sort=relevance&api-key=[YOUR_API_KEY]' \
  --header 'Accept: application/json' \
  --compressed
