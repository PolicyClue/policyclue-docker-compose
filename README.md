# How to setup
1. install docker & docker compose on your local machine
2. clone Repository
3. copy the `example_env` to .env and modify the secret values
4. run docker compose: `docker compose up -d`
  * wait for docker-compose to finish (migrations shall automatically run)
5. policyclue should now be accessible on localhost