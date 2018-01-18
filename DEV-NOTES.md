# Dev Notes
Keeping notes on building my first Stellar App.

## Horizon
Helpful server that runs an API to interact with the Stellar network. They have a test and public server running that you can use in production.

For deving, we can run a local Horizon server. They offer a docker image with an environment ready to run Horizon.

pull the images:
`docker pull stellar/quickstart`

run the image:
`docker run --rm -it -p "8000:8000" -v "/c/stellar:/opt/stellar" --name stellar stellar/quickstart --testnet`
