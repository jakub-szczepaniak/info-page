# info-page
My personal page

# Adding new articles
`docker exec -it <container_id> hugo new path/title.md -s /src/my-site`
The -s switch is important as the hugo page lives in the subdirectory, not in the root folder.