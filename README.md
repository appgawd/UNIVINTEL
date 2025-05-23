
## Run Locally

update the REACT_APP_ORG_ID in the .env file with the org id from the api

 `curl -s http://localhost:3000/organizations/$ORG_ID/hierarchy | jq .id`

Sample response:

"c6246b9c-3e0b-4f2d-be40-6e2ac8b4f379"


### Run docker compose
`docker-compose up  --build -d`


Access the app at http://localhost:3002/



