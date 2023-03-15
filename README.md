# deployment status
[![Netlify Status](https://api.netlify.com/api/v1/badges/d756a8f7-572b-4320-ba46-e4f9eff7312a/deploy-status)](https://app.netlify.com/sites/strong-hotteok-e4a08a/deploys)

# info-page
My personal page

# Adding new articles
`docker exec -it <container_id> hugo new path/title.md -s /src/my-site`
The -s switch is important as the hugo page lives in the subdirectory, not in the root folder.