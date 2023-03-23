# deployment status

[![Netlify Status](https://api.netlify.com/api/v1/badges/9f20aa7f-62f2-4698-b8a5-a8a6e917833a/deploy-status)](https://app.netlify.com/sites/mellifluous-tanuki-c3c7ec/deploys)
# info-page
My personal page

# Adding new articles
`docker exec -it <container_id> hugo new path/title.md -s /src/my-site`
The -s switch is important as the hugo page lives in the subdirectory, not in the root folder.